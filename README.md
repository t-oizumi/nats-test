##動作方法
 1.docker-compose up
 2.起動したインスタンスそれぞれにログインする。
  docker exec -it ID /bin/bash
 3.subの待ち受けを起動する。
 ./nats-sub <subejct名>
 <subject名は任意の文字列>
 4.pubを実行する
 ./nats-pub <subject名> <message>

