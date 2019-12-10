```bash
$ echo '{"dbName":"mysql-test34","limitCnt":3,"limitEnable":1,"params":{"id":"1"},"sqlContent":"select id,name,sex,score from student where id=#{id}","switchSql":0}' | http POST 'http://sv-brood-dropship-host:9004/dropship/unitedif/test/query' \
    'Content-Type:application/json;charset=UTF-8' \
    'Accept:application/json'
```