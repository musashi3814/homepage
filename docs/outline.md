あなたはプロのフロントエンドエンジニア兼Webデザイナーです。
以下の要件と提供データに基づいて、AI作成らしくないモダンでレスポンシブなポートフォリオサイト（ホームページ）を作成してください。
GitHub Pagesでデプロイすることを前提とし、新しいリポジトリ用の構成で出力してください。

## 【技術要件】
- **技術スタック**: HTML5, Tailwind CSS (CDN経由でOK), Vanilla JavaScript (年齢自動更新用)
  - ※もしReact(Vite)等の方がモダンに仕上がる場合は、Reactのコードベースで出力し、GitHub Actionsでのデプロイ手順（`gh-pages`の使用など）を添えてください。
- **デザイン**: モダン、ミニマル、かつ技術者らしさを感じるデザイン（ダークモード対応が望ましい）。
- **レスポンシブ対応**: スマートフォン、タブレット、PCで美しく表示されること。
- **動的機能**: 生年月日（2002/08/24）から現在の年齢を計算し、表示を自動更新するJavaScript関数を実装すること。
- **アニメーション**: スクロール時のフェードインや、ホバー時の軽いトランジションなど、控えめで上品なアニメーションを取り入れること。

## 【サイト構成】
1. **Heroセクション**: 名前、肩書き、簡単な自己紹介、各種リンク（GitHub, X, LinkedIn）、連絡先
2. **About Me**: 年齢（自動更新）、所属、趣味、特技
3. **Experience**: インターンシップと経歴（タイムライン形式が望ましい）
4. **Education**: 学歴
5. **Research**: 研究内容（概要とリンク）
6. **Projects**: 開発プロジェクトやハッカソン等の実績
7. **Awards**: 受賞歴（ExperienceやProjectsに紐づけても、独立セクションでも可）

---

## 【表示するコンテンツデータ】

### [Basic Information]
- 名前: 羽田野 武蔵 (Hadano Musashi)
- 生年月日: 2002年8月24日（※年齢はJSで自動計算して「OO歳」と表示）
- 内定先: 株式会社MIXI (ソフトウェアエンジニア)

### [access]
- 電話番号: 080-6472-0535
- Mail: musashi3814@gmail.com / hadano.musashi.056@s.kyushu-u.ac.jp
- GitHub: https://github.com/musashi3814
- X (Twitter): https://x.com/tuyosonanamae
- LinkedIn: https://www.linkedin.com/in/musashi-hadano-7367303a7

### [About Me]
- 所属: 九州大学大学院 システム情報科学府 情報理工学専攻 修士2年 人間情報システム研究室
- 趣味: 
  - お笑い鑑賞（東京03。毎年欠かさず単独ライブに参戦。角田LOVE）
  - カメラ（Nikon Z50II）
  - 本屋巡り
- 特技: 
  - ナポリタン（パスタ作り全般が得意だが、特にナポリタンが別格。最近結構本気で喫茶店を開きたいと思っている）
  - ラテアート（元カフェ店員のため得意だと自負している。なお、そのカフェは2026年1月に閉店）
  - 早歩き（競歩経験があるわけでも足が速いわけでもないが、デフォルトの歩く速度が速い）

### [Education]
- 2025年4月 – 2027年3月(見込): 九州大学大学院 システム情報科学府 情報理工学専攻 修士課程
- 2023年4月 – 2025年3月: 九州大学 工学部 電気情報工学科 計算機工学コース (3年次編入学、GPA: 3.81 / 学科内10位 / カフェバイトに明け暮れる)
- 2018年4月 – 2023年3月: 久留米工業高等専門学校 電気電子工学科 (席次1位)

### [Experience (Internships & Work)]
- 2026年1月: 株式会社デジタルフォルン (学生インターン / CES 2026参加)
  - レポート: https://note.com/tuyosonanamae/n/n2bbb17c42a2c
- 2025年12月 (1ヶ月): 株式会社サイバーエージェント (バックエンドエンジニア)
  - 技術: TypeScript, Node.js, DDD, MongoDB
  - テックブログ: https://developers.cyberagent.co.jp/blog/archives/61378/
- 2025年10月 (1ヶ月): 株式会社リクルート (バックエンドエンジニア)
  - 技術: Java, Spring Boot 他
