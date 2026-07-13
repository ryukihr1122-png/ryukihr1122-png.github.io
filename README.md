# ryukihr1122-png.github.io

RYUKI HARA の個人開発アプリ共通デベロッパサイト。

- `index.html` — アプリ一覧（トップ）
- `privacy.html` — プライバシーポリシー（全アプリ共通）
- `app-ads.txt` — AdMob 認証用（発行者ID単位なので全アプリ共通で使い回し）

## 新しいアプリを追加するとき
1. `index.html` の「配信中のアプリ」にカードを1枚追記
2. App Store Connect で、そのアプリのデベロッパWebサイトURLをこのサイトに設定
3. app-ads.txt は変更不要（同じ発行者IDなら共通）
