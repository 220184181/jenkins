FROM tomcat:8-jre8
MAINTAINER wifi

#将war包添加进webapps中
ADD target/springmvc_day01_01_start.war /usr/local/tomcat/webapps/ 

#启动tomcat shell执行程序
CMD ["catalina.sh", "run"] 
