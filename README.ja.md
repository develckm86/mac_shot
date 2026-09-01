<div align="center">

<img src="docs/images/00-icon.png" width="88" alt="">

# スクリーンショット · ScreenCapture

**Mac のスクリーンショットを、そのまま Windows で。**
範囲をドラッグすれば、その場でデスクトップに PNG が保存されます。

[한국어](README.md) · [English](README.en.md) · [简体中文](README.zh-CN.md) · 日本語

### [⬇ ScreenCapture.exe をダウンロード（Windows 10 · 11 · 64bit）](https://github.com/develckm86/mac_shot/releases/latest/download/ScreenCapture.exe)

無料 · インストール不要 · アカウント不要 · ダウンロードしてそのまま実行

画面収録も使うなら [`ffmpeg.exe`](https://github.com/develckm86/mac_shot/releases/latest/download/ffmpeg.exe) も入手して**同じフォルダー**に置いてください。
([2 つをまとめた zip](https://github.com/develckm86/mac_shot/releases/latest/download/ScreenCapture-0.4.0-win64.zip))

<!-- Microsoft Store の公開後、下の行のコメントを外して URL を入れてください。
[<img src="https://get.microsoft.com/images/ja%20dark.svg" width="200" alt="Microsoft Store で入手">](https://apps.microsoft.com/detail/ストアID)
-->
**Microsoft Store** — 申請準備中です。公開されたらここにバッジが入ります。

</div>

---

## なぜ作ったか

Windows にもキャプチャツールはありますが、**保存が面倒**です。クリップボードに入り、
通知を押し、エディタが開き、保存先を選ぶ。Mac なら範囲をドラッグした時点で
デスクトップに PNG が置かれています。このアプリはその流れを持ってきたものです。

ウインドウはありません。起動すると通知領域に入り、あとはショートカットだけです。

## できること

### ドラッグしたら終わり — `Ctrl+Shift+4`

![範囲キャプチャ](docs/images/03-region.png)

十字カーソルで範囲をドラッグし、離した瞬間にファイルが保存されます。ドラッグ中は
サイズが表示され、離すときに `Ctrl` を押していればファイルではなくクリップボードへ。

### macOS と同じツールバー — `Ctrl+Shift+5`

![スクリーンショットツール](docs/images/02-toolbar.png)

画面全体・ウインドウ・範囲のキャプチャに加えて、画面全体の収録と範囲収録。選択範囲は
8 方向のハンドルで調整でき、内側をドラッグすれば全体を動かせます。

### 保存先 · タイマー · マイク

![オプション](docs/images/04-options.png)

macOS スクリーンショットのオプションメニューを、項目も順番もそのまま。ひとつだけ
追加されているのが **言語** です。

### 途中で落ちても録れた分は残ります

![収録中の表示](docs/images/05-recording.png)

収録中は画面上部に経過時間と停止ボタンが出ます。**この表示は録画には写りません。**
断片単位でディスクに書いていくので、収録中にアプリが強制終了しても、そこまでの
映像はそのまま再生できます。

### 撮ったあとは右下にしばらく

![フローティングサムネール](docs/images/06-thumbnail.png)

クリックで開き、他のアプリへドラッグして渡せます。右クリックで開く・フォルダーに
表示・コピー・削除。

### 初回起動では使いかたが先に出ます

![起動時の案内](docs/images/01-guide.png)

ウインドウのないアプリは何が起きたか分かりにくいものです。画面中央にショートカットが
5 秒間表示されて消えます。通知領域のメニューからいつでも呼び出せます。

## ショートカット

Mac の `Cmd` を `Ctrl` に置き換えただけです。

| macOS | Windows | 動作 |
| --- | --- | --- |
| `Cmd+Shift+3` | `Ctrl+Shift+3` | 画面全体をキャプチャ — ディスプレイごとに 1 ファイル |
| `Cmd+Shift+4` | `Ctrl+Shift+4` | ドラッグして範囲をキャプチャ |
| `Cmd+Shift+4` → `Space` | 同じ | ウインドウ選択に切り替え |
| `Cmd+Shift+5` | `Ctrl+Shift+5` | スクリーンショットツール |
| `Cmd+Ctrl+Shift+3/4` | `Ctrl+Alt+Shift+3/4` | ファイルではなくクリップボードへ |
| `Cmd+Ctrl+Esc` | `Ctrl+Alt+Esc` | 収録を停止 |

ドラッグ中の `Space`（位置を動かす）· `Shift`（軸をひとつだけ）· `Alt`（始点を中心に
対称）· `Ctrl`（クリップボードへ）· `Esc`（キャンセル）も Mac と同じです。

## インストール

1. [`ScreenCapture.exe`](https://github.com/develckm86/mac_shot/releases/latest/download/ScreenCapture.exe) をダウンロードし、好きなフォルダーに置きます。
2. 実行するとそのまま通知領域に入ります。**インストールも管理者権限も不要です。**
3. 画面収録を使うなら [`ffmpeg.exe`](https://github.com/develckm86/mac_shot/releases/latest/download/ffmpeg.exe) を**同じフォルダー**に置きます。
   なくてもキャプチャは動きます — 収録だけが使えなくなります。

不要になったらファイルを削除するだけです。設定だけが `%APPDATA%\ScreenCapture` に残ります。

> 署名なしの実行ファイルなので、初回起動時に SmartScreen が一度確認してきます。
> **詳細情報 → 実行**を選んでください。

## 言語

12 言語に対応しています。既定では Windows の表示言語に従い、オプションメニューから
手動で選ぶこともできます。

한국어 · English · 日本語 · 简体中文 · 繁體中文 · Español · Português ·
Français · Deutsch · Русский · Italiano · Tiếng Việt

言語別の使用説明書は [`docs/manual/`](docs/manual) にあります。

## 広告について

このアプリは無料で、広告によって運営されています。**キャプチャが終わったあとだけ**、
タスクバーの上に正方形のバナーが 9 秒間表示されて消えます。

![広告バナー](docs/images/08-ad.png)

- 上部に必ず広告表示と ✕ が付いています。
- キャプチャが始まる前にバナーを片付けます — **撮った画像や録画には写りません。**
- キャプチャを妨げません。インターネットに繋がっていなければ何も出ません。
- バナー画像を取得する以外に、**データの収集も送信も行いません。** 撮った画像と
  映像は指定したフォルダーの中だけに残ります。

## 動作環境

| | |
| --- | --- |
| OS | Windows 10 バージョン 2004 以降 / Windows 11（64bit） |
| 権限 | 管理者権限は不要 |
| ディスク | 約 170MB（アプリ + ffmpeg） |

## ライセンスと再配布

**誰でもそのまま配布して構いません。** ウェブサイト、ブログ、USB、社内配布いずれも
許可は要りません。できないのは、広告を取り除いたり広告リンクを差し替えたコピーを
配ることだけです — それがこのアプリを無料に保っている仕組みです。条件の全文は
[LICENSE](LICENSE) にあります。

同梱の `ffmpeg.exe` は FFmpeg 自体のライセンス（LGPL/GPL）に従います。

---

<div align="center">
不具合や要望は <a href="https://github.com/develckm86/mac_shot/issues">Issue</a> へどうぞ。
</div>
