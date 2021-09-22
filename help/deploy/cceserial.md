---
title: エンタープライズおよびAcrobatのシリアル番号の有効期限に関するCreative Cloudとは
description: Creative Cloud for enterpriseおよびAcrobatのシリアル番号の有効期限について
role: User
level: Beginner, Intermediate
exl-id: bc457be0-86dc-4e8a-b6b2-34bc76af2d21
source-git-commit: 6b819aef801e003e5a160d24ba69522cf6a7e715
workflow-type: tm+mt
source-wordcount: '848'
ht-degree: 3%

---

# エンタープライズおよびAcrobatのシリアル番号の有効期限に関するCreative Cloudとは

従来、Adobe社は、Enterprise Term License Agreement(ETLA)に基づいて、当社のアプリケーション(Creative Suite、Creative Cloud for enterprise、Acrobat XI、Acrobat DC)と共にシリアル番号をお客様に発行してきました。 これらのシリアル番号は有効期限が設定されています。 有効期限が過ぎると、製品は機能しなくなるので、シリアル番号が期限切れになる前に移行を計画することが重要です。 このページでは、エンドユーザーがAdobeアプリとサービスに引き続きアクセスできるようにするために必要な手順の概要を説明します。

## シリアル番号の有効期限を確認しています

### シリアル番号の検索

ETLA契約に関連するシリアル番号のライセンスは、[Adobe Licensing Webサイト](https://licensing.adobe.com/) (LWS)で入手できます。 次の手順に従って、表示とダウンロードを行います。

1. Adobe IDとパスワードを使用して、[Adobe Licensing Webサイト](https://licensing.adobe.com/) (LWS)にサインインします。
1. **[ライセンス]>[シリアル番号の取得]**&#x200B;を選択します。
1. **エンドユーザーID**&#x200B;または&#x200B;**展開先ID**&#x200B;を入力します。
1. （オプション）結果をフィルター処理するには、**製品名**、**製品バージョン**、または&#x200B;**プラットフォーム**&#x200B;を選択します。
1. 「検索」をクリックします。
1. 製品名とシリアル番号が表示されます。
1. （オプション）シリアル番号のリストをダウンロードするには、「EXPORT TO CSV」を選択します。

![シリアル番号を検索](assets/retrieveserialnumbers.png)

### 有効期限の確認

[AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html)は、IT管理者が、期限切れまたは期限切れのシリアル番号を使用しているかどうかを確認するためのコマンドラインユーティリティです。 このツールには、製品ライセンス識別子(LEID)、暗号化されたシリアル番号、有効期限などの情報が表示されます。 この[ページ](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html)には、MacまたはWindowsコンピュータでツールをダウンロードし、使用する方法が記載されています。

## シリアル番号の有効期限の前後のエンドユーザーエクスペリエンスを理解する

AcrobatとCreative Cloud for Enterpriseアプリの両方で、有効期限が切れる60日前から（アプリ内の）メッセージの表示が開始されます。 シリアル番号が切れると、製品は動作しなくなり、ユーザーに対して処理を行うよう求められます。

### エンタープライズエクスペリエンス向けのクリエイティブクラウド

次の情報は、エンドユーザーの操作性の概要を示します。 以下に短いビデオを示し、エンドユーザーの操作性を確認します。

>[!VIDEO](https://video.tv.adobe.com/v/331746?hidetitle=true)

**有効期限前**

シリアル番号の有効期限が切れる60日前から、すべてのエンタープライズアプリ用Creative Cloudで、製品内のダイアログボックスがエンドユーザーに表示されます。 このメッセージは毎週表示され、有効期限が切れる30日前までは毎日表示され、*ライセンスの有効期限が切れる日付まで表示されます。 このAdobe製品は、2020年11月29日に期限切れになる予定のライセンスを使用しています。 管理者に連絡して、引き続き*&#x200B;にアクセスできることを確認してください。

![CCE before expirationメッセージ](assets/cceexpiring.png)

**有効期限切れ後**

シリアル番号が期限切れになると、ユーザーはエンタープライズアプリのCreative Cloudにアクセスできなくなります。 有効期限が切れた後の最初の起動時に、*入力したシリアル番号の有効期限が切れたことを示すダイアログ・ボックスが表示されます。 この製品はライセンスを取得できません。 カスタマーサポート*&#x200B;にお問い合わせください。

![CCE after expirationメッセージ](assets/cceafterexpire.png)

それ以降にアプリを起動しようとすると、エンドユーザーは&#x200B;**今すぐサインイン**&#x200B;するように求められ、その後に独自のAdobe IDを作成して試用モードに入るオプションが表示されます。 ただし、エンドユーザーが作成した新しいAdobe IDは、組織のライセンスに関連付けられず、ユーザーの混乱を招きます。 業務の中断や不要な混乱を避けるには、シリアル番号が期限切れになる前に、ユーザーを名前付きユーザーライセンスに移行します。

![CCEサインインダイアログ1](assets/ccesignin1.png)

![CCEサインインダイアログ2](assets/ccesignin2.png)

### Acrobatの操作性

次の情報は、エンドユーザーの操作性の概要を示します。 以下に短いビデオを示し、エンドユーザーの操作性を確認します。

>[!VIDEO](https://video.tv.adobe.com/v/331749?hidetitle=true)


**有効期限前**

シリアル番号が期限切れになる60日前に、Acrobatは製品内のポップアップメッセージをエンドユーザーに表示します。 これは1週間に1回、有効期限が切れる7日前まで表示されます。 次に、*Adobe Acrobatのライセンスの有効期限が30/11/2020に切れると、毎日表示されます。 Acrobatの使用を中断せずに続行するには、管理者に問い合わせてください。*

![Acrobatの期限切れメッセージ](assets/acrobatexpiring.png)

**有効期限切れ後**

シリアル番号が期限切れになると、ユーザーはAcrobatにアクセスできなくなります。 有効期限が切れた後の最初の起動時に、*入力したシリアル番号の有効期限が切れたことを示すダイアログ・ボックスが表示されます。 この製品はライセンスを取得できません。 カスタマーサポートにお問い合わせください。*

![期限切れ後のAcrobatメッセージ](assets/acrobatafterexpire.png)

Acrobatの起動を試みると、エンドユーザーは&#x200B;**今すぐサインイン**&#x200B;するように求められ、その後に独自のAdobe IDを作成して試用モードに切り替えるオプションが表示されます。 ただし、エンドユーザーが作成した新しいAdobe IDは、組織のライセンスに関連付けられず、ユーザーの混乱を招きます。

![Acrobatサインインダイアログ1](assets/acrobatsignin1.png)

![Acrobatサインインダイアログ2](assets/acrobatsignin2.png)

## お問い合わせ

[AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html)ツールの使用に関する質問や、シリアル番号の配置から名前付きユーザーへの移行に関するヘルプが必要な場合は、次のオプションを使用できます。
* Adobe Enterprise Onboardingチームに電子メールを送信します – **entonb@adobe.com**
* [管理コンソール](https://adminconsole.adobe.com/support)でサポートチケットを開く
* AdobeアカウントマネージャまたはCustomer Success Managerに連絡する
