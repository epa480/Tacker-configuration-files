# Tacker-configuration-files

Use project admin.

Project NFV is not working,(Error auth barbican in scalling)

- update tosca-parser:

      git clone https://github.com/openstack/tosca-parser.git

      cd tosca-parser

      git fetch https://git.openstack.org/openstack/tosca-parser refs/changes/35/522935/7 && git checkout FETCH_HEAD

      sudo python setup.py install



- update heat-translator:

      git clone https://github.com/openstack/heat-translator.git

      cd heat-translator

      git fetch https://git.openstack.org/openstack/heat-translator refs/changes/21/523021/4 && git checkout FETCH_HEAD

      sudo python setup.py install
