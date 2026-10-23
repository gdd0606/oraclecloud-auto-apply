# A1 抢机状态

- 更新时间: 2026-10-23 01:46:25 UTC
- 结果: ❌ 本次创建失败，下次重试。错误: Warning: To increase security of your API key located at /home/runner/.oci/oci_api_key.pem, append an extra line with 'OCI_API_KEY' at the end. For more information, refer to https://docs.oracle.com/iaas/Content/API/Concepts/apisigningkey.htm. To suppress the warning, set the env variable SUPPRESS_LABEL_WARNING=True
ServiceError:
{
    "client_version": "Oracle-PythonSDK/2.184.1, Oracle-PythonCLI/3.90.2",
    "code": "QuotaExceeded",
    "logging_tips": "Please run the OCI CLI command using --debug flag to find more debug information.",
    "message": "bootVolumeQuota Service limit reached.",
    "opc-request-id": "7C97EDB33E2D4797B556AFC91F7E8568/6D624319608742AD70BCDA6A4B49589F/F8F8BB0436F1E413BA7EFF1DA475A7A6",
    "operation_name": "launch_instance",
    "request_endpoint": "POST https://iaas.ap-osaka-1.oraclecloud.com/20160918/instances",
    "status": 400,
    "target_service": "compute",
    "timestamp": "2026-10-23T01:46:25.265488+00:00",
    "troubleshooting_tips": "See [https://docs.oracle.com/iaas/Content/API/References/apierrors.htm] for more information about resolving this error. If you are unable to resolve this issue, run this CLI command with --debug option and contact Oracle support and provide them the full error message."
}
