---
title: Creative Cloudエンタープライズ版とAcrobatのシリアル番号の有効期限について
description: エンタープライズ版およびAcrobat版のCreative Cloudのシリアル番号の有効期限について
role: User
level: Beginner, Intermediate
exl-id: bc457be0-86dc-4e8a-b6b2-34bc76af2d21
source-git-commit: 6b819aef801e003e5a160d24ba69522cf6a7e715
workflow-type: tm+mt
source-wordcount: '848'
ht-degree: 3%

---

# Creative Cloudエンタープライズ版とAcrobatのシリアル番号の有効期限について

これまで、Adobeはエンタープライズタームライセンス契約 (ETLA) に基づいてお客様にアプリケーション (Creative Suite、Creative Cloudエンタープライズ版、Acrobat XI、Acrobat DCなど ) のシリアル番号を発行してきました。 これらのシリアル番号には有効期限があります。 有効期限が過ぎると製品は機能しなくなります。そのため、シリアル番号が期限切れになる前に移行を計画することが重要です。 このページでは、エンドユーザーが引き続きアプリケーションやサービスにアクセスできるように、必要なAdobe手順について説明します。

## シリアル番号の有効期限の確認

### シリアル番号の検索

ETLA契約のシリアル番号ライセンスは、 [Adobeライセンス Web サイト](https://licensing.adobe.com/) (LWS) を選択します。 表示およびダウンロードするには、次の手順に従います。

1. ログイン [Adobeライセンス Web サイト](https://licensing.adobe.com/) (LWS) にAdobe IDとパスワードを入力します。
1. 選択 **ライセンス/シリアル番号の取得**&#x200B;を選択します。
1. 入力する **エンドユーザー ID** または **デプロイ先 ID**&#x200B;を選択します。
1. （オプション） **製品名**, **製品バージョン**、または **Platform** 」をクリックして結果をフィルタリングします。
1. 「検索」をクリックします。
1. 製品名とシリアル番号が表示されます。
1. （オプション）「EXPORT TO CSV」を選択して、シリアル番号のリストをダウンロードします。

![シリアル番号の検索](assets/retrieveserialnumbers.png)

### 有効期限の確認

この [AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) は、コンピューター上のAdobe製品で期限切れのシリアル番号が使用されているか、期限切れのシリアル番号が使用されているかを確認するための IT 管理者向けコマンドラインユーティリティです。 このツールには、製品ライセンス識別子 (LEID)、暗号化シリアル番号、有効期限などの情報が表示されます。 この [ページ](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) Macまたは Windows コンピューターでツールをダウンロードして使用する方法について説明します。

## シリアル番号の有効期限が切れる前と切れた後のエンドユーザーエクスペリエンスについて

AcrobatとCreative Cloudエンタープライズ版アプリケーションの両方で、有効期限の 60 日前からメッセージが（アプリケーションに）表示されます。 シリアル番号が期限切れになると、製品は動作しなくなり、ユーザーにアクションを促します。

### Creative Cloudエンタープライズ版

次の情報は、エンドユーザーの操作の概要を示しています。 以下の短いビデオに続いて、エンドユーザーのエクスペリエンスについて説明します。

>[!VIDEO](https://video.tv.adobe.com/v/331746?hidetitle=true)

**有効期限前**

シリアル番号が期限切れになる 60 日前から、エンタープライズ版アプリのすべてのCreative Cloudで、エンドユーザーに製品内ダイアログボックスが表示されます。 このメッセージは、有効期限の 30 日前まで毎週表示され、有効期限が設定されるまで毎日表示されます。 *ライセンスの有効期限が近づいています。 このAdobe製品のライセンスは 2020 年 11 月 29 日に期限切れになります。 引き続きアクセスするには、管理者に連絡してください*&#x200B;を選択します。

![CCE期限前メッセージ](assets/cceexpiring.png)

**有効期限後**

シリアル番号が期限切れになると、ユーザーはエンタープライズアプリケーションのCreative Cloudにアクセスできなくなります。 有効期限が切れた後の最初の起動時に、 *入力したシリアル番号は期限切れです。 この製品はライセンス認証できません。 カスタマーサポートにお問い合わせください*&#x200B;を選択します。

![CCEの有効期限後のメッセージ](assets/cceafterexpire.png)

それ以降アプリケーションを起動しようとすると、エンドユーザーに **ログインする** その後、独自のAdobe IDを作成して体験版モードにするオプションが表示されます。 ただし、エンドユーザーが作成した新しいAdobe IDは、組織のライセンスに関連付けられず、ユーザーに混乱を招きます。 業務の中断や混乱を避けるため、シリアル番号の有効期限が切れる前に、ユーザー指定ライセンスにユーザーを移行してください。

![CCEログインダイアログ 1](assets/ccesignin1.png)

![CCEログインダイアログ 2](assets/ccesignin2.png)

### Acrobat experience

次の情報は、エンドユーザーの操作の概要を示しています。 以下の短いビデオに続いて、エンドユーザーのエクスペリエンスについて説明します。

>[!VIDEO](https://video.tv.adobe.com/v/331749?hidetitle=true)


**有効期限前**

Acrobatでは、シリアル番号の有効期限の 60 日前から、エンドユーザーに製品内ポップアップメッセージが表示されます。 これは有効期限の 7 日前まで週に 1 回表示されます。 その後、毎日のように述べて表示されます *Adobe Acrobatのライセンスは 2020 年 30 月 11 日に期限切れになります。 システムを停止することなくAcrobatを引き続き使用するには、管理者に連絡してください。*

![Acrobat期限切れの通知](assets/acrobatexpiring.png)

**有効期限後**

シリアル番号が期限切れになると、ユーザーはAcrobatにアクセスできなくなります。 有効期限が切れた後の最初の起動時に、 *入力したシリアル番号は期限切れです。 この製品はライセンス認証できません。 カスタマーサポートにお問い合わせください。*

![有効期限後のAcrobatメッセージ](assets/acrobatafterexpire.png)

それ以降にAcrobatを起動しようとすると、エンドユーザーに **ログインする** その後、独自のAdobe IDを作成して体験版モードにするオプションが表示されます。 ただし、エンドユーザーが作成した新しいAdobe IDは、組織のライセンスに関連付けられず、ユーザーに混乱を招きます。

![Acrobat Sign in dialog 1](assets/acrobatsignin1.png)

![Acrobat Sign in dialog 2](assets/acrobatsignin2.png)

## サポートが必要な場合は、お問い合わせください

の使用に関して質問がある場合は、 [AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) シリアル番号のデプロイメントからユーザー指定ライセンスへの移行には、いくつかのオプションがあります。
* エンタープライズオンボーディングチームにAdobeメールを送信します。 **entonb@adobe.com**
* サポートチケットを開く [Admin Console](https://adminconsole.adobe.com/support)
* カスタマーアカウントマネージャーまたはAdobeサクセスマネージャーにお問い合わせください。
