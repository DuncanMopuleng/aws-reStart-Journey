# Storage Notes
Storage in computing is defined as place to store data so that it can later be used to make information and make real life decision. Storage holds files, programs and data(information) permanently and temporarily. Data can be permanently stored in storage devices such as HDDS, Flash drives, CDS and etc, it can be stored temporarily on devices such as RAM. As the computing changes, people started adopted more advanced services such as the cloud for security and accessibily such as Dropbox, Onedrive, Google drive, Amazon S3 etc. **The course focuses more Amazon S3 storage**

## Introduction & Definition

**Amazon S3:** is defined as scalable, durable, secure object storage in the cloud. Stores objects (files) in buckets (containers).

### Features
- Highly durable (99.999999999%).
- Scalable, secure, cost-effective.
- Supports versioning, lifecycle policies, replication, and encryption.

## Types of Storage
- S3: Object storage
- EBS: Block storage for EC2
- EFS: Network file system

## Use Cases
- Backup & restore
- Big data analytics
- Static website hosting
- Archival storage
- Media storage & content delivery file access across instances

| Class                       | Purpose                      |
| --------------------------- | ---------------------------- |
| **S3 Standard**             | Frequently accessed data     |
| **S3 Intelligent-Tiering**  | Automatic cost optimization  |
| **S3 Standard-IA**          | Infrequent access            |
| **S3 One Zone-IA**          | Infrequent access, single AZ |
| **S3 Glacier**              | Archival, low cost           |
| **S3 Glacier Deep Archive** | Long-term archival           |

## Shared Responsibility Model

**AWS:** Infrastructure, durability, availability.

**Customer:** Data, access control, encryption, backups, and lifecycle management.


## AWS allows two ways to store data, EBS and EFS.
Below is short precise notes of the above services AWS

**Definition:** Persistent block storage for EC2 instances.

**Volume types:** Different kinds of storage optimized for performance and cost.

General Purpose SSD (gp3/gp2) → Balanced performance.
Provisioned IOPS SSD (io2/io1) → High-performance for databases.
Throughput Optimized HDD (st1) → Big, sequential workloads.
Cold HDD (sc1) → Infrequent access, low cost.
EBS Snapshots: Point-in-time backup stored in S3, can restore volumes.

### EC2 Instance Store

- Temporary storage physically attached to host.
- Data lost if instance stops/terminates.
- High-performance, low-latency.

## Amazon EFS (Elastic File System)

- Managed network file system.
- Accessible by multiple EC2 instances.
- Automatically scales storage.

### Amazon FSx

**FSx for Windows File Server →** Managed Windows file storage, supports SMB protocol.

**FSx for Lustre →** High-performance storage for compute-intensive workloads (like HPC).

### Shared Responsibility Model for EC2 Storage

**AWS:** Manages underlying infrastructure, hardware, and replication.
**Customer:** Manages data, encryption, backups, and access control.

### Summary

**EBS →** Persistent block storage

**Instance Store →** Temporary local storage

**EFS →** Shared scalable file storage

**FSx →** Managed specialized file systems

Snapshots & backups → Customer’s responsibility

### Reflection
Storage is an important topic, Amazon shows how technology has advanced to ensure that people or organisations are provided with better flexible, reliable cloud storage, and storage classes that let users optimize cost, improve on accessibility, and more importantly their ensuring their information is durable. 
