# mail-automation-assets

Google Chat アプリのアバター画像を公開するためだけのリポジトリ。

| ファイル | 用途 | URL |
|---|---|---|
| `chat-bot-avatar.png` | Chat アプリ「メルマガエラーレポート」のアバター（1024×1024） | https://early-bird-agent.github.io/mail-automation-assets/chat-bot-avatar.png |

Chat アプリのアバターは HTTPS の URL でしか指定できず、ファイルをアップロードする欄が無い。
公開 GCS バケットは組織ポリシー（`allowedPolicyMemberDomains`）で作れないため、GitHub Pages に置いている。
転送量が GitHub 負担で、こちらに請求先が紐づかないのが選定理由。

生成元は非公開リポジトリ `early-bird-agent/mail-automation` の
`poc/tour28_エラーレポート取得/assets/`。差し替えるときは両方を更新する。
