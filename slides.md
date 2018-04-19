## InteliJ IDEA ハンズオン

--

PhpStormとかRubyMineもだいたい同じ機能あると思うよ。

--

実はInteliJ IDEA UltimateだけでPhpStormかPyCharmとかRubyMaineと同等の機能が使える。

---

## 概要

* 開発元
    * JetBrains

* 対応OS
    * いろいろ

* 対応言語
    * 日本語にしようと思えばできる

--

    
* 価格(サムライズム)
    * パーソナルライセンス 15,400 > 12,300 > 9,200
    * コマーシャルライセンス 0 > 60,000 > 48,000 > 35,900
    * Community版はタダでScalaが書ける

--

やたらと高機能なので把握が難しい

--

リファクタリング機能をJavaのIDEとして初めて搭載したやつ  

---

## サポートしてる言語とか

* <u>**Java**</u>
* <u>**Kotlin**</u>
* Groovy
* JavaFX
* Java Script
* Coffee Script
* Type Script

--

* HTML/XHTML/CSS
* Sass/SCSS/Less
* XML/XSL
* Action Script/HXML
* Python/Cython
* Ruby/JRuby
* (Elixir)

--

* SQL
* (Perl)
* (PHP)
* (Scala)
* (Clojure)
* (Dart)
* (Haxe)
* (TypoScript)
* (Haskell)

---

## サポートしているフレームワークとか

* JSP
* JSF
* EJB
* Ajax
* Google Web Tool Kit
* Google App Engine

--

* Struts
* Struts2
* JBoss Seam
* Spring
* Hibernate/JPA
* Web Service

--

* Ruby on Rails
* Grails
* Java ME MIDP/CLDC
* OSGI
* Android

--

* Tapestry
* FreeMarker
* Velocity
* Django
* Play

---

## サポートするその他いろいろ

* Git
* CVS
* Apache Subversion
* Apache Ant
* Apache Maven
* JUnit
* TestNG
* Gradle
* Compas

---

## 代表的な機能

* <u>**Refactoring**</u>
* <u>**Postfix Completion**</u>
* Live Template
* Database Tool Window

---

## Live Template

HTMLとかを編集しながらプレビューできます。
LiveEditプラグインとChromeにJetBrains IDE Extensionをインストールしたら使えます。
これを使うとHTMLの編集を行うとブラウザでリアルタイムにレンダリングされます。

---

## Database Tool Window
データソースにアクセスして、カラムを覗いたり発行したSQLを観たりテーブルの構造を観たりできます

---
## Refactoring
とても強い

--

## Postfix Completion
一番推したい機能です。
Booleanを返す式の後ろで ".if"とか打つとif文のテンプレートをその場に展開してくれたりします。  
慣れるとコーディングスピードが上がるかもしれない。

--

例

    fun hoge = arrayList.isEmpty()
    hoge.if//<---これが

    fun hoge  = arrayList.isEmpty()
    if(hoge){
        //if文のテンプレートが展開されてカーソルがここに来る
    }



