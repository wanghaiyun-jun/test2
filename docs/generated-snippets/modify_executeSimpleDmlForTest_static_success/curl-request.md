```bash
$ curl 'http://sv-brood-dropship-host:9004/dropship/unitedif/test/modify' -i -X POST \
    -H 'Content-Type: application/json;charset=UTF-8' \
    -H 'Accept: application/json' \
    -d '{"dbName":"mysql-test34","limitCnt":3,"limitEnable":1,"params":{"score":"88","id":"1"},"sqlContent":"update student set score=#{score} where id=#{id}","switchSql":0}'
```