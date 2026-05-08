# プライバシーポリシー / Privacy Policy

**Page Detective**  
最終更新日：2026年5月8日

---

## 日本語

### 収集する情報

Page Detective は、ユーザーがチェック実行ボタンを押したときに限り、現在開いている Web ページの以下の情報を読み取ります。

- ページの URL・タイトル
- ページ内の画像 URL・alt 属性
- ページ内のリンク URL・テキスト
- Meta タグの内容（title、description、viewport、OGP など）
- 見出し要素（h1〜h6）のテキスト
- ページ読み込み速度（Navigation Timing API の計測値）
- JSON-LD 構造化データの内容

### 情報の取り扱い

- 読み取った情報はすべて **お使いのデバイス上のみ** で処理します
- チェック結果および通知済みバージョン情報は Chrome の `chrome.storage.local`（端末ローカル）に保存されます
- 開発者または第三者のサーバーへデータを送信することは **一切ありません**
- HTTP ステータスチェック機能では、ページ内のリンク先 URL へ直接リクエストを送信します。これはリンク先サーバーのステータスコードを確認する目的のみであり、個人情報は含まれません

### 外部サービスの利用

本拡張機能は外部のアナリティクス・広告・トラッキングサービスを一切使用しません。

### 権限の使用目的

| 権限 | 使用目的 |
| ------ | ------ |
| `activeTab` | チェック実行時に現在のタブの情報を取得するため |
| `scripting` | ページの解析スクリプトをタブ上で実行するため |
| `storage` | チェック結果を端末にローカル保存するため |
| `sidePanel` | サイドパネルで結果を表示するため |
| `tabs` | アップデート時に更新内容ページを新しいタブで開くため |
| `host_permissions: <all_urls>` | HTTP ステータスチェック時にページ内リンク先への fetch を行うため |

### お問い合わせ

プライバシーに関するご質問は、GitHub リポジトリの Issues よりご連絡ください。

---

## English

### Information We Collect

Page Detective reads the following information from the currently active web page only when the user initiates a check:

- Page URL and title
- Image URLs and alt attributes
- Link URLs and text
- Meta tag content (title, description, viewport, OGP, etc.)
- Heading elements (h1–h6) text
- Page load performance metrics (via Navigation Timing API)
- JSON-LD structured data

### How We Handle Information

- All data is processed **locally on your device only**
- Check results and the last-notified version string are stored in Chrome's `chrome.storage.local` (device-local storage)
- **No data is ever transmitted** to the developer's servers or any third-party servers
- The HTTP status check feature sends requests directly to the URLs found on the page for the sole purpose of verifying their HTTP status codes. No personal information is included in these requests

### Third-Party Services

This extension does not use any external analytics, advertising, or tracking services.

### Permission Usage

| Permission | Purpose |
| ------ | ------ |
| `activeTab` | To read the current tab's content when a check is initiated |
| `scripting` | To inject and run the analysis script in the active tab |
| `storage` | To save check results locally on the device |
| `sidePanel` | To display results in the side panel |
| `tabs` | To open the update notes page in a new tab after a major or minor update |
| `host_permissions: <all_urls>` | To fetch link URLs for HTTP status checking |

### Contact

For privacy-related inquiries, please open an issue on the GitHub repository.

---

Copyright © togetoge. All rights reserved.
