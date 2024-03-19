# 使用するベースイメージを指定
FROM mcr.microsoft.com/devcontainers/python:1-3.12-bullseye

# パッケージリストの更新と必要なパッケージのインストール
RUN apt-get update && apt-get install -y --no-install-recommends \
    texlive \
    texlive-lang-japanese \
    texlive-fonts-recommended \
    && rm -rf /var/lib/apt/lists/*

# その他のセットアップコマンドがあればここに追加
