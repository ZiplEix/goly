# Goly

a simple and fast url shortener written in go to learn Fiber, Gorm and Svelte.

My very first web project, so don't expect too much.

## Installation

```bash
git clone
cd goly
yarn install # or npm install
yarn run dev # or npm run dev
sudo docker run --name auth-psql -e POSTGRES_USER=admin -e POSTGRES_PASSWORD=test -d postgres:14
go run main.go

```