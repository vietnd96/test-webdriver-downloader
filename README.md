## Introduction

WebDriver Extensions module is a wonderful library addition to the Selenium scripting practice.<br>
It facilitates multiple browser execution, automatic driver download. For more
details: https://webdriverextensions.github.io/webdriverextensions-maven-plugin/index.html <br><br>
In this practice, the Selenium Server jar is used to start Grid also would be downloaded in the same directory. The
versions, download URLs are controlled via ./driver-repository.json <br>
When all drivers and Selenium Server are downloaded, perform to start Hub and Node.<br>

## List dependency repositories

* [test-parent-pom](../../../test-parent-pom)

## Source code usage

1. Clone repository "test-parent-pom" (**mandatory**)

```shell
git clone git@github.com:vietnd96/test-parent-pom.git
```

2. Clone this repository

```shell
git clone git@github.com:vietnd96/test-webdriver-downloader.git
```

3. Build the project to trigger the downloading

```shell
mvn clean install
```

```shell
cd Drivers
java -jar selenium-server hub
```

```shell
cd Drivers
java -jar selenium-server node --port 5555
```

## Reference

A sample project with entire repositories together for the test execution.<br>

* [test-automation-project](../../../test-automation-project)
