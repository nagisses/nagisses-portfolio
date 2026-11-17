# nagisses Works

nagisses の作品集サイト。HTML 1枚と画像だけで動く静的サイトです（ビルド不要）。

- `index.html` … ページ本体。アニメーションは GSAP 3.12.5・ScrollTrigger・Lenis 1.1.14 をページ内に埋め込んでいます
- `img/` … 作品のスクリーンショット
- `vercel.json` … Vercel の設定（画像を長くキャッシュ）

## 公開
Vercel にこのリポジトリをつなぐと、`main` に push するたびに自動で公開されます。
Framework Preset は「Other」、Build Command と Output Directory は空のままで動きます。

## 作品を足すとき
`index.html` の `<!-- 04 LEO -->` のような作品ブロックをまねて追加し、画像を `img/` に置きます。
