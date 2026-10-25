# Goodesign — 写真1枚から行うAIインテリアデザインとバーチャルステージング

[English](README.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Deutsch](README.de.md) · [Italiano](README.it.md) · [Español](README.es.md)

**Goodesign** ([www.goodesign.io](https://www.goodesign.io)) は、AIによるインテリアデザインとバーチャルステージングのウェブサイトです。部屋の写真を1枚アップロードし、スタイルを選ぶか希望を文章で伝えれば、変更を適用した同じ部屋のレンダリング画像が返ってきます。部屋がまだ存在しないうちから説得力のある見せ方をする必要のある人々のために作られています。空の物件をリスティングするエージェント、リフォームを計画するオーナー、方向性を提案するステージャー、スクロールの手を止める写真が必要な売り手です。

ここにはソースコードはありません。このページは、製品を示し、実際に何をするかを説明し、繰り返し質問される部分 — スタイルライブラリ、タスクページ、料金、対応言語 — を記録するためにあります。

## まずはここから

| | |
|---|---|
| 製品 | [www.goodesign.io](https://www.goodesign.io) |
| スタイルライブラリ（31のスタイル） | [/styles](https://www.goodesign.io/styles) |
| 施工例ギャラリー | [/gallery](https://www.goodesign.io/gallery) |
| 各タスクの機能 | [/features](https://www.goodesign.io/features) |
| プランと料金 | [/pricing](https://www.goodesign.io/pricing) |
| 指示の書き方 | [/how-to-prompt](https://www.goodesign.io/how-to-prompt) |
| ナレッジハブ（132記事） | [/knowledge-hub](https://www.goodesign.io/knowledge-hub) |
| ヘルプセンター | [/help](https://www.goodesign.io/help) |
| お問い合わせ | [hello@goodesign.io](mailto:hello@goodesign.io) |

| ビフォー | アフター |
|---|---|
| ![ビフォー](https://www.goodesign.io/gallery/before/r2-c3.webp) | ![アフター](https://www.goodesign.io/gallery/after/r2-c3.webp) |

*空の部屋の写真1枚から、家具付きの部屋が返ってきます。壁も窓もドアもそのまま、手作業のレタッチはありません。*

## 何ができるか

**部屋のスタイルを作り替える。** 空の部屋や老朽化した部屋を、別の方向性で見せます。ライブラリには31の命名済みスタイルが揃っています — Japandi、Scandinavian、Wabi Sabi、Mid Century、Boho、Industrial、Art Deco、Quiet Luxury、Mediterranean、Korean、Japanese Modern、Modern Chinese、Cream、Natural Wood、Maximalist、そしてそのほか16 — あるいは、自分で書いた指示を伝えることもできます。

**1つだけ変えて、あとはそのまま。** 差がつくのはタスクページです。何でも書き込める「この部屋を想像して」形式の入力欄ではなく、それぞれの作業に専用のページと専用の操作が用意されています：

| 作業 | ページ |
|---|---|
| 空の部屋をステージング | [virtual-staging](https://www.goodesign.io/virtual-staging) |
| 最初に部屋を空にする | [empty-your-space](https://www.goodesign.io/empty-your-space) |
| 家具のある部屋を作り替える | [redesign-furnished-rooms](https://www.goodesign.io/redesign-furnished-rooms) |
| 配置はそのまま、家具を変える | [swap-furniture-objects](https://www.goodesign.io/swap-furniture-objects) |
| 家具はそのまま、仕上げを変える | [furniture-facelift](https://www.goodesign.io/furniture-facelift) |
| 足りない物を追加 | [add-furniture-objects](https://www.goodesign.io/add-furniture-objects) |
| 不要な物を削除 | [object-removal](https://www.goodesign.io/object-removal) |
| 壁を塗り替える | [repaint-wall](https://www.goodesign.io/repaint-wall) |
| 床や表面を変える | [restyle-surfaces](https://www.goodesign.io/restyle-surfaces) |
| 同じ部屋を昼から黄昏時に | [day-to-dusk](https://www.goodesign.io/day-to-dusk) |
| 単調な灰色の空を差し替える | [sky-replacement](https://www.goodesign.io/sky-replacement) |
| 庭を作り替える | [lawn-replacement](https://www.goodesign.io/lawn-replacement) |
| プールを追加 | [add-pool](https://www.goodesign.io/add-pool) |
| 外構の構造物を作り直す | [render-exterior-structures](https://www.goodesign.io/render-exterior-structures) |
| 家全体のリフォームをプレビュー | [interior-home-renovation](https://www.goodesign.io/interior-home-renovation) |
| 季節やイベントの変更 | [seasonal-reset](https://www.goodesign.io/seasonal-reset) · [festive-flip](https://www.goodesign.io/festive-flip) |
| 写真を鮮明にして拡大 | [image-enhancement](https://www.goodesign.io/image-enhancement) · [image-upscale](https://www.goodesign.io/image-upscale) |
| 商品とシーンの写真 | [product-scenes](https://www.goodesign.io/product-scenes) · [merchant-product-visualizer](https://www.goodesign.io/merchant-product-visualizer) |

## 料金

クレジット制です。1クレジットで画像1枚を作成できます。無料アカウントは5クレジットから始まり、カードは不要です。有料プランは月額で、いつでも解約できます。

| プラン | 月額 |
|---|---|
| Free | $0 · 開始時5クレジット |
| Essential | $14 |
| Pro | $29 |
| Advanced | $49 |
| Agency | $99 |

請求は、記録上の販売者（merchant of record）として Creem を通じて行い、PayPal を直接の選択肢として利用できます。最新の金額は常に [/pricing](https://www.goodesign.io/pricing) をご確認ください。

## 対応言語

このサイトは7つのロケールに対応しています。それぞれに同じ240ページ — スタイルライブラリ、タスクページ、ナレッジハブ、法務ページ、比較・ランキングページ — が揃い、`hreflang` の代替指定と `x-default` を備えています。各言語はパスのプレフィックスで切り替わるため、読者はそのまま自分の言語版に到達します。

| ロケール | エントリーポイント |
|---|---|
| English（デフォルト、プレフィックスなし） | [www.goodesign.io](https://www.goodesign.io) |
| 日本語 | [/ja](https://www.goodesign.io/ja) |
| 한국어 | [/ko](https://www.goodesign.io/ko) |
| Deutsch | [/de](https://www.goodesign.io/de) |
| Français | [/fr](https://www.goodesign.io/fr) |
| Español | [/es](https://www.goodesign.io/es) |
| العربية（右から左） | [/ar](https://www.goodesign.io/ar) |

スラグはすべてのロケールで英語のままなので、`/ja/virtual-staging` と `/de/virtual-staging` は2つの言語で同じページを指します。

## 開発者のために、そしてボットのために

- **`llms.txt`** は [www.goodesign.io/llms.txt](https://www.goodesign.io/llms.txt) に公開しています。また、[robots.txt](https://www.goodesign.io/robots.txt) のクロール方針では、主要なAIおよび回答エンジンのユーザエージェントをブロックせず許可しています。
- **構造化データ。** 料金ページには5つのプランと料金を示す `Product`/`Offer` ブロックが組み込まれています。そのため、モデルや検索エンジンはマークアップから数値を推測するのではなく、そのまま読み取れます。
- **技術スタック。** Next.js App Router に React Server Components と Tailwind CSS を組み合わせ、リバースプロキシとCDNの背後でスタンドアロンビルドを運用しています。ロケールごとのコンテンツはCookieの書き換えではなく、静的ルートディレクトリから配信しています。
- **このリポジトリに含まれないもの。** アプリケーションのソース、インフラストラクチャのアドレス、キー、内部的なコストやモデルティアの詳細、そして顧客アカウントに関する一切の事項。ここの文言を流用する際は事前にご確認ください。

## お問い合わせ

製品やこのページへのご質問：[hello@goodesign.io](mailto:hello@goodesign.io)

---

© Goodesign. すべての権利は保留されます。このページの文章とその翻訳は、許可なく複製または再配布することができません。本ページへのリンクはいつでも可能です。
