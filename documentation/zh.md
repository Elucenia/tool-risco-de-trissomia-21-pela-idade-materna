<!-- ELUCENIA technical documentation · risco-de-trissomia-21-pela-idade-materna · zh · no clinical/professional/rights approval -->

# 根据母亲年龄估算唐氏综合征风险

[条件、来源与许可](https://elucenia.org/zh/tools/risco-de-trissomia-21-pela-idade-materna)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 预产期时母亲年龄

`idade`

年 · 范围: 15–50

## 方法版本

Morris–Mutton–Alberman 2002：英格兰/威尔士1989–1998活产逻辑模型；非通用孕期风险

## 已记录的公式

Morris, Mutton, Alberman (2002): 风险 = 1 ÷ \[1 + e(7.330 − 4.211 ÷ (1 + e−0.282 × (年龄 − 37.23)))\]

逻辑模型拟合英格兰及威尔士全国唐氏综合征登记数据（1989至1998），校正至无筛查和终止妊娠情形。

## 限制与适用人群

此公式依据英格兰和威尔士1989–1998年数据，按母亲年龄描述活产儿唐氏综合征患病率，估计无筛查和选择性终止妊娠的情况。它不能提供任意孕周的风险，也不能代替个体筛查或诊断。

## 参考文献

- [Morris JK, Mutton DE, Alberman E. Revised estimates of the maternal age specific live birth prevalence of Down's syndrome. J Med Screen, 2002.](https://doi.org/10.1136/jms.9.1.2)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

35岁时的基线（先验）风险：0.28%

| 结果详情 | |
| --- | --- |
| 概率 | 0.283% |

这是起始风险：联合筛查或 NIPT 会将其上调或下调。


### 2

40岁时的基线（先验）风险：1.16%

| 结果详情 | |
| --- | --- |
| 概率 | 1.164% |

这是起始风险：联合筛查或 NIPT 会将其上调或下调。


### 3

25岁时的基线（先验）风险：0.07%

| 结果详情 | |
| --- | --- |
| 概率 | 0.075% |

这是起始风险：联合筛查或 NIPT 会将其上调或下调。

