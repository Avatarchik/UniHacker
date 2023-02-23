# UniHacker	[English Doc](https://github.com/tylearymf/UniHacker/blob/main/README_EN.md)

[![Latest Version](https://img.shields.io/github/v/release/tylearymf/UniHacker?color=%23FF3300)](https://github.com/tylearymf/UniHacker/releases/latest)
[![License](https://img.shields.io/github/license/tylearymf/UniHacker)](https://github.com/tylearymf/UniHacker/blob/main/LICENSE)
[![Latest](https://img.shields.io/github/downloads/tylearymf/UniHacker/latest/total)](https://github.com/tylearymf/UniHacker/releases/latest)
[![Total Download Count](https://img.shields.io/github/downloads/tylearymf/UniHacker/total)](https://github.com/tylearymf/UniHacker/releases)
![Star Count](https://img.shields.io/github/stars/tylearymf/UniHacker?style=social)
![Fork Count](https://img.shields.io/github/forks/tylearymf/UniHacker?style=social)
![Support Platforms](https://img.shields.io/powershellgallery/p/Pester)
<!--[![Open Issues](https://img.shields.io/github/issues/tylearymf/UniHacker)](https://github.com/tylearymf/UniHacker/issues)
[![Close Issues](https://img.shields.io/github/issues-closed/tylearymf/UniHacker)](https://github.com/tylearymf/UniHacker/issues?q=is%3Aissue+is%3Aclosed)-->

**支持破解所有国际版本的Unity和UnityHub。**

**自从 Unity2022.2.0 及以上版本重构了License逻辑，目前无法破解。问题跳转：[#78](https://github.com/tylearymf/UniHacker/issues/78)**

下载地址

1. Unity国际版 官方下载地址（需要配置代理，代理没配置好可能会下载的国内版）

   * https://unity3d.com/get-unity/download/archive

2. UnityHub国际版 官方下载地址（需要配置代理，代理没配置好可能会下载的国内版）

   * https://unity.com/download#how-get-started

3. Unity国际版 UnityHub国际版 第三方下载地址（不需要配置代理，基本上下载的都是国际版）

   * https://github.com/AlianBlank/download.unity.com

4. UnityHub直链下载地址（需要配置代理，代理没配置好可能会下载的国内版）

   * Windows：https://public-cdn.cloud.unity3d.com/hub/prod/UnityHubSetup.exe

   * Mac：https://public-cdn.cloud.unity3d.com/hub/prod/UnityHubSetup.dmg

   * Linux：https://docs.unity3d.com/hub/manual/InstallHub.html#install-hub-linux


**使用教程**

* 在软件上选择你要破解的 Unity.exe 后，点击破解即可使用，这时已经可以双击Unity.exe打开工程了。如果提示不支持请提交 issue
* 如果还需要配合Unity Hub，那么也在软件上选择 Unity Hub.exe，点击破解，即可搭配Unity Hub一起使用
* 注意：**只破解 Unity Hub.exe 是无法打开工程的，因为破解 Unity.exe 才是主要的**

**Unity Hub登录教程**

1. 将UnityHub的语言改成English，走后面的流程会自动打开 unity.com，如果还是打开的 unity.cn，那么再走这个步骤：删除本地缓存目录
   * Windows：%AppData%/UnityHub（C:\Users\你的用户名\AppData\Roaming\UnityHub）
2. 在[Proxifier](https://www.proxifier.com/)的规则设置中将UnityHub加入代理，需要配合梯子，具体网络搜索，这里不细说
3. 打开UnityHub，点击Sign In，会跳转到 https://api.unity.com/v1/oauth2/...，注意这里是 .com是正确的，如果是 .cn的说明你的第一步或者第二步操作有问题
4. 注册个Unity国外账号（用邮箱注册就可以了，不需要手机号），然后登录好后会自动跳转会UnityHub，如果没反应，可以退出UnityHub再点击登录

注意事项

* 上面的地址下载时需要 **全程代理**，不然可能会出现时重定向为国内地址，具体在软件分析时会提示为 **国内特供版** 。
* **国内特供版的是不支持破解的**。

## Docker

[unihacker-docker](https://github.com/tylearymf/unihacker-docker)

## Windows 系统

### 支持破解的Unity版本

| 2023.x | 2022.2 |       2022.1       |       2021.x       |       2020.x       |       2019.x       |
| :----: | :----: | :----------------: | :----------------: | :----------------: | :----------------: |
|  :x:   |  :x:   | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |

|       2018.x       |       2017.x       |        5.x         |        4.x         |      |      |
| :----------------: | :----------------: | :----------------: | :----------------: | ---- | ---- |
| :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |      |      |

### 支持破解的Unity Hub版本

|        3.x         |        2.x         |      |      |      |      |
| :----------------: | :----------------: | :--: | ---- | ---- | ---- |
| :heavy_check_mark: | :heavy_check_mark: |      |      |      |      |

## Mac 系统

### 支持破解的Unity版本

| 2023.x | 2022.2 |       2022.1       |       2021.x       |       2020.x       |       2019.x       |
| :----: | :----: | :----------------: | :----------------: | :----------------: | :----------------: |
|  :x:   |  :x:   | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |

|       2018.x       |       2017.x       |        5.x         |        4.x         |      |      |
| :----------------: | :----------------: | :----------------: | :----------------: | ---- | ---- |
| :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |      |      |

### 支持破解的Unity Hub版本

|        3.x         |        2.x         |      |      |      |      |
| :----------------: | :----------------: | :--: | ---- | ---- | ---- |
| :heavy_check_mark: | :heavy_check_mark: |      |      |      |      |

## Linux 系统

### 支持破解的Unity版本

| 2023.x | 2022.2 |       2022.1       |       2021.x       |       2020.x       |       2019.x       |
| :----: | :----: | :----------------: | :----------------: | :----------------: | :----------------: |
|  :x:   |  :x:   | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |

|       2018.x       |       2017.x       |      |      |      |      |
| :----------------: | :----------------: | ---- | ---- | ---- | ---- |
| :heavy_check_mark: | :heavy_check_mark: |      |      |      |      |

### 支持破解的Unity Hub版本

|        3.x         |        2.x         |      |      |      |      |
| :----------------: | :----------------: | :--: | ---- | ---- | ---- |
| :heavy_check_mark: | :heavy_check_mark: |      |      |      |      |

## 免责声明

本软件的任何使用仅用于非营利性的教育和测试目的。

## 鸣谢

> [asar](https://github.com/Jiiks/asar.net)
>
> [unity-patch](https://github.com/aevitas/unity-patch)
>
> [Avalonia](https://github.com/AvaloniaUI/Avalonia)
