# WordPressWithDocker
WordPressが立ち上がるDockerを作る

## Usage
現状、clone後にdocker-compose up -dで起動し
localhostのポート8080に接続するとWordPressサーバー、
ポート3306に接続するとPHPMｙAdmin
が使用できる。
WordPressのファイルはコンテナ起動後に作成されるwww/html内に保存される
