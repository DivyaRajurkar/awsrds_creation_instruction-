# awsrds_creation_instruction
```markdown
# AWS RDS Database Creation Instructions

## RDS MySQL Database Creation (No. 2)
1. Navigate to: `RDS => Database`
2. **Database Name:** mysqlbd  
3. **Tier:** firetier  
4. **Password:** Mypassword  
5. **Private Key:** Yes  
6. **Database Name:** mysqldbbackup: "no"  
7. Click **Create Database**  

---
**common Steps:**
1. Navigate to: `aws => rsd => database => name_mysql_db => Connectivity & security => Security => VPC security groups`
2. Edit inbound rule: Add port no anywhere `0.0.0.0`

## RDS MSSQL Database Creation (No. 4)
1. Navigate to: `RDS => Database`
2. **Database Name:** mssqlbd  
3. **Tier:** firetier  
4. **Password:** Mypassword  
5. **Private Key:** Yes  
6. **Database Name:** Not available as an option  
7. **Backup:** "no"  
8. Click **Create Database**  
```
