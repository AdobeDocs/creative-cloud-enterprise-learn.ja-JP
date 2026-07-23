---
title: テンプレートライブラリ
description: プロジェクトに合わせてカスタマイズできる既製のFireflyグラフテンプレートを参照
feature: Image Editing, Gen AI
role: User
level: Beginner
jira: KT-
hide: true
hidefromtoc: true
source-git-commit: b19c93a5c0f7b0009a17ae97eb35f6738cf21630
workflow-type: tm+mt
source-wordcount: '672'
ht-degree: 3%

---

# &#x200B;5. テンプレートライブラリ

Fireflyグラフのテンプレートのクイックリファレンス索引で、各テンプレートが生成または実行する内容ごとに分類されています。 すべての例は出発点となります。つまり、独自のブランド、製品、プロンプトを入れ替えてから、本番環境でテンプレートを使用します。

## 画像の生成とスタイル

| グラフテンプレート | 説明 | [!BADGE ユースケース]{type=Informative tooltip="活用例"} |
|---|---|---|
| [**はじめに – 画像を生成する**](/help/firefly/graph/templates/get-started-gen-image.md) | このテンプレートは基本的なグラフです。つまり、1つのプロンプトノードを1つの生成ノードに1つの出力に変換します。 | 小売、健康、教育 |
| [**一貫した文字生成**](/help/firefly/graph/templates/character-gen.md) | このグラフテンプレートでは、キャラクタの1つのリファレンスイメージをロードし、新しいショットごとにシーンまたはポーズのプロンプトを入れ替えます。 | 旅行、小売、教育 |
| [**スタイル抽出**](/help/firefly/graph/templates/style-extraction.md) | このグラフテンプレートでは、参照画像を使用してカラー、ライト、テクスチャの処理を抽出します。 | 旅行、小売、飲料 |
| [**夕焼けの雰囲気**](/help/firefly/graph/templates/sunset-vibes.md) | このグラフテンプレートでは、テキストプロンプトから3Dタイポグラフィ画像を作成できます。 | 旅行、飲料、小売 |

## セグメント化と合成

| グラフテンプレート | 説明 | [!BADGE ユースケース]{type=Informative tooltip="活用例"} |
|---|---|---|
| [**はじめに – 画像をセグメント化する**](/help/firefly/graph/templates/get-started-segment-image.md) | このグラフテンプレートでは、任意のソース画像を読み込み、セグメントノードを実行して、被写体を背景から分離します。 | 健康、小売、自動車 |
| [**レイヤーの合成とブレンド**](/help/firefly/graph/templates/composite-blend-layers.md) | このグラフテンプレートでは、製品のカットアウトと背景シーンを別々のレイヤー入力として重ねます。 | 飲み物、小売、旅行 |
| [**特定色域の選択の補正**](/help/firefly/graph/templates/selective-color-correction.md) | このグラフテンプレートでは、修正が必要な特定の領域をマスクし、そのノードのみにターゲットカラーを設定します。 | 通信および通信、小売、財務 |

## ビデオとモーション

| グラフテンプレート | 説明 | [!BADGE ユースケース]{type=Informative tooltip="活用例"} |
|---|---|---|
| [**はじめに – ビデオの生成**](/help/firefly/graph/templates/get-started-video-gen.md) | このグラフテンプレートでは、承認済みの静止画キーアートとショートモーションプロンプトをフィードします。 | 金融、飲料、小売 |
| [**Bullet Time VFX**](/help/firefly/graph/templates/bullet-time-vfx.md) | このグラフテンプレートでは、ヒーロー製品または被写体画像にフィードして、その周りに角度を持った回転シーケンスを生成し、フリーズしたフレームスイープを自動的にステッチします。 | アウトドア、小売、自動車 |

## ストーリーボード

