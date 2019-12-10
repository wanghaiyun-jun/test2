# Dropship Open Service API 文档

## 1、概  要.
本文为Dropship运输机服务对外统一接口API的说明文档。

API的说明包括：
* http-request信息(http-request头信息与报文)
* http-request请求字段
* http-response信息(http-response头信息与报文)
* http-response响应字段
等等。

## 2、通用说明
Dropship响应码(resCd)说明

|  字段   | 类型  | 解释 |
|  ----  | ----  | ----|
| `resCd`  | `String` | 响应码："1": "操作成功";"其他值": 错误 |

## 3、API
### 3.1、统一静态查询接口访问数据请求
#### 3.1.1、统一静态查询接口访问数据请求 接口描述
* http-request信息

[http-request](generated-snippets/query_queryDataByIfName_static_success/http-request.md ':include')

* http-request请求字段

[http-request](generated-snippets/query_queryDataByIfName_static_success/request-fields.md ':include')

* http-response信息

[http-response](generated-snippets/query_queryDataByIfName_static_success/http-response.md ':include')

* http-response响应字段

[http-response](generated-snippets/query_queryDataByIfName_static_success/response-fields.md ':include')

* curl-request示例

[curl-request](generated-snippets/query_queryDataByIfName_static_success/curl-request.md ':include')

* httpie-request示例

[httpie-request](generated-snippets/query_queryDataByIfName_static_success/httpie-request.md ':include')

#### 3.1.2、统一静态查询接口访问数据请求 验证成功时响应报文

* 验证成功场景

返回响应码:"1"。(响应码参考[2、通用说明])

* 响应报文示例

[response-body](generated-snippets/query_queryDataByIfName_static_success/response-body.md ':include')

#### 3.1.3、统一静态查询接口访问数据请求 验证失败时响应报文

* 验证失败场景

返回响应码:"1"以外。(响应码参考[2、通用说明])

* 响应报文示例

[response-body](generated-snippets/queryDataByIfName_static_fail/response-body.md ':include')

### 3.2、统一静态更新接口访问数据请求
#### 3.2.1、统一静态更新接口访问数据请求 接口描述
* http-request信息

[http-request](generated-snippets/modify_executeSimpleDml_static_success/http-request.md ':include')

* http-request请求字段

[http-request](generated-snippets/modify_executeSimpleDml_static_success/request-fields.md ':include')

* http-response信息

[http-response](generated-snippets/modify_executeSimpleDml_static_success/http-response.md ':include')

* http-response响应字段

[http-response](generated-snippets/modify_executeSimpleDml_static_success/response-fields.md ':include')

* curl-request示例

[curl-request](generated-snippets/modify_executeSimpleDml_static_success/curl-request.md ':include')

* httpie-request示例

[httpie-request](generated-snippets/modify_executeSimpleDml_static_success/httpie-request.md ':include')

#### 3.2.2、统一静态更新接口访问数据请求 验证成功时响应报文

* 验证成功场景

返回响应码:"1"。(响应码参考[2、通用说明])

* 响应报文示例

[response-body](generated-snippets/executeSimpleDml_static_fail/response-body.md ':include')

#### 3.2.3、统一静态更新接口访问数据请求 验证失败时响应报文

* 验证失败场景

返回响应码:"1"以外。(响应码参考[2、通用说明])

* 响应报文示例

[response-body](generated-snippets/queryDataByIfName_static_fail/response-body.md ':include')

### 3.3、统一动态查询接口访问数据请求
#### 3.3.1、统一动态查询接口访问数据请求 接口描述
* http-request信息

[http-request](generated-snippets/query_queryDataByIfName_dynamic_success/http-request.md ':include')

* http-request请求字段

[http-request](generated-snippets/query_queryDataByIfName_dynamic_success/request-fields.md ':include')

* http-response信息

[http-response](generated-snippets/query_queryDataByIfName_dynamic_success/http-response.md ':include')

* http-response响应字段

[http-response](generated-snippets/query_queryDataByIfName_dynamic_success/response-fields.md ':include')

* curl-request示例

[curl-request](generated-snippets/query_queryDataByIfName_dynamic_success/curl-request.md ':include')

* httpie-request示例

[httpie-request](generated-snippets/query_queryDataByIfName_dynamic_success/httpie-request.md ':include')

#### 3.3.2、统一动态查询接口访问数据请求 验证成功时响应报文

* 验证成功场景

返回响应码:"1"。(响应码参考[2、通用说明])

* 响应报文示例

[response-body](generated-snippets/query_queryDataByIfName_dynamic_success/response-body.md ':include')

#### 3.3.3、统一动态查询接口访问数据请求 验证失败时响应报文

* 验证失败场景

返回响应码:"1"以外。(响应码参考[2、通用说明])

