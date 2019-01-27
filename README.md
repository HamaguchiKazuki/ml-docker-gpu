# ml-docker-gpu
docker-composeで機械学習環境構築

- ```docker_install.sh```でdockerを入れる
- ```nvidia_docker2_install```でnvidia-docker2を入れる
- ```cd docker_setting && docker-compose build && docker-compose up```で起動
- ```jupyter```のトークンを利用してログイン URL: http://127.0.0.1:8888
- ソースコードは```ml_docker_gpu/docker_setting/src```に入れとくと共有される

