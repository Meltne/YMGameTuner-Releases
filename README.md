# YMGameTuner Releases

ゲーム用 PC の Windows・GPU（NVIDIA / Radeon）・メモリ・回線を、元に戻せる形で調整するツール **YMGameTuner** の配布用リポジトリです（ソースコードはここにはありません）。

## インストール

1. [Releases](https://github.com/Meltne/YMGameTuner-Releases/releases/latest) から `YMGameTuner-win-Setup.exe` をダウンロードして実行します。インストールしない場合は `YMGameTuner-win-Portable.zip` を展開して `YMGameTuner.exe` を起動します。
2. 署名していないため、Windows の SmartScreen が出たら「詳細情報」→「実行」を押してください。
3. 設定の変更に管理者権限が要るため、起動のたびに UAC の確認が出ます。
4. 新しいバージョンがあると画面上部に表示されます。「更新して再起動」で更新できます。

## 元に戻す

- 適用の前に復元ポイントを作ります（システム保護が無効なら有効化を確認します）。
- 「履歴と戻し」から、適用した単位でも項目ごとでも元の値に戻せます。
- 標準アプリの削除だけは戻せません。Microsoft Store から入れ直してください。

## 動作環境

- Windows 10 22H2 以降 / Windows 11（64bit）
- NVIDIA GeForce / AMD Radeon の設定項目は、その GPU があるときだけ表示されます
- Home エディションでは、グループポリシーで効く項目は表示されません

困ったときは、「設定」→「診断」→「クリップボードへコピー」の内容を作者に送ってください。
