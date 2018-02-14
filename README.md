NEM Core
====================
[![Build Status](https://travis-ci.org/NemProject/nem.core.svg?branch=master)](https://travis-ci.org/NemProject/nem.core)
NEM核心是NIS和NCC的重要组成部分。可以说最有趣的部分之一是org.nem.core.crypto，其中包括签名和验证签名等所有加密过程。

在该核心之上包含交易，块和消息等构建块。
The NEM core is an important part for both NIS and NCC. Arguably one of the  most interesting parts would be org.nem.core.crypto, which includes all cryptographic procedures like signing and verifying of signatures.

Above that core includes building blocks like Transactions, Blocks and Messages.

compilation:

    mvn install

模块：
    async：异步
    connect:连接
    crypto：包括签名和验证签名等所有加密过程
    function：函数
    i18n：自定义资源包控件，支持从属性文件加载UTF8资源
    math：矩阵和线性代数
    messages：简单消息和加密消息
    metadata：元数据
    model:一些实体类
    node：节点
    serialization：序列化
    time：时间
    utils：工具类
    
由另外一个项目：nem.deploy来启动发布    