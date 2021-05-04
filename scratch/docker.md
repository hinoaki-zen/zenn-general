## docker-compose for arm64

### ビルド済バイナリ
https://github.com/linuxserver/docker-docker-compose/releases/

### ビルド方法

```bash
git clone https://github.com/docker/compose.git
cd compose
git checkout 1.29.1

sudo ./script/build/linux
```

## ufw と docker -p

docker: -p, docker-compose: ports
docker: --expose, docker-compose: expose

https://qiita.com/jqtype/items/9574ef74868b73323939

