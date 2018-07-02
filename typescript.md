## 概要
TypeScriptは型がついたJavaScriptです。

## インストール方法(Mac)
### Node.jsのインストール
`brew install node`

### npmを使って、TypeScriptをインストール
`sudo npm i -g typescript`
強制なので、パスワードを入力するとインストールができるかと思います。

### Quick Start
`npm install -g typescript`

当然の振る舞いですね
```.js
const a: number = 3;
const b: string = a; // エラー: Type 'number' is not assignable to type 'string'.
```