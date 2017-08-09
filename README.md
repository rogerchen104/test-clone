# e104-sms 
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
*   
## git submodule 
* git clone https://github.com/104corp/104isgd-dev-sms2.git # clone git or git pull
* git submodule init # 初始化submodule
* git submodule update # update submoudle code

## maven cli
* mvn clean install #執行mavn install
* mvn spring-boot:run #執行application
