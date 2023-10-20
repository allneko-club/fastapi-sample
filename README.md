# FastAPI Sample

fastapiのサンプル

<a href="https://github.com/allneko-club/fastapi-react-sample" class="external-link" target="_blank">fastapi-react-sample</a>のバックエンドとして使用しています。

## Features
* FastAPI
* python 3.10
* ドメイン駆動設計(DDD)風にディレクトリ構造を変更
* **Secure password** hashing by default.
* **JWT トークン認証**
* **SQLAlchemy** models.
* **Alembic** migrations.
* **CORS** (Cross Origin Resource Sharing).
* **Celery** worker that can import and use models and code from the rest of the backend selectively.
* **Pytest** tests framework
* **factory boy** model factory for tests.

### Notice
* デフォルトではメール機能をオフにしているため、パスワードリカバリーなどメールを送信する機能を使うとエラーが発生します。
* M系メモリ内臓のMacでpoetryを使うとエラーが発生する場合があります。poetryでrequirements.txtを出力し、Virtualenvなどの仮想環境を使うと動作します。
---
