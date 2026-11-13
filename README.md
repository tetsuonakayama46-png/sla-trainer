# SLA Trainer（スマホ版・単体PWA）

https://tetsuonakayama46-png.github.io/sla-trainer/

- バックエンド不要。参照音声はブラウザTTS、採点はデモ採点、進捗は端末内（localStorage）に保存
- iPhone: Safariで開く → 共有 → 「ホーム画面に追加」でアプリ化（マイク許可は初回のみ）
- 電車内: イヤホン推奨。録音開始時に環境音を300ms計測し、VAD閾値を自動調整
- 本格版（Supabase保存・Azure採点）は `sla-adhd-system` リポジトリ（PC）側
