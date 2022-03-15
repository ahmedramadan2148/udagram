# pipline Process
The pipline circleci is connected to github  repo then fetch the changes 

## step of command pipline 
1- orbs that used in pipline 
 > circleci/aws-cli@2.1.0
 ##
 > circleci/node@5.0.0
 ##
 > circleci/aws-elastic-beanstalk@2.0.1

2- checkout the code from repositories 
 > checkout 
##
3- install backend and frontend dependency 
 > npm install 
 ##
4- build the backend and frontend 
 > npm run build 
##
5- deploy backend and frontend 
 > npm run deploy 
