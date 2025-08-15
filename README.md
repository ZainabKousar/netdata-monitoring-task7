Netdata Monitoring Setup

This project involves setting up Netdata on an AWS EC2 instance to monitor system performance in real-time. Netdata provides detailed metrics such as CPU usage, memory utilization, disk space, network activity, and running processes.

Key Details:

Environment: AWS EC2 (2 vCPUs, 3.82 GB RAM, 8 GB Disk, Linux kernel 6.14.0-1010-aws)

Metrics Collected: Over 1,100 metrics including CPU, RAM, disk, network, and plugin-based stats.

Plugins Enabled: System monitoring, cgroups, diskspace, network viewer, and multiple exporters (e.g., OpenMetrics, Graphite).

Database Storage: Ephemeral DB at /var/cache/netdata and permanent DB at /var/lib/netdata.

Access: Netdata dashboard available via web interface for real-time visualization.

Purpose:
To enable live system health tracking, detect anomalies early, and optimize server performance.
