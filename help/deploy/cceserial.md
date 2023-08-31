---
title: エンタープライズ版およびAcrobat版のシリアル番号の有効期限に関するCreative Cloudについて
description: エンタープライズ版およびAcrobat版Creative Cloudのシリアル番号の有効期限について
role: Admin
level: Beginner, Intermediate
exl-id: bc457be0-86dc-4e8a-b6b2-34bc76af2d21
source-git-commit: 245f753d62fe83e76fad6e1d7c3d820a5550464a
workflow-type: tm+mt
source-wordcount: '844'
ht-degree: 3%

---

# エンタープライズ版およびAcrobat版のシリアル番号の有効期限に関するCreative Cloudについて

従来、Adobeでは、エンタープライズタームライセンス契約(ETLA)のお客様に対して、アプリケーション(Creative Suite、エンタープライズ版Creative Cloud、Acrobat XI、Acrobat DCなど)にシリアル番号を発行していました。 これらのシリアル番号には有効期限があります。 有効期限を過ぎると、製品は動作しなくなります。シリアル番号の有効期限が切れる前に移行を計画することが重要です。 このページでは、エンドユーザーが引き続きAdobeのアプリケーションとサービスにアクセスできるようにするために必要な手順の概要を説明します。

## シリアル番号の有効期限の確認

### シリアル番号の検索

ETLA契約に関連付けられたシリアル番号ライセンスは、を介して利用できます。 [Adobeライセンスwebサイト](https://licensing.adobe.com/) (LWS)。 次の手順に従って、表示およびダウンロードします。

1. にログイン [Adobeライセンスwebサイト](https://licensing.adobe.com/) (LWS)をAdobe IDとパスワードで指定します。
1. を選択 **ライセンス/シリアル番号を取得**.
1. を入力します **エンドユーザーID** または **デプロイ先ID**.
1. （オプション） **製品名**, **製品バージョン**、または **Platform** 結果をフィルター処理します。
1. 「検索」をクリックします。
1. 製品名とシリアル番号が表示されます。
1. （オプション）「EXPORT TO CSV」を選択して、シリアル番号のリストをダウンロードします。

![シリアル番号の確認](assets/retrieveserialnumbers.png)

### 有効期限の確認

この [AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) は、コンピューター上のAdobe製品の有効期限が既に切れているか、まもなく期限切れになるシリアル番号を使用しているかどうかをIT管理者が確認するためのコマンドラインユーティリティです。 このツールには、製品ライセンス識別子(LEID)、暗号化されたシリアル番号、有効期限などの情報が表示されます。 この [ページ](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) MacまたはWindowsコンピューターにツールをダウンロードして使用する手順が記載されています。

## シリアル番号の有効期限が切れる前と後のエンドユーザーのエクスペリエンスについて

AcrobatおよびCreative Cloud法人版アプリでは、期限切れの60日前から、（アプリ内の）メッセージの表示が開始されます。 シリアル番号の期限が切れると、製品の動作が停止し、ユーザーに処理を行うように求めるメッセージが表示されます。

### エンタープライズエクスペリエンスのCreative Cloud

次の情報は、エンドユーザーエクスペリエンスの概要を示しています。 以下に短いビデオを示し、エンドユーザーのエクスペリエンスを確認します。

>[!VIDEO](https://video.tv.adobe.com/v/331746?hidetitle=true)

**期限前**

シリアル番号の有効期限が切れる60日前から、すべてのエンタープライズアプリのCreative Cloudに製品内ダイアログボックスが表示されます。 このメッセージは、期限切れの30日前まで毎週表示され、その後、次のように期限切れ日まで毎日表示されます *ライセンスの有効期限が切れます。 このAdobe製品は、2020年11月29日に期限切れになるライセンスを使用しています。 アクセスを継続するには、管理者にお問い合わせください*.

![有効期限前CCEメッセージ](assets/cceexpiring.png)

**有効期限の後**

シリアル番号の期限が切れると、ユーザーはエンタープライズアプリのCreative Cloudにアクセスできなくなります。 有効期限が切れた後に最初に起動すると、次のようなダイアログボックスが表示されます。 *入力したシリアル番号の有効期限が切れています。 この製品はライセンスを取得できません。 カスタマーサポートにお問い合わせください*.

![期限切れ後のCCEメッセージ](assets/cceafterexpire.png)

それ以降にアプリを起動しようとすると、エンドユーザーに対して、 **ログインする** その後に、独自のAdobe IDを作成して体験版モードに入るオプションが表示されます。 ただし、エンドユーザーが作成した新しいAdobe IDは、組織のライセンスに関連付けられず、ユーザーの混乱を引き起こします。 ビジネスの中断や不必要な混乱を避けるために、シリアル番号の有効期限が切れる前にユーザーを指定ユーザーライセンスに移行してください。

![CCEログインダイアログ1](assets/ccesignin1.png)

![CCEログインダイアログ2](assets/ccesignin2.png)

### Acrobat experience

次の情報は、エンドユーザーエクスペリエンスの概要を示しています。 以下に短いビデオを示し、エンドユーザーのエクスペリエンスを確認します。

>[!VIDEO](https://video.tv.adobe.com/v/331749?hidetitle=true)


**期限前**

シリアル番号の有効期限が切れる60日前から、Acrobatはエンドユーザーに製品内ポップアップメッセージを表示します。 有効期限の7日前まで、これは週1回表示されます。 その後、次のように毎日表示されます。 *お客様のAdobe Acrobatのライセンスは、2020年30月11日に期限切れになります。 Acrobatを引き続き使用するには、管理者に連絡してください。*

![Acrobat期限切れ間近のメッセージ](assets/acrobatexpiring.png)

**有効期限の後**

シリアル番号の期限が切れると、Acrobatにアクセスできなくなります。 有効期限が切れた後に最初に起動すると、次のようなダイアログボックスが表示されます。 *入力したシリアル番号の有効期限が切れています。 この製品はライセンスを取得できません。 カスタマーサポートにお問い合わせください。*

![期限切れ後のAcrobatメッセージ](assets/acrobatafterexpire.png)

それ以降Acrobatを起動しようとすると、エンドユーザーに対して、 **ログインする** その後に、独自のAdobe IDを作成して体験版モードに入るオプションが表示されます。 ただし、エンドユーザーが作成した新しいAdobe IDは、組織のライセンスに関連付けられず、ユーザーの混乱を引き起こします。

![ダイアログ1のAcrobat Sign](assets/acrobatsignin1.png)

![ダイアログ2のAcrobat Sign](assets/acrobatsignin2.png)

## サポートが必要な場合はお問い合わせください

の使用について質問がある場合 [AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) シリアル番号のデプロイメントからユーザー指定のデプロイメントに移行するツールまたはサポートが必要な場合は、いくつかのオプションがあります。
* Adobeエンタープライズオンボーディングチームにメールを送信します –  **entonb@adobe.com**
* でサポートチケットを開く [Admin Console](https://adminconsole.adobe.com/support)
* Adobeアカウントチームにご連絡ください
