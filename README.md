# cloudhub2.0
Cloudbhub 2.0 mule application deployment
this is a mule application created for cloudhub 2.0 deployment poc

#How to Build

> mvn clean package   -> build project and create jar file
> mvn clean install  -> add jar file on .me repository local cache

#How to Deploy to Cloudhub

>mvn clean deploy -DmuleDeploy

target - Cloudhub-US-East-2  (US East Ohio)
clientId- 55e16c9614154393940396fb3553a223
clientSecret - 4E204c1fA768441bA6899C887977043e

#Reference
https://docs.mulesoft.com/mule-runtime/4.4/deploy-to-cloudhub-2
