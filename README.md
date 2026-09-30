# スキルシート – HirokiMorita577

ポートフォリオサイト：[portfolio.html](./portfolio.html)

---

## プロフィール
- **名前**：森田裕生
- **所属**：日本工業大学 先進工学部 情報メディア工学科
- **学年**：3年生（2026年現在）
- **GitHub**：[https://github.com/HirokiMorita577](https://github.com/HirokiMorita577)

---

## スキル一覧

| 分野 | 使用技術・ツール | 経験期間 | 補足情報 |
|---|---|---|---|
| プログラミング言語 | Python, C, VB, TypeScript, JavaScript | 約6年 | Python が主力。授業・個人制作・チーム開発で使用 |
| フロントエンド | HTML, CSS, React, Vite | 約3年 | GitHub Pages / Vercel での公開経験あり |
| 3D・物理演算 | Three.js, cannon-es, Blender | 約1年半 | GLTF モデル表示、三人称操作、物理ステージを実装 |
| バックエンド | Flask, SQLite, Firebase | 約1年 | 匿名SNS のプロトタイプを設計・実装 |
| AI・機械学習 | PyTorch, ALE (Atari), Google Colab | 約1年 | DQN / SARSA / HRA による強化学習、論文再現 |
| 生成AI・API | Claude API, Gemini / Voyage 埋め込み | 約1年 | 投稿文のジャンル自動分類に利用 |
| インフラ・デプロイ | Docker, Vercel, GitHub Pages | 約1年 | Web アプリのコンテナ化とデプロイ |
| バージョン管理 | Git / GitHub | 約4年 | チーム開発・複数リポジトリ運用 |
| その他 | pytest, VS Code, Markdown, LINE LIFF | 約3年 | 要件定義書・技術仕様書の作成経験あり |

---

## 制作物・プロジェクト

### Ms. Pac-Man 強化学習（HRA 論文再現）｜チーム開発・2026
- 内容：NeurIPS 2017「Hybrid Reward Architecture for Reinforcement Learning」を Atari 2600 版 Ms. Pac-Man で再現。報酬を要素ごとに分解し、各価値関数を合算して行動を決定
- 成果：学習時の直近100エピソード平均 14,845 点（11,000 エピソード時点。論文記載の人間平均は 15,693 点）
- 工夫：要件定義書の作成、RAM 読み取りと画面の照合、衝突判定の診断ツール、Colab 長時間学習の保存・再開機能。前段で DQN / SARSA 比較と PSO によるパラメータ探索
- 技術：Python, PyTorch, ALE, Google Colab, pytest
- URL：[https://github.com/HirokiMorita577/MediaDesignTeam1](https://github.com/HirokiMorita577/MediaDesignTeam1)

### ハピディアリー｜学内ビジネスプランコンテスト出場・2026
- 内容：学内ビジコンに出場したビジネスプランのプロジェクト。完全匿名で「マウントの生まれない」幸せの記録・共有SNS を提案し、プロトタイプまで実装
- 工夫：いいね数・フォロワー数を持たず、1投稿が届く人数を固定。投稿文から AI でジャンルを推定。任意ログインはユーザー名をハッシュ化して保存し、CSRF 対策も実装
- 技術：Flask, SQLite, JavaScript, Claude API, Docker
- URL：[https://github.com/HirokiMorita577/HapiDiary](https://github.com/HirokiMorita577/HapiDiary)

### HackU GNP — LINE 位置情報アプリ｜ハッカソン・2025
- 内容：LINE LIFF 上で動く Web アプリ。プロフィールと現在地を地図に表示し、制限時間つきで参加者同士が遊べる
- 技術：React, TypeScript, Vite, LINE LIFF, Firebase, Vercel
- URL：[https://github.com/HirokiMorita577/HackU_GNP](https://github.com/HirokiMorita577/HackU_GNP)

### 音声合成 Web アプリ｜ハッカソン・2025
- 内容：React のフロントエンドと Python の音声合成（Tortoise TTS）サーバーで、入力テキストを読み上げる
- 技術：React, Python, Tortoise TTS
- URL：[https://github.com/HirokiMorita577/Hakkason_React_Project](https://github.com/HirokiMorita577/Hakkason_React_Project)

### Three.js 3D モデル紹介サイト｜個人開発・2025
- 内容：GLTF モデルの読み込み、三人称視点のキャラクター操作、cannon-es による物理演算とステージ構築
- 技術：Three.js, cannon-es, Blender, HTML/CSS
- URL：[https://hirokimorita577.github.io/threejs-demo/](https://hirokimorita577.github.io/threejs-demo/)

---

## 資格・学習履歴
- ITパスポート（取得済み）
- 基本情報技術者試験（学習中）

---

## 自己PR

> 好奇心と実験精神を大切に、手を動かしながら学びを深めるスタイルを取っています。
> Three.js の 3D 表現から始まり、現在は強化学習の論文再現や、ビジネスプランコンテストに向けた Web サービス開発にも取り組んでいます。
> 要件定義書や仕様書を先に書き、検証を重ねながら形にすることを大切にしています。
> インターンやチーム開発にも積極的に関わっていきたいです。

---

## 連絡先
- GitHub：[@HirokiMorita577](https://github.com/HirokiMorita577)
- メール：hiroki.morita.bite@gmail.com
