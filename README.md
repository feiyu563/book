---
description: >-
  Prometheus
  Alert是开源的运维告警中心消息转发系统,支持主流的监控系统Prometheus,Zabbix,日志系统Graylog和数据可视化系统Grafana发出的预警消息,支持钉钉,微信,华为云短信,腾讯云短信,腾讯云电话,阿里云短信,阿里云电话等
---

# PrometheusAlert

### PrometheusAlert全家桶

![author](https://img.shields.io/badge/author-jikun.zhang-blueviolet.svg) ![license](https://img.shields.io/github/license/feiyu563/PrometheusAlert.svg) ![last commit](https://img.shields.io/github/last-commit/feiyu563/PrometheusAlert.svg) ![issues](https://img.shields.io/github/issues/feiyu563/PrometheusAlert.svg) ![stars](https://img.shields.io/github/stars/feiyu563/PrometheusAlert.svg) ![forks](https://img.shields.io/github/forks/feiyu563/PrometheusAlert.svg) [![docker](https://img.shields.io/docker/pulls/feiyu563/prometheus-alert.svg)](https://hub.docker.com/r/feiyu563/prometheus-alert)![Travis](https://img.shields.io/badge/language-Go-green.svg) ![Travis](https://img.shields.io/badge/language-JavaScript-yellow.svg)![Travis](https://img.shields.io/badge/language-Shell-blue.svg)

* 如果这个项目能为您带来帮助，我将感到非常荣幸！同时非常欢迎您加入PrometheusAlert全家桶的微信群一起探讨关于PrometheusAlert新一期的开发计划。
* PrometheusAlert的成长离不开所有爱好运维和开发的朋友们的支持！如果您也对这个项目感兴趣，请[点击一下 Star](https://github.com/feiyu563/PrometheusAlert/stargazers) 以示鼓励，谢谢

  

![dashboard](https://gitee.com/feiyu563/PrometheusAlert/raw/master/doc/dashboard.png)

![dashboard-tpl-list](https://gitee.com/feiyu563/PrometheusAlert/raw/master/doc/dashboard-tpl-list.png)

![dashboard-test](https://gitee.com/feiyu563/PrometheusAlert/raw/master/doc/dashboard-test.png)

PrometheusAlert是开源的运维告警中心消息转发系统，支持主流的监控系统Prometheus、Zabbix，日志系统Graylog2，Graylog3、数据可视化系统Grafana、SonarQube等支持WebHook接口的系统发出的预警消息，支持将收到的这些消息发送到钉钉，微信，飞书，腾讯短信，腾讯电话，阿里云短信，阿里云电话，华为短信，容联云电话等。

![it](https://gitee.com/feiyu563/PrometheusAlert/raw/master/doc/it.png)

### PrometheusAlert具备如下特性

* 支持任意包含WebHook接口系统的消息作为消息来源，常见的如Prometheus，Zabbix，Graylog2，Graylog3，Grafana，SonarQube和其他WebHook接口的系统。
* 支持多种类型的发送目标，支持钉钉，微信，飞书，腾讯短信，腾讯语音，阿里云短信，阿里云语音，华为短信，容联云电话。
* 针对Prometheus增加了告警级别，并且支持按照不同级别发送消息到不同目标对象。
* 简化Prometheus分组配置，支持按照具体消息发送到单个或多个接收方。
* 增加手机号码配置项和号码自动轮询配置，可固定发送给单一个人告警信息，也可以通过自动轮询的方式发送到多个人员且支持按照不同日期发送到不同人员。
* 增加Dashboard，提供配置测试，告警消息模版自定义，告警模版测试等功能
* 增加代理支持，感谢[@pzqu](https://github.com/pzqu)提交
* 增加飞书，容联云告警方式，感谢[@bigdimple](https://github.com/bigdimple)提交
* 增加自定义告警消息模版支持，可以通过自定义模版对任意服务WebHook进行支持

### 项目源码

* [GitHub: PrometheusAlert](https://github.com/feiyu563/PrometheusAlert)
* [码云: PrometheusAlert](https://gitee.com/feiyu563/PrometheusAlert)

### FOR HELP

Email: 244217140@qq.com

![me](https://gitee.com/feiyu563/PrometheusAlert/raw/master/doc/wx.png)

