概要
====
[コスモリウム]の展示で、[Image Loading]などのデータ外部取得で利用するGitHub Pages用リポジトリです。

[コスモリウム]: https://virtualspaceprogram.org/information/2022-10-14-COSMORIUMannounce "『VR宇宙博物館 コスモリウム』は、「人はなぜ宇宙に惹かれるのか？」を基本テーマに、VRならではの展示を経てその自らの答えを探すワールドです。"
[Image Loading]: https://creators.vrchat.com/worlds/udon/image-loading/ "Image Loading allows you to download images from the internet and use them as textures in your materials."

リポジトリの公開状態について
============================
GitHub Pagesを利用するため、**このリポジトリはpublicになっており、誰でも閲覧できます。**

現在の対象コンテンツ
====================
スーパーカミオカンデ
------------------------------
[Super-Kamiokande Realtime Monitor]から取得した現在のスーパーカミオカンデの観測データをpng形式で返します。

Image Loading用です。

URL: https://virtualspaceprogram.github.io/cosmorium-daily-images/super-kamiokande.png

[Super-Kamiokande Realtime Monitor]: https://www-sk.icrr.u-tokyo.ac.jp/realtimemonitor/

### 更新頻度
[毎日JST12:04ごろに更新。 (1日に1回更新)](./.github/workflows/build-and-deploy.yaml#L2-L4)

### 実行ログ
https://github.com/VirtualSpaceProgram/cosmorium-daily-images/actions/workflows/build-and-deploy.yaml

### 取得対象の衛星の変更
YAML形式の配列で記述された [source.yaml] を書き替えます。

※masterブランチへのpush権限が必要。

[source.yaml]: ./source.yaml
