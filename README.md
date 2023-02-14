# 第九回課題

・MyBatisでReadの実装をしてみる。

# 仕様

GETリクエストで以下のテーブルの中身を返す。

| id| name| 
| :---: | :---: | 
| 1 | tanaka | 
| 2 | yamada | 
| 3 | takahashi | 

# 出力結果

![スクリーンショット 2022-12-23 19 48 58 2](https://user-images.githubusercontent.com/118739580/218702990-c4fe9816-0c7a-4384-9367-5e06ae9a7935.jpg)


# Spring Boot設定

Spring Bootの設定にはspring initializrを使用して設定しました。

| Project| Gradle Project| 
| :---: | :---: | 
| Language | Java | 
| Spring Boot | 3.0.0 | 
| packing | Jar | 
| Java | 17 | 

# PC環境

OS macOS 13.1（22C65）

CPU Apple M1

# 開発環境

IntelliJ IDEA

ランタイムバージョン: 17.0.4.1+7-b469.62 aarch64

# 実行環境

JavaSE-17
