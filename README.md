# e104-sms  
[![Build Status](https://travis-ci.com/104corp/104isgd-dev-sms2.svg?token=xa7MXxjsxHfihJxzQohj&branch=master)](https://travis-ci.com/104corp/104isgd-dev-sms2)
## module structure
```
---- e104-sms
             |-- pom.xml (pom)
             |
             |-- e104-sms-api #controller & main application
             |        |-- pom.xml (jar)
             |
             |-- e104-sms-service #service & vo(value object)
             |        |-- pom.xml (jar)
             |
             |-- e104-sms-dao   #dao & domain
                      |-- pom.xml (jar)
 ```            
             
## java package
*	api - com.e104.sms2.api.\[?Domain\](ex:com.e104.sms2.api.user)
*	dao - com.e104.sms2.dao.\[?Domain\](ex:com.e104.sms2.dao.userinfo)
*	service - com.e104.sms2.serive.\[?Domain\](ex:com.e104.sms2.service.userservice)
*	domainObject - com.e104.sms2.domain.\[?Domain\](ex:com.e104.sms2.domain.user)
*	vo - com.e104.sms2.vo.\[?Domain\](ex:com.e104.sms2.vo.user)

## git submodule 
* git clone https://github.com/104corp/104isgd-dev-sms2.git # clone git or git pull
* git submodule init # 初始化submodule
* git submodule update # update submoudle code

## maven cli
* mvn clean install #執行mavn install
* mvn spring-boot:run #執行application

##	其它資源參考
* [google styleguide](https://google.github.io/styleguide/javaguide.html#s5.1-identifier-names "google styleguide")
* [Maven 模組說明](https://google.github.io/styleguide/javaguide.html#s5.1-identifier-names "Maven 模組說明")
* [GIT SUBMODULE介紹與功能](https://blog.wu-boy.com/2011/09/introduction-to-git-submodule/ "GIT SUBMODULE介紹與功能")
