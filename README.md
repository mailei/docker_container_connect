# docker_container_connect
- mysqlとphpmyadminとubuntuのcomposeファイル
- docker networkの動作を検証するための目的で作成。
- 初回phpmyadminはDBのUser権限エラーが発生するため、mysqlに直接ログインし、grantで権限付与
- 参考
  - https://gist.github.com/tamanobi/cfef34197d531945872173fcb0906cf5
