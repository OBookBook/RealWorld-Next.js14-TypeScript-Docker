<p align="center">
  <a href="https://nextjs.org/blog/next-14" target="_blank">
    <img src="https://nextjs.org/static/blog/next-14/twitter-card.png" width="650" alt="Nextjs Logo">
  </a>
</p>

# Conduit プロジェクト - Next.js 14 実装

Conduit は、RealWorld プロジェクトの一環として、Medium.com のクローンサイトを作成するためのブログプラットフォームです。このプロジェクトは、実際の世界と同じ機能を持つプラットフォームを作ることで、学習したいフレームワークの技術を習得することを目的としています。

## UI実装

以下のページの HTML と CSS を実装し、ページを作成してください。この段階では機能は実装せず、見た目のみを整えます。

- Home
- Create/Edit Article
- Article

## 機能実装

![image](https://github.com/OBookBook/RealWorld-Next.js14-TypeScript-Docker/assets/130152109/0e886f9e-9c0c-4af8-b987-1781bba9ab27)

- Home: `http://localhost:3000/`

![image](https://github.com/OBookBook/RealWorld-Next.js14-TypeScript-Docker/assets/130152109/ad02e723-9617-4fb6-bdd3-5eec22c5ae84)

- Create Article: `http://localhost:3000/article/create-edit`

![image](https://github.com/OBookBook/RealWorld-Next.js14-TypeScript-Docker/assets/130152109/0b44664a-87f2-411d-9f6d-511f70025539)


- Edit Article: `http://localhost:3000/article/create-edit?slug=1&edit=true`

![image](https://github.com/OBookBook/RealWorld-Next.js14-TypeScript-Docker/assets/130152109/b11be7e3-c2a5-4507-add0-e149780c791d)

- Article (認証機能や著者、お気に入り機能は実装不要): `http://localhost:3000/article/1`


## 工夫した点

- **作成ページと編集ページの統合**:

  - 目的: 作成ページと編集ページを一つに統合し、コードの保守性と再利用性を向上させました。

- **typesフォルダを作成した型定義**:

  - 目的: コードの可読性と保守性を向上させるために、型定義を分離して管理しました。

- **コンポーネントの再利用**:

  - 目的: 共通のコンポーネントを作成し、コードの重複を減らし、保守性を向上させました。
  
# Setup

## Environment

```shell
docker-compose up -d
```

# Next.js

http://localhost:3000/

# Container Shell

```bash
docker-compose exec client bash
```
