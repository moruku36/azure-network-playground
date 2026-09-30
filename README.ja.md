# Azure Network Playground

[English](readme.md) | [日本語](README.ja.md)

Connection MonitorでHTTP通信を発生させ、ネットワークの診断ログを共通のLog Analyticsに集約する、BicepベースのAzure検証環境です。


## 主なファイル・資料

- [docs/](docs)
- [modules/](modules)
- [src/](src)

## 詳しい使い方

セットアップ、設定、コマンド例、元プロジェクトの説明は[英語版](readme.md)にまとめています。この日本語版では概要と資料の入口を案内しています。

Connection Monitorで定期的にHTTP通信を発生させ、Hub-Spokeネットワーク上のFirewall、Application Gateway、Load Balancer、VPN、NSG、VMのログを観察します。診断設定と共通Log AnalyticsもBicepで作成します。
