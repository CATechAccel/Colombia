

# Colombia
- AnnictAPI(https://developers.annict.jp)
  からアニメ作品の情報をスマホのアプリのようなUIで表示させて自由にお気に入りできるアプリです。


|一覧画面|お気に入り画面|
|:-----:|:--------:|
|<img src="https://user-images.githubusercontent.com/59905087/110882089-c27d8780-8324-11eb-8410-d260c78cb708.png" width="200px"> | <img src="https://user-images.githubusercontent.com/59905087/110882125-d0330d00-8324-11eb-9bc6-d12983799a34.png" width="200px"> |

## Demo
![Videotogif](https://user-images.githubusercontent.com/59905087/110885542-661d6680-832a-11eb-9213-c9d01b855959.gif)

## スケジュール
  - 開発期間: 2/2(火) ~ 2/28(日)

## このアプリの仕様
  - お気に入り機能を作成しそれをローカルのデータベースに保存する
  - お気に入りをしたものを確認/消去できるUIの作成
  - 追加の機能をチームで相談して決める

## 開発ルール
- ツールは基本的に GitHub のものを利用する
  - ドキュメントは Wiki, スケジュール管理は Projects など
- 事前にやることを Issue として作成し Assign をしてから実装に移る
- Pull Request を作成して他のチームメンバー全員に Approve をもらってから Merge する
- ライブラリの導入には CocoaPods を利用する
- ライブラリの導入は事前に21卒に相談を行う(誰か一人にokをもらえばよい)
- ブランチ名は以下のルールに従う
    - プレフィックス/#{Issueの番号}
      - `feature/#{Issueの番号}` 機能作成時に用いる
      - `fix/#{Issueの番号}` 既存の機能の修正時に用いる
- 
