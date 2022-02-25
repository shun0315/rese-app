# Rese-app

飲食店予約アプリケーションです。飲食店の検索・お気に入り・予約等の機能を備えております。ユーザーの他に店舗オーナーや、管理者のアカウントも用意されています。
<img width="1336" alt="スクリーンショット 2022-02-23 10 39 39" src="https://user-images.githubusercontent.com/91045911/155640873-ec5c001a-18c0-4247-8071-dcda3079319e.png">

## アプリケーション URL

https://rese-app-shun.herokuapp.com/rese/home

## 機能一覧

ユーザー

-   会員登録（メール認証有り）
-   店舗の検索（エリア・ジャンル・店舗名）
-   店舗のお気に入り登録
-   店舗の予約（追加・変更・キャンセル）
-   店舗の評価・口コミ投稿
-   スマホ・タブレット画面での予約情報の QR コード表示
-   Stripe を利用した事前決済機能

店舗オーナー

-   ユーザーの予約一覧確認
-   店舗情報の確認・変更

管理者

-   ユーザーの一覧確認
-   店舗の一覧確認
-   店舗オーナーの一覧確認
-   店舗オーナーの新規登録
-   ユーザーとオーナーに対してのメール送信

その他

-   レスポンシブ対応（スマートフォン・タブレット・PC）
-   リアルタイムフォームバリデーション
-   マルチログイン機能（ユーザー・店舗オーナー・管理者）
-   予約当日に自動リマインドメール通知

## 使用技術

フロントエンド

-   HTML/CSS
-   JavaScript
-   Vue.js 2.6.14

バックエンド

-   PHP 8.0.14
-   Laravel 8.78.0
-   Mysql 5.7.34

インフラ

-   Heroku
-   Heroku PostgresSQL
-   Docker：ローカル環境のみ対応（https://github.com/shun0315/rese-app-docker）

## ER 図

![rese drawio](https://user-images.githubusercontent.com/91045911/155051780-a16c63d9-a6ec-4251-b37d-eae97ed56da5.png)
