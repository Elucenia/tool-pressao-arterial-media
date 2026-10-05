<!-- ELUCENIA technical documentation · pressao-arterial-media · ja · no clinical/professional/rights approval -->

# 平均動脈圧・脈圧

[条件・出典・許諾](https://elucenia.org/ja/tools/pressao-arterial-media)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 収縮期血圧

`pas`

mmHg · 範囲: 50–300

### 拡張期血圧

`pad`

mmHg · 範囲: 20–200

## 方法の版

平均圧=(収縮期+2拡張期)/3、脈圧=収縮期−拡張期、通常の心拍リズムの成人近似、ブラジル指針2020

## 記載された計算式

平均動脈圧 = 拡張期血圧 + (収縮期血圧 − 拡張期血圧) ÷ 3

脈圧 = 収縮期血圧 − 拡張期血圧

## 限界・対象集団

AHA 2019 声明では、拡張期血圧に脈圧の 3 分の 1 を加える近似は正常な心拍数を前提とします。圧波形の直接積分ではありません。適切な手技と機器で測定した mmHg 単位の収縮期・拡張期血圧を用い、測定条件を記録してください。収縮期血圧から拡張期血圧を引いたものは脈圧であり、脈拍数ではありません。結果単独で高血圧を診断したり、すべての重症患者の目標を設定したりするものではありません。

## 参考文献

- [Barroso WKS et al. Diretrizes Brasileiras de Hipertensão Arterial – 2020. Arq Bras Cardiol, 2021.](https://doi.org/10.36660/abc.20201238)

- [AHA scientific statement2019,Measurement of Blood Pressure in Humans](https://pmc.ncbi.nlm.nih.gov/articles/PMC11409525/)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026
