# spring-boot-starter-swagger2
A spring boot starter with swagger 2.0 api documentation enabled

Base on springfox Swagger2, you can find more information from [springfox](http://springfox.io)

## How to build and install

1. git clone the code from github

2. run the command in your console with maven:

```
	mvn install
```

## How to use 

- import the config in you `pom.xml`

```xml
<dependency>
    <groupId>com.github.ganity</groupId>
    <artifactId>spring-boot-starter-swagger2</artifactId>
    <version>0.0.1-SNAPSHOT</version>
</dependency>
```

- add the follow config in you `application.yml` or `application.properties` 

```shell
swagger:
  enable: true #if enable swagger
  group: item #the api group name 
  title: item-title #the title
  description: item description
  version: v1.10
  contact-name: ganily
  contact-url: http://www.aaa.com
  contact-email: igman@163.com
  base-package: video.lark.mall.item.service #the base package for RequestHandlerSelectors default all the package
  terms-of-service-url: https://github.com/ganity
  license: Apache License Version 2.0
  license-url: https://github.com/springfox/springfox/blob/master/LICENSE
```

- run your Application


## Paths
- All Swagger Resources(groups) `http://localhost:8080/springfox/swagger-resources`
- Swagger UI endpoint: `http://localhost:8080/springfox/swagger-ui.html`
- Swagger docs endpoint: `http://localhost:8080/springfox/v2/api-docs`


