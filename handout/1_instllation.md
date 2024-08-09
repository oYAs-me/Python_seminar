# 第一回: 環境構築とTwitterデータ取得の準備

## 環境構築

### Visual Stadio Code(VSCode)のインストール

- <a href="https://code.visualstudio.com/download" target="_blank" rel="noopener noreferrer">ダウンロードリンク</a>から対応するOSでインストールする
- 特にこだわりがなければ、青いボックスのを選択すればよい
- ダウンロードしたインストーラを実行する
- 基本的には「次へ」を選択すればよいが、必要に応じて「デスクトップ上にアイコンを作成する」を選択する

#### 環境設定

- VSCodeを起動し、![Extension](/images/extension.png)を選択する
- 検索欄を用いて、「Japanse Language Pack for Visual Studio Code」「Python」（どちらもMicrosoftが作成者）をインストールする
- インストール終了後，VSCodeを再起動する
- 表示が日本語化されれば初期設定は終了

---

### Pythonのインストール

<a href="https://www.python.org/downloads/" target="_blank" rel="noopener noreferrer">ダウンロードリンク</a>から最新版のPythonをインストールする

VSCodeの画面上部のタブから「ターミナル」>「新しいターミナル」を選択して

```bash
Python
```

と入力する。

`Python 3.12.5 (tags/v3.12.5:ff3bc82, Aug  6 2024, 20:45:27) [MSC v.1940 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.`などのようにバージョン情報が返ってくることを確認できればインストール完了

上手くいかない場合は<a href="https://note.com/qk01yasu/n/n5c81d4706f91" target="_blank" rel="noopener noreferrer">私の書いた記事</a>を参考にすると解決する場合もある

---

### Twitterデータ取得

<a href="https://x.com/settings/download_your_data" target="_blank" rel="noopener noreferrer">𝕏の設定</a>から「アーカイブをリクエスト」する

---

おわり
