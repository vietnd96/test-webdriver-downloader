## Introduction

WebDriver Extensions module is a wonderful library addition to the Selenium scripting practice.<br>
It facilitates multiple browser execution, automatic driver download. For more
details: https://webdriverextensions.github.io/webdriverextensions-maven-plugin/index.html <br><br>
In this practice, the Selenium Server jar is used to start Grid also would be downloaded in the same directory. The
versions, download URLs are controlled via ./driver-repository.json <br>
When all drivers and Selenium Server are downloaded, perform to start Hub and Node.<br>

```console
mvn clean install
---
cd Drivers
---
java -jar selenium-server hub
---
java -jar selenium-server node --port 5555
```

## Referrence

A sample project with entire repositories together for the test execution.<br>

* [fs-test-automation](https://github.com/vietnd96/fs-test-automation)
