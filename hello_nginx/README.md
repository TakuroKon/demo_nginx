ビルド
docker build -t websrv .
起動
docker run -it --rm -p 8080:80 websrv