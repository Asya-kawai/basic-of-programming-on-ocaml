# Basic of programming on OCaml

A book that describes the basics of OCaml programming.

## How to build

```bash
satysfi basic-of-programming-on-ocaml.saty -o basic-of-programming-on-ocaml.pdf
```

You can open and read `basic-of-programming-on-ocaml.pdf`.

## Cover

* `./img/hyoshi.jpg`

satysfiはpngもサポートするらしいが・・・まだ対応していないようだ。

## Table of contents

* はじめに
* 基本的なデータと型
  * int,float,bool,char,string
* 変数と関数
  * 変数の定義
  * 関数の定義
* 条件分岐
  * if
* データと型とパターンマッチ（タプル、リスト）
  * List and Patterns, Records
  * match
  * 再帰関数を使ったプログラミング（一部）を参考？
* 再帰関数
  * 再帰関数を使ったプログラミング（一部）を参考
  * 自然数と再帰を参考
  * 新しい形の再帰を参考
  * 再帰的データ構造を参考
* 関数の引数
  * ラベル付き引数
  * オプション型とオプショナル引数
* その他のデータと型
  * レコード
  * バリアント
    * Variantsを参考
  * ユニット型
    * これも入れておいたほうがいいか
    * 再帰関数で入れるか
* エラーハンドリング
  * 例外と例外処理を参考
  * Erro Handlingを参考
* モジュール
  * Files,Modules, and Programsを参考
  * モジュールを参考
* ファンクタ

以降はそれほど大きなウェイトを占めないようにする。 

* 逐次実行
  *逐次実行を参考
* 値の書き換えと参照透過性
  * 値の書き換えと参照透過性を参考
* オブジェクトとクラス
  * Objects,Classを参考
* ファーストクラスモジュール
  * 入れない


いくつかのデータと型が説明できていないため、どこかに入れたい。

* https://www2.lib.uchicago.edu/keith/ocaml-class/data.html

## 表記ルール

* 各章で最初に出現する変数、関数、戻り値は`\codem{}`を用いて強調する
  * 当該の章にて2度目以降の出現は装飾せず本文として扱う
* 複数行にわたるコードは`\d-code{}`を用いて本文と区別する
* 文中にコード、数式またはアスキーアートを挿入する場合は`\d-codem{}`を用いる
  * 本当は区別したい
* いづれ → いずれ
* 下記、以下。どちらもOK
* 使用、利用。どちらもOK
* て見ます → てみます
* わかります → 分かります
* いいます → 言います
* 次の通り → 次のとおり
* など → 等
* あたる → 当たる
* まったく → 全く
* とる → 取る、採る、執る、摂る等。
* この時 → このとき
* 予め → あらかじめ
* して下さい → してください
* 上手い → うまい
* 繋ぐ → つなぐ
* 一度しか出現しないシンボル`<...>`は連番なし
* 何度も出現するシンボル`<...>`は最初のものは0から連番。以降は1〜nとする
* パターンマッチ等によって変数名または関数名の連番とパターンマッチに用いる連番がズレる場合は、イコールの右辺側を1〜nの連番とする

## 表現メモ
* 変数を値に束縛する = 変数は値に束縛される = 値に変数を束縛する
  * http://www.nct9.ne.jp/m_hiroi/func/ocaml01.html#chap02 でも「変数を値に束縛します」とある
* 値は変数を束縛する←これは間違い。値で変数を束縛する ならOK

## その他

* 章内にサブセクションを設け、モジュールを利用してより実践的な利用方法について解説する
