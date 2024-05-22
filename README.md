

## 開始

自分のRepositoryにForkする。(右上Forkボタン、"Create fork")

```bash
git clone git@github.com:<あなたのユーザー名>/test-web1.git
pnpm install
pnpm dev
```

[http://localhost:3000](http://localhost:3000) を開く。

## 課題1

Next.jsとChakra UIを使用して、`src/pages/index.tsx`のみを編集して、以下のようなページを作ってください。

どちらもすでにインストールされています。

### 使用するAPI

`https://pokeapi.co/api/v2/pokemon/<ID>`(ID 25がピカチュウ)

取得したJSONの中の、`json.name`が名前(英語)、`json.sprites.front_default`が画像です。
