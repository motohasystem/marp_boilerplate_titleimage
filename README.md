
<img src="./img/アクリル絵の具で塗装する.png" width="200px" />
⇨
<img src="./img/title.png" width="300px" />

# Marp用のタイトル画像ボイラープレートの使い方

このリポジトリは、Marpを使用してブログ用のタイトル画像スライドを作成するためのボイラープレートです。以下の手順に従って、簡単にタイトル画像を生成することができます。

生成するタイトル画像は1280x680のサイズを想定しています。必要に応じて`title_image.css`の中身に手を加えてみてください。

## 必要なもの

- Node.js
- Marp CLI

## セットアップ

1. Node.jsをインストールします。
2. Marp CLIをグローバルにインストールします。

   ```bash
   npm install -g @marp-team/marp-cli
   ```

3. このリポジトリをクローンします。

   ```bash
   git clone https://github.com/motohasystem/marp_boilerplate_titleimage
   cd marp_boilerplate_titleimage
   ```

## スライドの作成

1. `index.md` ファイルを編集して、スライドの内容を記述します。Markdown形式でスライドを作成できます。

2. `make.bat` を実行して、スライドを画像として生成します。

   ```bash
   make.bat
   ```

   これにより、`index.png` という名前の画像ファイルが生成されます。

## カスタムテーマの使用

- `themes` フォルダ内にカスタムCSSテーマが含まれています。`make.bat` 内で使用するテーマを指定することができます。

  例: `themes/title_image.css` を使用する場合は、`make.bat` 内の `--theme` オプションを変更します。

## 注意事項

- `make.bat`はWindows用のバッチファイルであることにご注意ください。
- スライドのデザインをカスタマイズするには、`themes` フォルダ内のCSSファイルを編集してください。

このボイラープレートを使用して、素晴らしいスライドを作成してください！
