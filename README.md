# README

## WithTODO-トドと一緒に習慣化

### ■サービス概要
<span style="color: LightSeaGreen; ">WithTODO(ウィズトド)</span>は、基本的なToDoリスト機能に加え、タスク達成によりトドのキャラクターを育成できるアプリです。習慣化を楽しくするためのツールとして、ユーザーのタスク管理をサポートします。

### ■ このサービスへの思い・作りたい理由
どんなアプリを作ろうか、と思案している最中にふと”ToDo”がローマ字読みだと”トド”であることに気づいたのが始まりです。アプリを起動すると愛らしいトドのマスコットキャラクターが出迎えてくれる、そんな光景が考える間もなく頭に浮かびました。それをただ頭の中に留めておくなんてもったいない！

### ■ ユーザー層について
- 学生・主婦・社会人

    日常的にタスク管理を活用する層を広く想定しています。

### ■サービスの利用イメージ
ユーザーはアプリに日々のタスクを登録し、達成するごとにトドのキャラクターにエサや育成アイテムを与えていきます。それを継続することでトドが成長し、ユーザーは視覚的な達成感を得ることができます。

### ■ ユーザーの獲得について
SNSでの告知

### ■ サービスの差別化ポイント・推しポイント
### トド育成機能

タスクを達成することでトドを育成することができ、ユーザーのモチベーション維持が期待できます

### トドを介したユーザー交流機能
成長したトドに育成アイテムを持たせ任意で旅に送り出すことができます。送り出したトドはランダムな他のユーザーの元へ訪れ、育成アイテムをプレゼントします。その際、旅に送り出したユーザーの達成したタスクを紹介することで、他ユーザーのモチベーションアップを期待します。タスクの公開非公開は設定可能です。

### トドのご飯を通じて頑張りを可視化
こなしたタスクはトドのご飯となり、食事ログとして記録されていきます

### ■ 機能候補
### MVPリリース時に作りたい機能

- ユーザー登録・ログイン機能
- 基本的なToDoリスト機能（タスク追加、編集、削除）
- 「やってみる」機能（他のユーザーのタスクを自分のタスクリストに追加）
- トドのキャラクター表示と育成機能（エサやり、時間帯による会話）
- トドの旅機能（交流要素）
- 通知機能（タスクのリマインド）

### 本リリースまでに作りたい機能
- トドのカスタマイズ機能の強化（アイテム,ガシャ追加）
- トドの会話追加(年中行事、誕生日etc...)
- トドの画像出力・シェア機能
- タスク達成によるポイントシステム

### ■ 機能の実装方針予定
- ベース : Ruby3系, Ruby on Rails7系
- イラスト : 自筆
- CSS : bulma
- 通知機能 ： LINE通知,ActionCable
- 画像関連 : Rmagick
- その他 : ActiveJob

### 画面遷移図
Figma :  https://www.figma.com/design/gLNyfcEhIpuMYfyr3gQJ9w/WithToDo%E7%94%BB%E9%9D%A2%E9%81%B7%E7%A7%BB%E5%9B%B3?node-id=0-1&t=YpODiirdteXdp4ct-1

### チェックリスト
- [x] ユーザー登録・ログイン機能
- [x] 基本的なToDoリスト機能（タスク追加、編集、削除）
- [x] ~~タスク達成によるポイントシステム~~ 「やってみる」機能に変更*1
- [x] トドのキャラクター表示と育成機能（エサやり、時間帯による会話）
- [x] トドの旅機能（交流要素）
- [x] 通知機能（タスクのリマインド）

*1 ポイントのバランス等を考え出すとキリがないので一旦保留にし、別機能で独自性を出す方向にしました

### 未ログインでも閲覧または利用できるページ
- [x] トップページ

### メールアドレス・パスワード変更確認項目
直接変更できるものではなく、一旦メールなどを介して専用のページで変更する画面遷移になっているか？
- [x] メールアドレス
- [x] パスワード

### ER図
![WithToDoER図](https://i.gyazo.com/d4e65423d4ed57b1b942061a6b8e1ed1.png)
gyazo → https://gyazo.com/d4e65423d4ed57b1b942061a6b8e1ed1