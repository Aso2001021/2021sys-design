```uml

@startuml
ユーザー -> webサーバー :商品情報入力
webサーバー -> DBサーバー :情報処理
DBサーバー -> DBサーバー :csv処理
DBサーバー -> webサーバー :csv処理
webサーバー -> ユーザー :csv出力
