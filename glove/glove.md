## 网络配置

设置网络：
Netplan 是 Ubuntu 和其他基于 Debian 的 Linux 发行版上用于管理网络配置的工具。它通过 YAML 文件配置网络，然后使用 systemd-networkd 或 NetworkManager 应用这些配置。
修改 `sudo nano /etc/netplan/50-cloud-init.yaml`
保存并应用设置：`sudo netplan apply`
如果保存前想测试一下，输入：`sudo netplan try`