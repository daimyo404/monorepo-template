<div id="top"></div>

## 😃 プロダクト名 😃
<!-- プロダクトの説明を記載-->

<!-- シールド一覧 -->
<p style="display: inline">
  <!-- フロントエンドのフレームワーク一覧 -->
  <img src="https://img.shields.io/badge/-React-555.svg?logo=react&style=flat">
  <!-- バックエンドのフレームワーク一覧 -->
  <img src="https://img.shields.io/badge/-Node.js-000000.svg?logo=node.js&style=flat">
  <!-- 言語一覧 -->
  <img src="https://img.shields.io/badge/Javascript-276DC3.svg?logo=javascript&style=flat">
  <img src="https://img.shields.io/badge/-TypeScript-007ACC.svg?logo=typescript&style=flat">
  <!-- ミドルウェア一覧 -->
  <img src="https://img.shields.io/badge/-MySQL-4479A1.svg?logo=mysql&style=flat&logoColor=white">
  <!-- インフラ一覧 -->
  <img src="https://img.shields.io/badge/-terraform-20232A?style=flat&logo=terraform&logoColor=844EBA">
</p>

## 📕 目次

1. [概要](##概要)
2. [環境](##環境)
3. [ディレクトリ構成](##ディレクトリ構成)
4. [開発環境構築](##開発環境構築)
5. [Git運用ルール](##Git運用ルール)
6. [外部ドキュメント](##外部ドキュメント)
7. [トラブルシューティング](#トラブルシューティング)

## 👋 概要
<!-- 言語、フレームワーク、ミドルウェア、インフラの一覧とバージョンを記載 -->

モノレポのテンプレートリポジトリです。

## 💻 環境
<!-- 言語、フレームワーク、ミドルウェア、インフラの一覧とバージョンを記載 -->

| 言語・フレームワーク  | バージョン |
| --------------------- | ---------- |
| Python                | 3.11.4     |
| Django                | 4.2.1      |
| Django Rest Framework | 3.14.0     |
| MySQL                 | 8.0        |
| Node.js               | 16.17.0    |
| React                 | 18.2.0     |
| Next.js               | 13.4.6     |
| Terraform             | 1.3.6      |

## 📂 ディレクトリ構成

<!-- Treeコマンドを使ってディレクトリ構成を記載 -->

❯ tree -a -I "node_modules|.git| static" -L 2
.  
├── .editorconfig  
├── .gitignore  
├── .husky  
│   ├── _  
│   └── commit-msg  
├── .vscode  
│   ├── extensions.json  
│   └── settings.json  
├── README.md  
├── backend  
│   └── package.json  
├── biome.json  
├── commitlint.config.js  
├── frontend  
│   └── package.json  
├── infra  
├── package-lock.json  
└── package.json  

## 💻 開発環境構築
### パッケージのインストール
全ての環境にインストール

```bash
npm install [packageName] -ws
```

特定のワークスペースにインストール
```bash
npm install [パッケージ名] -w [ワークスペース名]
```

## 🌲 Git運用ルール
## 📄 外部ドキュメント