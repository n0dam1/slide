# Clean Architecture　（途中まで）読んだ

@n0dam1

Shinjukuもくもくプログラミング #22

---

## 自己紹介
- 7月よりヘルスケア系のRailsエンジニア
- その前は、4ヶ月ほど友人のスタートアップ
  - メディアをやるということで一人目のエンジニアとして入社しましたが入社2週間後にメディアは撤退しました
- その前は、ビールの会社の情報子会社で６年ほどシステムエンジニア
  - Excel方眼紙、スクショエビデンス、忖度 etc...

---

## 今日やること

- Clean Architecture本を読む

![](https://images-fe.ssl-images-amazon.com/images/I/51mQrYTahJL.jpg)

---

## 今日の成果

1. イントロダクション
2. 構成要素から始めよ：プログラミングパラダイム　👈から
3. 設計の原則
4. コンポーネントの原則
5. アーキテクチャ 👈まで
6. 詳細

---

## なんで読んでるの？

- 作ってるアプリケーションがFat Model
  - 表示用のロジックがあったり他のModelを過剰に呼び出していたり
- 適切に分割したい
- じゃあその「適切」とは？の指針にするため

---

## 感想

- いわゆる下図のクリーンアーキテクチャの話は後半になるまで出てこない

![](https://camo.qiitausercontent.com/aa4e4f88dd885f486d7ab736311f886a7538a1df/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e616d617a6f6e6177732e636f6d2f302f36303435372f38666534633336362d343636652d653434632d613761362d6633613734336636393138332e706e67)

---

## 感想

- それまではクリーンアーキテクチャの前提となる設計原則の解説がつらつらとされている

---

### 設計の原則(SOLID原則)
- 単一責任の原則
- オープン・クローズドの原則
- リスコフの置換原則
- インターフェイス分離の原則
- 依存関係逆転の原則

---

### コンポーネントの原則
- 再利用・リリース等価の原則
- 閉鎖性共通の原則
- 全再利用の原則

- 非循環依存関係の原則
- 安定依存の法則
- 安定度・抽象度等価の原則

---

## 感想

- コードを書くようになってから4ヶ月のエンジニアには難しかった、、
- アーキテクチャはフレームワーク非依存であるべき、とあったが精鋭の集団でしか無理では
- ViewModelとかPresenterとか曖昧になりがちな言葉の共通認識をつくるのに役立つのでは

---

## 以上
