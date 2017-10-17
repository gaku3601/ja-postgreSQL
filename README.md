[![Docker Automated buil](https://img.shields.io/docker/automated/jrottenberg/ffmpeg.svg)](https://hub.docker.com/r/gaku3601/ja-postgresql/)
# Overview
This repository store Dockerfile that create postgreSQL environmet that was converted to Japanese specifications.

# Supported Tags and Dockerfile links
[`10.0`](https://github.com/gaku3601/ja-postgreSQL/tree/10.0) [Dockerfile](https://github.com/gaku3601/ja-postgreSQL/blob/10.0/Dockerfile)  
[`9.6.5`](https://github.com/gaku3601/ja-postgreSQL/tree/9.6.5) [Dockerfile](https://github.com/gaku3601/ja-postgreSQL/blob/9.6.5/Dockerfile)  

# Usage
Please prepare docker-compose.yml that was writed like following code.
~~~
version: '3'

services:
    db:
        image: gaku3601/ja-postgresql 
~~~
And type the following command and start up docker container.
~~~
docker-compose up -d
~~~

This is the only work, You can get postgreSQL environment that was converted to Japanese specifications.

# 概要
このリポジトリは日本仕様へ設定変更したpostgreSQLを起動するDockerfileを格納したものです。  
docker hubにも登録しておりますので、よければそちらもご参照ください。  
[docker hub](https://hub.docker.com/r/gaku3601/ja-postgresql/)  

# サポートしているタグとDockerfileへのリンク集
[`10.0`](https://github.com/gaku3601/ja-postgreSQL/tree/10.0) [Dockerfile](https://github.com/gaku3601/ja-postgreSQL/blob/10.0/Dockerfile)  
[`9.6.5`](https://github.com/gaku3601/ja-postgreSQL/tree/9.6.5) [Dockerfile](https://github.com/gaku3601/ja-postgreSQL/blob/9.6.5/Dockerfile)  

# 使用方法
以下のようなdocker-compose.ymlを用意します。
~~~
version: '3'

services:
    db:
        image: gaku3601/ja-postgresql 
~~~
dockcer-compose.ymlが用意できたら、いつも通り、以下コマンドでdocker containerを起動するだけです。
~~~
docker-compose up -d
~~~
これだけの作業で簡単に日本仕様のpostgreSQL環境を手に入れることができます。  

# 開発&Issue
コード等に問題ありましたら、Pull requestのほどお待ちしております。  
また、質問等に関してはIssueを上げていただけますと、確認できる範囲で対応致します。
