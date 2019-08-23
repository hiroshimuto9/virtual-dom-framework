# virtual-dom-framework
## 動作環境

```
node -v
v11.12.0

npm -v
6.9.0
```

## 初期設定
1 . プロジェクトディレクトリの作成
```../
mkdir virtual-dom-framework
cd virtual-dom-framework
```

2 . pacage.jsonの生成
```../virtual-dom-framework
npm init -y
```

3 . typescriptパッケージの追加
```../virtual-dom-framework
npm install -D typescript
npm install -D @types/node
```
※ -D は --save-devの略

4 . tsconfig.jsonの生成
```../virtual-dom-framework
npx tsc --init
```

5 . tsconfig.jsonを参考資料と同設定にする。

※　今回は参考資料と同環境にする(細かい設定については、興味ある方調べてみてください。)

6 . webpack.config.jsの生成
```../virtual-dom-framework
npm install --save-dev webpack
npm install webpack-cli --save-dev
```
1. webpack.config.jsを作成
2. 設定を記述(ファイル参照)

7 . ts-loaderの追加
※ TypeScriptをwebpackで処理するためのもの
```
npm install -D ts-loader
```

8 . 開発用サーバーを立てる
1. モジールをインストール
```
npm install --save-dev webpack-dev-server
```
2. package.jsonにscriptを追加
```json
"scripts": {
      "start": "webpack-dev-server"
}
```

