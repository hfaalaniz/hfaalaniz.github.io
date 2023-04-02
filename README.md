SharpSCADA - 工控网关, 轻量级组态软件.
===================
简介
-------------
采用技术：
开发语言：C#
运行环境：.NET Framework
数据库：SQL Server

功能：
-------------

* 1.轻量级工控网关：
支持当前几种主要的工业协议如西门子的Profinet、AB的EtherNetIPs、施耐德的Modbus和OPC。采用类OPC接口网关。

* 2.数据采集、归档、预警及配置工具
支持实时数据采集、历史数据归档、变量触发预警，并使用TagConfig工具简单的配置实现。

* 3.人机界面（设计时和运行时）

*设计时：
采用Microsoft Visual Studio + 设计器插件（在VS2010-VS2015社区版测试通过）。
通过继承HMIControlBase接口并书写极少量的代码即可实现复杂的图元组件。
支持图元拖放、组合、连线、变量绑定及编辑功能。

*运行时：Microsoft Visual Studio编译运行为可执行文件。
