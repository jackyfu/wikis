# game_server

## 配置 app.conf.php

	日志路劲
	mogoDB
	redis
	mysql


## tools 目录下初始化数据
### autoload.php  

	php gen_autoload.php

### 初始化data目录下的数据

	php gen_data.php



## 监控
### 错误日志

	mkdir -p /data/zhanguo_app/dev/logs
	mkdir game_server
	mkdir front_server
	chmod -R 777 /data/zhanguo_app/dev/logs

	tail -f /data/zhanguo_app/dev/logs/game_server/game_server/game_2017_12_18.log


### workers 目录下的监控
#### work.php

#### continuous_login_activity_reconup.php


#### delete_track_log.php



#### track_log.php


#### verify_receipt.php









