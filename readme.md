## 1、new Dynamic Web project
target runtime: tomcat v8.5
Dynamic web module version: 2.5
configuration: JavaServer Faces v1.2 Project

## 2、创建MyJsfAction.java

## 3、新建userChoose.jsp

## 4、新建newJava.jsp, newC.jsp

## 5、修改配置文件faces-config.xml

## 6、修改web.xml

## 7、run on tomcat8.5,浏览器地址栏：http://localhost:8080/jsp-demo/pages/userChoose.jsf

## 8、需要注意将jsp文件放置在WebRoot目录下，否则找不到

## 9、需要导入jstl的jar包，否则，会报错java.lang.NoClassDefFoundError: javax/servlet/jsp/jstl/core/Config