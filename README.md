# nifi
Apache NiFi

## deploy nifi cluster
Nifi can be provisioned in parallel with kafka cluster deployment as there is no overlap at this stage. Running time is about four and a half minutes on AWS for a minimal number of hosts (3):

    ./deploy $platform_root/ucsd/inventory/hostsfile.none $platform_root/ucsd demo aws $ec2_region development none
