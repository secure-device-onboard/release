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
379abd890eb58aafabe5bdad04146bf71a053924b33f884e5abd129cdca0f577 - all-in-one-demo-v1.10.2.tar.gz
f4c95a3934b5bda6b425d64efd79812c11a9256a93181d932388aa2c6c24a7fe - client-sdk-v1.10.2.tar.gz
708cde9daea13c4bebbcb11906d363f705d84b598000ed311cd415415757dc36 - iot-platform-sdk-v1.10.2.tar.gz
9d55c015130802f37dc0ce76be07ef7635f2e7e7545c31cb2331301edafa9a78 - pri-v1.10.2.tar.gz
8494d2be27c5c696a4c15d231d98c3b66537bad562b7453d9adb8c70c66eeb35 - rendezvous-service-v1.10.2.tar.gz
9bd98cc519f5e008efeaf84d4cf2f376e3b49c6c10d92ad61378bbc13ebb7bee - supply-chain-tools-v1.10.2.tar.gz
```
### Documentation

https://secure-device-onboard.github.io/docs/  

*Please ignore Source code zip/tar.gz files. These are default artifacts generated during GitHub Release process.*  
