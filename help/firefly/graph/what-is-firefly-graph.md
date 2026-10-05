---
title: 1. [!DNL Firefly Graph]とは
description: グラフと1つのプロンプトの違い、および各手順を表示および再利用できる要素にする理由について説明します
feature: Image Editing, Gen AI
role: User
level: Beginner
jira: KT-22055
hide: true
product_v2:
  - id: e66c61b1-1ca4-4c42-8df9-e5cb44b0555c
    internal-label: Creative Cloud
feature_v2:
  - id: c31d989b-c5df-5b16-8862-a611a5e6e70b
    internal-label: Gen AI
  - id: fec89bf3-1b77-4b07-a0b9-96726856a0ad
    internal-label: Editing
subfeature_v2:
  - id: b29e1156-4668-4c0c-84e3-9347e94225ed
    internal-label: Image editing
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
    internal-label: Beginner
source-git-commit: b4ccb0a72c95fa56cd4908aae754dfb8b399cd31
workflow-type: tm+mt
source-wordcount: '316'
ht-degree: 0%
---
# &#x200B;1. [!DNL Firefly Graph]とは

ほとんどのAI生成ツールでは、1つのプロンプトから1つの出力が得られます。 もし短い変更があれば、手作業で全体を再構築し、最終的なファイル以外に手を加えるものはありません。

ホタルのグラフの動作が異なります。 1つのプロンプトの代わりに、**グラフ**&#x200B;を構築します。これは、すべての入力、変換、および出力が一緒にキャプチャされる、視覚的で手順を追ったワークフローです。 1つの手順を変更して再実行します。チェーン全体を再構築するわけではありません。 すべてのステップは目に見えるノードであり、チームは検査、調整し、そのまま引き継ぐことができます。

![ビジュアルグラフのスクリーンショット](../assets/graph.png){align="center"}

つまり、グラフはクリエイティブなプロセスに取って代わるものではなく、そのプロセスを目で見て、再利用し、スケールできるものに変えてしまうのです。

## ステップが表示されました

すぐに使えるワークフローを考えてみましょう。まずは簡単な説明から始め、入力内容を収集して、バリエーションを作成し、調整、書き出しを行います。 グラフはこれらの手順を変更するのではなく、個々の手順を表示して再利用できるようにします。

| 今日のワークフロー | グラフによって表示される内容 |
|---|---|
| 概要から開始 | タイトルはグラフ入力になります |
| 入力を収集 | 入力はノードに直接接続されます |
| バリエーションを作成 | バリエーションは並行して実行されます |
| 調整 | 残りのノードに触れずに1つのノードを調整 |
| 書き出し | グラフから直接エクスポート |

ここからが転換です。同じ作業ですが、途中で行われたすべての決定は、黒いボックスではなく、次回から一からやり直す必要がある見え、調整、再利用できるものになります。

## 次のステップ

アイデアに問題がなければ、[2に移動します。 キーコンセプト： nodes, connections, and templates](https://experienceleague.adobe.com/ja/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/key-concepts) – 実際にグラフを構築する際に使用する語彙を学ぶ

[ホタルグラフの使用](https://experienceleague.adobe.com/ja/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/overview-firefly-graph)に戻ります。
