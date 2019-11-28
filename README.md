# openshift4-pxe
Deploys an infrastructure box that runs dnsmasq as a PXE server, matchbox and haproxy to provision OpenShift 4.2


Modify group_vars/all to include the information about the nodes. Included roles will use that information to configure matchbox and haproxy.