- 2025年8月 – 2025年9月 (2ヶ月): 株式会社MIXI (ソフトウェアエンジニア)
  - 技術: AWS, Python (Flask), LLM
- 2025年8月 (2週間): 株式会社コロプラ (バックエンドエンジニア)
  - 技術: PHP (Laravel)
- 2024年4月 – 2025年3月 (1年): 株式会社Aakel
  - 技術: TypeScript (React.js), Python (FastAPI), AWS

### [Research]
**1. ウェアラブルデバイスの行動データに対するプライバシー保護に向けた研究 (九州大学)**
ウェアラブルセンサのためのプライバシーリスク抑制技術の研究。オートエンコーダを用いて、動作の「クセ」から個人が特定されるリスクを抑えつつ、歩行等の活動認識に必要な特徴のみを抽出する手法を開発。モデル軽量化技術を駆使し、ESP32のような計算資源の限られた端末でも動作可能な低負荷設計を実現。
- 論文 (ACM Transactions on Computing for Healthcare Journal): https://dl.acm.org/doi/10.1145/3793553
- 情報処理学会 UBI研究会 ヤングリサーチャー賞: https://app.ait.kyushu-u.ac.jp/archives/2526
- J-GLOBAL: https://jglobal.jst.go.jp/detail?JGLOBAL_ID=202402275895858717

**2. ハードウェア適応型AIアルゴリズムのFPGA実装 (久留米高専 / 九州工業大学との共同研究)**
従来のAIが抱える消費電力・学習時間の課題に対し、ハードウェアに適した学習アルゴリズム「DFA」をVerilogHDLによるFPGA専用回路で評価。より速く、低電力で動かすための基礎技術を実証。（現在の論理ゲート型ML研究の先駆け）
- J-GLOBAL: https://jglobal.jst.go.jp/detail?JGLOBAL_ID=202402224624489067

### [Projects]
**1. 自治体のお困りごと可視化マップ / 2024年度 福岡未踏 Solveコース採択**
地域のお困りごとを可視化・共有するサービスの開発。2人チームのバックエンド担当として、API開発（Python/FastAPI）とインフラ構築（AWS）を担当。自治体へのヒアリングを通じた要件定義から、拡張性を考慮したDB・API設計、運用を見据えたログ設計まで一貫して経験。
- VORN Challenge 2025 優秀賞 受賞
- リンク集:
  - https://mitou-fukuoka.org/2024/09/03/2024solve-pro-saitaku/
  - https://mitou-fukuoka.org/works/solve-city-share-map/
  - https://note.com/mitou_fukuoka/n/n48b05e5b3bda
  - https://vorn-challenge-2025.com/report/

**2. 飲み促しシステム (IoT×ゲーム)**
プレイヤーの飲酒量を測り、最も飲んでいない人に罰ゲームを与えるゲーム。スマホアプリ(Flutter)とコースター(M5Stack＋重量センサー、3Dプリンタ成形)をBLEで接続。アプリのUI実装とBLE接続部分、グラス交換等のエッジケース処理の工夫を担当。
- 受賞: 研究室内アプリコンテスト優勝、MCPCナノコン応用コンテスト トリリオンノード奨励賞
- GitHub: https://github.com/futamurasho/onigoroshi
- ProtoPedia: https://protopedia.net/prototype/5639

**3. 論理ゲート型MLライブラリの開発 (未踏IT2026 二次審査中)**
行列演算中心のAIを見直し、論理ゲートでNNを構成する次世代MLライブラリの開発。PyTorch風の記述で設計・学習できる「コアモジュール」と、ハードウェア用ファイル(HDL)に自動変換する「拡張モジュール」を提供。GPUに依存しないエッジAIの民主化を目指す。

### [Awards & Publications]
- 2026.2: 「ACM Transactions on Computing for Healthcare Journal」論文掲載
- 2025.10: 「VORN Challenge 2025」 優秀賞
- 2025.9: 国際学会「IEEE ICMU 2025」口頭発表
- 2024.11: 「第84回情報処理学会UBI研究会」口頭発表 ヤングリサーチャー賞
- 2024.9: 「2024年度 福岡未踏 Solveコース」採択
- 2023.8: 「2023年 電気学会 電子・情報・システム部門大会」口頭発表

---
上記内容に基づき、そのままコピペして利用可能なコードファイル一式と、GitHub Pagesへのデプロイ手順を出力してください。