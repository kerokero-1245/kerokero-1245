# kerokero-1245

個人開発の Web アプリとモバイルアプリを置いています。フロントエンドもサーバーサイドも経験があります。再利用性を考えて実装し、業務にコミットしていきたいと考えています。そういう職場で働きたいです。

## つくったもの

| 作品 | 内容 | 技術 | 見どころ | デモ |
|---|---|---|---|---|
| [ぴよぴよランド](https://github.com/kerokero-1245/kerokero-1245.github.io) | 4〜5 歳の姪のための知育アプリ 3 本（めいろ・さんすう・ことば）と、その入口になるランチャー | Expo (React Native Web) / TypeScript | 3 本の共通部品・声・BGM を piyo-assets に切り出し、CI で検査して Pages へ自動公開 | https://kerokero-1245.github.io/ |
| [karada-log](https://github.com/kerokero-1245/karada-log) | 食事を記録して目標と比べる、個人用の減量管理 PWA | React / TypeScript / Vite / IndexedDB | IndexedDB に保存、Markdown で書き出し。テスト 56 ファイル、CodeQL と Dependabot | https://kerokero-1245.github.io/karada-log/ |
| [MAISON NOIR](https://github.com/kerokero-1245/maison-noir) | ダークテーマの EC サイト。カートから Stripe 決済、注文履歴まで | Next.js / TypeScript / Tailwind CSS / Stripe | Webhook と成功ページが同じ確定処理を通り、注文は 1 件。価格はサーバが決め、CI は E2E も検査 | なし |
| [これ、大丈夫？](https://github.com/kerokero-1245/kore-daijobu) | 高齢の親向けの詐欺相談アプリ | Expo / React Native / TypeScript | 匿名サインインと RLS で親子をペアリング、Realtime で相談と返信が往復 | https://kerokero-1245.github.io/kore-daijobu/ （Web 版・偽バックエンド） |
