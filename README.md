MyBatis Parent
==============

[![Build Status](https://travis-ci.org/mybatis/parent.svg?branch=master)](https://travis-ci.org/mybatis/parent)
[![Maven central](https://maven-badges.herokuapp.com/maven-central/org.mybatis/mybatis-parent/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.mybatis/mybatis-parent)
[![License](https://img.shields.io/:license-apache-brightgreen.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)

![mybatis](http://www.mybatis.org/images/mybatis-logo.png)

MyBatis-Parent is the MyBatis parent POM which has to be inherited by all MyBatis modules.


## 此项目存在的目的（必看）
mybatis-3依赖于此项目，需要打包后给它引用
执行clean，然后install;将jar安装到本地仓库，然后mybatis-3项目就可以找到此jar。

