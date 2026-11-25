# Nocturne Works の入口ページと、小さな作品

Claude Fable 5.2 に作ってもらった、ブラウザで動く小品集です。1作品=1つの `index.html`。ビルド不要・外部通信なし。

| 作品 | 内容 |
|---|---|
| tower/ | 積み塔(タップで重ねるゲーム) |
| simon/ | 光の順番(記憶ゲーム・音つき) |
| garden/ | 粒子の庭(なぞって遊ぶ) |
| breath/ | ひと息タイマー(時間を計るだけ。医療目的ではありません) |

`index.html` は、公開している制作物(ゲーム・アプリ・LPの見本・Claude Code用プラグイン)への入口です(リンクは 2026-11-25 に開けることを確認)。プラグインの欄には、Claude Code 用プラグイン4つ(publish-guard・pwa-kit・hasshin-kit・decision-card)と、それぞれのスキルへのリンクがあります。

ミニFPS(雨の倉庫)は別リポジトリ: https://yhy-coding.github.io/rain-depot/

## 動作確認(どこまで確認したか)
- 自動テスト(Playwright + Chromium、375×667・タッチ)で操作とエラー0を確認。
- 本物のiPhone Safariでの確認は、まだ行っていません(未確認)。

## ライセンス
MIT License(`LICENSE`)。
