# Docker Image のビルド
$ docker build -t docker-puppeteer .

# スクリプトの実行
$ docker run --rm -v $(pwd):/tmp -w /tmp docker-puppeteer
