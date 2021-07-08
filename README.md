# gulp-wp-flocss-remの使い方


- ThemeNameはテーマ名に変更する
- 以下の「フォルダ名の書き換えが必要」はThemeNameに合わせる
	- ThemeName・・・テーマフォルダ（★ **フォルダ名の書き換えが必要**）
	- sass
	- gulpfile.js・・・★ **テーマフォルダ名の書き換えが必要**
	- package.json
	- .gitignore
	- .editorconfig
	- index.php

## JSの記述
- assets内のjsフォルダ内で直書きする


## 画像
- assets内のimgフォルダ内で直書きする
- 必要に応じてフォルダを作成してその中にいれる
- 画像の変更があれば自動圧縮
- assetsのimg内にアップロードすればそこで勝手に圧縮されてそこに上書きされる仕組み

## 使い方
- npm i でインストール → node_modulesが生成されればOK
- gulp もしくは npx gulp で起動

# gulp-wp-flocss-rem-fromSP
