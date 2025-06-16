# Stackクラス テストリスト（TODO）

## 基本的な空のStack操作

- [ ] 新しいStackは空である
  - [ ] 新しいStackのサイズは0である
  - [ ] 新しいStackでisEmpty()はtrueを返す

## push操作

- [ ] pushで要素を1つ追加できる
- [ ] pushで要素を追加後、isEmptyはfalseを返す
- [ ] pushで要素を追加後、sizeは1になる
- [ ] pushで複数の要素を順次追加できる
- [ ] pushで文字列、数値、オブジェクトなど異なる型を追加できる

## pop操作

- [ ] pushした要素をpopで取り出せる
- [ ] popは最後にpushした要素を返す（LIFO）
- [ ] popした後、sizeが1減る
- [ ] 複数回pushした要素を正しい順序でpopできる
- [ ] すべてpopした後、Stackは空になる

## top操作

- [ ] topで最後にpushした要素を参照できる
- [ ] topは要素を取り出さない（sizeは変わらない）
- [ ] pushした後、topとpopは同じ値を返す

## size操作

- [ ] 空のStackでsizeは0
- [ ] 要素を追加するたびにsizeが増加
- [ ] 要素を削除するたびにsizeが減少

## isEmpty操作

- [ ] 空のStackでisEmptyはtrue
- [ ] 要素があるStackでisEmptyはfalse
- [ ] すべてpopした後、isEmptyはtrue

## エラーケース・例外処理

- [ ] 空のStackでpopするとundefinedを返す
- [ ] 空のStackでtopするとundefinedを返す

## 型安全性（TypeScript）

- [ ] 型パラメータでジェネリックとして動作する
