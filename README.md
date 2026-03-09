# VRC-Photos-Pro
VRChatでの思い出を、もっと手軽に、もっと鮮明に。

VRC-Photos-Proは、VRChatで撮影した写真の管理・共有を劇的に効率化するデスクトップユーティリティです。
Tauri (Rust) と React を使用して構築されており、軽量かつ高速に動作します。

## 主な機能
### 自動写真同期: 
VRChatの写真フォルダを監視し、新しい写真をリアルタイムで取り込みます。

### メタデータ解析: 
写真に埋め込まれたワールド名や撮影日時などのメタデータを自動で抽出。

### 簡単SNS投稿: 
アプリから直接、管理した写真をSNSにアップロード可能。(XAPIを使用しており、freeプランで利用しているため、制限がかかることがよくあるので、サブ機能くらいで考えておいてください！)

### 自動アップデート: 
常に最新の機能とセキュリティを提供します（Tauri自作アップデーター実装済み）。

### ワールド情報の記録: 
どこで撮った写真かを忘れることはもうありません。

### インストール方法
Releases ページにアクセスします。
VRC-Photos-Pro_0.2.0_x64_en-US.msi をダウンロードして実行します。
インストール完了後、デスクトップのショートカットから起動してください。

### 技術スタック
Frontend: React / TypeScript / Vite
Backend: Rust (Tauri)
Sidecar: get_meta (メタデータ抽出用バイナリ)
Workflow: Vibe-coding (Cursor / Gemini)

### 開発者について
個人でアプリケーションやWebサイトを作っています！

Twitter: https://x.com/NtxMp7Nyh79DpTE

BOOTH: https://unyaunya00.booth.pm/
