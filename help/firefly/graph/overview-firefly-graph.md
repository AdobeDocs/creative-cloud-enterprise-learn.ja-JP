---
title: Adobe [!DNL Firefly Graph] の概要
description: Adobe [!DNL Firefly Graph]の詳細
feature: Image Editing, Gen AI
role: User
level: Beginner
jira: KT-21971
hide: true
hidefromtoc: true
source-git-commit: d31d8b492c7f86f6369b88f8940dd752bd535e20
workflow-type: tm+mt
source-wordcount: '733'
ht-degree: 3%

---

# Fireflyグラフの基本を学ぶ

以前にAI生成ツールを使用したことがある場合は、プロンプトを入力して結果を1つ取得し、次に似た機能が必要になったときに最初からやり直すことに慣れていると思われます。 Fireflyグラフは動作が異なります。 単一のプロンプトの代わりに、グラフを作成します。これは、すべての入力、変換、出力が接続され、一緒に保存される視覚的なステップバイステップのワークフローです。 このページでは、最初のグラフを構築するために必要なすべての手順を説明します。コアコンセプト、手順を追った最初のワークフロー、すぐに開いて適応できる既製のテンプレートのライブラリなどです。

>[!TIP]
>
>1回の食事の代わりに、レシピのように考えてください。 グラフを作成したら、それを渡したり、新しい入力で再実行したり、1つのステップを変更して下流のすべてのデータを自動的に更新したりできます。

<!-- START CARDS HTML - DO NOT MODIFY BY HAND -->
<div class="columns">
    <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="1. What is Firefly Graph?">
        <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
            <div class="card-image">
                <figure class="image x-is-16by9">
                    <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/what-is-firefly-graph" title="1. Fireflyグラフとは" target="_blank" rel="referrer">
                        <img class="is-bordered-r-small" src="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/what-is-firefly-graph./media_1e4b47165b24a2520374b63071fd64c083a0fbeee.png?width=400&format=png&optimize=medium" alt="1. Fireflyグラフとは"
                             style="width: 100%; aspect-ratio: 16 / 9; object-fit: cover; overflow: hidden; display: block; margin: auto;">
                    </a>
                </figure>
            </div>
            <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
                <div class="top-card-content">
                    <p class="headline is-size-6 has-text-weight-bold">
                        <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/what-is-firefly-graph" target="_blank" rel="referrer" title="1. Fireflyグラフとは">1. Fireflyグラフとは</a></p>
                    <p class="is-size-6">Fireflyグラフの概要と1つのプロンプトとどのように比較するかについて説明します</p>
                </div>
                <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/what-is-firefly-graph" target="_blank" rel="referrer" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
                    <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">読み取り</span>
                
            </div>
        </div>
    </div>
    <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="2. Firefly Graph key concepts">
        <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
            <div class="card-image">
                <figure class="image x-is-16by9">
                    <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/key-concepts" title="2. Fireflyグラフのキーコンセプト" target="_blank" rel="referrer">
                        <img class="is-bordered-r-small" src="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/key-concepts./media_1fc8692f32b84c93c75c094fb15d096fbdd023c5c.png?width=400&format=png&optimize=medium" alt="2. Fireflyグラフのキーコンセプト"
                             style="width: 100%; aspect-ratio: 16 / 9; object-fit: cover; overflow: hidden; display: block; margin: auto;">
                    </a>
                </figure>
            </div>
            <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
                <div class="top-card-content">
                    <p class="headline is-size-6 has-text-weight-bold">
                        <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/key-concepts" target="_blank" rel="referrer" title="2. Fireflyグラフのキーコンセプト">2. Fireflyグラフのキーコンセプト</a></p>
                    <p class="is-size-6">Fireflyグラフの使用を開始する際に役立つ重要な概念について説明します</p>
                </div>
                <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/key-concepts" target="_blank" rel="referrer" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
                    <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">読み取り</span>
                
            </div>
        </div>
    </div>
    <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="3. Create your first graph">
        <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
            <div class="card-image">
                <figure class="image x-is-16by9">
                    <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/create-your-first-graph" title="3. 最初のグラフを作成" target="_blank" rel="referrer">
                        <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3495912?quality=12&hidetitle=true&format=jpeg&nocache=1784039110238" alt="3. 最初のグラフを作成"
                             style="width: 100%; aspect-ratio: 16 / 9; object-fit: cover; overflow: hidden; display: block; margin: auto;">
                    </a>
                </figure>
            </div>
            <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
                <div class="top-card-content">
                    <p class="headline is-size-6 has-text-weight-bold">
                        <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/create-your-first-graph" target="_blank" rel="referrer" title="3. 最初のグラフを作成">3. 最初のグラフを作成</a></p>
                    <p class="is-size-6">カンバスから書き出しへのウォークスルー</p>
                </div>
                <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/create-your-first-graph" target="_blank" rel="referrer" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
                    <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">視聴</span>
                
            </div>
        </div>
    </div>
    <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="4. Customize a template">
        <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
            <div class="card-image">
                <figure class="image x-is-16by9">
                    <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/customize-template" title="4. テンプレートのカスタマイズ" target="_blank" rel="referrer">
                        <img class="is-bordered-r-small" src="https://cdn.experienceleague.adobe.com/thumb/exl-cards/tutorial || 'default'}.png" alt="4. テンプレートのカスタマイズ"
                             style="width: 100%; aspect-ratio: 16 / 9; object-fit: cover; overflow: hidden; display: block; margin: auto;">
                    </a>
                </figure>
            </div>
            <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
                <div class="top-card-content">
                    <p class="headline is-size-6 has-text-weight-bold">
                        <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/customize-template" target="_blank" rel="referrer" title="4. テンプレートのカスタマイズ">4. テンプレートのカスタマイズ</a></p>
                    <p class="is-size-6">テンプレートに自分のアイデアを反映させる</p>
                </div>
                <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/customize-template" target="_blank" rel="referrer" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
                    <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">読み取り</span>
                
            </div>
        </div>
    </div>
    <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Introducing Firefly Graph">
        <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
            <div class="card-image">
                <figure class="image x-is-16by9">
                    <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/introducing-graph" title="Fireflyグラフの概要" target="_blank" rel="referrer">
                        <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3492621?quality=12&hidetitle=true&format=jpeg&nocache=1784039110453" alt="Fireflyグラフの概要"
                             style="width: 100%; aspect-ratio: 16 / 9; object-fit: cover; overflow: hidden; display: block; margin: auto;">
                    </a>
                </figure>
            </div>
            <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
                <div class="top-card-content">
                    <p class="headline is-size-6 has-text-weight-bold">
                        <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/introducing-graph" target="_blank" rel="referrer" title="Fireflyグラフの概要">Fireflyグラフの概要</a>
                    </p>
                    <p class="is-size-6">このウェビナーでは、Fireflyの完全なビジュアルワークフローシステムであるGraphについて説明します。</p>
                </div>
                <a href="https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/introducing-graph" target="_blank" rel="referrer" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
                    <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">視聴</span>
                
            </div>
        </div>
    </div>
</div>
<!-- END CARDS HTML - DO NOT MODIFY BY HAND -->