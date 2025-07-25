## 关于

本仓库 Fork 至[1Panel-dev/appstore](https://github.com/1Panel-dev/appstore) 为避免重复 去除了官方仓库的应用

### 国内网络

> GitHub 加速方式
>
> > - https://github.yeqing.net

#### 使用压缩包方式获取应用

`1Panel`计划任务类型`Shell 脚本`的计划任务框里，添加并执行以下命令，或者终端运行以下命令，

```shell
wget -P /opt/1panel/resource/apps/local hhttps://github.yeqing.net/https://github.com/Yeqingky/appstore/archive/refs/heads/dev.zip

unzip -o -d /opt/1panel/resource/apps/local/ /opt/1panel/resource/apps/local/localApps.zip

cp -rf /opt/1panel/resource/apps/local/appstore-localApps/apps/* /opt/1panel/resource/apps/local/

rm -rf /opt/1panel/resource/apps/local/appstore-localApps

rm -rf /opt/1panel/resource/apps/local/localApps.zip
```

然后应用商店刷新本地应用即可。

### 国际互联网络

#### 使用压缩包方式获取应用

`1Panel`计划任务类型`Shell 脚本`的计划任务框里，添加并执行以下命令，或者终端运行以下命令，

```shell
wget -P /opt/1panel/resource/apps/local https://github.com/Yeqingky/appstore/archive/refs/heads/dev.zip

unzip -o -d /opt/1panel/resource/apps/local/ /opt/1panel/resource/apps/local/localApps.zip

cp -rf /opt/1panel/resource/apps/local/appstore-localApps/apps/* /opt/1panel/resource/apps/local/

rm -rf /opt/1panel/resource/apps/local/appstore-localApps

rm -rf /opt/1panel/resource/apps/local/localApps.zip
```

然后应用商店刷新本地应用即可。

## 应用

- tgDrive

  tgDrive 是一款使用 Java 开发的基于 Telegram Bot 的网盘应用
  
  https://github.com/SkyDependence/tgDrive

- AllinSSL

  AllinSSL 是一个集证书申请、管理、部署和监控于一体的SSL证书全生命周期管理工具
  
  https://github.com/allinssl/allinssl