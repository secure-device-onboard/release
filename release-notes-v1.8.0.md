### New features

**all-in-one-demo**: The demo component was added to facilitate faster demonstration of SDO protocol
using different client implementations.  
**client-sdk**: An example service-info module (sys_info) was added.  
**pri**: CBOR encoding/decoding library is added for future protocol (in 'protocol-next' branch).  
**pri**: Example scripts are added to demonstrate protocol execution.  
**rendezvous-service**: Example docker scripts are added for deployment of service.  
**supply-chain-tools**: Example docker scripts are added for deployment of services.  

### Changes to existing features

**client-sdk**: Several security fixes has been incorporated.  
**client-sdk**: Linux naming convention has been used for variable and function names.  
**client-sdk**: 'Resale' feature is now supported.  
**iot-platform-sdk**: The Owner Redirect information is configurable during run-time.  
**pri**: OwnershipTransferClient accepts configurable number of retries.  
**pri**: Timeout for serviceinfo script execution has been increased in Device module.  
**supply-chain-tools**: UUID field is added to Ownership Voucher table.  

### Discontinued features

**cri**: The repository has been renamed as 'pri'.  

### Fixed Issues

**client-sdk**: Fixed network discovery issue with WPAD.  
**iot-platform-sdk**: Fixed mTLS connection failure to enable execution against latest JDK version.  

### Known Issues

**pri**: A problem was discovered after release in which the PRI TO0Client and Device implementations are not able to complete TO0/TO1 operations against hosted Rendezvous service if they were executed in an open network (not behind a proxy).  See this [Github issue](https://github.com/secure-device-onboard/pri/issues/45) for details.  This issue will be fixed in SDO 1.8.1.  
**client-sdk**:  A problem was discovered after release in which the link to the TPM2_TSS_ENGINE component used by the Client SDK to build with TPM support no longer exists.  See this [Github issue](https://github.com/secure-device-onboard/client-sdk/issues/64) for details.  This issue will be fixed in SDO 1.8.1.  

### Supported hardware platforms

**client-sdk**: X86, ARM-SE (source only)  

### Documentation

https://secure-device-onboard.github.io/docs/  

*Please ignore Source code zip/tar.gz files. These are default artifacts generated during GitHub Release process.*  
