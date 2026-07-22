---
title: テンプレートライブラリ
description: プロジェクトに合わせてカスタマイズできる既製のFireflyグラフテンプレートを参照
feature: Image Editing, Gen AI
role: User
level: Beginner
jira: KT-
hide: true
hidefromtoc: true
source-git-commit: 5a555416c5f45ca92de7df48e4b7cf8418102269
workflow-type: tm+mt
source-wordcount: '610'
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

## ストーリーボード

* [**ストーリーボードへのテキスト**](/help/firefly/graph/templates/text-to-storyboard.md) – このグラフテンプレートでは、テキスト入力ノードをストーリーの要素に置き換えます。 各行のストーリーボードフレームが作成されます。ストーリーボードフレームは順番に生成され、1つのパネルセットとしてレビュー用にレイアウトされます。
* [**ストーリーボードビルダー**](/help/firefly/graph/templates/storyboard-builder.md) – このグラフテンプレートでは、ストーリーボードのシーンをシーンごとに構築し、ストーリーの1ビートにつき1つのノードを追加します。 パネルの最終的な順序をロックする前に、ノードを並べ替えて別の順序でテストします。

## 3Dと文字

* [**リアルタイムシェーダ**](/help/firefly/graph/templates/real-time-shaders.md) – このグラフテンプレートでは、イメージから開始して3つの異なるカスタムシェーダを適用し、結果をリアルタイムでプレビューします。 最初から再レンダリングするのではなく、ノード上でシェーダパラメータを直接調整します。
* [**文字モデルの生成**](/help/firefly/graph/templates/character-model-generation.md) – このグラフテンプレートでは、イラストの3Dアニメーションスタイルを作成します。 テンプレートは、空のシーンから開始するのではなく、クリーンアップのためにモデラに渡す準備ができたベース3Dモデルパスを生成します。
* [**ビニール製のおもちゃデザイン**](/help/firefly/graph/templates/vinyl-toy-design.md) – このグラフテンプレートでは、キャラクターまたはマスコットのリファレンスを入力し、それをスタイライズされたビニール製のおもちゃ形式でレンダリングします。 ライセンスや製品レビューのデッキには、折り返し式があります。
* [**スケッチして3Dに変換**](/help/firefly/graph/templates/sketch-to-3d.md) ：このグラフテンプレートでは、スケッチを3Dのキャラクターに変換します。 このグラフは、回転する3Dターンアラウンドを構築し、物理的なプロトタイプを作成する前に内部のデザインレビューを行うことができます。

[Fireflyグラフの使い方](https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/overview-firefly-graph)に戻ります。