horizon-city/
│
├── index.html                  # トップページ（メインビジュアル・サーバー紹介・最新情報）
├── terms.html                  # 利用規約
├── privacy.html                # プライバシーポリシー
├── law.html                    # 特定商取引法に基づく表記
├── rules.html                  # サーバールール
├── team.html                   # 運営チーム紹介
├── contact.html                # お問い合わせ・案内ページ
│
├── assets/                     # 静的リソース用ディレクトリ
│   ├── css/
│   │   ├── style.css          # 全ページ共通スタイル
│   │   ├── normalize.css      # CSSリセット・ノーマライズ
│   │   └── responsive.css     # レスポンシブ対応用CSS（オプション）
│   │
│   ├── js/
│   │   ├── main.js            # 全ページ共通JavaScript
│   │   ├── menu.js            # ハンバーガーメニュー・ナビゲーション制御
│   │   └── smooth-scroll.js   # スムーススクロール機能（オプション）
│   │
│   ├── images/
│   │   ├── logo.png           # サイトロゴ（ヘッダー用）
│   │   ├── logo-white.png     # サイトロゴ白バージョン（フッター用）
│   │   ├── favicon.ico        # ファビコン
│   │   ├── og-image.png       # OGP画像（SNSシェア用）
│   │   │
│   │   ├── hero/              # トップページヒーローイメージ
│   │   │   ├── hero-bg.jpg    # メインビジュアル背景
│   │   │   └── hero-bg-sp.jpg # スマホ用メインビジュアル
│   │   │
│   │   ├── team/              # 運営チーム写真・アイコン
│   │   │   ├── member-01.jpg
│   │   │   ├── member-02.jpg
│   │   │   └── default-avatar.png  # デフォルトアバター
│   │   │
│   │   ├── icons/             # アイコン類
│   │   │   ├── discord.svg
│   │   │   ├── twitter.svg
│   │   │   └── youtube.svg
│   │   │
│   │   └── common/            # 共通使用画像
│   │       ├── bg-pattern.png # 背景パターン
│   │       └── section-divider.svg  # セクション区切り線
│   │
│   └── fonts/                 # Webフォント（使用する場合）
│       └── .gitkeep           # ディレクトリ保持用
│
├── includes/                   # 共通パーツ用ディレクトリ（将来的にSSI/PHP化を想定）
│   ├── header.html            # 共通ヘッダー（現状は各HTMLに直接記述）
│   └── footer.html            # 共通フッター（現状は各HTMLに直接記述）
│
├── docs/                       # ドキュメント・規約原本管理
│   ├── terms-draft.md         # 利用規約下書き
│   ├── privacy-draft.md       # プライバシーポリシー下書き
│   └── update-history.md      # サイト更新履歴
│
├── .gitignore                  # Git管理除外設定
├── README.md                   # サイト構成・開発ガイド
└── sitemap.xml                 # サイトマップ（SEO対策）