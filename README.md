
After struggling to get Lustre 1.8.8 to install on RHEL 6.4 with
kernel 2.6.32-358 *when using the Mellanox Infiniband OFED
drivers*, I thought I'd share a set of RPMs that work.

RPMS are located in folders with the following naming convention:

    lustre-<lustre_version>_<ofed_version>_<kernel_version>.<release>.<arch>