* 响应报文示例

[response-body](generated-snippets/queryDataByIfName_dynamic_fail/response-body.md ':include')

### 3.4、统一静态查询测试接口访问数据请求
#### 3.4.1、统一静态查询测试接口访问数据请求 接口描述
* http-request信息

[http-request](generated-snippets/query_queryDataByIfNameForTest_static_success/http-request.md ':include')

* http-request请求字段

[http-request](generated-snippets/query_queryDataByIfNameForTest_static_success/request-fields.md ':include')

* http-response信息

[http-response](generated-snippets/query_queryDataByIfNameForTest_static_success/http-response.md ':include')

* http-response响应字段

[http-response](generated-snippets/query_queryDataByIfNameForTest_static_success/response-fields.md ':include')

* curl-request示例

[curl-request](generated-snippets/query_queryDataByIfNameForTest_static_success/curl-request.md ':include')

* httpie-request示例

[httpie-request](generated-snippets/query_queryDataByIfNameForTest_static_success/httpie-request.md ':include')

#### 3.4.2、统一静态查询测试接口访问数据请求 验证成功时响应报文

* 验证成功场景

返回响应码:"1"。(响应码参考[2、通用说明])

* 响应报文示例

[response-body](generated-snippets/query_queryDataByIfNameForTest_static_success/response-body.md ':include')

#### 3.4.3、统一静态查询测试接口访问数据请求 验证失败时响应报文

* 验证失败场景

返回响应码:"1"以外。(响应码参考[2、通用说明])

* 响应报文示例

[response-body](generated-snippets/query_queryDataByIfNameForTest_static_fail/response-body.md ':include')

### 3.5、统一静态更新测试接口访问数据请求
#### 3.5.1、统一静态更新测试接口访问数据请求 接口描述
* http-request信息

[http-request](generated-snippets/modify_executeSimpleDmlForTest_static_success/http-request.md ':include')

* http-request请求字段

[http-request](generated-snippets/modify_executeSimpleDmlForTest_static_success/request-fields.md ':include')

* http-response信息

[http-response](generated-snippets/modify_executeSimpleDmlForTest_static_success/http-response.md ':include')

* http-response响应字段

[http-response](generated-snippets/modify_executeSimpleDmlForTest_static_success/response-fields.md ':include')

* curl-request示例

[curl-request](generated-snippets/modify_executeSimpleDmlForTest_static_success/curl-request.md ':include')

* httpie-request示例

[httpie-request](generated-snippets/modify_executeSimpleDmlForTest_static_success/httpie-request.md ':include')

#### 3.5.2、统一静态更新测试接口访问数据请求 验证成功时响应报文

* 验证成功场景

返回响应码:"1"。(响应码参考[2、通用说明])

* 响应报文示例

[response-body](generated-snippets/modify_executeSimpleDmlForTest_static_success/response-body.md ':include')

#### 3.5.3、统一静态更新测试接口访问数据请求 验证失败时响应报文

* 验证失败场景

返回响应码:"1"以外。(响应码参考[2、通用说明])

* 响应报文示例

[response-body](generated-snippets/modify_executeSimpleDmlForTest_static_fail/response-body.md ':include')

### 3.6、统一动态查询测试接口访问数据请求
#### 3.6.1、统一动态查询测试接口访问数据请求 接口描述
* http-request信息

[http-request](generated-snippets/query_queryDataByIfNameForTest_dynamic_success/http-request.md ':include')

* http-request请求字段

[http-request](generated-snippets/query_queryDataByIfNameForTest_dynamic_success/request-fields.md ':include')

* http-response信息

[http-response](generated-snippets/query_queryDataByIfNameForTest_dynamic_success/http-response.md ':include')

* http-response响应字段

[http-response](generated-snippets/query_queryDataByIfNameForTest_dynamic_success/response-fields.md ':include')

* curl-request示例

[curl-request](generated-snippets/query_queryDataByIfNameForTest_dynamic_success/curl-request.md ':include')

* httpie-request示例

[httpie-request](generated-snippets/query_queryDataByIfNameForTest_dynamic_success/httpie-request.md ':include')

#### 3.6.2、统一动态查询测试接口访问数据请求 验证成功时响应报文

* 验证成功场景

返回响应码:"1"。(响应码参考[2、通用说明])

* 响应报文示例

[response-body](generated-snippets/query_queryDataByIfNameForTest_dynamic_success/response-body.md ':include')

#### 3.6.3、统一动态查询测试接口访问数据请求 验证失败时响应报文

* 验证失败场景

返回响应码:"1"以外。(响应码参考[2、通用说明])

* 响应报文示例

[response-body](generated-snippets/query_queryDataByIfNameForTest_dynamic_fail/response-body.md ':include')








