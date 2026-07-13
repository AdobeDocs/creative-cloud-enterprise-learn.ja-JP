---
title: ​3. 最初のグラフを作成
description: 最初のFireflyグラフワークフローを構築するためのステップバイステップのウォークスルー
feature: Image Editing, Gen AI
role: User
level: Beginner
jira: KT-
hide: true
hidefromtoc: true
source-git-commit: 4dd919a2b06f0852dc0010b0f79d5a0b2eae4c1a
workflow-type: tm+mt
source-wordcount: '193'
ht-degree: 1%

---

# &#x200B;3. 最初のグラフを作成

ノード、接続、およびテンプレートの内容がわかったら、最初のワークフローを構築する準備が整います。

1. Fireflyを開いて、左側のメニューから&#x200B;**グラフ**&#x200B;を選択します。
1. **新しいグラフの作成**&#x200B;を選択します。
1. 空白のキャンバスを右クリックして、**+新しいノード**&#x200B;を選択します。
1. 左側のメニューで&#x200B;**入力**&#x200B;を選択し、**入力画像**を選択します。
   ![ノード](../assets/node.png)
このノードを使用すると、グラフィックを読み込むことができます。
1. 画像をノードにドラッグ&amp;ドロップします。
   ![イメージのあるノード](../assets/node-image.png)
1. 空白のカンバスを右クリックして、**+新しいノード**&#x200B;を選択し、ダイアログで&#x200B;**グラデーションマスク**&#x200B;を選択します。
1. 空白のカンバスを右クリックして、**+新しいノード**&#x200B;を選択し、ダイアログで「**マスクを適用**」を選択します。
1. **入力画像**&#x200B;ノードの出力を&#x200B;**マスクの適用**&#x200B;画像ノードの入力に接続します。
1. **グラデーションマスク**&#x200B;出力を&#x200B;**マスクを適用**マスク/チャンネル入力に差し込みます。
   ![プラグインノード](../assets/plug-in.png)

## 次のステップ

テンプレートから作成する場合 [4に移動します。 独自の概要を反映するようにテンプレート](https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/customize-template)をカスタマイズします。
