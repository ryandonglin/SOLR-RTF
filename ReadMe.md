# Introduction

this is a bref package for user who wanna to deploy solr 6.3.0 in tomcat, as you know , a lot of situations can be met while deploying solr 6.3.0 in tomcat, using our Solr-RTF (Ready to Fly), just run ./apache/bin/start.sh in our packageand you will suceessfully runing a solr instance in standlone mode. 

# Useage

usage git command to download solr-rtf package or down load from this page:
```
git pull git@github.com:ryandonglin/SOLR-RTF.git
```
Here is only one brunch in our project, since this project already integrate apache tomcat, so just step into the runtime folde and start our application, using the command :
```
cd ./runtime/apache/bin
./startup.sh
```
after executing the command shell, browse <http://localhost:8080/solr/index.html> in your browser, you will get a new solr instance with name of test

# Contract Me
<ryandonglin@sina.com>
