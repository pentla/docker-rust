# Rust 勉強会

Rust 入れてもいいよって人はこっちから
https://www.rust-lang.org/ja/learn/get-started

環境汚したくない人のための docker-compose 環境

## 立ち上げ

```bash
docker-compose up -d
```

## Rust モジュールの作成

```bash
docker-compose exec rust /bin/bash

# workshopっていう名前のRustのパッケージの作成
cargo new workshop

# workshopクレート
cd workshop

cargo run workshop
```

hello, world って表示されれば完成です。
