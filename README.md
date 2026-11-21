# Awesome Object Storage

A curated directory of S3-compatible object-storage providers and self-hosted object stores.

## 📑 Table of Contents

- [Decentralized Storage (1)](#decentralized-storage)
- [S3-Compatible Clouds (9)](#s3-compatible-clouds)
- [Self-Hosted Object Storage (8)](#self-hosted-object-storage)
- [Zero-Egress Storage (3)](#zero-egress-storage)


## Decentralized Storage

- [Storj](https://storj.io/) - Storj is a decentralized, S3-compatible object storage network that encrypts and distributes data across independent node operators. It is suitable for backup, media, and cloud-native workloads. Users pay for storage and bandwidth used. ([Read more](/details/storj.md)) `Paid` `API` `Decentralized` `S3-Compatible` `Encryption`

## S3-Compatible Clouds

- [Alibaba Cloud Object Storage Service](https://www.alibabacloud.com/product/object-storage-service) - Alibaba Cloud OSS is an S3-compatible object storage service for large-scale data storage. It offers standard, infrequent access, and archive storage classes. Pricing is based on storage volume, requests, and data transfer. ([Read more](/details/alibaba-cloud-object-storage-service.md)) `Paid` `Enterprise` `API` `S3-Compatible` `Archive`
- [Amazon S3](https://aws.amazon.com/s3) - Amazon Simple Storage Service is a scalable, secure, and highly available cloud object storage service. It supports backup, archiving, big data analytics, and cloud-native applications. Pricing is based on storage used, requests, and data transfer. ([Read more](/details/amazon-s3.md)) `Paid` `Enterprise` `API` `S3-Compatible`
- [Backblaze B2](https://www.backblaze.com/b2) - Backblaze B2 is an S3-compatible cloud storage platform for backup, archiving, and application data. It offers free egress up to a multiple of stored data and competitive per-GB pricing. A free tier includes 10 GB of storage. ([Read more](/details/backblaze-b2.md)) `Free Plan` `Freemium` `API` `Zero-Egress` `S3-Compatible`
- [DigitalOcean Spaces](https://www.digitalocean.com/products/spaces) - DigitalOcean Spaces is an S3-compatible object storage service for developers and small businesses. It includes a built-in CDN and predictable monthly pricing with included storage and transfer. Data is stored across multiple availability zones. ([Read more](/details/digitalocean-spaces.md)) `Paid` `API` `S3-Compatible` `CDN`
- [IBM Cloud Object Storage](https://www.ibm.com/cloud/object-storage) - IBM Cloud Object Storage is an S3-compatible enterprise storage service with regional, cross-regional, and single-site deployment options. It is designed for archives, analytics, and cloud-native applications. Pricing varies by storage class and region. ([Read more](/details/ibm-cloud-object-storage.md)) `Paid` `Enterprise` `API` `S3-Compatible` `Archive`
- [Oracle Cloud Infrastructure Object Storage](https://www.oracle.com/cloud/storage) - Oracle Cloud Infrastructure Object Storage is an S3-compatible internet-scale storage service. It offers standard, infrequent access, and archive tiers with no minimum commitment. Data is encrypted and redundantly stored. ([Read more](/details/oracle-cloud-infrastructure-object-storage.md)) `Paid` `Enterprise` `API` `S3-Compatible` `Archive`
- [Scaleway Object Storage](https://www.scaleway.com/en/object-storage) - Scaleway Object Storage is an S3-compatible object storage service hosted in Europe. It offers a free tier and usage-based pricing for storage and requests. It integrates with Scaleway's cloud ecosystem. ([Read more](/details/scaleway-object-storage.md)) `Free Plan` `Freemium` `API` `S3-Compatible` `European`
- [Tigris](https://tigrisdata.com/) - Tigris is an S3-compatible object storage platform built for developers and edge applications. It offers global replication and strong consistency with a free tier and usage-based pricing. It is managed by Tigris Data. ([Read more](/details/tigris.md)) `Freemium` `API` `S3-Compatible` `Global`
- [Vultr Object Storage](https://www.vultr.com/products/object-storage) - Vultr Object Storage is an S3-compatible object storage service for developers and enterprises. It provides flat-rate pricing with included storage and outbound transfer. Data is stored redundantly across Vultr's infrastructure. ([Read more](/details/vultr-object-storage.md)) `Paid` `API` `S3-Compatible` `Cloud`

## Self-Hosted Object Storage

- [Apache Ozone](https://ozone.apache.org/) - Apache Ozone is an open-source, distributed object store designed for Hadoop and big data workloads. It provides an S3-compatible API and scales to billions of objects. It is licensed under Apache 2.0. ([Read more](/details/apache-ozone.md)) `Open Source` `Self-Hosted` `API` `S3-Compatible` `Big Data`
- [Caringo Swarm](https://www.caringo.com/) - Caringo Swarm is a software-defined object storage platform for private and hybrid cloud deployments. It provides an S3-compatible API and features self-healing storage and policy-driven management. It is offered under commercial licensing. ([Read more](/details/caringo-swarm.md)) `Enterprise` `Self-Hosted` `API` `S3-Compatible` `Hybrid Cloud`
- [Ceph](https://ceph.io/) - Ceph is an open-source software-defined storage platform providing object, block, and file storage in a unified system. Its RADOS Gateway offers an S3-compatible API for object storage. Ceph is released under the GNU LGPL v2.1 license. ([Read more](/details/ceph.md)) `Open Source` `Self-Hosted` `API` `S3-Compatible` `Enterprise`
- [Cloudian HyperStore](https://www.cloudian.com/) - Cloudian HyperStore is an on-premises, S3-compatible object storage platform for enterprise data lakes and archives. It supports geo-replication, tiering, and exabyte-scale deployments. It is sold as commercial software with enterprise support. ([Read more](/details/cloudian-hyperstore.md)) `Enterprise` `Self-Hosted` `API` `S3-Compatible` `On-Premises`
- [Dell EMC ECS](https://www.dell.com/en-us/data-storage/ecs.htm) - Dell EMC ECS is an enterprise-grade, S3-compatible object storage platform for on-premises and hybrid cloud. It supports multi-tenancy, geo-replication, and cloud tiering. It is sold as hardware and software with enterprise support. ([Read more](/details/dell-emc-ecs.md)) `Enterprise` `Self-Hosted` `API` `S3-Compatible` `On-Premises`
- [MinIO](https://min.io/) - MinIO is an open-source, S3-compatible object storage server for self-hosted cloud infrastructure. It supports high-performance workloads, erasure coding, and multi-cloud deployments. It is released under the GNU AGPL v3 license. ([Read more](/details/minio.md)) `Open Source` `Self-Hosted` `API` `S3-Compatible` `Enterprise`
- [OpenStack Swift](https://opendev.org/openstack/swift) - OpenStack Swift is an open-source object storage system for cloud infrastructure. It provides a RESTful API and is designed for scalability and durability. It is part of the OpenStack platform and licensed under Apache 2.0. ([Read more](/details/openstack-swift.md)) `Open Source` `Self-Hosted` `API` `Cloud Infrastructure`
- [SeaweedFS](https://seaweedfs.com/) - SeaweedFS is an open-source distributed storage system for blobs, objects, and files. It offers an S3-compatible API, automatic volume replication, and low-latency access. It is licensed under Apache 2.0. ([Read more](/details/seaweedfs.md)) `Open Source` `Self-Hosted` `API` `S3-Compatible` `Distributed`

## Zero-Egress Storage

- [Cloudflare R2](https://www.cloudflare.com/products/r2) - Cloudflare R2 is an S3-compatible object storage service with no egress fees. It stores data globally and integrates with Cloudflare's network. A free tier is available, with paid usage beyond allowances. ([Read more](/details/cloudflare-r2.md)) `Free Plan` `Freemium` `API` `Zero-Egress` `S3-Compatible`
- [IDrive e2](https://www.idrive.com/e2) - IDrive e2 is an S3-compatible object storage service with zero egress fees. It is designed for backup, cloud storage, and S3 migration scenarios. Plans include a free tier and paid options based on capacity. ([Read more](/details/idrive-e2.md)) `Free Plan` `Freemium` `API` `Zero-Egress` `S3-Compatible`
- [Wasabi](https://wasabi.com/) - Wasabi is an S3-compatible object storage service that charges for storage with no egress or API request fees. It targets backup, archive, and cloud application workloads. Pricing is capacity-based with no hidden charges. ([Read more](/details/wasabi.md)) `Paid` `API` `Zero-Egress` `S3-Compatible`


## ™️ Legal

All product names, logos, and brands are the property of their respective owners. All company, product, and service names used in this repository, related repositories, and associated websites are for identification purposes only. The use of these names, logos, and brands does not imply endorsement, affiliation, or sponsorship.

This work may include content generated by artificial intelligence (AI). While efforts have been made to ensure the accuracy and reliability of the information, we make no representations or warranties of any kind, express or implied, about the completeness, accuracy, reliability, suitability, or availability of the information contained herein. Users are advised to independently verify the information before making decisions based on it.

We disclaim any responsibility for errors, omissions, or inaccuracies in the content, whether generated by humans, AI, or any other means. By using this work, you agree to use it at your own risk and acknowledge that the information provided may not always be current or accurate.

If you believe that your intellectual property rights or other legal rights have been infringed, please contact us immediately at legal@ever.co and we will take appropriate action.

## 🛡️ License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a

[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/

[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png

[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg