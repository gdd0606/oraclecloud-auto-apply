# A1 抢机状态

- 更新时间: 2026-11-21 05:48:11 UTC
- 结果: ❌ 本次创建被甲骨文限流（429），已进入退避，退避结束后恢复重试。错误: Warning: To increase security of your API key located at /home/runner/.oci/oci_api_key.pem, append an extra line with 'OCI_API_KEY' at the end. For more information, refer to https://docs.oracle.com/iaas/Content/API/Concepts/apisigningkey.htm. To suppress the warning, set the env variable SUPPRESS_LABEL_WARNING=True
ServiceError:
{
    "client_version": "Oracle-PythonSDK/2.184.1, Oracle-PythonCLI/3.90.2",
    "code": "TooManyRequests",
    "logging_tips": "Please run the OCI CLI command using --debug flag to find more debug information.",
    "message": "Too many requests for the tenant",
    "opc-request-id": "CDA42DDC778F4BFFA174FFC7D2C77B8A/083E2CE0038C5FF59B30016B4B4958E8/95F84DDF445766B1BD0F7A0961F5C2E7",
    "operation_name": "launch_instance",
    "request_endpoint": "POST https://iaas.ap-osaka-1.oraclecloud.com/20160918/instances",
    "status": 429,
    "target_service": "compute",
    "timestamp": "2026-11-21T05:48:11.353399+00:00",
    "troubleshooting_tips": "See [https://docs.oracle.com/iaas/Content/API/References/apierrors.htm] for more information about resolving this error. If you are unable to resolve this issue, run this CLI command with --debug option and contact Oracle support and provide them the full error message."
}
- 退避: 限流退避中：连续第 1 次 429，本次退避至 2026-11-21 15:46（北京时间）后恢复重试，退避期间不向甲骨文发请求
