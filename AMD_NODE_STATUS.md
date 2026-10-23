# AMD 节点状态

- 更新时间: 2026-10-23 00:58:40 UTC
- 结果: ❌ AMD 实例创建失败。错误: Warning: To increase security of your API key located at /home/runner/.oci/oci_api_key.pem, append an extra line with 'OCI_API_KEY' at the end. For more information, refer to https://docs.oracle.com/iaas/Content/API/Concepts/apisigningkey.htm. To suppress the warning, set the env variable SUPPRESS_LABEL_WARNING=True
Action completed. Waiting until the resource has entered state: ('RUNNING',)
{
  "data": {
    "agent-config": {
      "are-all-plugins-disabled": false,
      "is-management-disabled": false,
      "is-monitoring-disabled": false,
      "plugins-config": null
    },
    "availability-config": {
      "is-live-migration-preferred": null,
      "recovery-action": "RESTORE_INSTANCE"
    },
    "availability-domain": "NfYv:AP-OSAKA-1-AD-1",
    "capacity-reservation-id": null,
    "cluster-placement-group-id": null,
    "compartment-id": "ocid1.tenancy.oc1..aaaaaaaacslhglklrsimu7b3fl4c5j4lqkdbybnn6rgcdn5pqtvsnj25ps3a",
    "dedicated-vm-host-id": null,
    "defined-tags": {},
    "display-name": "AMD-Node-1",
    "extended-metadata": {},
    "fault-domain": "FAULT-DOMAIN-1",
    "freeform-tags": {},
    "id": "ocid1.instance.oc1.ap-osaka-1.anvwsljrsn7dthqcjqgxvzhafaufyc73j2qmwp47bqlnzggh35o5rg4uk37q",
    "image-id": "ocid1.image.oc1.ap-osaka-1.aaaaaaaasbz4b7rawtq65nvs6gfroopawocwyth7w4scs5vhr44md4px6txq",
    "instance-configuration-id": null,
    "instance-options": {
      "are-legacy-imds-endpoints-disabled": false
    },
    "ipxe-script": null,
    "is-ai-enterprise-enabled": null,
    "is-cross-numa-node": false,
    "launch-mode": "PARAVIRTUALIZED",
    "launch-options": {
      "boot-volume-type": "PARAVIRTUALIZED",
      "firmware": "UEFI_64",
      "is-consistent-volume-naming-enabled": true,
      "is-pv-encryption-in-transit-enabled": false,
      "network-type": "PARAVIRTUALIZED",
      "remote-data-volume-type": "PARAVIRTUALIZED"
    },
    "licensing-configs": null,
    "lifecycle-state": "RUNNING",
    "metadata": {
      "ssh_authorized_keys": "ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIEu8ykbciYPcQobEJhcklZ4I/tUcJzS2T81H84LDQIWD hatch\nssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIGhQIAd5dDGhZd85SIWcMUadlYsFsbv5WTrHOmxYsTw1 oracle-vpn-osaka",
      "user_data": "IyEvYmluL2Jhc2gKZXhlYyA+IC92YXIvbG9nL25vZGUtc2V0dXAubG9nIDI+JjEKc2V0IC14ClZFUj0kKGN1cmwgLWZzU0wgaHR0cHM6Ly9hcGkuZ2l0aHViLmNvbS9yZXBvcy9TYWdlck5ldC9zaW5nLWJveC9yZWxlYXNlcy9sYXRlc3QgfCBncmVwIC1vUCAnInRhZ19uYW1lIjogInZcS1teIl0rJyB8IGhlYWQgLTEpCmlmIFsgLW4gIiRWRVIiIF07IHRoZW4KICBjdXJsIC1mc1NMIC1vIC90bXAvc2IudGFyLmd6ICJodHRwczovL2dpdGh1Yi5jb20vU2FnZXJOZXQvc2luZy1ib3gvcmVsZWFzZXMvZG93bmxvYWQvdiR7VkVSfS9zaW5nLWJveC0ke1ZFUn0tbGludXgtYW1kNjQudGFyLmd6IgogIHRhciAteHpmIC90bXAvc2IudGFyLmd6IC1DIC90bXAKICBpbnN0YWxsIC1tIDc1NSAvdG1wL3NpbmctYm94LSovc2luZy1ib3ggL3Vzci9sb2NhbC9iaW4vc2luZy1ib3gKZmkKbWtkaXIgLXAgL2V0Yy9zaW5nLWJveApVVUlEPSQoL3Vzci9sb2NhbC9iaW4vc2luZy1ib3ggZ2VuZXJhdGUgdXVpZCkKS1A9JCgvdXNyL2xvY2FsL2Jpbi9zaW5nLWJveCBnZW5lcmF0ZSByZWFsaXR5LWtleXBhaXIpClBSSVY9JChlY2hvICIkS1AiIHwgYXdrICcvUHJpdmF0ZUtleS97cHJpbnQgJDJ9JykKUFVCPSQoZWNobyAiJEtQIiB8IGF3ayAnL1B1YmxpY0tleS97cHJpbnQgJDJ9JykKU0lEPSQoL3Vzci9sb2NhbC9iaW4vc2luZy1ib3ggZ2VuZXJhdGUgcmFuZCAtLWhleCA4KQpjYXQgPiAvZXRjL3NpbmctYm94L2NvbmZpZy5qc29uIDw8RU9GMgp7CiAgImxvZyI6IHsgImxldmVsIjogImluZm8iIH0sCiAgImluYm91bmRzIjogWwogICAgewogICAgICAidHlwZSI6ICJ2bGVzcyIsCiAgICAgICJ0YWciOiAidmxlc3MtaW4iLAogICAgICAibGlzdGVuIjogIjo6IiwKICAgICAgImxpc3Rlbl9wb3J0IjogNDQzLAogICAgICAidXNlcnMiOiBbIHsgInV1aWQiOiAiJFVVSUQiLCAiZmxvdyI6ICJ4dGxzLXJwcngtdmlzaW9uIiB9IF0sCiAgICAgICJ0bHMiOiB7CiAgICAgICAgImVuYWJsZWQiOiB0cnVlLAogICAgICAgICJzZXJ2ZXJfbmFtZSI6ICJ3d3cubWljcm9zb2Z0LmNvbSIsCiAgICAgICAgInJlYWxpdHkiOiB7CiAgICAgICAgICAiZW5hYmxlZCI6IHRydWUsCiAgICAgICAgICAiaGFuZHNoYWtlIjogeyAic2VydmVyIjogInd3dy5taWNyb3NvZnQuY29tIiwgInNlcnZlcl9wb3J0IjogNDQzIH0sCiAgICAgICAgICAicHJpdmF0ZV9rZXkiOiAiJFBSSVYiLAogICAgICAgICAgInNob3J0X2lkIjogWyAiJFNJRCIgXQogICAgICAgIH0KICAgICAgfQogICAgfQogIF0sCiAgIm91dGJvdW5kcyI6IFsgeyAidHlwZSI6ICJkaXJlY3QiLCAidGFnIjogImRpcmVjdCIgfSBdCn0KRU9GMgovdXNyL2xvY2FsL2Jpbi9zaW5nLWJveCBjaGVjayAtYyAvZXRjL3NpbmctYm94L2NvbmZpZy5qc29uCmNhdCA+IC9ldGMvc3lzdGVtZC9zeXN0ZW0vc2luZy1ib3guc2VydmljZSA8PCdFT0YzJwpbVW5pdF0KRGVzY3JpcHRpb249c2luZy1ib3ggc2VydmljZQpBZnRlcj1uZXR3b3JrLnRhcmdldApbU2VydmljZV0KRXhlY1N0YXJ0PS91c3IvbG9jYWwvYmluL3NpbmctYm94IHJ1biAtYyAvZXRjL3NpbmctYm94L2NvbmZpZy5qc29uClJlc3RhcnQ9b24tZmFpbHVyZQpVc2VyPXJvb3QKW0luc3RhbGxdCldhbnRlZEJ5PW11bHRpLXVzZXIudGFyZ2V0CkVPRjMKc3lzdGVtY3RsIGRhZW1vbi1yZWxvYWQKc3lzdGVtY3RsIGVuYWJsZSAtLW5vdyBzaW5nLWJveApMSU5FPSQoaXB0YWJsZXMgLUwgSU5QVVQgLS1saW5lLW51bWJlcnMgLW4gfCBhd2sgJyQyPT0iUkVKRUNUIntwcmludCAkMTsgZXhpdH0nKQppZiBbIC1uICIkTElORSIgXTsgdGhlbiBpcHRhYmxlcyAtSSBJTlBVVCAiJExJTkUiIC1wIHRjcCAtLWRwb3J0IDQ0MyAtaiBBQ0NFUFQ7IGVsc2UgaXB0YWJsZXMgLUEgSU5QVVQgLXAgdGNwIC0tZHBvcnQgNDQzIC1qIEFDQ0VQVDsgZmkKaWYgY29tbWFuZCAtdiBuZXRmaWx0ZXItcGVyc2lzdGVudCA+L2Rldi9udWxsIDI+JjE7IHRoZW4gbmV0ZmlsdGVyLXBlcnNpc3RlbnQgc2F2ZTsgZmkKUElQPSQoY3VybCAtcyAtSCAiQXV0aG9yaXphdGlvbjogQmVhcmVyIE9yYWNsZSIgaHR0cDovLzE2OS4yNTQuMTY5LjI1NC9vcGMvdjIvdm5pY3MvIHwgcHl0aG9uMyAtYyAiaW1wb3J0IHN5cyxqc29uO3ByaW50KGpzb24ubG9hZChzeXMuc3RkaW4pWzBdWydwdWJsaWNJcCddKSIgMj4vZGV2L251bGwpCkxJTks9InZsZXNzOi8vJHtVVUlEfUAke1BJUH06NDQzP2VuY3J5cHRpb249bm9uZSZzZWN1cml0eT1yZWFsaXR5JnNuaT13d3cubWljcm9zb2Z0LmNvbSZmcD1jaHJvbWUmcGJrPSR7UFVCfSZzaWQ9JHtTSUR9JnR5cGU9dGNwJmZsb3c9eHRscy1ycHJ4LXZpc2lvbiNBTUQtTm9kZS1Pc2FrYSIKZWNobyAiJExJTksiID4gL3Jvb3Qvdmxlc3MtbGluay50eHQKY3AgL3Jvb3Qvdmxlc3MtbGluay50eHQgL2hvbWUvdWJ1bnR1L3ZsZXNzLWxpbmsudHh0CmNob3duIHVidW50dTp1YnVudHUgL2hvbWUvdWJ1bnR1L3ZsZXNzLWxpbmsudHh0CmVjaG8gInNldHVwIGRvbmUiID4gL3Jvb3Qvbm9kZS1zZXR1cC1kb25lLnR4dAo="
    },
    "placement-constraint-details": null,
    "platform-config": null,
    "preemptible-instance-config": null,
    "region": "ap-osaka-1",
    "security-attributes": {},
    "security-attributes-state": "STABLE",
    "shape": "VM.Standard.E2.1.Micro",
    "shape-config": {
      "baseline-ocpu-utilization": null,
      "gpu-description": null,
      "gpus": 0,
      "local-disk-description": null,
      "local-disks": 0,
      "local-disks-total-size-in-gbs": null,
      "local-volume-size-in-gbs": null,
      "max-vnic-attachments": 1,
      "memory-in-gbs": 1.0,
      "networking-bandwidth-in-gbps": 0.48,
      "ocpus": 1.0,
      "processor-description": "2.0 GHz AMD EPYC™ 7551 (Naples)",
      "resource-management": null,
      "vcpus": 2
    },
    "source-details": {
      "boot-volume-size-in-gbs": null,
      "boot-volume-vpus-per-gb": null,
      "image-id": "ocid1.image.oc1.ap-osaka-1.aaaaaaaasbz4b7rawtq65nvs6gfroopawocwyth7w4scs5vhr44md4px6txq",
      "instance-source-image-filter-details": null,
      "kms-key-id": null,
      "source-type": "image"
    },
    "system-tags": {
      "orcl-cloud": {
        "free-tier-retained": "true"
      }
    },
    "time-created": "2026-10-23T00:57:34.693000+00:00",
    "time-maintenance-reboot-due": null
  },
  "etag": "38681ff8ad12958f926a2388ae17a25feb39059f45528768191c785f82aeed3b"
}
