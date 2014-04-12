Openstack_nagios
================

Created by: Taha Ali
Created on: 4/11/2014


Custom NRPE plugins i created for Openstack monitoring 

export OS_TENANT_NAME=
export OS_AUTH_URL=
export OS_USERNAME=
export OS_PASSWORD=

the above parameters needs to be provided according to your enviroment and the following entry can be use as a command in nrpe.cfg
command[check_openstack_vmstatus]=/usr/lib64/nagios/plugins/check_openstack_vmstatus

