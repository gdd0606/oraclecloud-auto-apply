# A1 抢机状态

- 更新时间: 2026-11-02 02:14:52 UTC
- 结果: ❌ 本次创建失败，下次重试。错误: Warning: To increase security of your API key located at /home/runner/.oci/oci_api_key.pem, append an extra line with 'OCI_API_KEY' at the end. For more information, refer to https://docs.oracle.com/iaas/Content/API/Concepts/apisigningkey.htm. To suppress the warning, set the env variable SUPPRESS_LABEL_WARNING=True
ServiceError:
{
    "client_version": "Oracle-PythonSDK/2.184.1, Oracle-PythonCLI/3.90.2",
    "code": "InternalError",
    "logging_tips": "Please run the OCI CLI command using --debug flag to find more debug information.",
    "message": "Out of host capacity.",
    "opc-request-id": "94476722A80A4FE580FA700502EFEAD7/42E483114A9BCE631BF2E76A4B4958EC/C1D51D812A6074F97269162D5D1FD56B",
    "operation_name": "launch_instance",
    "request_endpoint": "POST https://iaas.ap-osaka-1.oraclecloud.com/20160918/instances",
    "status": 500,
    "target_service": "compute",
    "timestamp": "2026-11-02T02:14:52.271500+00:00",
    "troubleshooting_tips": "See [https://docs.oracle.com/iaas/Content/API/References/apierrors.htm] for more information about resolving this error. If you are unable to resolve this issue, run this CLI command with --debug option and contact Oracle support and provide them the full error message."
}
