# A1 抢机状态

- 更新时间: 2026-11-23 22:51:58 UTC
- 结果: ❌ 本次创建被甲骨文限流（429），已进入退避，退避结束后恢复重试。错误: Warning: To increase security of your API key located at /home/runner/.oci/oci_api_key.pem, append an extra line with 'OCI_API_KEY' at the end. For more information, refer to https://docs.oracle.com/iaas/Content/API/Concepts/apisigningkey.htm. To suppress the warning, set the env variable SUPPRESS_LABEL_WARNING=True
ServiceError:
{
    "client_version": "Oracle-PythonSDK/2.184.1, Oracle-PythonCLI/3.90.2",
    "code": "TooManyRequests",
    "logging_tips": "Please run the OCI CLI command using --debug flag to find more debug information.",
    "message": "Too many requests for the tenant",
    "opc-request-id": "C8DA7EDBA17D40E1829369242447E75F/447D101A3D5C38E08EC3046B4B4958E3/7EA61A5F255C75A5207700F6D9ACDC93",
    "operation_name": "launch_instance",
    "request_endpoint": "POST https://iaas.ap-osaka-1.oraclecloud.com/20160918/instances",
    "status": 429,
    "target_service": "compute",
    "timestamp": "2026-11-23T22:51:58.660161+00:00",
    "troubleshooting_tips": "See [https://docs.oracle.com/iaas/Content/API/References/apierrors.htm] for more information about resolving this error. If you are unable to resolve this issue, run this CLI command with --debug option and contact Oracle support and provide them the full error message."
}
- 退避: 限流退避中：连续第 1 次 429，本次退避至 2026-11-24 08:50（北京时间）后恢复重试，退避期间不向甲骨文发请求
