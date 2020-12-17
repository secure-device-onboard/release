v1.8.1

### Fixed Issues

**pri**: In SDO 1.8.0 release, the PRI TO0Client and Device implementations were not able to complete TO0/TO1 operations against hosted Rendezvous service if they were executed in an open network (not behind a proxy). The issue was fixed by specifying HTTP version as 1.1 for all HTTP clients. See this [Github issue](https://github.com/secure-device-onboard/pri/issues/45) for details.  
**client-sdk**: The link for the TPM2_TSS_ENGINE component specified in SDO 1.8.0 release no longer exists. The issue was fixed by updating the link to latest stable release. See this [Github issue](https://github.com/secure-device-onboard/client-sdk/issues/64) for details.  

### Supported hardware platforms

**client-sdk**: X86, ARM-SE (source only)  

### Documentation

https://secure-device-onboard.github.io/docs/  

*Please ignore Source code zip/tar.gz files. These are default artifacts generated during GitHub Release process.*  
