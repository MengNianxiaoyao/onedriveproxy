# onedriveproxy

# 说明
使用cloudflare workers，代理onedrive的下载流量。

## 环境变量

| 变量名 | 说明 |
| --- | --- |
| `addres` | onedrive的下载地址，形如xxx-my.sharepoint.com |
| `addresTW` | onedrive的下载地址，形如xxx-my.sharepoint.com |
| `addresHK` | onedrive的下载地址，形如xxx-my.sharepoint.com |
| `addresFR` | onedrive的下载地址，形如xxx-my.sharepoint.com |
| `blockedRegion` | 区域黑名单 |
| `blockedIPAddress` | IP地址黑名单 |
