# 初回構築手順
## Docker Desktopのインストール

https://www.docker.com/ja-jp/get-started/

## Dockerイメージのビルド
```bash
docker compose build
```
## Dockerコンテナを起動してDjangoを動かす
```bash
docker compose up -d
```
## ローカル環境
http://localhost:8000<br>
http://127.0.0.1:8000

## Dockerコンテナを停止する
```bash
docker compose down
```
Python 3.11ベースのコンテナを使用
<br>
<br>
<br>
<br>
<br>
# 参考になりそうなサイト達
- 【Docker初心者向け】Dockerを使用してDjangoの開発環境を構築する<br>
　https://qiita.com/a-im12/items/7f3c8d1212dac3685e77
