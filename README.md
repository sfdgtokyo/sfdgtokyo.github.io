# sfdgtokyo.github.io

## Webサイト更新方法

[Jekyll](https://jekyllrb.com/)を使って構築しています。

### 1. Jekyll/bundlerをインストールする

```sh
$ gem install jekyll
$ gem install bundler
```

### 2. このリポジトリを`git clone`する

```sh
$ git clone git@github.com:/sfdgtokyo.github.io.git
```

### 3. Bundler/npmでパッケージをインストールする

```sh
$ bundle install
$ npm install
```

### 4. サイトを監視・更新する

```sh
$ gulp
```

### 5. ブランチを作成 → ファイルを編集

適当なブランチを作成し、エディタで編集する

### 6. pull requestを出す