| グラフテンプレート | 説明 | [!BADGE ユースケース]{type=Informative tooltip="活用例"} |
|---|---|---|
| [**ストーリーボードへのテキスト**](/help/firefly/graph/templates/text-to-storyboard.md) | このグラフテンプレートでは、テキスト入力ノードをストーリーのエレメントに置き換えます。 | 財務、小売、テクノロジー |
| [**ストーリーボードビルダー**](/help/firefly/graph/templates/storyboard-builder.md) | このグラフテンプレートでは、ストーリーのビートごとに1つのノードを追加して、シーンごとにストーリーボードのシーンを構築します。 | 通信および通信、飲み物、旅行 |

## 3Dと文字

| グラフテンプレート | 説明 | [!BADGE ユースケース]{type=Informative tooltip="活用例"} |
|---|---|---|
| [**リアルタイムシェーダー**](/help/firefly/graph/templates/real-time-shaders.md) | このグラフテンプレートでは、イメージから始めて、3つの異なるカスタムシェーダを適用し、結果をリアルタイムでプレビューします。 | テクノロジー、自動車、小売 |
| [**文字モデルの生成**](/help/firefly/graph/templates/character-model-generation.md) | このグラフテンプレートでは、イラストの3Dアニメーションスタイルを作成します。 | アウトドア、テクノロジー、教育 |
| [**ビニール玩具のデザイン**](/help/firefly/graph/templates/vinyl-toy-design.md) | このグラフテンプレートでは、キャラクターまたはマスコットのリファレンスを入力し、それをスタイライズされたビニールのおもちゃの形式でレンダリングします。 | 小売、飲料、エンターテイメント |
| [**スケッチして3Dに変換**](/help/firefly/graph/templates/sketch-to-3d.md) | このグラフテンプレートでは、スケッチを3D文字に変換します。 | テクノロジー、自動車、エンターテイメント |

## 製品とブランドのモックアップ

| グラフテンプレート | 説明 | [!BADGE ユースケース]{type=Informative tooltip="活用例"} |
|---|---|---|
| [**ブランディングの視覚化**](/help/firefly/graph/templates/branding-visualization.md) | このグラフテンプレートでは、製品のシーンでロゴやブランドを視覚化する方法について説明します。 | テクノロジー、飲み物、金融 |
| [**ブランド製品のモックアップ**](/help/firefly/graph/templates/brand-product-mockup.md) | このグラフテンプレートでは、様々なシーンで製品を視覚化する方法を学習します。 | 小売、飲料、テクノロジー |
| [**エディトリアル写真**](/help/firefly/graph/templates/editorial-photoshoot.md) | このグラフテンプレートでは、モデルリファレンスをロードし、新しい外観ごとに服飾の入力を入れ替えます。 | 小売業、美容業、アウトドア |
| [**フォトスタジオ**](/help/firefly/graph/templates/photography-studio.md) | このグラフテンプレートでは、スタジオの背景に製品のレンダリングを配置し、結果が実際のスタジオのキャプチャのように読み取られるまで照明を調整します。 | 飲料、技術、小売 |
| [**デカールをサーフェスに適用**](/help/firefly/graph/templates/decal-to-surfaces.md) | このグラフテンプレートで、ベース製品のモックアップとデカールまたはロゴアセットを個別の入力値として読み込みます。 | アウトドア、自動車、小売 |

## バッチ処理と整合性処理

| グラフテンプレート | 説明 | [!BADGE ユースケース]{type=Informative tooltip="活用例"} |
|---|---|---|
| [**デザインシステムジェネレーター**](/help/firefly/graph/templates/design-system-generator.md) | このグラフテンプレートでは、webサイトのスクリーンショットに基づいてデザインシステムを生成します。 | テクノロジー、金融、コミュニケーション、通信 |
| [**顔写真の生成**](/help/firefly/graph/templates/headshots-generation.md) | このグラフテンプレートでは、企業の顔写真を一括して調和させます。 | テクノロジー、金融、医療 |

[Fireflyグラフの使い方](https://experienceleague.adobe.com/ja/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/overview-firefly-graph)に戻ります。