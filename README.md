Openstack_nagios
================
################################################################################
#                                                                              #
#                                                                              #
#   This program is free software; you can redistribute it and/or modify       #
#   it under the terms of the GNU General Public License as published by       #
#   the Free Software Foundation; either version 2 of the License, or          #
#   (at your option) any later version.                                        #
#                                                                              #
#   This program is distributed in the hope that it will be useful,            #
#   but WITHOUT ANY WARRANTY; without even the implied warranty of             #
#   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the              #
#   GNU General Public License for more details.                               #
#                                                                              #
#   You should have received a copy of the GNU General Public License          #
#   along with this program; if not, write to the Free Software                #
#   Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA
#   
#   Created by: Taha Ali
#   Created on: 4/11/2014
#                                                                              #
################################################################################

Custom NRPE plugins i created for Openstack monitoring 

export OS_TENANT_NAME=
export OS_AUTH_URL=
export OS_USERNAME=
export OS_PASSWORD=

the above parameters needs to be provided according to your enviroment and the following entry can be use as a command in nrpe.cfg
command[check_openstack_vmstatus]=/usr/lib64/nagios/plugins/check_openstack_vmstatus

