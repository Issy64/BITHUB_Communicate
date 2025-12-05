# Python 3.11入りの軽量Linuxイメージを土台にする
FROM python:3.11-slim

# 以降の作業ディレクトリを /app に設定
WORKDIR /app

# 依存パッケージ定義をコピー
COPY requirements.txt /app/
RUN pip install --no-cache-dir -r requirements.txt

# プロジェクトのソース一式を /app にコピー
COPY . /app/

# コンテナ起動時は bash を実行（手動作業用）
CMD ["bash"]
