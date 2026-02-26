# shin-nihon-tec-web

# ディレクトリ構成

'''
shin-nihon-tec-web/ (本番用リポジトリ)
│
├── index.html          # トップページ
│
├── events/             # 別ページとして飛ぶ「イベント」
│   ├── _template/      # 事務員さん用の雛形フォルダ
│   │   ├── index.html  # 雛形のHTML
│   │   └── dummy.jpg   # 雛形用のダミー画像（あれば）
│   │
│   └── 80th-ceremony/  # 80周年式典の詳細ページ
│       ├── index.html  # イベントのHTML
│       ├── slide1.jpg  # ★このイベントで使う写真たち
│       └── slide2.jpg  # ★このイベントで使う写真たち
│
└── assets/             # 全体で共通して使うものだけをまとめる
    ├── css/
    └── images/
        ├── logo.png    # 会社のロゴなど
        └── top-bg.jpg  # トップページの背景画像など
'''