📘 FastAPI CRM ポートフォリオ README（日本語）

概要

FastAPI と Vue 3 を使用して構築されたフルスタックの CRM（顧客管理）システムです。

🚀 主な機能

🔒 JWT 認証（ログイン・登録）

👤 顧客の CRUD（作成・更新・削除・一覧）

📦 FastAPI による RESTful API

💡 Vue 3（Composition API）を用いたフロントエンド

🐳 Docker による開発・本番環境構築

📄 Swagger / OpenAPI による API ドキュメント

🛠️ 技術スタック

層

技術構成

バックエンド

FastAPI, Pydantic, SQLAlchemy

フロントエンド

Vue 3, Vite, Axios

データベース

PostgreSQL（Docker）

認証

JWT

コンテナ

Docker, Docker Compose

📂 ディレクトリ構成（概要）

portfolio-fastapi-crm/
├── backend/
│   └── app/
│       ├── api/         # ルーター
│       ├── core/        # 認証・設定
│       ├── models/      # DB モデル
│       ├── schemas/     # スキーマ
│       └── services/    # ビジネスロジック
├── frontend/
│   └── src/
│       ├── components/
│       ├── views/
│       ├── router/
│       └── App.vue
├── docker-compose.yml
└── README.md

⚙️ 起動方法

git clone https://github.com/tnohara48/portfolio-fastapi-crm.git
cd portfolio-fastapi-crm
docker-compose up --build

フロントエンド: http://localhost:3000

バックエンド: http://localhost:8000

API ドキュメント: http://localhost:8000/docs

🧪 デモアカウント

メール: demo@example.com
パスワード: password123

📃 ライセンス

MIT License

🙋 作者

GitHub: tnohara48

📘 FastAPI CRM ポートフォリオ README（日本語）

概要

FastAPI と Vue 3 を使用して構築されたフルスタックの CRM（顧客管理）システムです。

🚀 主な機能

🔒 JWT 認証（ログイン・登録）

👤 顧客の CRUD（作成・更新・削除・一覧）

📦 FastAPI による RESTful API

💡 Vue 3（Composition API）を用いたフロントエンド

🐳 Docker による開発・本番環境構築

📄 Swagger / OpenAPI による API ドキュメント

🛠️ 技術スタック

層

技術構成

バックエンド

FastAPI, Pydantic, SQLAlchemy

フロントエンド

Vue 3, Vite, Axios

データベース

PostgreSQL（Docker）

認証

JWT

コンテナ

Docker, Docker Compose

📂 ディレクトリ構成（概要）

portfolio-fastapi-crm/
├── backend/
│   └── app/
│       ├── api/         # ルーター
│       ├── core/        # 認証・設定
│       ├── models/      # DB モデル
│       ├── schemas/     # スキーマ
│       └── services/    # ビジネスロジック
├── frontend/
│   └── src/
│       ├── components/
│       ├── views/
│       ├── router/
│       └── App.vue
├── docker-compose.yml
└── README.md

⚙️ 起動方法

git clone https://github.com/tnohara48/portfolio-fastapi-crm.git
cd portfolio-fastapi-crm
docker-compose up --build

フロントエンド: http://localhost:3000

バックエンド: http://localhost:8000

API ドキュメント: http://localhost:8000/docs

🧪 デモアカウント

メール: demo@example.com
パスワード: password123

📃 ライセンス

MIT License

🙋 作者

GitHub: tnohara48


