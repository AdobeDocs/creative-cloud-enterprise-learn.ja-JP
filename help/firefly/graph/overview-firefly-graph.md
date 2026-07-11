---
title: Adobe [!DNL Firefly Graph] の概要
description: Adobe [!DNL Firefly Graph]の詳細
feature: Image Editing, Gen AI
role: User
level: Beginner
jira: KT-21971
hide: true
hidefromtoc: true
source-git-commit: 408d802611eeeb20f61f5b750289782300b2bc1e
workflow-type: tm+mt
source-wordcount: '764'
ht-degree: 0%

---

# Adobe [!DNL Firefly Graph]の概要

以前にAI生成ツールを使用したことがある場合は、プロンプトを入力して結果を1つ取得し、次に似た機能が必要になったときに最初からやり直すことに慣れていると思われます。 Fireflyグラフは動作が異なります。 単一のプロンプトの代わりに、グラフを作成します。これは、すべての入力、変換、出力が接続され、一緒に保存される視覚的なステップバイステップのワークフローです。

>[!TIP]
>
>1回の食事の代わりに、レシピのように考えてください。 グラフを作成したら、それを渡したり、新しい入力で再実行したり、1つのステップを変更して下流のすべてのデータを自動的に更新したりできます。

このページでは、最初のグラフを構築するために必要なすべての手順を説明します。コアコンセプト、手順を追った最初のワークフロー、すぐに開いて適応できる既製のテンプレートのライブラリなどです。

## 基本を学ぶ

<!-- START CARDS HTML - DO NOT MODIFY BY HAND -->
<div class="columns">
    <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="What is Firefly Graph?">
        <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
            <div class="card-image">
                <figure class="image x-is-16by9">
                    <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/what-is-firefly-graph" title="Fireflyグラフとは" target="_blank" rel="referrer">
                        <img class="is-bordered-r-small" src="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/media_1c8848f3fe12b166eda2891db416bc533231107c8.png?width=400&format=webply&optimize=medium" alt="Fireflyグラフとは"
                             style="width: 100%; aspect-ratio: 16 / 9; object-fit: cover; overflow: hidden; display: block; margin: auto;">
                    </a>
                </figure>
            </div>
            <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
                <div class="top-card-content">
                    <p class="headline is-size-6 has-text-weight-bold">
                        <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/what-is-firefly-graph" target="_blank" rel="referrer" title="Fireflyグラフとは">Fireflyグラフとは</a>
                    </p>
                    <p class="is-size-6">グラフと単一のプロンプトの違いと、すべての手順を表示して再利用できる理由を説明します</p>
                </div>
                <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/what-is-firefly-graph" target="_blank" rel="referrer" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
                    <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">チュートリアルを読む</span>
                
            </div>
        </div>
    </div>
    <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Firefly Graph Key Concepts">
        <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
            <div class="card-image">
                <figure class="image x-is-16by9">
                    <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/key-concepts" title="Fireflyグラフのキーコンセプト" target="_blank" rel="referrer">
                        <img class="is-bordered-r-small" src="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/media_1241ec7a897ee7101ae8354ba98163a2bb9fee2fa.png?width=400&format=webply&optimize=medium" alt="Fireflyグラフのキーコンセプト"
                             style="width: 100%; aspect-ratio: 16 / 9; object-fit: cover; overflow: hidden; display: block; margin: auto;">
                    </a>
                </figure>
            </div>
            <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
                <div class="top-card-content">
                    <p class="headline is-size-6 has-text-weight-bold">
                        <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/key-concepts" target="_blank" rel="referrer" title="Fireflyグラフのキーコンセプト">Fireflyグラフのキーコンセプト</a>
                    </p>
                    <p class="is-size-6">Fireflyグラフのmental modelに関する4つのアイデア(node、connection、workflow、template)</p>
                </div>
                <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/key-concepts" target="_blank" rel="referrer" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
                    <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">チュートリアルを読む</span>
                
            </div>
        </div>
    </div>
</div>
<!-- END CARDS HTML - DO NOT MODIFY BY HAND -->

