# The Rust Book - 練習用ワークスペース

## 実行方法

ルートディレクトリから章を指定して実行：

```bash
cargo run -p ch01-hello-world
```

または章のディレクトリに移動して実行：

```bash
cd ch01-hello-world
cargo run
```

## チェック

```bash
# ワークスペース全体
cargo check

# 特定の章
cargo check -p ch03-common-concepts
```

## 章一覧

| ディレクトリ | 章 |
|---|---|
| ch01-hello-world | 1章: はじめに |
| ch02-guessing-game | 2章: 数当てゲーム |
| ch03-common-concepts | 3章: 一般的なプログラミングの概念 |
| ch04-ownership | 4章: 所有権 |
| ch05-structs | 5章: 構造体 |
| ch06-enums | 6章: 列挙型とパターンマッチング |
| ch07-packages-crates-modules | 7章: パッケージ・クレート・モジュール |
| ch08-collections | 8章: コレクション |
| ch09-error-handling | 9章: エラー処理 |
| ch10-generics-traits-lifetimes | 10章: ジェネリクス・トレイト・ライフタイム |
| ch11-testing | 11章: テスト |
| ch12-io-project | 12章: I/Oプロジェクト |
| ch13-iterators-closures | 13章: イテレータとクロージャ |
| ch15-smart-pointers | 15章: スマートポインタ |
| ch16-concurrency | 16章: 並行性 |
| ch17-oop | 17章: オブジェクト指向 |
| ch18-patterns | 18章: パターンマッチング |
| ch19-advanced-features | 19章: 高度な機能 |
| ch20-final-project | 20章: 最終プロジェクト |
