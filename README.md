# auth-app-practice

## 概要
COACHTECH 教材 Tutorial 10-1「認証機能 ハンズオン演習」で作成した成果物です。
Laravel Fortifyを利用して、ユーザー登録・ログイン・ログアウト機能を実装しました。

## 使用技術
- PHP 8.x
- Laravel 10.x
- Laravel Fortify（認証）
- MySQL
- Blade
- Laravel Sail
- GitHub

## 学んだこと
- Laravel Fortifyを利用したユーザー登録・ログイン・ログアウト機能の実装方法を学びました。
- 
- 

## 動作確認
 
  ### 環境構築について
  - ブラウザで http://localhost にアクセスし、Laravelのウェルカムページが表示されることを確認しました。

  ### Fortifyを使った認証機能について
  - ブラウザで http://localhost/register にアクセスし、以下の動作確認を行いました。
    - /registerでユーザー登録ができる。
    - /loginでログインができる。
    - ユーザー登録後、ダッシュボードにリダイレクトされる。
    - 未ログインで/dashboardにアクセスするとログインページにリダイレクトされる。
    - ダッシュボードにユーザー名が表示される。
    - ログアウト後、ウェルカムページにリダイレクトされる。