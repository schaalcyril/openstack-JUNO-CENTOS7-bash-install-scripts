openstack-JUNO-CENTOS7-bash-install-scripts
A simple OpenStack installer that allows you to install JUNO OpenStack on a CENTOS7.
It's a simple aggregate commande from the official documentation.

===========================================


NAME
     JUNOinstall.sh

SYNOPSIS
     JUNOinstall.sh -t {nodetype} -c {componant}

OPTIONS
     -t <Nodetype>
          controller | compute | network | storage

     -c <componanttype>
          keystone | glance | nova | nova-network | neutron | horizon | cinder
     
     -h
          View this help message about the available command-line options.
