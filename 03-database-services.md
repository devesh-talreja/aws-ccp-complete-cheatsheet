## 3. DATABASE SERVICES

### RDS (Relational Database Service)
**What:** Managed SQL databases
**Real-life:** Like hiring a DBA to manage your database
**Supports:** MySQL, PostgreSQL, MariaDB, Oracle, SQL Server, Aurora
**Key Points:**
- Automated backups, patching, scaling
- Multi-AZ for high availability
- Read Replicas for performance
- **Memory Trick:** "RDS = Really Doesn't Stress you = Managed databases"

### Aurora
**What:** AWS's own high-performance MySQL/PostgreSQL-compatible database
**Key Points:**
- 5x faster than MySQL, 3x faster than PostgreSQL
- Auto-scaling storage (up to 128TB)
- Up to 15 read replicas
- **Memory Trick:** "Aurora = AWS's top-tier RDS option"

### DynamoDB
**What:** Fully managed NoSQL database
**Real-life:** Like a super-fast spreadsheet that scales automatically
**Key Points:**
- Millisecond latency at any scale
- Serverless option available
- Key-value and document data
- **Memory Trick:** "DynamoDB = Dynamic and fast = NoSQL speed"

### Redshift
**What:** Data warehouse for analytics
**Real-life:** Like a giant analytical database for business intelligence
**Key Points:**
- Columnar storage
- Petabyte-scale
- Used with BI tools
- **Memory Trick:** "Redshift = Red for reports = Data warehouse"

### ElastiCache
**What:** In-memory caching service
**Supports:** Redis, Memcached
**Real-life:** Like keeping frequently used items on your desk instead of in a filing cabinet
**Memory Trick:** "ElastiCache = Elastic memory = Super fast temporary storage"

---

---

<p align="center">
  [← prev](02-storage-services.md) | [README](README.md) | [next →](04-networking-content-delivery.md)
</p>
