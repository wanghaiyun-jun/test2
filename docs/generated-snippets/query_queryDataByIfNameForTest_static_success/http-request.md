```http
POST /dropship/unitedif/test/query HTTP/1.1
Content-Type: application/json;charset=UTF-8
Accept: application/json
Host: sv-brood-dropship-host:9004
Content-Length: 156

{"dbName":"mysql-test34","limitCnt":3,"limitEnable":1,"params":{"id":"1"},"sqlContent":"select id,name,sex,score from student where id=#{id}","switchSql":0}
```