# 卓尔金升级3——智能实验

## 卓尔金历法实验室

{% content-ref url="../../../bfm-rins.-wei-mian-jian-meng-ke-xue-yan-jiu-yuan/shu-xue-li-qi.md" %}
[shu-xue-li-qi.md](../../../bfm-rins.-wei-mian-jian-meng-ke-xue-yan-jiu-yuan/shu-xue-li-qi.md)
{% endcontent-ref %}

## 1，无监督学习的归一化操作伪代码——

适用于任何**无顺序状态数据**（**不管数据分布如何**），应用sigmod函数之前的**归一化操作**：

```python
定义 a_1, b_1
定义 f_1(), f_2()

f_2() = LN(f_1()/a_1)
        /b_1 
        * 4 
# 因为sigmod函数x取(-4,4)时，y在约(0,1), 所以这里最后*4
# 你也可以*5，大概覆盖增长区间就行

a_1 = 几何平均数(f_1()) 
# 几何平均数：GEOMEAN

b_1 =  (算术平均数(极大值(LN(f_1()/a_1),N)
      - 算术平均数(极小值(LN(f_1()/a_1),N))
      / 2
# 算数平均数：AVERAGE
```
