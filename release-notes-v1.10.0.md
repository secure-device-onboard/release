v1.10.0

### New features

**all-in-one-demo**, **client-sdk**, **iot-platform-sdk**, **pri**, **rendezvous-service**, **supply-chain-tools**: The primary supported OS has been moved from Ubuntu 18.04 to Ubuntu 20.04.  
**all-in-one-demo**: Implemented REST endpoint to get additional information (serial number, UUID, timestamp for Device Initialization) about device.  
**all-in-one-demo**: Added new unit-tests, improved exception handling and updated input validation.  
**rendezvous-service**: The use of whitelist/blacklist is deprecated in favour of allowlist/denylist.  

### Changes to existing features

**iot-platform-sdk**, **pri**, **rendezvous-service**: Added check for known AppID to ensure only known TEE based clients can be used to onboard a device.  

### Discontinued features

None  

### Fixed Issues

**client-sdk**: TPM2 TSS Engine version has been updated to 1.1.0 to fix build issue.  
**client-sdk**: Fixed build issue when MODULES=true option was selected. It was only observed on Ubuntu 20.04.  
**iot-platform-sdk**, **pri**: HTTP version was forced to 1.1 to fix access issue with Sandbox RV while executing in open network.  
**rendezvous-service**: Enhanced logic to parse proxy information from environment variable. This information is used by the Docker scripts during runtime execution.  
**supply-chain-tools**: Fixed the incorrect UUID value in the database against ownership voucher entry.  

### Known Issues

None  

### Supported hardware platforms

**client-sdk**:  
X86 (source and binary)  
ARM-SE, ARM M4, ARM A7 (source only)  

### Documentation

https://secure-device-onboard.github.io/docs/  

*Please ignore Source code zip/tar.gz files. These are default artifacts generated during GitHub Release process.*  

