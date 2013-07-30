#hypertable-munin plugin

##Installation

This plugin needs to be installed in a node containing Hypertable Master and munin-node.

Copy the plug-in files `hypertable_rangeservers` and `hypertable_tables` into the munin plugin directory, e.g ``/etc/munin/plugins/``.

If your Hypertable installation is on a directory other than ``/opt/hypertable/current``, set the directory in ``/etc/munin/plugin-conf.d``):

    [hypertable_*]
    env.HYPERTABLE_HOME /opt/my_hypertable_installation/1.2.3



##License and Authors

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

Copyright 2013, by his authors: 

* Jordi Llonch <llonchj@gmail.com>
