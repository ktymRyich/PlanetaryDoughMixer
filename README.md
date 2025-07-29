# 遊星歯車式手回し生地こね器 / Planetary Dough Mixer

## 概要 / Overview

遊星歯車機構を用いた手回し式の生地こね器です。
軽くてよく膨らむ高加水の生地は粘度が高く、手ごねでは扱うのが困難です。
このこね器を利用すれば、高加水の生地を簡単に作ることができます。
さらに、生地の発酵用容器とバジル栽培用植木鉢も同梱しています。

A hand-cranked dough mixer utilizing a planetary gear mechanism. The efficient kneading motion allows you to easily make delicious dough. Also includes fermentation container and basil planter designs.

## 特徴 / Features

-   🔧 **遊星歯車機構**: 効率的な減速比で軽い力でもしっかりと混練
-   � **生地こね専用設計**: 最適な混練パターンでグルテンを効果的に形成
-   🖨️ **3D プリンタ対応**: 家庭用 3D プリンタで製作可能
-   📐 **複数フォーマット対応**: STEP、F3D、STL ファイルを提供
-   🌱 **発酵・栽培セット**: 発酵容器とバジル植木鉢も同梱

## デモ動画 / Demo Video

組み立てや使用方法については以下の動画をご覧ください：

[![Demo Video](https://img.youtube.com/vi/wXSlv8LYxr4/0.jpg)](https://youtu.be/wXSlv8LYxr4)

## ファイル構成 / File Structure

```
PlanetaryDoughMixer/
├── README.md           # このファイル
├── ver2pdm 図面.pdf     # 設計図面
├── planetaryDoughMixer/
│   ├── pdm.f3d         # Fusion 360形式（編集可能）
│   ├── pdm.step        # STEP形式（CAD互換）
│   └── pdm.stl         # STL形式（3Dプリント用）
├── fermantationCase/
│   ├── fermantationCase.f3d
│   ├── fermantationCase.step
│   └── fermantationCase.stl
└── basilPlanter/
    ├── basilPlanter.f3d
    ├── basilPlanter.step
    └── basilPlanter.stl
```

## 必要な材料 / Required Materials

### 3D プリント部品 / 3D Printed Parts

#### メインミキサー / Main Mixer

-   遊星歯車セット（サンギア、プラネットギア、リングギア）x 3
-   クランクハンドル
-   蓋と底

#### オプション / Optional

-   発酵容器（fermantationCase）
-   バジル植木鉢（basilPlanter）

### 追加部品 / Additional Components

-   ベアリング（NTN 625ZZ 推奨）
-   混練ボウル

## 印刷設定 / Print Settings

### 推奨設定 / Recommended Settings

-   **レイヤー高**: 0.2mm
-   **充填率**: 20-30%
-   **サポート**: ハンドル部分とオーバーハング部分で必要
-   **材質**: PETG 推奨（メインミキサー）、PLA 可（発酵容器・植木鉢）

### 部品別印刷設定 / Part-specific Print Settings

#### メインミキサー / Main Mixer

-   **材質**: PETG 推奨（強度重視）
-   **壁の層数**: 2-3 層

#### 発酵容器・植木鉢 / Fermentation Case & Basil Planter

-   **材質**: PLA 可
-   **壁の層数**: 4 層以上推奨（水密性・耐久性向上）

### 印刷順序 / Print Order

1. ギア部品（精度重要）
2. ハウジング
3. ハンドル部品

## 組み立て手順 / Assembly Instructions

1. **ベアリングの取り付け**
    - 各回転部にベアリング（625ZZ）を圧入
2. **ギア機構の組み立て**
    - サンギア、プラネットギア、リングギアを順番に組み立て
3. **ハウジングへの取り付け**
    - 組み立てたギア機構をハウジングに固定
    - 3 つのギア機構どうしは軸とともに GP ボンドで接着
4. **クランクハンドルの取り付け**
    - ハンドルを入力軸に接続

詳細な組み立て手順は[デモ動画](https://youtu.be/wXSlv8LYxr4)をご参照ください。

## 使用方法 / Usage

1. ミキシングボウルに小麦粉と水を入れる（加水率は 80%を推奨）
2. ボウルを滑り止めなどで固定
3. クランクハンドルを回転させる
4. 10-20 分程度混練を続ける

## カスタマイズ / Customization

### Fusion 360 での編集 / Editing in Fusion 360

`pdm.f3d`ファイルを Fusion 360 で開くことで、設計を自由に変更できます。

### 可能な改造例 / Possible Modifications

-   ギア比の変更
-   ボウルサイズの調整
-   ハンドル形状の変更

## トラブルシューティング / Troubleshooting

### よくある問題 / Common Issues

**ギアが重い / Gears are heavy**

-   ベアリングの取り付けを確認
-   印刷精度を確認（オーバーハングやサポート跡）

**混練が不十分 / Insufficient kneading**

-   回転速度を調整
-   生地の水分量を確認

## ライセンス / License

このプロジェクトはオープンソースです。個人利用・商用利用を問わず自由にご利用ください。

改良版や派生作品を作成された場合は、ぜひ共有してください！

## 貢献 / Contributing

改善提案やバグ報告は Issues でお待ちしています。プルリクエストも歓迎です。

## 作者 / Author

設計・開発に関する質問やフィードバックはお気軽にどうぞ。

---

**注意**: 3D プリント品質により強度が変わります。使用前に各部品の状態を確認してください。
