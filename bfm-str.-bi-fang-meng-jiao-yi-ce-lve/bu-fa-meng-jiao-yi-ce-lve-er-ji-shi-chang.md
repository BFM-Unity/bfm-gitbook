# 比坊梦交易策略(二级市场)♟

{% hint style="info" %}
## 游戏已经开始，请选择你的英雄。

### 注：不同的英雄分属不同的派系，你只能选择一种。

### 开场后，请不要换英雄，否则[后果自负](https://www.bilibili.com/video/BV1hJ411G7jN)。
{% endhint %}

## 战士：价值投资策略（俗称：街头捡烟蒂，低估成长，集中投资）

* 巴菲特的，PE和ROE（[链接](https://xueqiu.com/8287840120/102600210)）
* 彼得·林奇的，PEG（[链接1](https://xueqiu.com/8287840120/83909262)，[链接2](https://xueqiu.com/8287840120/74917276)）
* [林园怎么投资](../bfm-trad.-bi-fang-meng-jin-dian/gu-piao-xin-xi-gong-ju/xuan-gu.md)

{% hint style="info" %}
[我怎么投资](../bfm-trad.-bi-fang-meng-jin-dian/gu-piao-xin-xi-gong-ju/xuan-gu.md)（✨🌟✨🌟回测结果在这里🌟✨🌟✨）
{% endhint %}

## 辅助：结构性收益策略（俗称：保护无知，构建组合，分散投资）

* （🔥）固定比例动态平衡（[香农的恶魔，凯利系统](https://www.sohu.com/a/279180185\_99931606)）【算数平均收益与几何平均收益之差】

> **香农阐述了一个通过随机游走赚钱的方法**。他让观众试想一只价格随机上下波动的股票，上下波动并不存在整体趋势。然后把一半资金投入股票，另一半放在“现金”账户中。**每天，股票的价格都会发生变化。每天中午你都要“调整”投资组合。**
>
> 也就是说，你要计算出整个投资组合（股票+现金账户）现在的价值，然后从股票投资中抽出一部分加到现金账户或者从现金账户抽出一部分加到股票投资当中，这样做的目的是与最初股票和现金投资各一半的组合方式保持一致。

> 香农系统假定的是一只股票的几何平均收益为0
>
> 真正想要赚钱的人应该遵循（普通）凯利赌徒的做法，总是追求最大几何平均数。当凯利赌徒被允许按任何比例拆分资金总额投入现金账户和随机游走的股票时，他会选择一半对一半的拆分方式，因为这样做的几何平均数最大。香农的计划是凯利赌博的一个特例。
>
> 由于算数平均收益总是高于几何平均收益，因此，一只几何平均收益为0（假设）的不稳定股票的算数平均收益一定为正值。

* [固定比例动态平衡多标的优化（4332221111准则，或322111准则）](../bfm-da-bi-fang-meng-shu-chan/zi-chan-pei-zhi/the-haab-calendar/zhuo-er-jin-sheng-ji-6-cang-wei-dan-yuan.md)
* 🔥 [帕累托分布与市值修正幂率投资法](../bfm-da-bi-fang-meng-shu-chan/zi-chan-pei-zhi/the-tzolkin-calendar/zhuo-er-jin-sheng-ji-10-shi-zhan-mi-xiu.md)（按照市值的N次幂（N取0～3）分配投资组合，再定期再平衡）（虽然这个链接是比特币，但是道理相同，也可以用于股票）
* [凯利公式](https://guhhhhaa.gitbook.io/joinquant/jin-rong-li-lun-zong-jie/zi-chan-pei-zhi)
* [**马科维兹均值方差模型**  与 **凯利准则（几何平均数准则）**结合](https://guhhhhaa.gitbook.io/joinquant/jin-rong-li-lun-zong-jie/zi-chan-pei-zhi)
* [同根策略 与 同架策略](https://guhhhhaa.gitbook.io/joinquant/jin-rong-li-lun-zong-jie/zi-chan-pei-zhi/tong-gen-ce-lve-yu-tong-jia-ce-lve)
* [cholesky分解策略](https://guhhhhaa.gitbook.io/joinquant/jin-rong-li-lun-zong-jie/zi-chan-pei-zhi/ruo-chen-de-ce-lve)

## 刺客：套利与流动性收益策略（俗称：低买高卖）

* （🔥）固定比例动态平衡（[香农的恶魔，凯利系统](https://www.sohu.com/a/279180185\_99931606)）【算数平均收益与几何平均收益之差】
* [网格交易策略](https://guhhhhaa.gitbook.io/joinquant/joinquant/pan-dian-ge-zhong-wang-ge)【[调和平均数均价买入，算数平均数均价卖出](https://guhhhhaa.gitbook.io/joinquant/joinquant/wang-ge-fu-ying-ying-an-die-dan-mai-de-tiao-he-ping-jun-zhang-dan-mai-de-suan-shu-ping-jun-ji-suan)】

> 网格交易是赚调和平均买入价和算数平均卖出价的差，
>
> 动态平衡交易是赚几何平均收益和算数平均收益的差。
>
> 网格交易假设调和平均买入价为0，那么算数平均卖出价大于调和平均买入价，差价为正值。
>
> 动态平衡交易假设几何平均收益为0，那么算数平均收益大于几何平均收益为正值。

* [定投【调和平均数均价买入】](https://m.sohu.com/a/372948519\_120052323)
  * [优化定投+定卖](https://mp.weixin.qq.com/s?\_\_biz=MzI5ODY5MTQwMA==\&mid=2247488396\&idx=1\&sn=418d4ffe5504c9d67356fa145dcadeb9\&scene=21#wechat\_redirect)
* [金字塔仓位管理法](https://guhhhhaa.gitbook.io/joinquant/jin-rong-li-lun-zong-jie/zi-chan-pei-zhi/jin-zi-ta-cang-wei-guan-li-fa) （金字塔加仓与金字塔减仓，“底仓与浮仓分配”仓位管理的极致）

## 射手：趋势性收益策略（俗称：追涨杀跌）

* 海龟策略（[唐奇安通道](https://www.zhihu.com/zvideo/1386620312193126400)，[ATR开平仓止盈止损](https://www.zhihu.com/zvideo/1408466616892313601)）
* 美林时钟
* [大小市值轮动策略，二八轮动](http://www.360doc.cn/mip/554655681.html)
  * [抱团股会一直涨？无脑执行大小盘轮动策略，轻松跑赢指数5倍](https://mp.weixin.qq.com/s?\_\_biz=MzI5ODY5MTQwMA==\&mid=2247488496\&idx=1\&sn=05754fa8f993b802eaf5d0592496a0c7\&scene=21#wechat\_redirect)
  * [币圈轮动](https://mp.weixin.qq.com/s?\_\_biz=MzI5ODY5MTQwMA==\&mid=2247488576\&idx=1\&sn=015e9165bd427048214359cb4403889c\&chksm=eca0aa67dbd72371f4915c9e1e100825c7744d81e59292e464b0e1e067dfdd2d346cd0a07d87\&scene=178\&cur\_album\_id=1823729338689585161#rd)
* 布林带通道策略（这个不给链接，你自己去搜，出来一堆）
* 双均线策略（这个不给链接，你自己去搜，出来一堆）

{% content-ref url="../bfm-trad.-bi-fang-meng-jin-dian/gu-piao-xin-xi-gong-ju/xuan-gu.md" %}
[xuan-gu.md](../bfm-trad.-bi-fang-meng-jin-dian/gu-piao-xin-xi-gong-ju/xuan-gu.md)
{% endcontent-ref %}

## 法师：赌博策略（就是赌博）

* 马丁格尔(Martingale)策略（等价鞅，亏损加倍投注）
* 反马丁格尔(Anti-Martingale)策略（反等价鞅，盈利加倍投注）

（这个不给链接，你自己去搜，出来一堆）

{% embed url="https://m.hexun.com/futures/2014-08-27/167930226.html" %}

## 不想玩游戏了？可以去抢游戏之神特图的星杯

* [卓尔金历法](../bfm-da-bi-fang-meng-shu-chan/zi-chan-pei-zhi/the-tzolkin-calendar/)
  * 智能投顾表格，帮您轻松确定杠杆率，抄底+逃顶
  * **MVRV+S2F+币圈美林时钟+凯利准则收益率和收益率方差控制最大杠杆率+激活函数神经元最终确定仓位+帕累托分布+香农的恶魔+山寨币指数+市值占比幂率修正—共同构筑的基于Excel表格的策略！**
*   [BFM算法](../bfm-rins.-bi-fang-meng-ke-xue-yan-jiu-yuan/suan-fa-yan-jiu-yuan.md)

    三角套利的升级与扩展+O(N^3)算法优化的极致+FPGA硬件级别优化+量子退火未来发展
