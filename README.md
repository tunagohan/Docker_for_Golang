# DockerでGolangの環境を作る

## 始め方

```
ライブラリの取得
# $ docker-compose run app {ライブラリ名} download
$ docker-compose run app go-wrapper download
```

```
アップ
$ docker-compose up -d
```

```
依存ライブラリの変更
$ docker-compose run app {ライブラリ名} download
```

```
中に入る
$ docker exec -it go_docker bash
```

