# cloudhub2.0
Cloudbhub 2.0 mule application deployment
this is a mule application created for cloudhub 2.0 deployment poc

#How to Build

> mvn clean package   -> build project and create jar file
> mvn clean install  -> add jar file on .me repository local cache

#Publish asset to exchange (mandatory step for cloudhub2.0 deployment)
> mvn clean deploy
#more details on publishing asset on exchange can be found on https://docs.mulesoft.com/exchange/to-publish-assets-maven

once this steps is completed, you will be able to see your application on exchange using below url
https://anypoint.mulesoft.com/exchange/?type=app&show=all
be default you will not be able to see your application on exchange so try above url.

#How to Deploy to Cloudhub

>mvn clean deploy -DmuleDeploy

target - Cloudhub-US-East-2  (US East Ohio)
clientId- 55e16c9614154393940396fb3553a223
clientSecret - 4E204c1fA768441bA6899C887977043e

#Reference
https://docs.mulesoft.com/mule-runtime/4.4/deploy-to-cloudhub-2


target on cloudhub 2.0 deployment page- raise PR

*Cloudhub-US-East-1 (US East, N. Virginia)
*Cloudhub-US-East-2 (default;US East, Ohio)
*Cloudhub-US-West-1 (US West, N. California)
*Cloudhub-US-West-2 (US West, Oregon)
*Cloudhub-CA-Central-1 (Canada, Central)
*Cloudhub-SA-East-1 (South America, São Paulo)
*Cloudhub-EU-West-1 (EU, Ireland)
*Cloudhub-EU-Central-1 (EU, Frankfurt)
*Cloudhub-EU-West-2 (EU, London)
*Cloudhub-AP-SouthEast-1 (Asia Pacific, Singapore)
*Cloudhub-AP-SouthEast-2 (Asia Pacific, Sydney)
*Cloudhub-AP-NorthEast-1 (Asia Pacific, Tokyo)

# cloudhub2.0
Cloudbhub 2.0 mule application deployment
this is a mule application created for cloudhub 2.0 deployment poc

#How to Build

> mvn clean package   -> build project and create jar file
> mvn clean install  -> add jar file on .me repository local cache

#How to Deploy to Cloudhub

first publish your api on exchange which is mandate for clouhub 2.0 deployment

>mvn clean deploy

now,once asset is published on exchage we can deploy this on cloudhub 2.0

>mvn clean deploy -DmuleDeploy

target - Cloudhub-US-East-2  (US East Ohio)
clientId- 55e16c9614154393940396fb3553a223
clientSecret - 4E204c1fA768441bA6899C887977043e

#Reference
https://docs.mulesoft.com/mule-runtime/4.4/deploy-to-cloudhub-2
