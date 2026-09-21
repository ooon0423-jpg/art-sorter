<p align="center"><img src="docs/icon.png" width="96" alt="Art Sorter アイコン"></p>

<h1 align="center">Art Sorter</h1>

<p align="center"><b>イラスト、ファンアート、AI生成画像を数千枚単位で、キャラクターと場面ごとに並べるWindowsアプリ。処理はすべて自分のPC内で。</b></p>

<p align="center">
<a href="https://orilabs.studio/artsorter/ja/?utm_source=github">公式サイト</a> ·
<a href="https://orilabs.studio/artsorter/ja/get/?utm_source=github">Windows版をダウンロード</a> ·
<a href="https://orilabs.studio/artsorter/ja/guides/?utm_source=github">ガイド</a> ·
<a href="README.md">English</a> · <a href="README.ko.md">한국어</a> · <a href="README.zh.md">简体中文</a>
</p>

<p align="center"><img src="docs/before-after.jpg" alt="同じ画像。左はばらばらの状態、右はArt Sorterがキャラクターと場面ごとに並べた列" width="820"></p>

フォルダをドロップすると、ファイル名ではなく絵を見て一列に並べます。同じキャラクター同士、次に同じ場面同士、次に続きの順番で。サイズ違いのコピーまで別にまとめます。すべて自分のPCの中で動きます。

> このリポジトリは説明書と公開の問い合わせ窓口です。Art Sorter本体は無料体験つきの非公開ソースのデスクトップアプリです。

## できること

- **キャラクターでまとめる。** イラストで学習したモデルが、別の日や別の作者の絵でも同じキャラクターをまとめます。
- **次に場面と順番。** キャラクターの中で場面ごとに、次に続きの順番で並べます。
- **重複は別に。** まったく同じコピー、縮小・形式変換・保存し直したコピーを別フォルダに集め、比べて選べます。何も削除しません。
- **並べ直さずに追加。** 新しい画像は似た画像の隣に差し込まれます。整えた並びはそのままです。
- **出どころも見る。** 一つのフォルダ、または同じ名前の形の画像がほとんど一つのグループに入れば、はぐれた数枚を戻します。
- **名前は一度だけ。** 画像を選んで名前を入れると、まとめて変わります。触られたくないセットは固定できます。
- **すべて元に戻せる。** どの手順も取り消せ、移動したファイルはワンクリックで元のフォルダに戻ります。
- **タグの書き出し。** Hydrusサイドカー、digiKam・XnView MP向けXMP、Eagle、CSV。元のファイルは変更されません。
- **大きなコレクションにも。** 一度に数万枚、一時停止と再開ができます。
- **画面の言語は18種類。**

[![2分半のデモ動画](docs/sort-animation-poster.jpg)](https://youtu.be/OSMyfuTyGz8)

実際の結果：デモ用113枚（キャラクター3人×場面4つ）をノートPCで約2分半で並べ、最後の2枚がずれました。

## プライバシー

Art SorterはWebサービスではなくデスクトップアプリです。アカウントもアップロードもありません。画像、ファイル名、フォルダ名はPCの外に出ません。初回起動時に分析用モデルを一度ダウンロードすれば、ネットを切っても使えます。

確認なしにネットを使うもの：アップデート確認、その一度きりのモデルのダウンロード、匿名のPCコードによるライセンス確認。

## 動作環境

| | |
|---|---|
| OS | Windows 10 / 11（64ビット） |
| メモリ | 8GB（3万枚以上なら16GB推奨） |
| ディスク | 約1.5GB。インストーラー200MB、分析モデル840MBは初回に一度だけダウンロード |
| グラフィック | 任意。DirectX 12対応GPUがあれば自動で使います |

## 価格

- **最初の300枚は無料**です。アカウントもカードも不要です。
- その後は**買い切り**（サブスクではありません）。キー1つでPC1台、アップデートはすべて込み。
- 現在の価格は[公式サイトの価格欄](https://orilabs.studio/artsorter/ja/?utm_source=github#pricing)をご覧ください。

## ガイド

- [数千枚のAI生成画像を整理する方法](https://orilabs.studio/artsorter/ja/guides/organize-ai-images/?utm_source=github)
- [サイズ違いのコピーまで重複画像を探す](https://orilabs.studio/artsorter/ja/guides/find-duplicate-images/?utm_source=github)
- [アニメ・ファンアートをキャラクターごとに自動で整理する](https://orilabs.studio/artsorter/ja/guides/sort-by-character/?utm_source=github)
- [Eagleの代わりになるソフト](https://orilabs.studio/artsorter/ja/guides/eagle-alternative/?utm_source=github)
- [Hydrusの代わりになるソフト](https://orilabs.studio/artsorter/ja/guides/hydrus-alternative/?utm_source=github)

## 問い合わせと不具合の報告

うまく並ばないフォルダが見つかったら、それがいちばん役に立つ報告です。[問い合わせ](../../issues/new/choose)に、枚数、だいたいどんな画像か、何がおかしかったかを書いてください。スクリーンショットも歓迎ですが、公開されても問題ない画像だけにしてください。

メール：contact@orilabs.studio

---

韓国の一人スタジオ、OriLabs Studio（오리랩스）が作っています。
