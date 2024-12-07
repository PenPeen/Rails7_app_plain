# Setup

## Clone Repository

`git clone git@github.com:PenPeen/Rails7_app_plain.git`

## Start App

`docker-compose up -d`

## Create DB

`docker-compose exec web /bin/bash`

コンテナ内で以下実行
`rails db:setup`
