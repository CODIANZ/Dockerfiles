# Dockerfiles

## 概要

VSCodeの「[Remote-Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)」を使用して開発環境を構築するためのDockerfile置き場です。

## 使用方法

### C++

「[C++の開発環境をDockerで構築してVSCodeでリモート開発](https://qiita.com/terukazu/items/93a7362d501dd1d4a401)」を参照してください。

### Node.js
「[VSCode + Docker でフロントエンドの開発環境構築](https://qiita.com/terukazu/items/b78afe75fe6b2c918604)」を参照してください。

## dockerhub

* [nodejs](https://hub.docker.com/repository/docker/codianz/nodejs)
  * codianz/nodejs:14.16.0

### コマンドメモ

```sh
docker build -t codianz/XXXX:a.b.c .
```