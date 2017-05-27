# 开发者须知

青云 AppCenter 旨在成立一个帮助开发者快速开发云应用，并且帮助服务商使自己的产品和服务快速便捷抵达企业用户的商业化平台，因此我们对产品的质量要求是苛刻的，在发布产品之前一定要做以下检测，否则审核肯定通不过。开发供自己内部使用的用户也可以参考一下部分标准。

* 一个完整的产品不仅仅是服务创建成功就算完成任务，还要测试关闭集群、启动集群、删除集群、恢复集群、横向伸缩 (如果提供此弹性能力)，纵向伸缩等操作，每次操作完毕查看 job 是否成功，而且要查看服务是否正常，并且重中之重：一定要测试用户数据在每个测试之后有没有丢失。如果因为没有按照青云 AppCenter 规范开发应用导致数据丢失青云概不负责，而由应用提供商或开发者自己负责。青云审核也会重点审核这些内容；
* 同样一个完整的云应用应该包括监控、告警、健康检查，如果有尽量提供给用户；
* 应用的描述真实、完整、简洁明了、无错别字，需要用户购买 license 要在应用描述里写清楚；
* 如果提供的是体验版、单机版等非生成环境下的应用需要在 title 里注明。

有疑问请通过工单的方式和我们联系，谢谢！