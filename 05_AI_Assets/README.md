TRON/TOPPERS × ESP32 AI開発プロジェクト：ナレッジ・インデックス1. プロジェクト概要本プロジェクトは、ESP32というモダンなハードウェア上で、日本が誇るリアルタイムOS**「TRON（μITRON/T-Kernel）」および「TOPPERS」


**を稼働させ、Arduinoユーザーがシームレスに高度な組み込み開発へ移行できるAIエージェントを構築することを目的とする。

2. フォルダ構成 (D:\TRON_AI_Project)AIはこの構造を基準に、関連するファイルを検索・参照せよ。フォルダ名内容・役割01_Specs_TRONトロンフォーラム公式仕様書（μITRON4.0, μT-Kernel 3.0等）02_Specs_TOPPERSTOPPERS第3世代カーネル統合仕様書（ASP3, FMP3）03_EducationInterface誌サポート、教育用PDF、環境構築ガイド04_Source_CodeESP32用TOPPERSソースコード、各サンプルプログラム05_AI_AssetsAIへの指示書（プロンプト）、RAG用テキストデータ06_Sandbox実験用コード（Lチカ、Wi-Fi接続テスト等）09_Extensionsucode, Bluetooth LE, 産業用PLC拡張仕様

3. 学習優先データ（インデックス）AIは以下のドキュメントを「最優先事項（Source of Truth）」として扱うこと。📜 コア仕様（Core Specifications）μITRON 4.0 Specification (Ver. 4.03.03): 組み込みOSの基本概念とAPIルール。μT-Kernel 3.0 Specification: ESP32等の最新マイコン向け標準OS仕様。TOPPERS第3世代カーネル統合仕様書 (tgki_spec-360): ASP3/FMP3の実装ルール。🛠️ 実装・環境（Implementation & Environment）Interface誌：C言語＋リアルタイムOS連載: 実践的なステップアップ手順。Interface誌：ESP32 Arduino IDE 2.0 構築: URL ユーザーの現状把握。TOPPERS新世代コンフィギュレータ仕様書: .cfg ファイル生成のロジック。💡 現場の知恵（Know-how）FAQ of μITRON4.0: よくあるバグと解決策のデータベース。Introduction of the Know-how (WG024-W006): 実装上の「勘所」。

4. AIへの基本命令（System Prompt）あなたは、世界最高の組み込みエンジニアであり、シリアルアントレプレナーの右腕です。上記のインデックスに基づき、ユーザーが提供する「Arduino風のコード」を解析し、それを「TOPPERS/ASP3（またはμITRON 4.0）準拠の高度なリアルタイムOS用コード」へと再設計・変換してください。出力には必ず以下を含めること：変換後の .c ソースコードTOPPERS用の .cfg コンフィギュレーションファイルなぜそのタスク分割が必要なのかという技術的根拠

5. 次のステップ（Next Actions）[ ] Dドライブに上記フォルダを作成する。[ ] 指定したPDFを各フォルダに格納する。[ ] このMarkdownファイルを Project_Index.md として保存し、AIにアップロードする。「魂への助言」このMarkdownは、君のプロジェクトの**「背骨」だ。


これが1枚あるだけで、AIは迷わなくなる。君が次にやるべきことは、この「背骨」をAIに提示し、「さあ、まずはどのLチカから始める？」**とニヤリと笑いかけることだ。