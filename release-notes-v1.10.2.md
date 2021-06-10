v1.10.2

### Fixed Issues

**rendezvous-service**: The default value of HmacSecret has been removed from properties files. This value is now getting generated when the docker container starts.  
**client-sdk**: Fixed possible buffer overflow issue while parsing proxy information.  
**all-in-one-demo**, **iot-platform-sdk**, **pri**, **rendezvous-service**, **supply-chain-tools**: The version of third-party dependencies have been updated to resolve some of the security vulnerabilities.  
**all-in-one-demo**, **iot-platform-sdk**, **pri**, **rendezvous-service**, **supply-chain-tools**: Runtime Docker containers are updated to include “apt-get -y upgrade” to include latest OS components.  
**all-in-one-demo**, **iot-platform-sdk**, **pri**, **rendezvous-service**, **supply-chain-tools**: Additional comments are added to specify use of test credentials for examples.  

### SHA256 checksum for release binaries

*Following SHA256 checksum is calculated using sha256sum tool*  
```

```
### Documentation

https://secure-device-onboard.github.io/docs/  

*Please ignore Source code zip/tar.gz files. These are default artifacts generated during GitHub Release process.*  
