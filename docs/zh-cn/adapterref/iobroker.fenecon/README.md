---
translatedFrom: en
translatedWarning: 如果您想编辑此文档，请删除“translatedFrom”字段，否则此文档将再次自动翻译
editLink: https://github.com/ioBroker/ioBroker.docs/edit/master/docs/zh-cn/adapterref/iobroker.fenecon/README.md
title: ioBroker.fenecon
hash: F84h52mBqTyStvvgSqvErVUvJ2OFmiLyNwupupBm5fE=
---
![标识](../../../en/adapterref/iobroker.fenecon/admin/fenecon.png)

![NPM 版本](https://img.shields.io/npm/v/iobroker.fenecon.svg)
![下载](https://img.shields.io/npm/dm/iobroker.fenecon.svg)
![安装数量](https://iobroker.live/badges/fenecon-installed.svg)
![稳定存储库中的当前版本](https://iobroker.live/badges/fenecon-stable.svg)
![新平台](https://nodei.co/npm/iobroker.fenecon.png?downloads=true)

# IoBroker.fenecon
**测试：**![测试与发布](https://github.com/sg-app/ioBroker.fenecon/workflows/Test%20and%20Release/badge.svg)

## 费内康
[Fenecon](https://fenecon.de) 是一家德国光伏逆变器和储能系统制造商。所使用的能源管理系统 (FEMS) 基于 [openEMS](https://github.com/OpenEMS/openems) 软件。
Fenecon 是 openEMS 的贡献者。

＃＃ 适配器
该适配器连接到 FEMS 系统并通过 REST/JSON 接口检索所有可用数据。
此外，还执行有用的计算。

＃＃ 配置
为了建立连接，需要 FEMS 中央单元的 IP 地址。更新间隔也可以调整。
![fenecon 配置](../../../en/adapterref/iobroker.fenecon/img/configpage.png)

## 州
适配器启动时会自动生成状态。如果通过 FEMS 软件更新提供了其他状态，则日志文件中会显示警告消息。然后请重新启动适配器，新状态将被创建。

## Changelog

<!--
	Placeholder for the next version (at the beginning of the line):
	### **WORK IN PROGRESS**
-->
### 0.5.0 (2024-08-02)

-   (SG-App) set correct role states

### 0.4.2 (2024-08-02)

-   (SG-App) fix channel creation only one time on init

### 0.4.1 (2024-08-02)

-   (SG-App) refactor for latest repo
-   (SG-App) remove getObject calls on init
-   (SG-App) filter object ids if needed
-   (SG-App) check allowed length of address for channel and id creation

### 0.4.0 (2024-07-15)

-   (SG-App) refactor for latest repo

### 0.3.2 (2024-07-14)

-   (SG-App) calculate self consuming
-   (SG-App) dependency updates

### 0.3.1 (2024-07-11)

-   (SG-App) fix adapter checker warning

### 0.3.0 (2024-06-11)

-   (SG-App) set correct read write state
-   (SG-App) calculate autarchy
-   (SG-App) dependency updates

### 0.2.0 (2024-04-20)

-   (SG-App) collect all possible data from rest interface

### 0.1.0 (2024-04-17)

-   (SG-App) minor fix

### 0.0.2-alpha.0 (2024-04-16)

-   (SG-App) initial release

## License

MIT License

Copyright (c) 2024 Georg Schreiner <info@sg-app.de>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.