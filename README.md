# EFK
docker-compose
use dokcer-compose start up es cluster and kibana and fluentd
```
docker-compose up -d 
```
log pattern
```
2019-12-09 18:04:28.107 DEBUG 29793 --- [      Thread-11] o.s.jdbc.core.JdbcTemplate               : Executing SQL query [select stopword, sentiment from `dbw_auto_bmw_dlp`.`auto_stopword`]
2019-12-09 18:04:28.142 DEBUG 29793 --- [      Thread-11] o.s.jdbc.core.JdbcTemplate               : Executing SQL query [select stopword, sentiment from `dbw_auto_benz`.`auto_stopword`]
2019-12-09 18:04:28.321  INFO 29793 --- [           main] o.s.aop.framework.CglibAopProxy          : Final method [public final int cn.com.admaster.dbw.datamanager.CrossCategoryBhtDataManager3.getTeamId()] cannot get proxied via CGLIB: Calls to this method will NOT be routed to the target instance and might lead to NPEs against uninitialized fields in the proxy instance.
```
