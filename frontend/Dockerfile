# 空のコンテナ用
FROM alpine:latest

# 基本的なツールをインストール
RUN apk add --no-cache \
    bash \
    curl \
    git

# 作業ディレクトリを設定
WORKDIR /app

# デフォルトのコマンド
CMD ["/bin/bash"]
