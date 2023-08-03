# svelte-tutorial

SvelteKit は Svelte の一部で、新世代のフレームワークです。

## 必要なもの

- Node.js (バージョン 14 以上)
- pnpm (`npm install -g pnpm`)

## 新しい SvelteKit プロジェクトの作成

```bash
npm init svelte@next my-sveltekit-project
```

このコマンドを実行した後、質問に答えてセットアップを進めてください。（デフォルト設定で OK な場合は Enter を押して次へ進むことができます）

## プロジェクトディレクトリに移動

```bash
cd my-sveltekit-project
```

## `.npmrc`ファイルの作成

```bash
echo "{\"pnpm\":{\"hoist\":false}}" > .npmrc
```

## 依存関係のインストール

```bash
pnpm install
```

## 開発サーバーの起動

開発サーバーを起動して、SvelteKit プロジェクトを開始します。

```bash
pnpm run dev
```

この後、ブラウザで `http://localhost:5000` を開くと、SvelteKit のウェルカムページが表示されます。

## Tips

- `.svelte` ファイル内で JavaScript と CSS を記述することができます。
- `src/routes` フォルダにページコンポーネントを配置することで、自動的にルーティングが設定されます。
