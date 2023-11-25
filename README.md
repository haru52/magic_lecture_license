# Magic Lecture License

[![Test](https://github.com/haru52/magic_lecture_license/actions/workflows/test.yml/badge.svg)](https://github.com/haru52/magic_lecture_license/actions/workflows/test.yml)
[![Release](https://github.com/haru52/magic_lecture_license/actions/workflows/release.yml/badge.svg)](https://github.com/haru52/magic_lecture_license/actions/workflows/release.yml)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg)](https://haru52.com/magic_lecture_license/CODE_OF_CONDUCT.html)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](https://commitizen.github.io/cz-cli/)
[![semantic-release: conventionalcommits](https://img.shields.io/badge/semantic--release-conventionalcommits-e10079?logo=semantic-release)](https://github.com/semantic-release/semantic-release)

## 概要

Magic Lecture License は、マジック（手品）を解説する書籍やレクチャービデオなどに付与するライセンスです。このライセンスは、レクチャーの購入者が、レクチャー内で解説されている手順や技法などに対して有する権利（演技権など）と購入者が負う義務（タネ明かししないことなど）を規定します。

[Magic Lecture License ライセンス本文](https://haru52.com/magic_lecture_license/versions/)

## 利用方法

1. 利用したいライセンスのバージョンを確認してください。原則、最新バージョンの利用をお勧めします
   - [最新バージョン](https://github.com/haru52/magic_lecture_license/releases/latest)
   - [バージョン一覧](https://github.com/haru52/magic_lecture_license/releases)

### 利用方法 A

<!-- textlint-disable prh -->
1. 当ライセンスを適用したい製品内や Web サイトなどに以下のテキストを貼り付けてください
2. 貼り付けたテキスト内の `<>` と `1.0.0` を適切な文言に置き換えてください
<!-- textlint-enable prh -->

```txt
<本製品 | 本書 | 当映像 | 当店 | 当 Web サイト | 当レクチャー | など>に含まれるすべてのコンテンツは、次の Magic Lecture License v1.0.0 の下でのみ利用可能です。

https://haru52.com/magic_lecture_license/versions/v1.0.0.html
```

- メリット：製品内などに貼り付ける文章量が少なく済み、手軽
- デメリット：将来的にリンク切れになる可能性がある

### 利用方法 B

1. <https://haru52.com/magic_lecture_license/versions/v1.0.0.md> の `1.0.0` を利用したいライセンスのバージョンに置き換えてください
2. 1 で生成した URL にアクセスしてください
3. リンク先のライセンス本文をすべてコピーしてください
4. コピーしたテキストを、ライセンスを適用したい製品内や Web サイトなどに貼り付けてください

- メリット：リンク切れのリスクなし
- デメリット：製品内などに貼り付ける文章量が多くなってしまう

### 利用方法 C

1. <https://haru52.com/magic_lecture_license/versions/v1.0.0.md> の `1.0.0` を利用したいライセンスのバージョンに置き換えてください
2. 1 で生成した URL のリンク先ページ（`v1.0.0.md` など）をファイルとしてダウンロードしてください
3. ダウンロードした `v1.0.0.md` ファイルを `LICENSE` などのファイル名に変更してください
4. ライセンスを適用したい製品内などに `LICENSE` ファイルを同梱してください

- メリット：リンク切れのリスクなし
- デメリット
  - デジタルデータ製品のような形式以外には適用するのが難しい
  - 製品を構成するファイル数が増えてしまう

## 詳細

現在、マジックの書籍やレクチャービデオなどで解説されている手順や技法などを、それらの購入者がどのように利用してよいかを定める規定は大きく 2 つのケースに分かれていると思います。1 つは何も明記されていないケースで、もう 1 つは演技権などが厳しく制約されているケースです。

前者のように明確な規定がない場合、レクチャーで解説されている手順や技法などをどのように利用する（手順を演じる、技法を発展させるなど）かは購入者の裁量に任されてしまいます。その結果、ある購入者がレクチャー内容を不特定多数に向けてタネ明かしするなどして、マジックの秘密が守られなくなってしまうリスクが考えられます。一方、他の購入者はレクチャー内容をどこまで自由に利用してよいのか分からず、レクチャー内容の利用を控えてしまうかもしれません。この場合、新たなアイデアや手順などが生まれる可能性が阻害されることになります。

後者のように制約の厳しい規定がある場合、購入者によるタネ明かしなどを防ぐ効果が期待できます。その一方でこのような規定の下では、購入者が自由にマジックの演技を作り上げたり、他のマジシャンと活発に知識をやりとりしたりすることを妨げてしまう可能性があります。（レクチャー内容の利用範囲については原案者／著作者の意向を優先するのが一般的な価値観だと思われるため、このような厳しい規定が存在すること自体は基本的には問題ないと考えています）

<!-- textlint-disable japanese/sentence-length -->
以上より、現在のマジックの書籍やレクチャービデオなどの販売形態には、「1. マジックの秘密を守ること」、「2. マジシャン間で活発に知識を伝達できるようにすること」、「3. マジシャンが自由にマジックを演じられるようにすること」という 3 つの命題をうまく両立できていないという課題があるといえます。
<!-- textlint-disable japanese/sentence-length -->

そこで、この課題を解決するために Magic Lecture License を作りました。これは、マジックの書籍などに付帯させ、レクチャー内容に対して購入者が有する権利と購入者が負う義務を明記した文書です。特徴として、タネ明かしなどを禁じてマジックの秘密を守りつつ、購入者がレクチャー手順を演じることや、レクチャー技法を新しい技法に発展させることなどは極力制限しないようにしている点があります。

Magic Lecture License の利用により、マジックの秘密を守りつつ、マジシャンがより自由に活動できるようになることを期待しています。

### 問い合わせ

- [New Issue · haru52/magic_lecture_license](https://github.com/haru52/magic_lecture_license/issues/new/choose)
- [haru 連絡フォーム](https://docs.google.com/forms/d/e/1FAIpQLSddUF5PDhRpYPZ8VGVZClTBQCo-SQb4QzszOZanmWjUnH_stw/viewform?usp=sf_link)

### リンク

- [Changelog](docs/CHANGELOG.md)
- [コントリビューター行動規範](docs/CODE_OF_CONDUCT.md)
- [セキュリティポリシー](docs/SECURITY.md)
- [GitHub リポジトリ](https://github.com/haru52/magic_lecture_license)

## バージョニングポリシー

[セマンティック バージョニング 2.0.0](https://semver.org/lang/ja/spec/v2.0.0.html)

## ライセンス

- [CC0-1.0](LICENSE)（[日本語](https://creativecommons.org/publicdomain/zero/1.0/legalcode.ja)）
- Magic Lecture License という当ライセンス文書自体を利用・改変などする場合に適用されるライセンスが CC0 です
- CC0 は原則として利用者にいかなる制限も課さないため、Magic Lecture License の改変利用などは自由です

## コントリビューション

[コントリビューティングガイドライン](https://haru52.com/magic_lecture_license/docs/CONTRIBUTING.html)

## ドキュメント

[Magic Lecture License \| magic_lecture_license](https://haru52.com/magic_lecture_license/)

## 作者

[haru](https://haru52.com/)
