# 第三堂课总结

**<font size=4>航71  朱洁松  2017012150</font>**

## Python初步教程

**已掌握**

## Python库

**多刷题**

* numpy 矩阵计算
* pandas 表格
* matplotlib.py 绘图
* seaborn 绘图

## 因子投资

### 因子投资的发展

* 单因子
* 多因子
* 市场异常汇报
* 因子投资

### 美股因子分析

市场（市值）、规模、**价值**（账面市值比）、动量（涨幅）、风险（相对大盘beta）、质量（利润率）

EW均值、VM均股。EW>VM说明小市值的股跑赢了大市值股

### 因子测试

做多指标最高的股票组，做空指标最低的股票组，每年再平衡

零投资组合

## 创建交易策略

### 趋势跟随型策略

* 发现趋势苗头
* 顺着趋势方向下注
* 遵循“截断亏损，让利润奔跑”的原则

### 交易策略的要点

* 市场：买卖什么
* 头寸：买卖多少
* 入市：买卖时间
* 止损：卖出亏损头寸
* 退出：退出盈利头寸
* 战术：怎么买卖

### 头寸规模

定义波动性N：N=(19*PDN+TR)/20

PDN：前一日的N值

TR：当日的真实波动幅度，等于Max(H-L,H-PDC,PDC-L)

H：当日最高价、L：当日最低价、PDC：前日收盘价

头寸规模单位 = 账户的1%/(N*每一最小交易单位的资金)

举例：账户100万，股票波动性是5元，则买入的头寸规模为20手。

> 手是最小交易单位，1手为100股。
>
> 头寸规模有上限

### 入市信号

以20日突破为基础的短期系统，以及以55日为突破的长期系统

> 何为突破？价格升破前一高位或跌破前一低位

### 逐步建仓

* 在突破点建立一个单位的头寸

* 按N/2的价格间隔逐步扩大头寸

* 直到达到头寸规模上限

### 止损

海龟止损标准：任何一笔交易的风险程度不超过账户的2%

价格变动的上线就是2N，对于加仓情况，止损点上浮

### 退出

10日反向突破退出，或20日反向突破退出