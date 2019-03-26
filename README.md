# NATS 开源学习

> NATS源码学习系列文章基于[gnatsd1.0.0](https://github.com/nats-io/gnatsd/tree/v1.0.0)。该版本于2017年7月13
> 日发布（[Release v1.0.0](https://github.com/nats-io/gnatsd/releases/tag/v1.0.0)）,在此之前v0.9.6是2016年12月
> 16日发布的,中间隔了半年。算是一个比较完备的版本，但是这个版本还没有增加集群支持。为什么选择这个版本呢？
> 因为一来这个版本比较稳定，同时也包含了集群管理和[Stream](https://github.com/nats-io/nats-streaming-server)
> 落地相关的逻辑，相对完善。


* [0X00：协议](./gnatsd_source_00.md)
* [0X01：代码目录结构](./gnatsd_source_01.md)
* [0X02：Server构造](./gnatsd_source_02.md)
* [0X03：Client服务](./gnatsd_source_03.md)
* [0X04：协议解析](./gnatsd_source_04.md)
* [0X05：订阅消息](./gnatsd_source_05.md)
* [0X06：消息存储结构](./gnatsd_source_06.md)
* [0X07：发布消息](./gnatsd_source_07.md)
* [0X08：Router转发](./gnatsd_source_08.md)
* [0X09：测试代码](./gnatsd_source_09.md)
