# Microsoft BUILD 2025 基調講演 Day 2 - テクノロジーの深堀り

Microsoft BUILD 2025の2日目は、初日に発表された技術の詳細と、さらなる新機能の紹介に焦点が当てられました。本記事では、「Unpacking the tech」セッションと「Scott and Mark Learn to...LIVE」セッションの主要ポイントを紹介します。

![Microsoft BUILD 2025 Day 2](https://blog.azure.moe/wp-content/uploads/2025/05/screenshot_2025_05_21-4.png)

## Unpacking the tech セッション

「Unpacking the tech」セッションでは、Microsoftのエンジニアリングリーダーが初日に発表された技術の詳細に踏み込み、開発者がこれらの技術をどのように活用できるかを解説しました。

### Azure AI Foundry 詳細

Azure AI Foundryは、AIアプリケーションとエージェント開発のためのプラットフォームとして発表されました。Day 2では、その詳細な機能と実装方法が紹介されました。

主な機能：
- AIアプリケーション開発のためのエンドツーエンドライフサイクル管理
- 複数のAIモデルを統合したエージェント作成機能
- セキュリティとコンプライアンスのためのガバナンス機能

![Azure AI Foundry](https://azure.microsoft.com/en-us/blog/wp-content/uploads/2025/05/1042849_MS_Azure_Build-2025_BlogHeader-1_1260x708.webp)

> 「Azure AI Foundryは、AIモデル、ツール、インフラを統合し、エンドツーエンドのAIアプリケーションライフサイクルを実現します。これにより、開発者はAIエージェントの構築と管理に集中できます」

出典: [Azure AI Foundry: Your AI App and agent factory | Microsoft Azure Blog](https://azure.microsoft.com/en-us/blog/azure-ai-foundry-your-ai-app-and-agent-factory/?ocid=Build_FY25+X+P+100007898032300+051925)

### Azure AI Foundry Local

ローカル環境でのAIモデル実行を可能にする「Azure AI Foundry Local」についても詳しい解説がありました。

主な特徴：
- Windows/macOS上でのAIモデルローカル実行
- オフライン環境での開発サポート
- パフォーマンス最適化機能

![Azure AI Foundry Local](https://www.publickey1.jp/2025/windows-ai-foundry02.png)

出典: [［速報］マイクロソフト、AIモデルをWindows/macOSローカルで実行可能にする「Azure AI Foundry Local」発表 － Publickey](https://www.publickey1.jp/blog/25/aiwindowsmacosazure_ai_foundry_local.html)

### Microsoft Fabric の拡張

データ分析プラットフォーム「Microsoft Fabric」のAIエージェント統合と新機能が発表されました。

主な機能：
- データ統合の強化
- AIエージェントによる分析の自動化
- 高度なデータ可視化機能

![Microsoft Fabric](https://japan.zdnet.com/storage/2025/05/20/75a7e3b9a47d8c81d855d243664ac01f/microsoft-2025-digital-twin-builder-graphic.jpg)

出典: [マイクロソフト、分析プラットフォーム「Fabric」のデータ統合やAIエージェントを拡充 - ZDNET Japan](https://japan.zdnet.com/article/35233195/)

## Scott and Mark Learn to...LIVE

人気セッション「Scott and Mark Learn to...LIVE」では、Scott HanselmanとMark Russinovichが最新技術をライブデモで紹介しました。

### 新しいWindowsコマンドラインエディター「Edit」

Microsoft Windows向けの新しいコマンドラインテキストエディター「Edit」が発表されました。このエディターは、Vimよりも学習曲線が緩やかで、初心者にも使いやすいことを特徴としています。

![Windows Edit](https://asset.watch.impress.co.jp/img/wf/docs/2015/418/image1.png)

> 「多くの開発者がVimの急峻な学習曲線に苦労しています。私たちは、簡単に使い始められるが強力な機能を備えたエディターを開発しました」

出典: [「Vim」はちょっと……MicrosoftがWindows標準CLIテキストエディター「Edit」を発表 - 窓の杜](https://forest.watch.impress.co.jp/docs/news/2015418.html)

### エクスプローラーのGit統合

WindowsエクスプローラーにGitサポートが統合されることが発表されました。これにより、エクスプローラー上で直接Gitリポジトリの操作が可能になります。

主な機能：
- ブランチ切り替え
- コミット履歴の閲覧
- 変更のステージング

![Explorer Git Integration](https://asset.watch.impress.co.jp/img/wf/docs/2015/419/image2.png)

出典: [「エクスプローラー」の「Git」統合などが実現へ ～Microsoftが開発者向け新機能 - 窓の杜](https://forest.watch.impress.co.jp/docs/news/2015419.html)

### C#の最新機能

「What's Next in C#」セッションでは、C#言語の最新機能と次期バージョンの計画が発表されました。

主な新機能：
- パターンマッチングの拡張
- 高度なジェネリクスサポート
- パフォーマンス最適化

> 「C#は進化を続け、開発者の生産性と表現力を向上させながらも、パフォーマンスと安全性を確保します」

出典: [What's Next in C#](https://build.microsoft.com/en-US/sessions/BRK114)

## NLWeb の発表

マイクロソフトは自然言語からウェブアプリケーションを生成する「NLWeb」を発表しました。これにより、テキスト説明だけでウェブアプリを作成することが可能になります。

![NLWeb](https://res.cloudinary.com/zenn/image/fetch/s--iIoUL_h2--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_1200/https://storage.googleapis.com/zenn-user-upload/deployed-images/3c79819678a5bd404cb21bc3.png%3Fsha%3D7ae72a1cd7534985528d8054b2c7d9405d4592ae)

主な特徴：
- 自然言語からウェブアプリ自動生成
- コンポーネントベースのアーキテクチャ
- React/TypeScriptベースのコード出力

出典: [Microsoftが新発表した「NLWeb」とは何か？](https://zenn.dev/galirage/articles/what-is-nlweb)

## xAI モデルの追加

MicrosoftはAIマーケットプレイスにイーロン・マスク氏が設立したxAI社のモデルを追加することを発表しました。

> 「多様なAIモデルの選択肢を提供することで、お客様は自身のニーズに最も合ったモデルを選ぶことができます」

出典: [マイクロソフト、ｘＡＩのモデルをＡＩマーケットプレイスに追加 - Bloomberg](https://www.bloomberg.co.jp/news/articles/2025-05-19/SWIN53T1UM0W00)

## AIエージェントのセキュリティ強化

セキュリティとコンプライアンスを強化するための新ツールが発表されました。

主な機能：
- AIエージェントの認証と認可
- Entra Agent IDによる安全なアクセス管理
- コンプライアンスチェック機能

![AI Security](https://japan.zdnet.com/storage/2025/05/20/30da00447d550a6ab15b22dfd898a52c/gettyimages-2195052246.jpg)

出典: [マイクロソフト、「Build 2025」でAIエージェントの信頼性とセキュリティ強化ツールを発表 - ZDNET Japan](https://japan.zdnet.com/article/35233173/)

## まとめ

Microsoft BUILD 2025の2日目は、初日に発表された「AIエージェント時代」のビジョンをより実践的な側面から掘り下げました。開発者向けの詳細な情報が共有され、これらの新技術を実際のプロジェクトに取り入れる方法が示されました。特に、Azure AI FoundryとNLWebは、AIを活用したアプリケーション開発の新たな可能性を開くものと期待されています。

---

参考文献：
- [Microsoft Build 2025 | Day 2 Keynote - YouTube](https://www.youtube.com/live/5sM3JguEMzQ)
- [Unpacking the tech](https://build.microsoft.com/en-US/sessions/KEY020)
- [Scott and Mark Learn to...LIVE](https://build.microsoft.com/en-US/sessions/KEY040)
- [Microsoft Build 2025 Day 2 Keynote | ブチザッキ](https://blog.azure.moe/2025/05/21/microsoft-build-2025-day-2-keynote/)
- [Microsoft Build Day 2 - はつねの日記](https://hatsune.hatenablog.jp/entry/2025/05/21/080323)