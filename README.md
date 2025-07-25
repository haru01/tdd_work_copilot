# テスト駆動開発（TDD）学習プロジェクト

このプロジェクトは、テスト駆動開発（TDD: Test Driven Development）の手法を学ぶためのサンプルリポジトリです。

## 特徴
- TypeScript + Vitest によるテスト環境
- スタック（Stack）を題材に、TDDのRed/Green/Refactorサイクルを体験
- コマンドごとにTDDのステップをドキュメント化

## セットアップ
1. 依存パッケージのインストール

```sh
npm install
```

2. テストの実行（runモード）

```sh
npm test
```

## ディレクトリ構成
- `stack.test.ts` : スタックのテストコード
- `sample.test.ts` : サンプルテスト（1+1=2）
- `command/` : TDDの各ステップを記載したドキュメント

## 学習の進め方
1. `command/` ディレクトリの手順に従い、TDDの各ステップを体験してください。このリポジトリは、１、２は実行済みなので３から始めてください。
   1. github copilotのチャットを開いて、Agentモードに切り替えて、3.Red_新しいスタックは空であるテストを作成し実行.mdの内容を貼り付けて実行してください。

2. まずテストを書き（Red）、最小限の実装でテストを通し（Green）、リファクタリング（Refactor）を行います。
3. 各ステップで Stack.test.ts, Stack.ts, TODO.md を参照しながら進めてください。

---

## 参考
- [Vitest公式ドキュメント](https://vitest.dev/)
- [テスト駆動開発](https://www.agile-studio.jp/post/apm-test-driven-develpment)
- [テスト駆動開発（TDD）とは](https://ja.wikipedia.org/wiki/テスト駆動開発)
