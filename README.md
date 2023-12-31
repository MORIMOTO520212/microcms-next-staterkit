# microCMS and Next.js StarterKit, 早稲田コンピュータ研究会

## microCMSのセットアップ

microCMSをこれから始める方はまずアカウント作成から行います。  
公式ドキュメントの[アカウント登録](https://document.microcms.io/manual/signup)から手順に沿ってアカウント登録してください。  
次に、サービスの作成とサービスの設定を行ってください。  
すべてできたら、サービスドメインとAPIキーをコピーし、.envファイルに張り付けてください。

```config
MICROCMS_API_KEY=APIキー
MICROCMS_SERVICE_DOMAIN=サービスドメイン
BASE_URL=http://localhost:3000
```

## Getting Started

### Node.jsをインストール

本環境ではNode.js(version18以降)を使う。  
ローカル環境にNode.jsが入っていない場合にはインストールする必要がある。

### セットアップ

パッケージのインストール。

```bash
npm install
```

### First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## スターターキットの全体

![](./docs/structure.drawio.svg)

## webhookを通す

https://kimulaco.com/post/microcms-webhook-to-github-actions/

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
