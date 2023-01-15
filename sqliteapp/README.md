# sqliteapp

## 環境構築

環境設定ファイルをコピーして編集する。

```zsh
% cp .env.sample .env
```

セットアップする。

```zsh
% docker compose build
% docker compose run --rm app rails db:create
% docker compose run --rm app rails db:migrate
```

起動する。

```zsh
% docker compose up -d
```

破棄する。

```zsh
% docker compose down
```
