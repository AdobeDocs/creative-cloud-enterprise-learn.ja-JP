---
title: テンプレートライブラリ
description: 開いて自分のプロジェクトに適応できる既製のホタルグラフテンプレートを参照します
feature: Image Editing, Gen AI
role: User
level: Beginner
jira: KT-22134
hide: true
hidefromtoc: 'yes'
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
source-wordcount: '609'
ht-degree: 3%
---
# &#x200B;5. テンプレートライブラリ

ホタルグラフテンプレートのクイックリファレンスインデックスで、各テンプレートが生成または実行する内容で構成されます。 すべての例は出発点となります。つまり、独自のブランド、製品、プロンプトを入れ替えてから、本番環境でテンプレートを使用します。

## 画像の生成とスタイル

| グラフテンプレート | 説明 | 活用例 |
|---|---|---|
| [**はじめに – 画像を生成する**](/help/firefly/graph/templates/get-started-gen-image.md) | 1つのpromptノードから1つのgenerationノードへ、1つの出力へ変換する基本的なグラフ。 | <ul><li>ヒーロー画像</li><li>Placeholder test</li><li>サンプル画像</li></ul> |
| [**一貫した文字生成**](/help/firefly/graph/templates/character-gen.md) | キャラクタのリファレンスイメージを1つロードし、新しいショットごとにシーンまたはポーズのプロンプトを入れ替えます。 | <ul><li>繰り返し使われるマスコット</li><li>スポーク文字</li><li>インストラクターのキャラクター</li></ul> |
| [**スタイル抽出**](/help/firefly/graph/templates/style-extraction.md) | 参照画像を配置して、カラー、ライト、テクスチャの処理を抽出します。 | <ul><li>Lookの転送</li><li>季節感とマッチ</li><li>気分の一致</li></ul> |
| [**夕焼けの雰囲気**](/help/firefly/graph/templates/sunset-vibes.md) | テキストプロンプトから3Dタイポグラフィ画像を作成します。 | <ul><li>タグラインのオーバーレイ</li><li>季節に応じたタグライン</li><li>Flash販売財産</li></ul> |

## セグメント化と合成

| グラフテンプレート | 説明 | 活用例 |
|---|---|---|
| [**はじめに – 画像をセグメント化する**](/help/firefly/graph/templates/get-started-segment-image.md) | 任意のソース画像を読み込み、セグメンテーションノードを実行して、被写体を背景から分離します。 | <ul><li>カットアウトを消去</li><li>カタログの分離</li><li>背景の入れ替え</li></ul> |
| [**レイヤーの合成とブレンド**](/help/firefly/graph/templates/composite-blend-layers.md) | 製品のカットアウトと背景シーンを個別のレイヤー入力としてスタック付けします。 | <ul><li>ライフスタイル/ソーシャル合成</li><li>ホームページバナー</li><li>共同ブランドのコンポジット</li></ul> |
| [**特定色域の選択の補正**](/help/firefly/graph/templates/selective-color-correction.md) | 修正が必要な特定の領域をマスクし、そのノードのみにターゲットカラーを設定します。 | <ul><li>ブランドカラーマッチ</li><li>カラーの標準化</li><li>Strayカラー補正</li></ul> |

## ビデオとモーション

| グラフテンプレート | 説明 | 活用例 |
|---|---|---|
| [**はじめに – ビデオの生成**](/help/firefly/graph/templates/get-started-video-gen.md) | 承認済みの静止画キーアートとショートモーションプロンプトをフィードします。 | <ul><li>ビデオに最適なアート</li><li>ティーザーを起動</li><li>ビデオカット</li></ul> |
| [**Bullet Time VFX**](/help/firefly/graph/templates/bullet-time-vfx.md) | ヒーロー製品または被写体の画像にフィードして、その周りに一連の角度を付けて回転させ、フリーズフレームのスイープを自動的にステッチします。 | <ul><li>箇条書きのタイムショット</li><li>360フリーズフレーム</li><li>回転するヒーロー写真</li></ul> |

## ストーリーボード

