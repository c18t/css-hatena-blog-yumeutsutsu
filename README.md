# css-hatena-blog-yumeutsutsu
'それでいいです' のブログテーマ

## How to Develop
1. `yarn dev` します
2. Stylusに `@import url('http://127.0.0.1:8080/theme-hatena-blog-yumeutsutsu.css');` でスタイルを作ります
3. はてなを見ながらデザインします

## Project Making
```sh
$ gitignore code node windows macos
$ yarn init
$ yarn add stylus
$ yarn add ress
$ yarn add -D live-server
$ yarn add -D npm-run-all
$ echo '*.css' >> .gitignore
$ echo '*.map' >> .gitignore
$ echo '@import "node_modules/ress/ress.css";' > theme-hatena-blog-yumeutsutsu.styl
```

## License
[MIT](./LICENSE)
