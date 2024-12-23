# ansible-vsphere-vsan-nested
## _nested esxi,vcenter setting up vsan in the nested environment_

look at esxinested.yml for changes
- changes to cpu config and vm version
- changes to controller type

look at addhosts_vcenter.yml for changes

- changed order of enabling HA
- enable vsan
- pause timer (needed) and claim disks for cache and capcity based on size
- community.vmware.vmware_vmkernel (enabled vsan)
