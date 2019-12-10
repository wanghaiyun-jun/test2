```bash
$ echo '{"dbName":"mysql-test34","limitCnt":3,"limitEnable":1,"params":{"score":"88","id":"1"},"sqlContent":"update student set score=#{score} where id=#{id}","switchSql":0}' | http POST 'http://sv-brood-dropship-host:9004/dropship/unitedif/test/modify' \
    'Content-Type:application/json;charset=UTF-8' \
    'Accept:application/json'
```