## 最初のグラフを作成

<!-- START CARDS HTML - DO NOT MODIFY BY HAND -->
<div class="columns">
    <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Create your First Graph">
        <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
            <div class="card-image">
                <figure class="image x-is-16by9">
                    <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/create-your-first-graph" title="最初のグラフを作成" target="_blank" rel="referrer">
                        <img class="is-bordered-r-small" src="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/media_1522002b4ca9a5ead61abc2b0f367e873cc12c731.png?width=400&format=webply&optimize=medium" alt="最初のグラフを作成"
                             style="width: 100%; aspect-ratio: 16 / 9; object-fit: cover; overflow: hidden; display: block; margin: auto;">
                    </a>
                </figure>
            </div>
            <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
                <div class="top-card-content">
                    <p class="headline is-size-6 has-text-weight-bold">
                        <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/create-your-first-graph" target="_blank" rel="referrer" title="最初のグラフを作成">最初のグラフの作成</a>
                    </p>
                    <p class="is-size-6">空白のカンバスから書き出しまで、最初のFireflyグラフワークフローを構築するためのステップバイステップのウォークスルー</p>
                </div>
                <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/create-your-first-graph" target="_blank" rel="referrer" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
                    <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">チュートリアルを読む</span>
                
            </div>
        </div>
    </div>
    <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Customize a Template">
        <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
            <div class="card-image">
                <figure class="image x-is-16by9">
                    <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/customize-template" title="テンプレートのカスタマイズ" target="_blank" rel="referrer">
                        <img class="is-bordered-r-small" src="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/media_1caebbd45d337e6a6ff699be8a27cf0ec94a0fe03.png?width=400&format=webply&optimize=medium" alt="テンプレートのカスタマイズ"
                             style="width: 100%; aspect-ratio: 16 / 9; object-fit: cover; overflow: hidden; display: block; margin: auto;">
                    </a>
                </figure>
            </div>
            <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
                <div class="top-card-content">
                    <p class="headline is-size-6 has-text-weight-bold">
                        <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/customize-template" target="_blank" rel="referrer" title="テンプレートのカスタマイズ">テンプレートのカスタマイズ</a>
                    </p>
                    <p class="is-size-6">Fireflyグラフテンプレートを、自分の概要やアセットが反映されるワークフローに変換するための短いチェックリスト</p>
                </div>
                <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/customize-template" target="_blank" rel="referrer" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
                    <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">チュートリアルを読む</span>
                
            </div>
        </div>
    </div>
</div>
<!-- END CARDS HTML - DO NOT MODIFY BY HAND -->

## テンプレートライブラリ

<!-- START CARDS HTML - DO NOT MODIFY BY HAND -->
<div class="columns">
    <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Firefly Graph Template Library">
        <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
            <div class="card-image">
                <figure class="image x-is-16by9">
                    <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/template-library" title="Fireflyグラフテンプレートライブラリ" target="_blank" rel="referrer">
                        <img class="is-bordered-r-small" src="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/media_1922dda5ae5fcff927ebe700a90487f6dc5a49fe7.png?width=400&format=webply&optimize=medium" alt="Fireflyグラフテンプレートライブラリ"
                             style="width: 100%; aspect-ratio: 16 / 9; object-fit: cover; overflow: hidden; display: block; margin: auto;">
                    </a>
                </figure>
            </div>
            <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
                <div class="top-card-content">
                    <p class="headline is-size-6 has-text-weight-bold">
                        <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/template-library" target="_blank" rel="referrer" title="Fireflyグラフテンプレートライブラリ">Fireflyグラフテンプレートライブラリ</a>
                    </p>
                    <p class="is-size-6">プロジェクトに合わせてカスタマイズできる既製のFireflyグラフテンプレートを参照</p>
                </div>
                <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/template-library" target="_blank" rel="referrer" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
                    <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">チュートリアルを読む</span>
                
            </div>
        </div>
    </div>
</div>
<!-- END CARDS HTML - DO NOT MODIFY BY HAND -->
