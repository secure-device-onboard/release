v1.9.0

### New featuresi
**all-in-one-demo**: ‘rendezvous-service’ is integrated with this demo.   
**client-sdk**: Build system is updated to use cmake*.  
**client-sdk**: Unit-tests are added.  
**client-sdk**: A guide has been provided to port client-sdk to new platforms.  
**iot-platform-sdk**: On-Die ECDSA device attestation support is added.  
**iot-platform-sdk**: Resale protocol support is added in OCS-OPS REST contracts.  
**pri**: On-Die ECDSA device attestation support is added.  
**rendezvous-service**: The build system is migrated to use Maven* and the code is built using Java* 11. The binary packaging has been changed to WAR format.  
**rendezvous-service**: On-Die ECDSA device attestation support is added.  
**supply-chain-tools**: On-Die ECDSA device attestation support is added.  

### Changes to existing features

**iot-platform-sdk**: Application properties are moved to Docker* .env files.  
**iot-platform-sdk**: [Guidelines](https://secure-device-onboard.github.io/docs/latest/iot-platform-sdk/running-the-demo/#setting-up-serviceinfo-transfer) have been added for updating ServiceInfo configuration files in iot-platform-sdk. Not following the guidelines might result in failure to onboard the device.  
**rendezvous-service**: The hashes for the test keys are auto-populated into the allow-list in example Redis DB Docker instance.
**supply-chain-tools**: Application properties are moved to Docker* .env files.  
**supply-chain-tools**: Owner public keys (RSA2048, ECDSA P-256 and ECDSA P-384) are grouped together. During Ownership Voucher extension, appropriate public key is picked up based on the type of Manufacturer key.  

### Discontinued features

**client-sdk**: EPID support was removed.  

### Fixed Issues

None  

### Known Issues
**pri**: A problem was discovered after release in which the PRI TO0Client and Device implementations are not able to complete TO0/TO1 operations against hosted Rendezvous service if they were executed in an open network (not behind a proxy). See this [Github issue](https://github.com/secure-device-onboard/pri/issues/45) for details. This issue will be fixed in SDO 1.9.1.  
**iot-platform-sdk**: The HTTP client implementation in the IOT platform SDK was updated in release 1.9 to match the implementation in PRI. Because of this change, [the issue](https://github.com/secure-device-onboard/pri/issues/45) reported above also impacts the IOT Platform SDK in release 1.9, but doesn’t affect it in release 1.8. This issue will be fixed in SDO 1.9.1.  
**client-sdk**: A problem was discovered after release in which the link to the TPM2_TSS_ENGINE component used by the Client SDK to build with TPM support no longer exists. See this [Github issue](https://github.com/secure-device-onboard/client-sdk/issues/64) for details. This issue will be fixed in SDO 1.9.1.  

### Supported hardware platforms

**client-sdk**:  
X86 (source and binary)  
ARM-SE, ARM M4, ARM A7 (source only)  

### Documentation

https://secure-device-onboard.github.io/docs/  

*Please ignore Source code zip/tar.gz files. These are default artifacts generated during GitHub Release process.*  

