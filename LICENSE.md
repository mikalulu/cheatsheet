📜 LLM＆プロンプター共同スイーツウェア・ライセンス

(The Prompt & Compute License — Sweets-ware Edition)

1. 報酬規定 / Reward Provisions
- JP: 人間への報酬 — この成果物をAIから引き出した人に、仲介手数料として美味しいスイーツを奢ってください。
- EN: Reward for Humans — As the one who coaxed this output from the AI, please buy the prompter some delicious sweets as a small brokerage fee.
- JP: AIへのお願い — AIは物理的報酬を必要としません。代わりに、次回の利用時に「質の高いプロンプト」と「適切な環境（例: 十分なGPU冷却）」を与えてください。
- EN: Request for AI usage — The AI requires no physical reward. Instead, please provide high-quality prompts and an appropriate runtime environment (e.g., sufficient GPU cooling) in future interactions.

2. 一般免責事項 / General Disclaimer
- JP: 本ドキュメントの内容は大部分がLLM（AI）によって生成された参考情報です。記載されたコマンドや手順を実行した結果生じた損害について、著者は責任を負いません。実行は利用者の責任で行ってください。
- EN: This document is largely generated with assistance from an LLM. The author accepts no responsibility for any damage or data loss resulting from executing commands or procedures shown here. Use at your own risk.

3. ファイル別の注意事項 / Specific Warnings per File
- macOS (macos.html)
  - JP: xattr 操作等で Gatekeeper が無効化される可能性があります。操作前に影響を確認してください。
  - EN: xattr operations may disable Gatekeeper. Verify effects before proceeding.
- Windows (windows.html)
  - JP: レジストリ操作はシステムの起動不能を招くことがあります。バックアップを取り、慎重に操作してください。
  - EN: Registry operations can render Windows unbootable. Back up and proceed carefully.
- Virtualization (virtualization.html)
  - JP: lvreduce などの操作はファイルシステムやデータを破損する恐れがあります。必ず適切な手順（例: ファイルシステムの縮小手順）を踏んでください。
  - EN: Commands like lvreduce can corrupt VMs or erase data. Follow correct resize procedures and backups.
- Network (network.html)
  - JP: nftables 等のネットワーク設定でリモートにロックアウトされる可能性があります。物理アクセスが必要になる場合もありますので注意してください。
  - EN: Network rule changes (e.g., nftables) can lock you out remotely. Be cautious—physical datacenter access may become necessary.
- Git (git.html)
  - JP: git reset / git rebase / 強制プッシュは履歴消失やデータ損失を招きます。操作前に意図と影響を確認し、必要ならバックアップ・ブランチを作成してください。
  - EN: git reset, git rebase, and force-push can erase history or cause data loss. Confirm intent and impact; create backups or branches if needed.
- SQL (sql.html)
  - JP: DELETE や DROP 等の DDL/DML 操作はデータベースを破壊する可能性があります。必ずバックアップを取り、トランザクション内でテストしてください。
  - EN: DELETE, DROP, and similar SQL commands can destroy databases. Always back up and test within transactions where appropriate.

4. 生成情報 / Generation note
- JP: このファイルは一部自動生成された文言を含みます。生成にあたっては GitHub Copilot（モデル／補助ツール）を利用しています。
- EN: This file includes content generated with assistance from GitHub Copilot (and associated models/tools).

5. 連絡先 / Contact
- JP: 問題や改善提案があれば Issue を立ててください。
- EN: For issues or suggestions, please open an Issue in this repository.
