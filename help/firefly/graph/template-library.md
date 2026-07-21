---
title: テンプレートライブラリ
description: プロジェクトに合わせてカスタマイズできる既製のFireflyグラフテンプレートを参照
feature: Image Editing, Gen AI
role: User
level: Beginner
jira: KT-
hide: true
hidefromtoc: true
source-git-commit: d9650e6e2864d46a099c228eaff6d33975742f3a
workflow-type: tm+mt
source-wordcount: '374'
ht-degree: 0%

---

# &#x200B;5. テンプレートライブラリ

Fireflyグラフのテンプレートのクイックリファレンス索引で、各テンプレートが生成または実行する内容ごとに分類されています。 すべての例は出発点となります。つまり、独自のブランド、製品、プロンプトを入れ替えてから、本番環境でテンプレートを使用します。

## 画像の生成とスタイル

* [**基本操作 – 画像を生成する**](/help/firefly/graph/templates/get-started-gen-image.md) – 基本的なグラフの作成方法を説明します。1つのプロンプトノードを1つの生成ノードに1つの出力に変換します。 このテンプレートを使用して、新しいユーザーで最初に開くテンプレートを作成します。
* [**一貫したキャラクターの生成**](/help/firefly/graph/templates/character-gen.md) – キャラクターの1つの参照画像を読み込み、新しいショットごとにシーンまたはポーズのプロンプトを入れ替える方法について説明します。 キャラクタリファレンスは、周囲のシーンが変更されてもロックされたままです。
* [**スタイル抽出**](/help/firefly/graph/templates/style-extraction.md) – 参照画像をフィードして、色、光、テクスチャの処理を抽出する方法を説明します。 その後、同じグラフを通る新しい画像に処理を適用できます。
* [**夕焼けの雰囲気**](/help/firefly/graph/templates/sunset-vibes.md) – テキストプロンプトから3Dタイポグラフィ画像を作成する方法について説明します。 テンプレートは、配置とカラーバランスを自動的に処理します。

## セグメント化と合成

* [**はじめに – 画像をセグメント化する**](/help/firefly/graph/templates/get-started-segment-image.md) – ソース画像を読み込み、セグメント化ノードを実行して、被写体を背景から分離する方法について説明します。 背景の置き換えノードと組み合わせて、クリーンなカットアウトを作成します。
* [**レイヤーの合成とブレンド**](/help/firefly/graph/templates/composite-blend-layers.md) – 製品のカットアウトと背景シーンを別々のレイヤー入力として積み重ねる方法について説明します。 合成画像が1つのショットとして読み取られるまで、描画モードと照明ノードを調整します。
* [**特定色域の選択の補正**](/help/firefly/graph/templates/selective-color-correction.md) – 補正が必要な特定の領域をマスクし、そのノードのみにターゲット色を設定する方法を学習します。 残りの画像はグラフを通過しますが、変更されません。

## ビデオとモーション

* [**はじめに – ビデオの生成**](/help/firefly/graph/templates/get-started-video-gen.md) – 承認済みの静止画キーアートと短いモーションプロンプトをフィードする方法を説明します。 テンプレートは、新しいショットではなく、同じ主要なアートから構築されたビデオカットを生成します。
* [**ビュレットタイムVFX**](/help/firefly/graph/templates/bullet-time-vfx.md) – ヒーロー製品または被写体の画像にフィードして、周りに角度を持った回転シーケンスを生成し、フリーズフレームスイープを自動的に組み合わせる方法を学習します。

[Fireflyグラフの使い方](https://experienceleague.adobe.com/ja/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/overview-firefly-graph)に戻ります。