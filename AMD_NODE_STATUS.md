# AMD 节点状态

- 更新时间: 2026-10-23 05:53:57 UTC
- 结果: ❌ AMD 实例创建失败。错误: ServiceError:
{
    "client_version": "Oracle-PythonSDK/2.184.1, Oracle-PythonCLI/3.90.2",
    "code": "LimitExceeded",
    "logging_tips": "Please run the OCI CLI command using --debug flag to find more debug information.",
    "message": "The following service limits were exceeded: standard-e2-micro-core-count. You can request a service limit increase from the Console's Limits, Quotas and Usage page or from the Help menu.",
    "opc-request-id": "56B219527E8D459B854BCB5407B8AA67/50F7332E0EFE393C73F6DA6A4B49586E/10828AD9AF37FAD7CC17E6E40C89745D",
    "operation_name": "launch_instance",
    "request_endpoint": "POST https://iaas.ap-osaka-1.oraclecloud.com/20160918/instances",
    "status": 400,
    "target_service": "compute",
    "timestamp": "2026-10-23T05:53:56.853361+00:00",
    "troubleshooting_tips": "See [https://docs.oracle.com/iaas/Content/API/References/apierrors.htm] for more information about resolving this error. If you are unable to resolve this issue, run this CLI command with --debug option and contact Oracle support and provide them the full error message."
}
