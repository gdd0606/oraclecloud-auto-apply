# A1 抢机状态

- 更新时间: 2026-10-29 13:59:11 UTC
- 结果: ❌ 本次创建失败，下次重试。错误: Warning: To increase security of your API key located at /home/runner/.oci/oci_api_key.pem, append an extra line with 'OCI_API_KEY' at the end. For more information, refer to https://docs.oracle.com/iaas/Content/API/Concepts/apisigningkey.htm. To suppress the warning, set the env variable SUPPRESS_LABEL_WARNING=True
ServiceError:
{
    "client_version": "Oracle-PythonSDK/2.184.1, Oracle-PythonCLI/3.90.2",
    "code": "TooManyRequests",
    "logging_tips": "Please run the OCI CLI command using --debug flag to find more debug information.",
    "message": "Too many requests for the user",
    "opc-request-id": "6A8AF9F1246B4C6AB7B53975E12029F2/F6E8FD99D5F1D0872F51E36A4B495843/6B4B99CBA2202188B391D329DDBC0AFC",
    "operation_name": "launch_instance",
    "request_endpoint": "POST https://iaas.ap-osaka-1.oraclecloud.com/20160918/instances",
    "status": 429,
    "target_service": "compute",
    "timestamp": "2026-10-29T13:59:11.160089+00:00",
    "troubleshooting_tips": "See [https://docs.oracle.com/iaas/Content/API/References/apierrors.htm] for more information about resolving this error. If you are unable to resolve this issue, run this CLI command with --debug option and contact Oracle support and provide them the full error message."
}
