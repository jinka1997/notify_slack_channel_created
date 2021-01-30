（今から作っていく）
# slackで新しいチャンネルが作られたのを通知する

## 概要


## 開発環境
- .NET5
- App Service

## 周辺情報

### そもそも何使うの？
必要な Slack API はどれ？ - Slack アプリの作成のためのヒント
https://api.slack.com/lang/ja-jp/which-api

### チャンネル作成時にPOSTされるもの。
Slack Events APIでchannel_created を拾う
https://api.slack.com/apis/connections/events-api


### チャンネル指定でSlackに書き込み
