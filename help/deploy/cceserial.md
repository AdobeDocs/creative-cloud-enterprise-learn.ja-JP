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

これまで、Adobeはエンタープライズタームライセンス契約 (ETLA) に基づいて、アプリケーション (Creative Suite、エンタープライズ版Creative Cloud、Acrobat XI、Acrobat DCなど ) でシリアル番号を発行してきました。 これらのシリアル番号には有効期限があります。 有効期限を過ぎると製品は機能しなくなります。そのため、シリアル番号が期限切れになる前に移行を計画することが重要です。 このページでは、エンドユーザーが自分のアプリケーションやサービスに引き続きアクセスできるように、必要なAdobe手順について説明します。

## シリアル番号の有効期限の確認

### シリアル番号の検索

ETLA契約のシリアル番号ライセンスは、 [Adobeライセンス Web サイト](https://licensing.adobe.com/) (LWS) を選択します。 表示およびダウンロードするには、次の手順に従います。

1. ログイン [Adobeライセンス Web サイト](https://licensing.adobe.com/) (LWS) にAdobe IDとパスワードを入力します。
1. 選択 **ライセンス/シリアル番号の取得**&#x200B;を選択します。
1. 次の **エンドユーザー ID** または **デプロイ先 ID**&#x200B;を選択します。
1. （オプション） **製品名**, **製品バージョン**、または **Platform** を使用して結果をフィルタします。
1. 「検索」をクリックします。
1. 製品名とシリアル番号が表示されます。
1. （オプション）「CSV に書き出し」を選択して、シリアル番号のリストをダウンロードします。

![シリアル番号の検索](assets/retrieveserialnumbers.png)

### 有効期限の確認

この [AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) は、コンピューター上のAdobe製品が期限切れのシリアル番号を使用しているか、期限切れのシリアル番号を使用しているかを IT 管理者が確認するためのコマンドラインユーティリティです。 ツールには、製品ライセンス識別子 (LEID)、暗号化シリアル番号、有効期限などの情報が表示されます。 This [page](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) contains instructions on downloading &amp; using the tool on either Mac or Windows computers.

## シリアル番号の有効期限が切れる前と後のエンドユーザーエクスペリエンスについて

Both Acrobat and Creative Cloud for enterprise apps will begin to display messages (in the apps) starting 60 days before expiration. シリアル番号が期限切れになると、製品は機能しなくなり、ユーザーにアクションを促します。

### Creative Cloud for enterprise experience

次の情報は、エンドユーザーのエクスペリエンスの概要を示しています。 以下の短いビデオに続いて、エンドユーザーのエクスペリエンスについて説明します。

>[!VIDEO](https://video.tv.adobe.com/v/331746?hidetitle=true)

**有効期限前**

シリアル番号が期限切れになる 60 日前から、エンタープライズアプリケーションのすべてのCreative Cloudで、エンドユーザーに製品内ダイアログボックスが表示されます。 このメッセージは、有効期限の 30 日前まで毎週表示され、有効期限が設定されるまで毎日表示されます。 *ライセンスの有効期限が近づいています。 このAdobe製品のライセンスは 2020 年 11 月 29 日に期限切れになります。 引き続きアクセスするには、管理者に連絡してください*&#x200B;を選択します。

![CCE期限前メッセージ](assets/cceexpiring.png)

**有効期限後**

シリアル番号が期限切れになると、ユーザーはエンタープライズアプリケーションのCreative Cloudにアクセスできなくなります。 有効期限が切れた後の最初の起動時に、 *入力したシリアル番号は期限切れです。 この製品はライセンス認証できません。 カスタマーサポートにお問い合わせください*&#x200B;を選択します。

![CCEの有効期限メッセージ](assets/cceafterexpire.png)

それ以降アプリケーションを起動しようとすると、エンドユーザーに **ログインする** その後、独自のAdobe IDを作成して体験版モードに切り替えるオプションが表示されます。 ただし、エンドユーザーが作成した新しいAdobe IDは組織のライセンスに関連付けられず、ユーザーに混乱を招きます。 業務の中断や混乱を避けるため、シリアル番号の有効期限が切れる前に、ユーザー指定ライセンスにユーザーを移行してください。

![CCEサインインダイアログ 1](assets/ccesignin1.png)

![CCEサインインダイアログ 2](assets/ccesignin2.png)

### Acrobat experience

次の情報は、エンドユーザーのエクスペリエンスの概要を示しています。 以下の短いビデオに続いて、エンドユーザーのエクスペリエンスについて説明します。

>[!VIDEO](https://video.tv.adobe.com/v/331749?hidetitle=true)


**有効期限前**

シリアル番号が期限切れになる 60 日前から、Acrobatでは製品内ポップアップメッセージがエンドユーザーに表示されます。 これは有効期限の 7 日前まで週に 1 回表示されます。 その後、毎日のように述べて表示されます *Adobe Acrobatのライセンスは 2020 年 30 月 11 日に期限切れになります。 システムを停止することなくAcrobatを引き続き使用するには、管理者に連絡してください。*

![Acrobat期限切れメッセージ](assets/acrobatexpiring.png)

**有効期限後**

シリアル番号が期限切れになると、ユーザーはAcrobatにアクセスできなくなります。 有効期限が切れた後の最初の起動時に、 *入力したシリアル番号は期限切れです。 この製品はライセンス認証できません。 カスタマーサポートにお問い合わせください。*

![有効期限後のAcrobatメッセージ](assets/acrobatafterexpire.png)

それ以降にAcrobatを起動する場合は、エンドユーザーに **ログインする** その後、独自のAdobe IDを作成して体験版モードに切り替えるオプションが表示されます。 ただし、エンドユーザーが作成した新しいAdobe IDは組織のライセンスに関連付けられず、ユーザーに混乱を招きます。

![Acrobat Sign in dialog 1](assets/acrobatsignin1.png)

![Acrobat Sign in dialog 2](assets/acrobatsignin2.png)

## サポートが必要な場合は、お問い合わせください

この [AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) ツールまたはシリアル番号のデプロイメントから指定ユーザーへの移行でサポートが必要な場合は、いくつかのオプションがあります。
* エンタープライズオンボーディングチームにAdobeメールを送信します。 **entonb@adobe.com**
* Open a support ticket in [Admin Console](https://adminconsole.adobe.com/support)
* カスタマーアカウントマネージャーまたはAdobeサクセスマネージャーにお問い合わせください。
