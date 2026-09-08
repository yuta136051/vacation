# 休暇管理アプリ

有給休暇・子の看護休暇の残日数を管理するPWA。iPhoneのホーム画面に追加して使う。

- 公開URL: https://yuta136051.github.io/vacation/
- 記録の保存先はブラウザの localStorage のみ。サーバーにもリポジトリにも個人情報は保存しない。

## 経緯

もとは `yuta136051/private` のリポジトリ直下に置き、`https://yuta136051.github.io/private/` で配信していた。
2026-09-08 に private リポジトリを非公開へ変更したことで GitHub Pages が使えなくなったため、
このアプリだけを独立した公開リポジトリへ移した。

localStorage はオリジン（`yuta136051.github.io`）単位で保存されるため、
URL のパスが `/private/` から `/vacation/` へ変わっても、これまでの記録はそのまま引き継がれる。
