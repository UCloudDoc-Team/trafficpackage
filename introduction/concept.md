# 什么是共享流量包

## 产品简介

共享流量包UTP（UCloud Traffic Package）是预付费流量套餐产品，流量包购买后立即生效，并自动抵扣对应地域流量计费EIP产生的公网流量费用。相比于流量后付费，共享流量包具有易于管理、单价更低等优势。流量包过期或流量用尽，则该流量包失效。未失效的流量包不支持删除退费。


## 产品类型
支持全时流程包和闲时流量包，闲时时段会优先抵扣闲时流量包。同类型生效中的流量包存在多个时，则优先抵扣最先到期的流量包。
* 全时流量包的生效时间为资源所属地域的00:00-24:00。
* 闲时流量包的生效时间为资源所属地域的00:00-08:00。



## 使用限制
* 共享流量包不支持调整配置和续费，不支持删除退费。流量包到期后支持删除资源，不支持退款。
* 每个地域最多可存在20个生效中的流量包，包含全时流量包和闲时流量包。
* 抵扣该地域所有流量计费EIP产生的IPv4流量，不包含精品BGP类型的流量。

