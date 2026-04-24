## 2. STORAGE SERVICES

### S3 (Simple Storage Service)
**What:** Object storage for files
**Real-life:** Like Dropbox or Google Drive
**Key Points:**
- Unlimited storage
- 99.999999999% (11 9's) durability
- Objects up to 5TB
- **Memory Trick:** "S3 = Store Stuff Safely"

**Storage Classes (Cheapest to Most Expensive for retrieval):**
1. **S3 Standard:** Frequently accessed data
2. **S3 Intelligent-Tiering:** Auto-moves between tiers
3. **S3 Standard-IA:** Infrequently accessed, cheaper storage
4. **S3 One Zone-IA:** Single AZ, even cheaper
5. **S3 Glacier Instant Retrieval:** Archive, millisecond retrieval
6. **S3 Glacier Flexible Retrieval:** Archive, minutes to hours retrieval
7. **S3 Glacier Deep Archive:** Cheapest, 12+ hours retrieval

**Memory Trick:** "Standard → IA (Infrequent) → Glacier (Ice = Cold storage = Archive)"

### EBS (Elastic Block Store)
**What:** Hard drives for EC2 instances
**Real-life:** Like an external hard drive attached to your computer
**Key Points:**
- Tied to ONE Availability Zone
- Persists independently from EC2 instance
- Can be backed up as snapshots
- **Memory Trick:** "EBS = External Block Storage = Hard drive for EC2"

### EFS (Elastic File System)
**What:** Shared network file system (NFS)
**Real-life:** Like a shared network drive at work
**Key Points:**
- Can be mounted to multiple EC2 instances
- Automatically scales
- Linux only
- **Memory Trick:** "EFS = Everyone's File System = Shared storage"

### Storage Gateway
**What:** Hybrid cloud storage bridge
**Real-life:** Like a bridge connecting your home office to corporate servers
**Key Points:**
- Connects on-premises to AWS storage
- Three types: File, Volume, Tape Gateway

---

[< Compute Services](01-compute-services.md) | [Back to README](README.md) | [Database Services >](03-database-services.md)
