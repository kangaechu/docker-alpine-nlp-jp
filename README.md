Name
====

Alpine Linuxの自然言語処理パッケージ Dockerfile

## Description

Dockerで日本語の自然言語処理関連ツールを実行するためのDockerfileです。

Docker HubからPullできます。
```
$ docker pull kangaechu/docker-alpine-nlp-jp
```
https://hub.docker.com/r/kangaechu/docker-alpine-nlp-jp/

### 対応しているパッケージ

- [MeCab (+ IPADIC)](http://taku910.github.io/mecab/)
- [Juman](http://nlp.ist.i.kyoto-u.ac.jp/EN/index.php?JUMAN)
- [KNP](http://nlp.ist.i.kyoto-u.ac.jp/?KNP)
- [Juman++](https://github.com/ku-nlp/jumanpp)

## Requirement

Docker

## Usage

以下コマンドを実行します。
イメージが1.5GBくらいあるので時間がかかります。

```bash
$ docker run -it kangaechu/docker-alpine-nlp-jp /bin/sh
```

## Licence

[MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)

## Author

[kangaechu](https://github.com/kangaechu)
