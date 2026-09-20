# Battle à la carte Unity版（3D版）

既存Web版とは別作品のWindows 64-bit／Android ARM64ダウンロードゲームです。
公開中＆追加要素可能性あり。バージョン0.3.0、Unity 6000.6.0f1。

このリポジトリは紹介ページと配布用の管理リポジトリです。
Unityプロジェクトのソース一式は含みません。配布成果物はReleasesに保存します。

- ホームページ: https://donadonaa24-cyber.github.io/battle-a-la-carte-3d/
- ダウンロード: https://github.com/donadonaa24-cyber/battle-a-la-carte-3d/releases/latest
- ポータル: https://donadonaa24-cyber.github.io/aniani-asobiba/
- 既存Web版: https://donadonaa24-cyber.github.io/battle-a-la-carte--/

## Windows版の起動

ZIPをすべて展開し、`BattleALaCarte.exe`を起動してください。
DataフォルダやDLLを削除・分離しないでください。
ブラウザでexeを実行することはできません。WebGL/iOS版は未提供です。
Web版の保存データや共通アカウントとは連携していません。

## Android試験版

Android 8.0（API 26）以降、ARM64端末向けのAPKを配布しています。
AndroidスマートフォンからAPKを直接ダウンロードし、端末側の案内に従ってインストールできます。パソコンは不要です。
ZIP版には同じAPKと `VERSION_NOTES.txt` が入っています。
物理端末でのタッチ、セーフエリア、復帰、性能は未確認のため試験版です。

## v0.3.0

- CPUの補充後からターン終了までを6～7秒に調整し、各行動へ待機を分散。
- CPUターン後のプレイヤー補充カードを0.5秒間隔で表示し、ドロー演出が省略される問題を修正。
- Android ARM64試験版を追加。

版ごとの詳しい変更内容は、配布ZIPに同梱した `VERSION_NOTES.txt` で確認できます。

## 公開方式

GitHub Pagesは`main`のルートを静的配信します。
配布ZIPはRelease `v0.3.0`のアセットとしてアップロードします。
デバッグ用バックアップ、ログ、認証情報は配布対象外です。

