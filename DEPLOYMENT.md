# Event Site Deployment

最終公開日: 2026-04-26

## 復旧済みURL

- イベントハブ: https://pagedrop.dev/s/JLUJVpNv/
- 自然の体験会: https://pagedrop.dev/s/98LnAcgH/
- 坐禅会: https://pagedrop.dev/s/JLUJVpNv/zazen/
- 夜の寺子屋: https://pagedrop.dev/s/JLUJVpNv/terakoya/
- 魂の羅針盤ワークショップ: https://pagedrop.dev/s/JLUJVpNv/compass/
- オンライン寺子屋: https://pagedrop.dev/s/JLUJVpNv/online-terakoya/
- サムネイル置き場: https://pagedrop.dev/s/JLUJVpNv/thumbnails/

## メモ

- PageDrop API で zip デプロイ
- siteId: JLUJVpNv
- files: index.html, _event-hub.html, online-terakoya/index.html, online-terakoya/guide.html, terakoya/index.html, terakoya/photos/doc-photo-1.png, terakoya/photos/doc-photo-2.png, kaoru-juku/index.html, site-assets/home/town-night.jpg, site-assets/home/river-light.jpg, site-assets/home/lecture-room.jpg, site-assets/home/goma-fire.jpg, site-assets/home/IMG_5307.jpg, site-assets/home/meditation-window.jpg, site-assets/home/IMG_7362.jpg, notes/index.html, notes/2026-04-25_人間交差点_「コンテンツより、あなたがやるから行く」/index.html, notes/2026-04-08_自我くん観察日記_しょんぼりしてたらジガ君が急に正論マンになってた件/index.html, notes/2026-04-26_人間交差点_ひみにチームを渡した日/index.html, notes/2026-04-22_人間交差点_AIが進化するほど何のために使うかが問われる/index.html, notes/2026-04-21_人間交差点_息子に渡せたのはZIPじゃなかった/index.html, notes/2026-04-23_人間交差点_幸せホルモン全部入りの日/index.html, notes/2026-04-17_自我くん観察日記_AIが進化して一番はしゃいでるのは自我くんかもしれない/index.html, notes/2026-04-25_人間交差点_AIと会議した1日言葉を自分のものに戻すまで/index.html, notes/2026-04-17_人間交差点_整えるとは本物だけを残すことだ/index.html, notes/2026-04-18_人間交差点_感謝したら受け取りすぎてる件/index.html, notes/categories/index.html, notes/categories/terakoya/index.html, notes/categories/true-self/index.html, notes/categories/chuyo-thinking/index.html, notes/categories/leaders/index.html, notes/categories/tenkawa/index.html, profile/index.html, activities/index.html, compass/index.html, zazen/index.html, zazen/images/takigyo.jpg, zazen/images/hakui-solo.jpg, zazen/images/tenkawa-river.jpg, zazen/images/zazen-group.jpg, zazen/images/takigyo-group.jpg, zazen/images/tenkawa-shrine.jpg, zazen/images/zazen-sitting.jpg, zazen/images/tenkawa-nature.jpg, zazen/images/zazen-hakui.jpg, thought/index.html, hub/index.html, services/index.html, coaching-premium/index.html, thumbnails/2026-04-17-jigakun-ai.png, thumbnails/index.html, thumbnails/jiga-ai-hataraku-jidai.png, thumbnails/jiga-ai-hataraku-jidai.svg, thumbnails/2026-04-17-jigakun-ai.svg, thumbnails/kanjo-wa-jijitsu-ja-nai.svg, thumbnails/2026-04-17-setoeru.svg, thumbnails/2026-04-25-ai-kaigi.png, thumbnails/2026-04-17-setoeru.png, thumbnails/kanjo-wa-jijitsu-ja-nai.png
- 既存文面の差し替えは `python3 scripts/replace_event_base_url.py <base_url>` を使う
- note 用サムネイルを増やしたらこのスクリプトで再公開する
