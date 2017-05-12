**URL**：[http://192.168.1.9/api/lawyer](http://192.168.1.9/api/lawyer)

**功能实现**：推送律师信息到数据平台

**支持格式**：JSON

**HTTP请求方式**：POST

**请求参数**

| **参数** | **必选** | **类型及范围** | **说明** |
| :--- | :--- | :--- | :--- |
| CertificateNo | 否 | String | 职业证号 |
| Name | 是 | String | 律师姓名 |
| Firm | 是 | String | 所在律所 |
| CellPhoneNumber | 否 | String | 手机号 |
| ResidentProvinceId | 否 | String | 常驻省Id |
| ResidentCityId | 否 | String | 常驻市Id |
| FromName | 是 | String | 来源名称 例如：老到 |



