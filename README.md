# cocoRo脱毛 公式サイト

東大阪・布施エリアの美容脱毛サロン「cocoRo脱毛」のWebサイトです。

**公開URL:** https://sishigami-lab.github.io/cocoro-datsumo-site/

## ファイル構成

| ファイル | 内容 |
| --- | --- |
| `index.html` | トップページ（全セクション） |
| `style.css` | サイト全体のスタイル |
| `privacy.html` | プライバシーポリシー |
| `site-config.js` | LINE・Instagram・地図・電話番号の設定 |
| `news-config.js` / `news.json` | お知らせの設定とデータ |
| `robots.txt` / `sitemap.xml` | 検索エンジン向け設定 |

### 管理用ページ（検索避け設定済み）

| ファイル | 内容 |
| --- | --- |
| `easy-admin.html` | かんたん編集ガイド |
| `update-manual.html` | 更新マニュアル |
| `settings.html` | 設定画面 |
| `photo-editor.html` | 写真の差し替え |
| `news-editor.html` | お知らせの編集 |
| `link-editor.html` | リンクの変更 |

## 更新のしかた

1. ファイルを編集する
2. 変更を反映する:

   ```bash
   git add -A && git commit -m "更新内容を書く" && git push
   ```

3. 1〜2分でサイトに反映されます

## ローカルで確認する

```bash
python3 -m http.server 8000
```

ブラウザで http://localhost:8000 を開いてください。
