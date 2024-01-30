---
description: The Tzolkin Calendar
---

# 战略资产配置——卓尔金历 🕙

> My clock is paper financial time 我的**时钟**显示账面的**金融时间**
>
> ——[《C》- 岩崎琢](https://music.163.com/#/song?id=22713696)

> 歌者启动了**大眼睛**的进程。
>
> —— 《三体》- 刘慈欣

> [什么是卓尔金历？](https://www.jianshu.com/p/5b3a31f95a1d)

![](<../../.gitbook/assets/image (58).png>)

{% hint style="success" %}
### **现在部署你的飞行船：**

## [简版飞行船0.3](https://share.weiyun.com/57ZJmSnA)**（新版推荐🔥，需输入你的Glassnode API）**

### [**简版飞行船0.2**](https://share.weiyun.com/bky3C7YB)

[**简版飞行船0.1**](https://share.weiyun.com/6A8bEuC2)

[**飞行船6.12**](https://share.weiyun.com/LhAj6uYm)（大型旧版，表格在此下载，不推荐）
{% endhint %}

{% hint style="success" %}
#### [教程视频1](https://www.bilibili.com/video/BV1K64y1S7FS) | [教程视频2](https://www.bilibili.com/video/BV16X4y1g7tH/) | [宣传视频1](https://www.bilibili.com/video/BV13x411R7Lf) | [宣传视频2](https://www.bilibili.com/video/BV1zW411D7gJ)

#### [卓尔金历法纪念NFT（共100枚）](https://opensea.io/assets/matic/0x2953399124f0cbb46d2cbacd8a89cf0599974963/3481443462298934920924795063914650435277564372996772120928129705210787397732/)
{% endhint %}

{% hint style="info" %}
[**cryptosheets**](https://cryptosheets.com/) **|** [templates](https://cryptosheets.com/templates) | [templates2](https://app.cryptosheets.com/#/browse/templates) Excel 插件/模版

#### [微软Excel在线版](https://www.office.com/launch/excel?ui=zh-CN\&auth=1) | [谷歌Sheet在线版](https://docs.google.com/spreadsheets/u/0/)
{% endhint %}

## **介绍一下这个策略**

<details>

<summary>介绍一下这个策略</summary>

这个策略有如下特点：&#x20;

1，未经证实的规律&#x20;

2，长期跨周期策略，跨越牛市，熊市，震荡市&#x20;

3，需要做多做空，但是杠杆率不会超过2或-1&#x20;

4，基于Excel和CryptoSheets插件读取MVRV和S2F数据&#x20;

5，需要读取和判断历史周期的顶，底，减半时间&#x20;

6，基于山寨币指标数据来控制是否投资山寨币，并根据市值比例^幂律修正确定最终比例。&#x20;

7，底层策略是再平衡策略（Rebanlance）&#x20;

8，是一坨屎山&#x20;

9，现在用Excel表格做一个简版的半自动的，未来可能用KDE核密度估计

MVRV+S2F——>仓位杠杆率&#x20;

山寨币指标——>市值占比修正幂律因子——>市值占比修正幂律&#x20;

仓位杠杆率+市值^市值占比修正幂律——>最终各个币种的仓位比例

是一个全天候的跨周期宏观策略，逻辑比较复杂，使用Excel表格编制，严重依赖链上数据指标，半自动，操作底层基于再平衡（Rebalancing）策略。

这个策略有如下特点：&#x20;

1，未经证实的规律&#x20;

2，长期跨周期策略，跨越牛市，熊市，震荡市&#x20;

3，需要做多做空，但是杠杆率不会超过2或-1&#x20;

4，基于Excel和CryptoSheets插件读取MVRV和S2F数据&#x20;

5，需要读取和判断历史周期的顶，底，减半时间&#x20;

6，基于山寨币指标数据来控制是否投资山寨币，并根据市值比例^幂律修正确定最终比例。&#x20;

7，底层策略是再平衡策略（Rebalancing）&#x20;

8，是一坨屎山&#x20;

9，逻辑复杂，重构困难，只能作为灵感&#x20;

10，现在用Excel表格做一个简版的半自动的，未来可能用KDE核密度估计

策略主要逻辑：

MVRV+S2F——>仓位杠杆率&#x20;

山寨币指标——>市值占比修正幂律因子——>市值占比修正幂律&#x20;

仓位杠杆率+(市值^市值占比修正幂律)——>最终各个币种的仓位比例

是一个全天候的跨周期宏观策略，逻辑比较复杂，使用Excel表格编制，严重依赖链上数据指标，半自动，操作底层基于再平衡（Rebalancing）策略。

可以理解为：币圈的美林时钟，币圈的宏观调控核按钮，或，如何从零开始建立币圈宏观调控政策。

山寨季节指标=100个包括比特币的山寨币中，有多少山寨币比比特币收益高。&#x20;

市值占比修正幂率因子=山寨季节指标/50－1&#x20;

市值占比修正幂率=EXP（市值占比修正幂率因子）&#x20;

币种权重=币种市值占比^市值占比修正幂率&#x20;

币种比例=币种权重/SUM（币种权重）

然后把币种比例，导入再平衡策略。

这种诡异的思路，一般人想不出来，但是很合理。

当然，需要你自己选择币种，再根据市值算市值占比。

我直接用市场数据决定比例，连上再平衡策略，就不需要人工智能或者自己判断了。也不需要K线或者技术指标。

以前看到再平衡策略有这样的：

按照市值比例决定，按照平均比例决定，按照根号市值决定，我就想能不能做个统一的策略，

然后我想到了按照市值的一定的次幂决定比例，但是这个次幂到底是多少呢？

然后我想到了山寨季节指标，能判断山寨季节，但是山寨季节指标怎么和幂率连接在一起呢？

后来，我发现了

1，市值占比修正因子=山寨季节指标/50－1&#x20;

2，市值占比修正幂率=EXP（市值占比修正幂率因子） 这两个公式，于是一切就连接起来了。

然后我就只需要选择币种，不需要判断是什么行情了。

再平衡策略还有很多变种，比如

凯利公式（加权=收益/方差），

马科维兹（加权=收益/标准差），

桥水全天候（加权=1/标准差），

指数基金（加权=市值），

主动性基金（加权=市值^修正幂率），大概这样。

这些都是再平衡策略。

再平衡又叫，香农的恶魔，是信息论祖师爷香农提出的，我只知道这些。

如果你想坐庄，你应该只关心，配比，和杠杆率，不要关心价格。

配比，可以靠收益率，波动率，市值，市值季节指标来决定。

杠杆率，需要宏观指标决定，比如在加密币市场，我发现的宏观指标是链上数据，如MVRV，S2F，NVT。如果是传统金融市场，杠杆率的决定和GDP，CPI，PMI，或者货币，信贷有关。

坐庄就是做市商，你是不是做市商，和策略有关，和思路有关，与资金量无关。

因为韭菜看的是技术指标，消息面，价格曲线，他们在预测什么时间能涨到什么价格。&#x20;

做市商关心的是杠杆率，仓位配比，市值季节，牛熊周期。他们不会预测价格，只会判断周期阶段。

但是最牛逼的是两种人，拿着狗屎的人，拿着比特以太的人。 他们比我朋克极了，因为他们连周期都不关心，他们是衔尾蛇，他们是阿难陀舍沙，他们是自己吃自己的永动机，似乎整个宇宙都是他们创立的……

还有更朋克的黑客，他们甚至连钱到底是谁的，都不关心。

</details>

## **周期发现**

![](../../.gitbook/assets/卓尔金历法-大周期.png)

## 归纳推理

![卓尔金历法](../../.gitbook/assets/卓尔金历法-领航舵.png)

![图中数字指的是推荐仓位](../../.gitbook/assets/卓尔金历法-雷达.png)

## **历法**说明

**顺着三角形顺时针运行，**

**红色是牛市，绿色是熊市，蓝色是震荡市。**

**从蓝色到红色，减半开始，此时需要加杠杆，满仓多。**

**顺时针运行 ，落到第一个黑色框，就是牛市顶峰，熊市开始，可以做空。**

**顺时针运行 ，落到第二个黑色框，就是熊市底部，可以入场开网格。**

**就像一个时钟一样，很方便。**

## **美林时钟**

![](<../../.gitbook/assets/屏幕快照 2021-04-03 上午10.44.27.png>)

## 参数设置

\-1，2，4 或 -1.5，3，4

1，0，0.5

## 回测结果

![](<../../.gitbook/assets/屏幕快照 2021-09-20 上午11.47.15.png>)

{% content-ref url="zhuo-er-jin-li-fa-de-sheng-ji-1-ni-he-han-shu.md" %}
[zhuo-er-jin-li-fa-de-sheng-ji-1-ni-he-han-shu.md](zhuo-er-jin-li-fa-de-sheng-ji-1-ni-he-han-shu.md)
{% endcontent-ref %}

{% content-ref url="zhuo-er-jin-li-fa-de-sheng-ji-2-wu-cha-fen-xi.md" %}
[zhuo-er-jin-li-fa-de-sheng-ji-2-wu-cha-fen-xi.md](zhuo-er-jin-li-fa-de-sheng-ji-2-wu-cha-fen-xi.md)
{% endcontent-ref %}

{% content-ref url="zhuo-er-jin-sheng-ji-3-zhi-neng-shi-yan.md" %}
[zhuo-er-jin-sheng-ji-3-zhi-neng-shi-yan.md](zhuo-er-jin-sheng-ji-3-zhi-neng-shi-yan.md)
{% endcontent-ref %}

{% content-ref url="zhuo-er-jin-sheng-ji-3-tu-ling-wan-bei.md" %}
[zhuo-er-jin-sheng-ji-3-tu-ling-wan-bei.md](zhuo-er-jin-sheng-ji-3-tu-ling-wan-bei.md)
{% endcontent-ref %}

{% content-ref url="zhuo-er-jin-sheng-ji-4-dong-tai-tu-biao.md" %}
[zhuo-er-jin-sheng-ji-4-dong-tai-tu-biao.md](zhuo-er-jin-sheng-ji-4-dong-tai-tu-biao.md)
{% endcontent-ref %}

{% content-ref url="zhuo-er-jin-sheng-ji-5-shen-jing-wang-luo.md" %}
[zhuo-er-jin-sheng-ji-5-shen-jing-wang-luo.md](zhuo-er-jin-sheng-ji-5-shen-jing-wang-luo.md)
{% endcontent-ref %}

{% content-ref url="../the-haab-calendar/zhuo-er-jin-sheng-ji-6-cang-wei-dan-yuan.md" %}
[zhuo-er-jin-sheng-ji-6-cang-wei-dan-yuan.md](../the-haab-calendar/zhuo-er-jin-sheng-ji-6-cang-wei-dan-yuan.md)
{% endcontent-ref %}

{% content-ref url="zhuo-er-jin-sheng-ji-7-yin-li-tou-jing.md" %}
[zhuo-er-jin-sheng-ji-7-yin-li-tou-jing.md](zhuo-er-jin-sheng-ji-7-yin-li-tou-jing.md)
{% endcontent-ref %}

{% content-ref url="zhuo-er-jin-sheng-ji-8-huo-bi-zheng-ce.md" %}
[zhuo-er-jin-sheng-ji-8-huo-bi-zheng-ce.md](zhuo-er-jin-sheng-ji-8-huo-bi-zheng-ce.md)
{% endcontent-ref %}

{% content-ref url="the-tzolkin-calendar-0.md" %}
[the-tzolkin-calendar-0.md](the-tzolkin-calendar-0.md)
{% endcontent-ref %}

## 友情链接

{% hint style="success" %}
### 如果实在不会破解 **MicroSoft** Office **365**

#### 建议直接使用[拼多多](https://yangkeduo.com/search\_result.html?search\_key=office%20365%20mac)，

#### 拼多多上，只需要¥十几块，就可以一对一指导破解安装。

**推荐下载最新版的 MicroSoft 365 for Windows/Mac，这样才能支持CryptoSheets 插件扩展。**
{% endhint %}

{% content-ref url="zhuo-er-jin-sheng-ji-a2-can-shu-du-qu.md" %}
[zhuo-er-jin-sheng-ji-a2-can-shu-du-qu.md](zhuo-er-jin-sheng-ji-a2-can-shu-du-qu.md)
{% endcontent-ref %}

{% embed url="https://www.coolhub.top/" %}

{% embed url="https://otp.landian.vip/zh-cn/download.html" %}

{% embed url="http://www.52pjb.net/xiazai/26220.html#xzdz" %}

{% embed url="http://www.52pjb.net/xiazai/office/551.html" %}

{% embed url="https://qiujunya.com/article/2020/12/18/144.html" %}

链接: [https://pan.baidu.com/s/19aD-i0B7khux5R5xiYtPig](https://pan.baidu.com/s/19aD-i0B7khux5R5xiYtPig) 密码: eint--来自百度网盘超级会员V5的分享

{% embed url="https://camrojud.com/microsoft-office-365-product-key-crack-2020-for-mac-free-download/" %}

#### How to Activate & Crack Office 365 Lifetime?

1. First of all, [Download](https://www.microsoft.com/en-us/download/details.aspx?id=55942) the full version here
2. Install it.
3. Copy the product key and paste it into your software.
4. Please wait a few seconds, and It is a lifetime cracked.

{% embed url="https://sufan.maytide.net/read.php/1871.htm" %}
