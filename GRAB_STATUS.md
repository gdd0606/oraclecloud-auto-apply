# A1 抢机状态

- 更新时间: 2026-10-23 07:09:06 UTC
- 结果: ❌ 本次创建失败，下次重试。错误: Warning: To increase security of your API key located at /home/runner/.oci/oci_api_key.pem, append an extra line with 'OCI_API_KEY' at the end. For more information, refer to https://docs.oracle.com/iaas/Content/API/Concepts/apisigningkey.htm. To suppress the warning, set the env variable SUPPRESS_LABEL_WARNING=True
ServiceError:
{
    "client_version": "Oracle-PythonSDK/2.184.1, Oracle-PythonCLI/3.90.2",
    "code": "QuotaExceeded",
    "logging_tips": "Please run the OCI CLI command using --debug flag to find more debug information.",
    "message": "bootVolumeQuota Service limit reached.",
    "opc-request-id": "6FD27305EC7B4AC8A26079AEFBDCA4A0/E5C68BB5EB715E611208DB6A4B49585B/4E5E86A216421410C4DCA1E0368CB3CA",
    "operation_name": "launch_instance",
    "request_endpoint": "POST https://iaas.ap-osaka-1.oraclecloud.com/20160918/instances",
    "status": 400,
    "target_service": "compute",
    "timestamp": "2026-10-23T07:09:06.488890+00:00",
    "troubleshooting_tips": "See [https://docs.oracle.com/iaas/Content/API/References/apierrors.htm] for more information about resolving this error. If you are unable to resolve this issue, run this CLI command with --debug option and contact Oracle support and provide them the full error message."
}
