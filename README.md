# Comch
Slackのスラッシュコマンドでチャンネルにメンバーを招待
# Reaｄ
AWS Lamdba上で動くこと前提に書いています
Slackの仕様上、3秒以内にレスポンスを返さないとtimeoutしてしまうので、mainの関数を非同期で呼び出しています。