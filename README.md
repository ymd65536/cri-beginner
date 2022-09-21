# cri-beginner

cri-toolsを使ってみる

## インストール方法

### brew install でインストール

[Homebrew Formulae](https://formulae.brew.sh/formula/cri-tools)

```bash
brew install cri-tools
```

### GiHub のリリースページからインストール

[cri-tools](https://github.com/kubernetes-sigs/cri-tools/releases)

## コマンド一覧 - dockerコマンドとの対応表

|docker|crictl|説明|
|:---|:---|:---|
|docker pull|crictl pull|コンテナイメージの取得|
|docker images|crictl images|コンテナイメージの一覧|
|docker rmi|crictl rmi|イメージの削除|
|docker image inspecti|crictl inspecti|イメージの情報を取得|
|docker create|crictl create|コンテナの作成|
|docker run|crictl run|コンテナの実行|
|docker ps|crictl ps|コンテナの一覧|
|docker inspect|crictl inspect|コンテナの詳細を表示|
|docker stats|crictl stats|コンテナのリソース消費状態を表示|
|docker attach|crictl attach|コンテナにコンソール状態をアタッチ|
|docker exec|crictl exec|コンテナでプロセスを実行|
|docker logs|crictl logs|コンテナのログを表示|
|docker rm|crictl rm|コンテナを削除|
|docker stop|crictl stop|コンテナの停止|
|docker start|crictl start|コンテナの開始|
|docker update|crictl update|コンテナの更新|
|-|crictl runp|Podの実行|
|-|crictl rmp|Podの削除|
|-|crictl inspectp|Podの情報を表示|
|-|crictl stopp|Podの停止|
|-|crictl port-forard|Podのポートフォワード|
