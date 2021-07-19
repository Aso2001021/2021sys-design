```uml

@startuml
ユーザー -> webサーバー :
webサーバー -> DBサーバー :
DBサーバー -> DBサーバー :
DBサーバー -> webサーバー :
webサーバー -> ユーザー :
