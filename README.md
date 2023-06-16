# Mitre ATT&CK® Mappings for Amazon GuardDuty
Amazon GuardDuty 是一项安全监控服务，用于分析和处理基础数据来源，例如Amazon CloudTrail管理事件、Amazon CloudTrail事件日志、VPC 流日志和 DNS 日志。它还处理 Kubernetes 审计日志、RDS 登录活动、S3 日志、EBS 卷和运行时监控等功能。简而言之就是针对云的一系列监控并告警，该项目通过对其告警进行ATT&CK进行对应，可以帮助我们应对云相关威胁。有些告警会跨越多个类别，只采取最有可能存在的情况，帮助我们判别其行为，以上结果仅代表个人对其理解。

Amazon GuardDuty is a security monitoring service that analyzes and processes underlying data sources such as Amazon CloudTrail Management events, Amazon CloudTrail Event logs, VPC flow logs, and DNS logs. It also handles functions such as Kubernetes audit logs, RDS login activity, S3 logs, EBS volumes, and runtime monitoring. In short, it is a series of monitoring and alarm for the cloud. This project can help us deal with cloud-related threats by ATT&CK corresponding to its alarms. Some alarms span multiple categories and take only the most likely cases to help us identify their behavior, and the results above represent only an individual's understanding of them.

截止2023年6月1日，GuardDuty总共有155条。

As of Jun 1, 2023, there are 155 unique GuardDuty Findings.

# 参考链接
https://github.com/amrandazz/attack-guardduty-navigator
https://docs.amazonaws.cn/guardduty/latest/ug/guardduty_finding-types-active.html
https://attack.mitre.org/techniques/enterprise/

