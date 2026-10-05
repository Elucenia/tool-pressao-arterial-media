<!-- ELUCENIA technical documentation · pressao-arterial-media · zh · no clinical/professional/rights approval -->

# 平均动脉压与脉压

[条件、来源与许可](https://elucenia.org/zh/tools/pressao-arterial-media)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 收缩压

`pas`

mmHg · 范围: 50–300

### 舒张压

`pad`

mmHg · 范围: 20–200

## 方法版本

平均压=(收缩压+2舒张压)/3；脉压=收缩压−舒张压；常规心律成人近似；巴西指南2020

## 已记录的公式

平均动脉压 = 舒张压 + (收缩压 − 舒张压) ÷ 3

脉压 = 收缩压 − 舒张压

## 限制与适用人群

根据 AHA 2019 声明，以舒张压加三分之一脉压近似平均动脉压，前提是心率正常；它不是对压力波形的直接积分。请使用通过适当技术和设备测得的 mmHg 单位收缩压、舒张压，并记录测量条件。收缩压减舒张压是脉压，而不是脉率。单一结果不能确立高血压诊断，也不能作为危重患者的通用目标。

## 参考文献

- [Barroso WKS et al. Diretrizes Brasileiras de Hipertensão Arterial – 2020. Arq Bras Cardiol, 2021.](https://doi.org/10.36660/abc.20201238)

- [AHA scientific statement2019,Measurement of Blood Pressure in Humans](https://pmc.ncbi.nlm.nih.gov/articles/PMC11409525/)

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
