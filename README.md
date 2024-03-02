# componentaa_development_standards

## 概要

- [富士通株式会社](https://global.fujitsu/ja-jp/)が2004年に作成し、2007年に一般公開したComponentAA開発標準（ドキュメント標準編）1.0a版です。
- ドキュメント標準とは、コンピューターシステム開発における要求定義/設計/構築/テストを実施するためのドキュメントの標準を規定したものです。
  - ドキュメントの雛形、記述例、作成手順、記述要領、ドキュメント作成に必要となる用語や概念の解説などが含まれています。
- ComponentAA開発標準（ドキュメント標準編）は、添付の使用許諾条件に従う条件で、使用、複製、改変、再配布が認められています。
- 内容はかなり古くなってしまいましたが、大規模システムを対象としたドキュメント標準で、公開されているものとしては数少ない事例と思われます。ドキュメント標準の事例としてもしばしば参照されているのですが、2024年現在富士通株式会社からの公開は停止されていますので、ここに公開することとしました。

## 特徴

- 全体
  - 開発手法：ウォーターフォール
  - 適用対象システムの規模： 中規模～大規模向け （数10k steps程度以上向けと思われます）
  - ドキュメントの雛形はExcel形式です。解説資料は word および power point 形式で作成されています。
  - UML記法が部分的に取り入れられています。
- 要件定義工程ドキュメントは汎用性があります。リリースから20年経た現在でも利用可能なドキュメントは多いでしょう。
- 設計および構築工程ドキュメントは、2004年当時に主流だったアーキテクチャと技術に最適化されています。現在利用されているアーキテクチャや技術にはフィットしない部分が多いと思います。ドキュメント体系など抽象レベルの考え方は参考にできる部分があるかもしれません。
  - アプリケーション形態は、オンライン処理（３層構造／２層構造）、および、バッチ処理に対応しています。
  - オンライン処理のプレゼン層は、Java(Servlet/Applet/Javaアプリ)に最適化されています。
  - オンライン処理のアプリ層は、Java(EJB)およびCOBOLに最適化されています。
  - 言語は、Java および COBOL に最適化されています。
- ComponentAA開発標準のエッセンスは、IPAの「機能要件の合意形成ガイド」にも反映されました。

## 参考情報

- [ComponentAA開発標準 ご紹介資料](https://www.fujitsu.com/downloads/JP/archive/jp/jsdas/document/caa-intro20040520.pdf), 富士通株式会社, 2004/5/20
- [開発プロセスの標準化とWebアプリケーション開発への対応](https://www.fujitsu.com/downloads/JP/archive/imgjp/jmag/vol57-1/paper03.pdf), FUJITSU, 2006/1, 斉藤涼子/沖山智/平井宣
- [ComponentAA開発標準の実践適用事例](https://www.fujitsu.com/downloads/JP/archive/imgjp/jmag/vol57-1/paper12.pdf), FUJITSU, 2006/1, 米村有三
- [発機能要件の合意形成ガイド](https://www.ipa.go.jp/archive/digital/iot-en-ci/jyouryuu/ent03-a.html), IPA, 2010/3

以上
