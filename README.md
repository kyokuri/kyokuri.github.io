kyokuri.pwsj.org
================

京都クリエイティブワークショップの公式Webサイトです。

Howto
===============

- アップロードする前にはローカルでテストするのがオススメです。
- レビュー前のエントリを上げる時はレポジトリを切るか、`published: false`にすると公開サイトの一覧に載らないので、適切に利用しましょう。

```sh
$ bundle install
$ bundle exec jekyll serve
```

Less
===============
```sh
$ npm install -g less
$ lessc --clean-css stylesheets/common.less > stylesheets/common.less.css
```
