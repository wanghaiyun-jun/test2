```bash
$ curl 'http://sv-brood-dropship-host:9004/dropship/unitedif/test/query' -i -X POST \
    -H 'Content-Type: application/json;charset=UTF-8' \
    -H 'Accept: application/json' \
    -d '{"dbName":"mysql-test34","dynamicWhere":[{"ifId":105,"joinCondition":1,"statement":"t1.id=#{id}"},{"ifId":105,"joinCondition":2,"statement":"t1.score=#{score}"}],"limitCnt":3,"limitEnable":1,"mainSql":"select t1.*,t2.no from student t1 left join class t2 on t1.id=t2.no","params":{"score":"96","id":"1"},"sqlContent":"select t1.*,t2.no from student t1 left join class t2 on t1.id=t2.no where 1=1 and t1.id=#{id} and t1.score=#{score}","switchSql":1}'
```