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
1. `command/` ディレクトリの手順に従い、TDDの各ステップを体験してください。
2. まずテストを書き（Red）、最小限の実装でテストを通し（Green）、リファクタリング（Refactor）を行います。
3. 各ステップでREADMEやテストコードを参照しながら進めてください。

---

## 参考
- [Vitest公式ドキュメント](https://vitest.dev/)
- [テスト駆動開発（TDD）とは](https://ja.wikipedia.org/wiki/テスト駆動開発)
