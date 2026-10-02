# CURRENT_STATE

更新日: 2026-10-02

- このリポジトリはBattle à la carte Unity版（3D版）の紹介・配布サイト。Unityのゲームソースは含まない。
- 紹介ページの現在の配布リンク: v0.5.0、Windows 64-bit ZIP / Android ARM64 APK。ブラウザ・WebGL・iPhone版は未提供。
- 2026-10-02: 古い対戦画像を、2026-10-01にUnityの検証用Windows Playerから取得した現在の対戦画面へ差し替え。
- メインメニュー、6ミッション、カードスリーブの実画面を追加。各画像は別タブで原寸表示できる。
- 画像は1600×900のロスレスWebP。元の `battle-3d.png` とUnity側の検証PNGは保持。
- 対応環境の注意書きに「今後、Mac版・iPhone版を実装予定（公開時期は未定）」を追加（2026-10-02、オーナー指示）。
- 2026-10-02 にcommit・pushし、GitHub Pagesで公開。
- 確認: 320×568、390×844、430×932、844×390、1366×768のブラウザで、全4画像の読み込み、PC3列/モバイル1列、横はみ出しなし、別タブでの原寸表示を通過。元PNGとWebPは全画素一致。Android版は実機で起動確認済み（オーナー確認）。

画像の参照元は、Unityプロジェクトの `Verification/03-set.png`、`Verification/01-main-menu-five-cards.png`、`Verification/24-mission-list.png`、`Verification/25-sleeve-picker.png`。ゲーム本体のコード・ビルド・配布ファイルは今回変更しない。
