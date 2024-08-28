# Diesel ORM with SQLite demo

Demo project demonstrating how to use Diesel ORM with SQLite in Rust. This is based on the [Getting Started guide](https://diesel.rs/guides/getting-started) from the official documentation and the [SQLite examples](https://github.com/diesel-rs/diesel/tree/2.2.x/examples/sqlite) in the Diesel repo.

Interested in using Diesel and SQLite in a [Tauri](https://tauri.app/) app? Check out [this guide](https://blog.moonguard.dev/how-to-use-local-sqlite-database-with-tauri) that explains how it's used in the Orion project. Or better yet, check out [the source code](https://github.com/taecontrol/orion).

Don't want to use an ORM? Check out the [tauri-sql plugin](https://github.com/tauri-apps/tauri-plugin-sql), which is based on [sqlx](https://github.com/launchbadge/sqlx).

## How to run

```
$ echo "DATABASE_URL=file:test.db" > .env
$ diesel migration run

$ cargo run --bin show_posts
```