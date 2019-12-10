```http
POST /dropship/unitedif/test/modify HTTP/1.1
Content-Type: application/json;charset=UTF-8
Accept: application/json
Host: sv-brood-dropship-host:9004
Content-Length: 165

{"dbName":"mysql-test34","limitCnt":3,"limitEnable":1,"params":{"score":"88","id":"1"},"sqlContent":"update student set score=#{score} where id=#{id}","switchSql":0}
```