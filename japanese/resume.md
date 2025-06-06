# 職務経歴書

名前は **李 庭旻** と書いて **イ ジョンミン** と読みます

## 要約

- **フロントエンドエンジニア歴４年以上**
  - React ３年以上、Typescript ３年以上、Next.js ２以上
- **改善意識**が高く、実際に改善を行える**行動力**がある
- 自分が理解したことを、わかりやすく**アウトプット**することが得意
  - 技術記事: https://zenn.dev/luvmini511 (いいね5,000以上)
  - 社内勉強会: https://speakerdeck.com/gardensky511
- **日本語**流暢、**英語**もそこそこできる
  - 韓国語ネイティブ、日本語は JLPT N1 所有、英語は TOEIC 880点
- **デザイン**に対する理解があり、デザイナーと協業しやすい
  - デザイン専攻で Bachelor 学位保有

## 職務経歴

### ◼︎ パーソルキャリア株式会社 (2024.03 - 現在)

#### ◻︎ doda サイト開発PJ (2024.03 - 現在)
Java（JSP）と jQuery で構築された古い doda のウェブフロントエンドをページごとに、もしくは部分的に React に置き換えるPJ

- 技術スタック: **React、Typescript、Next.js（page router）、Redux Toolkit、CSS Modules** など
- 役割: リードフロントエンドエンジニア
- 成果
  - 開発プロセス改善
    - Reactコードと古いサイトのリポジトリが別々で、手動でReact資材をコピペしなければならない課題に対し、git のサブモジュール機能と GitHub Actions を活用して React 資材のビルド・コピペを自動化。その結果、開発体験の向上と資材の二重管理問題を解決
  - エンジニア教育・育成
    -  ジュニアフロントエンドエンジニアの育成課題に対し、ペアプログラミングやこまめなコードレビューを実施。技術力の向上に加え、バグを事前に発見することで、リリース後のクリティカルなバグ防止
  - 開発プロセス改善
    - 従来はCIがなく、型エラーや単体テストが失敗したままでもマージされる状況を改善するため、CIの導入を提案・実施。その結果、開発プロセスの安全性が向上
  - リバースエンジニアリングと仕様書作成
    - 仕様書やドキュメントが全くない状況で、古いサイトのコードを調査し、仕様を洗い出して仕様書を作成

#### ◻︎ 自作 UI ライブラリーPJ (2024.04 - 現在)
ライブラリー化された doda のデザインシステムの運用・補修

- 技術スタック: **React、Typescript、CSS Modules** など
- 役割: リードフロントエンドエンジニア
- 成果 
  - リリース作業とリリースノート作成自動化
    - リリース作業とリリースノート作成が手作業で時間がかかる課題に対し、リリースプロセス全体を GitHub Actions で自動化。その結果、リリース作業の所要時間が約40分以上から3分以下に短縮 
  - UIライブラリーのドキュメント整備
    - ドキュメントにUIパターンの記載や props の説明がなく、利用者にとって情報が不十分だった課題に対し、すべてのUIコンポーネントの全パターンを記載し、propsの説明を追加。その結果、わかりやすく実用的なドキュメントを構築
  - バージョニングルール整備
    - 一貫性のないバージョニングが行われていた課題に対し、バージョニングルールを策定・ドキュメント化を実施。その結果、Semantic Versioning を実現し、運用の安定性と信頼性を向上

