# rds-terraform

## 使用技術
- Amazon RDS
- terraform v0.13.5

## RDS (Relational Database Service)
AWS クラウドでリレーショナルデータベースを簡単にセットアップし、運用し、拡張することのできるウェブサービス。

使用できるRDBMS
- Amazon Aurora  
Amazonが提供しているリレーショナルデータベース。  
MySQLおよびPostgreSQLと互換性がある、クラウド向けのリレーショナルデータベース。  
標準的なMySQLデータベースと比べて最大で5倍、標準的なPostgreSQLデータベースと比べて最大で3倍高速。  
[Amazon Aurora（高性能マネージドリレーショナルデータベース）\| AWS](https://aws.amazon.com/jp/rds/aurora/?aurora-whats-new.sort-by=item.additionalFields.postDateTime&aurora-whats-new.sort-order=desc)
- MySQL
- MariaDB
- PostgreSQL
- Oracle
- Microsoft SQL Server

#### メリット
- 管理が簡単
- スケーラビリティが高い
- 可用性と耐久性が高い
- セキュア
- 高速
- 安価

### Terraform
IaCと呼ばれるAWSやGCPといったインフラをコードで管理することができるツール。  

### 参考
- [Amazon RDS（マネージドリレーショナルデータベース）\| AWS](https://aws.amazon.com/jp/rds/)
- [Amazon RDSってなに？ – Amazon Web Service\(AWS\)導入開発支援](https://www.acrovision.jp/service/aws/?p=316)
- [aws\_db\_instance \| Resources \| hashicorp/aws \| Terraform Registry](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/db_instance)
- [【RDS構築】terraform AWS環境構築 第5回 \- たけログ](https://takelg.com/terraform-aws-rds/)
- [Terraform Aurora MySQL 編 \| 30歳未経験からのITエンジニア](https://www.se-from30.com/aws/terraform-aurora-mesql/)