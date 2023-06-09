# 事前準備

## 必要なアカウントや設定

- OpenAI 社のアカウント
- Microsoft Azure アカウント
- LINE アカウント
- お使いのスマートフォンで LINE アプリケーションがインストールされてチャットができること
- OpenAI 社 ChatGPT API キーがあること

詳細の設定は以下をご覧ください。

## OpenAI 社のアカウントの取得

![e87f6ca928239a4f4318995f3000b692](https://i.gyazo.com/e87f6ca928239a4f4318995f3000b692.jpg)

[OpenAI 社のトップページ](https://openai.com/)の右上のメニューから Sign up ボタンをクリックします。

![2fe8702eb8814bf040e8c19f977ef5a8](https://i.gyazo.com/2fe8702eb8814bf040e8c19f977ef5a8.png)

さらにパスワードを設定し、Continueを押すと、メールが送信されます。

![img](https://gyazo.com/bd9dcdba593bcb272dc2d99072520370.png)

下記のようなメールが届きます。

![img](https://gyazo.com/124872c2fc0a7f64a31eee463a7b729a.png)

メールのVerify email addressをクリックするとメールアドレスが認証されました。

![](https://gyazo.com/253a5ae39b635820b1648615670fb480.png)

再度[ログインページ](https://chat.openai.com/auth/login)にアクセスし、先ほどのメールアドレスとパスワードを使用して、ログインしましょう。

初ログインに成功すると、下記のような名前と生年月日の入力ページが表示されます。

![img](https://gyazo.com/fbf6c39afc5a82deaf375edd76630555.png)

名前と生年月日を入力すると次は、電話番号の入力を行います。

![img](https://gyazo.com/30684ec04633bc9c67b276071e1e2a01.png)

Secd codeをクリックするとOpenAIから6桁の認証コードが送られてきます。

※皆さんは596196ではありません。

![img](https://gyazo.com/52916d53b93b0795553808ed65e41473.png)

送られてきた認証コードを下記の画面で入力します。

![img](https://gyazo.com/3caf47b4dcdc0182d2ed8dfa9cf071f7.png)

電話番号の認証に成功すると、ChatGPTの画面に映ります。

![img](https://gyazo.com/49038171a1c26ad93ae3bcd41c0c06fe.png)

次に[OpenAI Platform](https://platform.openai.com/)に移ります。アカウントが作成できているとアプリの選択ページが表示されます。これでOpenAIアカウントの準備は終了です。

![c23a9f0bd362823347f92d420e4ab185](https://i.gyazo.com/c23a9f0bd362823347f92d420e4ab185.png)

このような API ページ https://platform.openai.com/ が表示されます。

## Microsoft Azure アカウントの取得

Azure サービスを作成して使用するには、まず、サインアップする必要があります。 これまで Azure の試用や支払いを行ったことがない方は、Azure 無料アカウントにサインアップすることができます。

Azure 無料アカウントを作成するには、有効なクレジット カードが必要です。このカードは本人確認のみに使用されます。アップグレードを選択するまで、カードは "課金されません"。

![4d5dc4dac3c60876d9aac271779397e2](https://i.gyazo.com/4d5dc4dac3c60876d9aac271779397e2.jpg)

Web ブラウザーで、https://azure.microsoft.com/free にアクセスします。利用可能な特典と無料サービスの詳細については、ページを下までスクロールしてご覧ください。

![8f8ea427c2240e70123c882021e55874](https://i.gyazo.com/8f8ea427c2240e70123c882021e55874.png)

無料ではじめるボタンをクリックします。

![bc9ded8c14d64cf556280a50a00f3268](https://i.gyazo.com/bc9ded8c14d64cf556280a50a00f3268.png)

Microsoft または GitHub のアカウントでサインインするか、無料の Microsoft アカウントを作成します。

- 自分の情報ページで、適切な国またはリージョンを選択します。 氏名、メール アドレス、電話番号を入力します。 国や地域によっては、VAT 番号など、追加のフィールドが表示される場合があります。 「次へ」を選択して続行します。
- 電話による本人確認ページで、国番号を選択し、自分がすぐに使える電話の番号を入力します。
- 入力後、テキストまたは通話で確認コードを取得できます。関連するボタンを選択し、確認コードボックスにコードを入力して、コードの確認を選びます。
- 確認コードが正しい場合は、有効なクレジット カードの詳細を入力するように求められます。 カード情報を入力し「次へ」を選択します。
- 最後の手順では、契約とプライバシーに関する声明を確認し、サインアップを選択します。

これらの無料のアカウントが正常に設定されたので、Azure portal のホーム ページが表示されるはずです。

📝参考資料

- 演習 - Azure アカウントを作成する - Training | Microsoft Learn
  - https://learn.microsoft.com/ja-jp/training/modules/create-an-azure-account/3-exercise-create-an-azure-account
- Azure の基礎の概要 - Training | Microsoft Learn
  - https://learn.microsoft.com/ja-jp/training/modules/intro-to-azure-fundamentals/

## LINE Developers に LINE アカウントでログイン

![image](https://i.gyazo.com/4bb4c0bffb3c961ea749ec833e2e826b.jpg)

→ [LINE Developers ログイン](./00-preparation/01-line-developer-login.md)

## LINE Bot を 1 つ作成

![94ebdeba5924a72b3932db3033f94a98](https://i.gyazo.com/94ebdeba5924a72b3932db3033f94a98.png)

→ [LINE Bot 作成](./00-preparation/02-create-linebot.md)

## OpenAI 社 ChatGPT API キーの取得

![59721bc470b73edf42fe34f4ae88a4e3](https://i.gyazo.com/59721bc470b73edf42fe34f4ae88a4e3.png)

→ [ChatGPT API キーの取得](./00-preparation/03-get-chatgpt-api-key.md)