| グラフテンプレート | 説明 | 活用例 |
|---|---|---|
| [**ストーリーボードへのテキスト**](/help/firefly/graph/templates/text-to-storyboard.md) | テキスト入力ノードをストーリー内の要素に置き換えます。 | <ul><li>ストーリーボードにスクリプトを作成</li><li>ストーリーボードを起動</li><li>解説ストーリーボード</li></ul> |
| [**ストーリーボードビルダー**](/help/firefly/graph/templates/storyboard-builder.md) | シーンごとにストーリーボードシーンを構築し、ストーリーの1ビートごとに1つのノードを追加します。 | <ul><li>物語構造試験</li><li>ぺーシング検査</li><li>物語の弧</li></ul> |

## 3Dと文字

| グラフテンプレート | 説明 | 活用例 |
|---|---|---|
| [**リアルタイムシェーダー**](/help/firefly/graph/templates/real-time-shaders.md) | イメージから始めて、3つの異なるカスタムシェーダを適用し、結果をリアルタイムでプレビューします。 | <ul><li>コンフィギュレータシェーダー</li><li>マテリアルプレビュー</li><li>製品レンダリング</li></ul> |
| [**文字モデルの生成**](/help/firefly/graph/templates/character-model-generation.md) | イラストの3Dアニメーションスタイルを作成します。 | <ul><li>マスコットモデル</li><li>基本3Dモデル</li><li>インストラクターモデル</li></ul> |
| [**ビニール玩具のデザイン**](/help/firefly/graph/templates/vinyl-toy-design.md) | キャラクターまたはマスコットのリファレンスを入力し、スタイライズされたビニールのおもちゃの形式でレンダリングします。 | <ul><li>収集可能な概念</li><li>マスコット数字</li><li>ライセンス提案</li></ul> |
| [**スケッチして3Dに変換**](/help/firefly/graph/templates/sketch-to-3d.md) | スケッチを3Dキャラクタに変換します。 | <ul><li>ハードウェアのターンアラウンド</li><li>車両および小道具の所要時間</li><li>文字変換</li></ul> |

## 製品とブランドのモックアップ

| グラフテンプレート | 説明 | 活用例 |
|---|---|---|
| [**ブランディングの視覚化**](/help/firefly/graph/templates/branding-visualization.md) | 製品シーンでロゴやブランドを視覚化する。 | <ul><li>サブブランドビジュアル</li><li>パレットテスト</li><li>IDのプレビュー</li></ul> |
| [**ブランド製品のモックアップ**](/help/firefly/graph/templates/brand-product-mockup.md) | 様々なシーンで製品を視覚化する。 | <ul><li>店内モックアップ</li><li>製品のモックアップ</li><li>建築のモックアップ</li></ul> |
| [**エディトリアル写真**](/help/firefly/graph/templates/editorial-photoshoot.md) | モデルリファレンスをロードし、新しい外観ごとに服飾の入力を入れ替えます。 | <ul><li>ルックブック撮影</li><li>エディトリアルシリーズ</li><li>Colorwayラインアップ</li></ul> |
| [**フォトスタジオ**](/help/firefly/graph/templates/photography-studio.md) | スタジオの背景に製品のレンダリングを配置し、結果が実際のスタジオのキャプチャのように読み取られるまで照明を調整します。 | <ul><li>SKU studio shot</li><li>ページレンダリングを起動</li><li>製品ラインショット</li></ul> |
| [**デカールをサーフェスに適用**](/help/firefly/graph/templates/decal-to-surfaces.md) | 基本製品のモックアップとデカールまたはロゴアセットを個別の入力値として読み込みます。 | <ul><li>ブランドの変更のプレビュー</li><li>ライブリプレビュー</li><li>ロゴ配置テスト</li></ul> |

## バッチ処理と整合性処理

| グラフテンプレート | 説明** | 活用例 |
|---|---|---|
| [**デザインシステムジェネレーター**](/help/firefly/graph/templates/design-system-generator.md) | Webサイトのスクリーンショットに基づいてデザインシステムを生成します。 | <ul><li>アイコンパターンセット</li><li>カラーシステム</li><li>視覚言語</li></ul> |
| [**顔写真の生成**](/help/firefly/graph/templates/headshots-generation.md) | 企業の顔写真を一括で調整します。 | <ul><li>ディレクトリの顔写真</li><li>チームページの顔写真</li><li>プロフェッショナルな顔写真</li></ul> |
