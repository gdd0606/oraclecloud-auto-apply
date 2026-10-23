# OCI 账单诊断（只读）

- 生成时间: 2026-10-23 10:01:29 UTC

## 区域订阅与主区域
- region: ap-osaka-1 home=true status=READY

## 实例清单（全部形态，含已终止以外的全部状态）
- AMD-Node-1 | shape=VM.Standard.E2.1.Micro | state=RUNNING | fd=FAULT-DOMAIN-1 | created=2026-10-23T00:57:34.693000+00:00 | id_tail=4uk37q | free_tier_retained=true
- AMD-Node-1 | shape=VM.Standard.E2.1.Micro | state=TERMINATED | fd=FAULT-DOMAIN-3 | created=2026-10-23T02:35:59.450000+00:00 | id_tail=zgam7a | free_tier_retained=true
- 实例总数: 2

## 启动卷清单（含未挂载的孤儿卷）
- AMD-Node-1 (Boot Volume) | sizeGB=50 | state=AVAILABLE | created=2026-10-23T00:57:39.091000+00:00 | id_tail=bs25lq
- AMD-Node-1 (Boot Volume) | sizeGB=50 | state=TERMINATED | created=2026-10-23T02:36:05.733000+00:00 | id_tail=4tm57a
- 未终止启动卷总容量: 50 GB

## 块存储卷清单

## 最近10天费用（按服务+SKU，每日）
- 费用查询失败或无权限:
ServiceError:
{
    "client_version": "Oracle-PythonSDK/2.184.1, Oracle-PythonCLI/3.90.2",
    "code": "InvalidParameter",
    "logging_tips": "Please run the OCI CLI command using --debug flag to find more debug information.",
    "message": "Passed UTC date does not have the right precision: hours, minutes, seconds, and second fractions must be 0",
    "opc-request-id": "D470EA6DD8E54E4EA2F5308DEDBA6C08/4251B844FDEE7BA17F30DB6A4B495881/D7C1AA1AE5C4FEEBC07653CFCF6CADE2",
    "operation_name": "

## 最近10天费用（按资源汇总）
- 按资源费用查询失败或无权限

（完）
