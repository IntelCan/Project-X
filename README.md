
## pre-install

1. install OpenJDK8
    - set `JAVA_HOME` environment variable
1. (optional) install latest gradle
    - otherwise just use `$ ./gradlew`
1. (optional) install python 2.7.x
    - set `PYTHON` environment variable
    - `$ gradle npminstall` may complain otherwise


## build & run

* `$ gradle clean build bootRun`
* using browser, navigate to`localhost:8080`



## license
[MIT](/LICENSE)
