sonic-sai-vm
----------------------
This repo contains all switch abstraction interface (SAI) public API implementation used by the Dell SAI implementation for virtual machine (VM). This repo contains all public API implementation for SAI. The network adaptation service (NAS) component utilize this SAI API for operations of VM based network processor unit (NPU) simulation. 

## Build
--------
See [sonic-nas-manifest](https://github.com/Azure/sonic-nas-manifest) for more information on common build tools.

### Build requirements
* `sonic-logging-dev`
* `sonic-common-dev`
* `sonic-sai-api-dev`
* `sonic-sai-common-utils-dev`
* `sonic-db-sql-dev`

Copy the Debian files to the parent folder (default location of Debian files), then run the `sonic_build` command.

BUILD CMD: sonic_build libsonic-logging libsonic-common sonic-sai-api libsonic-sai-common-utils libsonic-db-sql -- clean binary

(c) Dell 2016
