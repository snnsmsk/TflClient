# TflClient

The application makes HTTP GET request and https://api.tfl.gov.uk/ displays the result on the prompt.

### Development Environment 

Solution developed in Visual Studio Community 2017 edition and .Net Framework 4.7.03190. Solution contains of one console aplication and one unittest application.

### Build

Solution can be compiled within Visual Studio 2017 or Developer Command Prompt for VS 2017 tool with the command :

```
devenv tflclient.sln /build
```
Build outputs:
```
TflClient\TflClient\bin\Release\TflClient.exe
```
```
TflClient\TflClient.UnitTest\bin\Release\TflClient.UnitTest.dll
```

### Running the output

Client output exe can be run with Windows Powershell with roadId parameter
```
.\TflClient.exe roadId
```

### Running the tests

Unit tests can be run Test Window in within Visual Studio 2017.

### Config

TflClient and TflClient.UnitTest applications have to be configured for TflApiAppKey and TflApiAppId.
Parameters are configured like below in value :
```
<add key="TflApiAppKey" value="" />
<add key="TflApiAppId" value="" />
```
```
TflClient\TflClient\bin\Release\TflClient.exe xml config file  
```
```
TflClient\TflClient.UnitTest\bin\Release\TflClient.exe xml config file
```
## Authors

* **Sinan Simsek** 