#### ◻︎ その他
私が FE に関するテーマを決め、約20-30分程度の発表資料を作成、参加者に説明する勉強会を主催中 ([過去資料はこちら](https://speakerdeck.com/gardensky511))

最大参加人数約26人ほどで、平均的に18人ほど参加してくれてるし、毎回好評いただいてる

### ◼︎ フリーランス (2023.01 - 現在)

#### ◻︎ 株式会社良品計画 (2023.05 - 現在)
- 2023.05 - 2024.02 フルタイム
- 2024.05 - 現在 副業

##### ○ 店舗スタッフ向け業務システムリプレースPJ (2024.06 - 現在)
業務システムを内製化のためにフロントエンドアプリケーションを新規開発、運用

- 技術スタック: **React、Typescript、Next.js（app router）、zustand、Storybook、OpenSearch、Prisma、CSS Modules** など
- 役割: フロントエンドエンジニア
- 成果
  - 初期表示の遅いという課題に対し、複数のデータフェッチを Suspense を用いて HTML 作成とデータフェッチを並行して行い、初期表示速度を大幅に改善
  - アプリケーションが設計方針通りに実装されていなかったため、全体をリファクタリングし設計方針に沿った構造に改善。また、各レイヤーの責務を明確化した設計ドキュメントを作成・共有することでチームの設計理解促進に貢献

##### ○ オンラインストアリプレースPJ (2023.05 - 2024.06)
SPA の WEB サイトの性能・ SEO 改善のためにフロントエンドアプリケーションを新規開発、運用

- 技術スタック: **React、Typescript、Next.js（app router）、Redux Toolkit、Storybook、GraphQL、CSS Modules** など
- 役割: フロントエンドエンジニア
- 成果
  - 開発プロセス改善
    - 毎週人が手動でパッケージのアップデート状況を調べてバージョンアップPRを作成する課題に対し、[Renovate](https://github.com/renovatebot/renovate) を導入してPR作成を自動化。その結果、グリーンキープ作業の負担を大幅に軽減
    - 新しいコンポーネント作成時に手動で複数ファイルを作成する手間や作成方法のばらつきがある課題に対し、[scaffdog](https://scaff.dog/) を導入してコンポーネントの雛形を自動生成。その結果、開発の効率化と雛形の統一実現

#### ◻︎ 株式会社BuySell Technologies (2023.01 - 2023.06)

買取店舗で使用する業務システムのWEBフロントエンド開発

- 技術スタック: **React、 Next.js（page router）、 Typescript、 GraphQL、 React-hook-form、 zod、Material UI** など
- 役割: フロントエンドエンジニア
- 成果
  - E2Eテストケース実行時間短縮
    - MagicPod（E2Eテストツール）のテストケースでチェックボックスとラジオボタンがあるページの実行時間が長い課題に対し、スタイリングを見直すことで改善を実施。その結果、テスト実行時間を30秒以上から10秒以下に短縮
  - 監視体験向上
    - Sentry で異なる issue が自動でグルーピングされ、監視が難しい課題に対し、GraphQLオペレーションごとに issue をグルーピングする設定を実装。その結果、異なるオペレーション間の誤ったグルーピングを防ぎ、監視体験を改善（[詳しくはこちら](https://zenn.dev/luvmini511/articles/fbc1ac22b360a7)）


### ◼︎ ourly株式会社 (2022.08 - 2022.12)

電子社内報・社員一覧システムのWEBフロントエンド開発
- 技術スタック: **React、 Next.js（page router）、 Typescript、 ReduxToolkit** など
- 役割: フロントエンドエンジニア

### ◼︎ BASE株式会社 (2022.05 - 2022.07)

BASEショップのWEBフロントエンド開発

- 技術スタック: **Vue.js、 Typescript** など
- 役割: フロントエンドエンジニア

### ◼︎ 株式会社ビットエー (2020.04 - 2022.03)

#### ◻︎ 大手総合人材サービス会社 (2021.05 - 2022.03)

大規模転職支援モバイルアプリケーションのフロントエンド開発
- 技術スタック: **ReactNative、 React、 Typescript、 ReduxToolkit** など
- 役割: フロントエンドエンジニア

#### ◻︎ 大手電機メーカー企業 (2020.11 - 2021.04)

PC対応のみだったWEBの社内ポータルサイトを CSS を全体的に改修してレスポンシブにリニュアル

- 技術スタック: **Nunjucks、 PostCSS、 Vanilla Javascript** など
- 役割: フロントエンドエンジニア

## 学歴

- 2024.03 - 現在 | [The Cyber University of Korea](https://eng.cuk.edu/index.do), Div. of **Computer Engineering**
- 2014.03 - 2020.02 | [Hongik University](https://www.hongik.ac.kr/en/index.do), Div. of **Visual Communication Design**
