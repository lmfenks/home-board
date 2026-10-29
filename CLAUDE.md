# home-board

iPad mini 2（iOS 12 / Safari 12）に常時表示するダッシュボード。`index.html` 1 ファイルで、GitHub Pages（https://lmfenks.github.io/home-board/）から配信する。

- Safari 12 で動かすため、JS は ES5（var / function、アロー関数・テンプレート文字列・`?.` などは使わない）、CSS は flex の `gap` を使わない。
- **変更を push するときは、必ず `index.html` の `var BUILD = '...'` を新しい値に書き換える。** iPad 側はこの値を比べて新しい版に自動で切り替わるので、書き換え忘れると反映されない。
- 確認は iPad の画面サイズで行う：横 1024×690、縦 768×946（Safari のツールバーあり）。
