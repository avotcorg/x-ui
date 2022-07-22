本项目基于上游X-UI项目进行略微的功能改动！后续将紧跟上游X-UI版本更新！在此感谢[vaxilu](https://github.com/vaxilu/x-ui)、[FranzKafkaYu](https://github.com/FranzKafkaYu/x-ui)及各位为此项目做出贡献

----------------------------------------------------------------------------------------------------------------------------------------------

### 纯IPV4/纯IPV6的VPS直接运行一键脚本

```

wget -N --no-check-certificate https://raw.githubusercontents.com/avotcorg/x-ui/main/install.sh && bash install.sh

bash <(curl -Ls https://raw.githubusercontents.com/avotcorg/x-ui/master/install.sh)


```

--------------------------------------------------------------------------------------------------------------------------------------------------
### 关于TG通知（上游内容）

使用说明:在面板后台设置机器人相关参数

Tg机器人Token

Tg机器人ChatId

#### Tg机器人周期运行时间，采用crontab语法参考语法：

30 * * * * * //每一分的第30s进行通知

@hourly //每小时通知

@daily //每天通知（凌晨零点整）

@every 8h //每8小时通知

@every 30s  //每30s通知一次

#### TG通知内容：

节点流量使用

面板登录提醒

节点到期提醒

流量预警提醒

#### TG机器人可输入内容：

/delete port将会删除对应端口的节点

/restart 将会重启xray服务，该命令不会重启x-ui面板自身

/status 将会获取当前系统状态

/enable port将会开启对应端口的节点

/disable port将会关闭对应端口的节点

/version v1.5.5将会升级xray到1.5.5版本

/help 获取帮助信息
---------------------------------------------------------------------------------------------------------------------------------------------------
