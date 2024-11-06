## Plan9 Mk

This repository enables easy build of Mk (and only Mk) on Unix from the plan9port.

### Usage

Execute `mkmk`, git will clone the plan9port repository for you and a custom install script will be injected. The Mk binary will be under the current directory as `mk`.

Executing `mkmk` with the option `-p` and with root privilege, the script will install Mk to `/usr/local/bin` and delete the cloned plan9port repo for you.

### License

Same as plan9port.
