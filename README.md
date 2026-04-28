# Event Site

イベント案内ページを再公開しやすいようにまとめた静的サイト出力先です。

## 何が入るか

- `index.html` - イベント一覧ハブ
- `zazen/index.html` - 坐禅会ページ
- `terakoya/index.html` - 夜の寺子屋ページ
- `online-terakoya/index.html` - オンライン寺子屋ページ
- `online-terakoya/guide.html` - オンライン寺子屋の案内スライド
- `_event-hub.html` - 4ページを一覧できるハブ
- `hub/index.html` - ブラウザ公開用のイベント一覧ハブ

## 更新方法

```bash
python3 scripts/build_event_site.py
```

新しい公開URLが決まったら、旧Netlify URLの参照をまとめて置き換えられます。

```bash
python3 scripts/replace_event_base_url.py https://new-domain.example.com
```

## 公開の考え方

- このフォルダはそのまま静的ホスティングに置けます
- 旧Netlify URL `https://vocal-heliotrope-981246.netlify.app` へのリンクは、出力時に相対パスへ置き換えます
- Google Forms や Zoom など外部サービスのURLは、そのまま残します
- 自然の体験会は独立した正規URL `https://pagedrop.dev/s/98LnAcgH/` へ直接リンクします

## 安全メモ

- この作業では公開先アカウントの認証情報は扱いません
- APIキーや個人情報をここへ追加しないでください
