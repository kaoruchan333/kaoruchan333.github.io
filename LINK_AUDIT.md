# Event Link Audit

調査日: 2026-04-14

## 確認結果

- `https://vocal-heliotrope-981246.netlify.app` は 404
- `https://vocal-heliotrope-981246.netlify.app/zazen/` は 404
- `https://vocal-heliotrope-981246.netlify.app/terakoya/` は 404
- Google Forms の埋め込みURLは到達可能

## ローカル原本

- `resources/nature-events/イベント案内_4月28日.html`
- `resources/zazen-event/index.html`
- `resources/terakoya-event/index.html`
- `resources/online-terakoya/index.html`
- `resources/online-terakoya/guide.html`

## 旧URLの参照が残っている場所

- `scripts/morning_brief.py`
- `content/drafts/2026-04-11_*.md`
- `resources/online-terakoya/index.html`
- `resources/nature-events/URL一覧.md`

## 次にやること

1. `python3 scripts/build_event_site.py` を実行する
2. `event-site/` を新しい静的ホスティング先へ配置する
3. 新URLが決まったら、旧Netlify URLの参照を一括置換する
