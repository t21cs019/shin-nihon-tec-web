# shin-nihon-tec-web

# ディレクトリ構成

shin-nihon-tec-web/ (本番用リポジトリ)
│
├── index.html          # ★トップページ（企業情報、事業内容などは全てこの中！）
│
├── events/             # ★別ページとして飛ぶ「イベント」等はここに入れる
│   ├── _template/      # 事務員さん用の雛形フォルダ
│   │   └── index.html
│   │
│   └── 80th-ceremony/  # 80周年式典の詳細ページ
│       └── index.html  # (https://.../events/80th-ceremony/ でアクセス)
│
└── assets/             # 画像や共通ファイルをまとめる
    ├── css/
    └── images/
        ├── top/        # トップページ用の画像
        └── events/     # イベント用の画像