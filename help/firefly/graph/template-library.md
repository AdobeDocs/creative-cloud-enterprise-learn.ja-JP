---
title: テンプレートライブラリ
description: プロジェクトに合わせてカスタマイズできる既製のFireflyグラフテンプレートを参照
feature: Image Editing, Gen AI
role: User
level: Beginner
jira: KT-
hide: true
hidefromtoc: true
source-git-commit: 1b6b9793b2fa33365ccf6fb0f049632a67f09cae
workflow-type: tm+mt
source-wordcount: '390'
ht-degree: 0%

---

# &#x200B;5. テンプレートライブラリ

Fireflyグラフのテンプレートのクイックリファレンス索引で、各テンプレートが生成または実行する内容ごとに分類されています。 すべての例は出発点となります。つまり、独自のブランド、製品、プロンプトを入れ替えてから、本番環境でテンプレートを使用します。

## 画像の生成とスタイル

* [**はじめに – 画像を生成する**](/help/firefly/graph/templates/get-started-gen-image.md) – このテンプレートは基本グラフです。つまり、1つのプロンプトノードを1つの生成ノードに1つの出力に変換します。 このテンプレートを使用して、新しいユーザーで最初に開くテンプレートを作成します。
* [**一貫したキャラクタ生成**](/help/firefly/graph/templates/character-gen.md) – グラフテンプレートでキャラクタのリファレンスイメージを1つロードし、新しいショットごとにシーンまたはポーズのプロンプトを入れ替えます。 キャラクタリファレンスは、周囲のシーンが変更されてもロックされたままです。
* [**スタイル抽出**](/help/firefly/graph/templates/style-extraction.md) – このグラフテンプレートでは、参照画像を使用して色、光、テクスチャの処理を抽出します。 その後、同じグラフを通る新しい画像に処理を適用できます。
* [**夕焼けの雰囲気**](/help/firefly/graph/templates/sunset-vibes.md) – このグラフテンプレートでは、テキストプロンプトから3Dタイポグラフィ画像を作成できます。 テンプレートは、配置とカラーバランスを自動的に処理します。

## セグメント化と合成

* [**はじめに – 画像をセグメント化する**](/help/firefly/graph/templates/get-started-segment-image.md) – このグラフテンプレートでは、任意のソース画像を読み込み、セグメント化ノードを実行して、被写体を背景から分離します。 背景の置き換えノードと組み合わせて、クリーンなカットアウトを作成します。
* [**レイヤーの合成とブレンド**](/help/firefly/graph/templates/composite-blend-layers.md) – このグラフテンプレートでは、製品のカットアウトと背景シーンを別々のレイヤー入力として積み重ねます。 合成画像が1つのショットとして読み取られるまで、描画モードと照明ノードを調整します。
* [**特定色域の選択の補正**](/help/firefly/graph/templates/selective-color-correction.md) – このグラフテンプレートでは、補正が必要な特定の領域をマスクし、そのノードのみにターゲットカラーを設定します。 残りの画像はグラフを通過しますが、変更されません。

## ビデオとモーション

* [**はじめに – ビデオの生成**](/help/firefly/graph/templates/get-started-video-gen.md) – このグラフテンプレートでは、承認済みの静止キーアートと短いモーションプロンプトをフィードします。 テンプレートは、新しいショットではなく、同じ主要なアートから構築されたビデオカットを生成します。
* [**ビュレットタイムVFX**](/help/firefly/graph/templates/bullet-time-vfx.md) – このグラフテンプレートでは、ヒーロー製品または被写体の画像にフィードして、その周りに角度を持った回転シーケンスを生成し、フリーズフレームスイープを自動的に組み合わせます。

[Fireflyグラフの使い方](https://experienceleague.adobe.com/ja/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/overview-firefly-graph)に戻ります。