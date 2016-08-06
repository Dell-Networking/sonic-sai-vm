SONiC sai-vm
----------------------
This repo contains all SAI public API implementation that is used by the Dell SAI implementation for VM.


Description
-----------

This repo has all public API implemenation for SAI.The NAS component utilizes this SAI API for operations of VM (virtual machine) based NPU simulation. 

Building
--------
Please see the instructions in the sonic-nas-manifest repo for more details on the common build tools.  [Sonic-nas-manifest](https://stash.force10networks.com/projects/SONIC/repos/sonic-nas-manifest/browse)

Build Requirements:
 - sonic-logging-dev
 - sonic-common-dev
 - sonic-sai-api-dev
 - sonic-sai-common-utils-dev
 - sonic-db-sql-dev

Copy the debian files to the parent folder (default location of debian files) and then run the following command:

BUILD CMD: sonic_build libsonic-logging libsonic-common sonic-sai-api libsonic-sai-common-utils libsonic-db-sql -- clean binary

(c) Dell 2016
