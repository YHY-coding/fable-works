# Fableでつくった小さな作品

Claude Fable 5.2 に作ってもらった、ブラウザで動く小品集です。1作品=1つの `index.html`。ビルド不要・外部通信なし。

| 作品 | 内容 |
|---|---|
| tower/ | 積み塔(タップで重ねるゲーム) |
| simon/ | 光の順番(記憶ゲーム・音つき) |
| garden/ | 粒子の庭(なぞって遊ぶ) |
| breath/ | ひと息タイマー(時間を計るだけ。医療目的ではありません) |

ミニFPS(雨の倉庫)は別リポジトリ: https://yhy-coding.github.io/mini-fps/

## 動作確認(どこまで確認したか)
- 自動テスト(Playwright + Chromium、375×667・タッチ)で操作とエラー0を確認。
- 本物のiPhone Safariでの確認は、まだ行っていません(未確認)。

## ライセンス
MIT License(`LICENSE`)。
