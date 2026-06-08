## Topics Covered

### 1. Azure Storage Redundancy
Azure protects data by replicating it using different redundancy options:

- **LRS (Locally Redundant Storage)**: Stores 3 copies of data within a single datacenter. Protects against hardware failures.
- **ZRS (Zone-Redundant Storage)**: Replicates data across multiple availability zones within a region.
- **GRS (Geo-Redundant Storage)**: Replicates data to a secondary region for disaster recovery.
- **GZRS (Geo-Zone Redundant Storage)**: Combines zone and geo replication for maximum durability.
- **RA-GRS / RA-GZRS**: Allows read access from the secondary region.

Key takeaway:  
Storage redundancy determines how resilient data is against failures at hardware, datacenter, zone, or regional level.

---

### 2. Azure Storage Services
core Azure Storage services and their use cases:

- **Blob Storage**: Stores unstructured data like images, videos, backups, and logs.
- **File Storage**: Managed file shares accessible via SMB/NFS.
- **Queue Storage**: Messaging system for asynchronous communication between applications.
- **Disk Storage**: Block storage used by Azure Virtual Machines.
- **Table Storage**: NoSQL key-value storage for structured data.

Key takeaway:  
Azure Storage is highly scalable, secure, and supports different data types depending on application needs.

---

### 3. Azure Virtual Networking
Azure Virtual Networks (VNets) provide secure communication between resources.

Key concepts:
- VNets allow isolation and segmentation of resources.
- Subnets divide a VNet into smaller network segments.
- Public endpoints allow internet access, while private endpoints restrict access within the network.
- Azure supports communication between:
  - Azure resources
  - On-premises networks (VPN/ExpressRoute)
  - Internet (via public IP or load balancer)

Network security features:
- Network Security Groups (NSGs) control inbound and outbound traffic.
- Route tables and user-defined routes control traffic flow.
- Virtual network peering allows communication between VNets.

Key takeaway:  
Azure networking is designed around secure segmentation and controlled communication between resources.

---

## Security Understanding

- Data must be protected based on sensitivity and availability requirements.
- Network segmentation reduces attack surface.
- Private access should be preferred over public exposure.
- Redundancy improves disaster recovery and availability.

---

## Key Skills Learned

- Understanding Azure storage architecture and redundancy models
- Differentiating between Azure storage services and their use cases
- Designing secure virtual network architectures
- Applying basic cloud security principles such as:
  - Least privilege
  - Network isolation
  - Defense in depth

---

## Reflection

Today I strengthened my understanding of how Azure handles data storage resilience and secure networking. I now understand how cloud systems are designed to ensure availability, durability, and security using redundancy, segmentation, and controlled access.
