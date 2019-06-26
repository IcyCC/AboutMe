# 基本资料

* 姓名: 苏畅
* 性别: 男
* 院校: 北京林业大学信息学院网络工程专业
* 主修课程: 网路编程 unix环境编程 数据结构 等
* 毕业时间: 2020年6月
* 邮箱: sam.suchang@qq.com
* 手机: 15311070339
* 求职意向: 后台开发 go c++ 均可, 接受转rust和java, 广告或基础设施相关业务最佳

# 实习经验

## 木瓜移动 

* 时间: 2017-07-2017.10
* 职位: Python后端工程师
* 工作内容: 
    1.  优化广告数据采集脚本 
    2.  进行运营后台业务开发, 优化运营后台首页加载速度
    3.  接入dsp的供应方平台接口

## 知乎

* 时间: 2018-05-2018.9
* 职位: 社区事业部-内容组-Python后端工程师
* 工作内容:
    1. 配置化爬虫的开发
    2. 配合首页和算法, 进行ops的数据标注平台前后端开发
    3. 制作ops平台的代码生成工具, 方便其他业务线快速接入ops平台


# 专业技能

* 编程语言: 熟练掌握Python和其C/C++拓展开发, 掌握 Golang, JavaScript 和 Morden C++ 

* Web后端: 熟练掌握 MySQL 和 Redis,
          了解 Nginx, Kafka,  Docker, Thirft
          有良好的架构设计意识
* Web前端: 熟练掌握Vue 了解React 拥有全栈开发的能力
* 计算机网络: 熟练掌握HTTP协议, 了解TCP/IP协议 , Socket编程 和 常见的并发模型 
* 计算机科学常识: 熟练掌握常见的算法以及数据结构,
了解unix操作系统及其环境编程, 
了解常见的网络安全攻击手段

            
# 近期项目

## reimu

> https://github.com/IcyCC/reimu

* 简介: 一个使用 Morden cpp 的 Reactro 的 linux 网络框架
* 关键词: C++ Socket poll 多线程 并发
* 工作:  
    1. 基于 poll + Eventloop + 线程池的模式, 实现对 tcp的客户端\服务端 和 定时任务 的并发编程的完善的封装.
    2. 编写SafeQueue, 并基于此实现了线程池， 将用户的操作放入线程池中操作.
    3. 设计了一套Buffer + 带有引用计数的Slice 的机制，减少了字符串的拷贝.

## wh_parser

* 简介: 一个支持类文华财经语法dsl的量化交易框架
* 关键词: Python C++ Cython ply 
* 工作: 
    1. 基于ply 实现了一个类似文化财经语法的dsl及其交易回测数据运行环境
    2. 基于开源回测框架修改, 简化代码接入自有数据源, 并且支持了分钟级别以及夜盘的期货回测
    3. 处理自有期货数据, 包括合约拆分, 逻辑交易时间计算, 主力合约确定 等
    4. 接入ctp接口进行实盘行情和交易的处理

## async_easyapi

> https://github.com/IcyCC/async_easyapi

* 简介: 基于python元类的后端增删改查基础工具包, 支持asyncio
* 关键词: Python 元类 开发效率 asyncio
* 工作:  
    1. 区别于在知乎编写的代码生成工具, 基于更高抽象的思路而不是模板生成代码来进行重复代码节约
    2. 通过继承几个基类快速实现后台api开发, 提供 flask 的 handler 和错误处理等常用工具

## 北京林业大学督导系统v2.0

> 前端 https://github.com/IcyCC/bjfu_supervision_font.git  
 > 后端 https://github.com/IcyCCbjfu_supervision_back.git

* 简介: 用于学校内的教师给教师进行教学打分的系统, 是对旧版php系统的重新开发
* 关键词: Python vue redis kafka mysql mongodb, gevent
*  工作: 
    1. 作为项目owner, 进行需求梳理, 人员分工,架构设计和大部分前端的开发, 完成了整个系统的业务
    2. 抛弃了老版系统的模板渲染的架构, 采用了前后端分离架构, 前端功能更强, 后端更轻量
    3. 抛弃了老版直接数据库写死问卷的做法, 提供了一个基于json的可视化的问卷编辑系统, 方便的增加或修改评价体系
    4. 使用消息队列, 降低后端各个模块(课程, 教师, 评价, 活动, 咨询, 消息等)的耦合度, 提高了性能和可维护性

## 智能终端跟踪系统

* 简介: 外包项目, 用于跟踪洒水车和农业喷药无人机的数据管理和监控
* 关键词: Python vue async_easyapi  BaiduMap, gevent
* 工作: 
    1. 作为项目owner, 进行需求梳理, 人员分工, 架构设计和部分功能前后端开发工作
    2. 基于 BaiduMap 进行设备行动轨迹的可视化展示, 提供不同倍速的轨迹回放和设备实时轨迹的查看
    3. 设计并实现了一套可能是业内优秀水平的运行报告渲染系统.

# 博客和git

* [github](https://github.com/IcyCC):  https://github.com/IcyCC
* [知乎](https://www.zhihu.com/people/su-chang-60-5/posts): https://www.zhihu.com/people/su-chang-60-5/posts 

# 校园经历

## 主修课程

网络编程, 交换路由, C/C++程序设计, unix环境编程, 数据结构, 计算机网络, 网络安全 等

## 课程设计

* [分布式霸道选举算法+基于Eventloop和morden cpp的网络库](https://github.com/IcyCC/bully_algo)
* [orm框架](https://github.com/IcyCC/db_hw.git)  
* [irc聊天服务器](https://github.com/IcyCC/easy_irc.git), 
* 课本公式内容检索系统
* [自动正文提取爬虫](https://github.com/IcyCC/unix_spiders)

## 数字林业实验室

* 时间: 2017-06 - 至今
* 工作: 多个项目owner, 承担了北京市生态监测网, 北林督导管理系统等项目的开发工作

# 个人简介

高中开始编程, 自学能力强  
不仅热爱计算机技术, 更喜欢思考如何利用技术高效优雅地解决问题  
开发经验丰富, 大学期间有约**10w**行左右的业务代码的开发经验, 合作和沟通能力强, 在校期间作为**负责人**带领由同学组成的团队开发了大小近十余个投入生产的项目, 涉及到各种技术栈,  有承担责任和在团队中扮演合适角色的能力  
好奇心强, 喜欢通过阅读各种项目的源码理解某个机制的运行原理 