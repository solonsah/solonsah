## Hi there 👋

# Solomon Nsah

## Senior Linux Infrastructure Engineer

I am a Senior Linux Infrastructure Engineer with 8+ years of experience designing, securing, automating, modernizing, and supporting enterprise Linux infrastructure across physical, virtual, on-premises, and AWS environments.

My work focuses on Red Hat Enterprise Linux, infrastructure automation, security hardening, high availability and clustering, virtualization and platform migrations, cloud infrastructure, monitoring and observability, storage, networking, middleware, and production operations.

I build secure, reliable, repeatable, and well-documented infrastructure solutions with an emphasis on automation, operational consistency, controlled change, validation, and recoverability.

## Technical Skills

- **Operating Systems:** Red Hat Enterprise Linux (RHEL 7/8/9/10), CentOS, AlmaLinux, Amazon Linux, Windows Server
- **Automation & Infrastructure as Code:** Ansible, Terraform, Bash/Shell Scripting, YAML, PowerShell, GitHub Actions
- **Virtualization & Containers:** KVM, QEMU, libvirt, VMware ESXi, vSphere, Microsoft Hyper-V, Proxmox, Docker
- **High Availability & Clustering:** Red Hat High Availability Add-On, Pacemaker, Corosync, HAProxy, Keepalived, Apache HTTPD Clustering, Load Balancing, Service Failover
- **Cloud Platforms:** AWS, Microsoft Azure
- **Linux Administration:** systemd, RPM, YUM/DNF, Cron, LVM, XFS, ext4, NFS, SSH/SCP, firewalld, SELinux, performance tuning, capacity planning
- **Web & Middleware:** Apache HTTP Server, Apache Tomcat, COTS Application Support
- **Databases:** MariaDB, MySQL, PostgreSQL, MongoDB, Oracle Database
- **Monitoring & Observability:** Prometheus, Grafana, Nagios, Datadog, Dynatrace, Elasticsearch, Splunk, AWS CloudWatch, APM
- **Security & Compliance:** DISA STIG, SCAP/OpenSCAP, SELinux, auditd, vulnerability management and remediation, system hardening, IAM, RBAC, SSO, SAML, SSL/TLS
- **Networking:** TCP/IP, DNS, DHCP, IPAM, routing, load balancing, VPN, Security Groups, NACLs
- **DevOps & IT Operations:** Git, GitHub, Jenkins, Bitbucket, Azure DevOps, ServiceNow, Jira, CI/CD, Change Management, CMDB

## Core Technical Skills

### Linux and Systems Administration

* Red Hat Enterprise Linux 7, 8, 9, and 10
* CentOS, AlmaLinux, and Amazon Linux
* System installation, provisioning, configuration, maintenance, and troubleshooting
* Package, kernel, service, process, and lifecycle management
* User, group, permissions, sudo, and SSH administration
* LVM, XFS, ext4, NFS, NAS, SAN, RAID, storage expansion, and filesystem recovery
* DNS, DHCP, IPAM, TCP/IP, routing, firewalld, and network troubleshooting
* Performance tuning, capacity planning, and resource optimization

### Automation and Infrastructure as Code

* Ansible
* Terraform
* Bash/Shell scripting
* YAML
* PowerShell
* Cron and systemd automation
* Automated patching, configuration management, health checks, and reporting
* Repeatable deployment, validation, and rollback workflows

### High Availability and Clustering

* Red Hat High Availability Add-On
* Pacemaker and Corosync
* HAProxy
* Keepalived
* Clustered Apache HTTPD nodes
* Load balancing and service failover
* Cluster node administration and health validation
* High-availability application infrastructure

### Security and Compliance

* DISA Security Technical Implementation Guides (STIG)
* SCAP/OpenSCAP compliance validation
* Vulnerability discovery, analysis, remediation, and validation
* SELinux and auditd
* System hardening and security baselines
* Identity and access management
* Role-based access control
* SSO, SAML, and MFA
* SSL/TLS and certificate management
* Security event analysis and incident response

### Cloud and Virtualization

* Amazon Web Services
* Microsoft Azure
* KVM, QEMU, and libvirt
* VMware ESXi and vSphere
* Microsoft Hyper-V
* Proxmox
* EC2, AMI, EBS, S3, RDS, IAM, VPC, ELB, Route 53, and CloudWatch
* Internet Gateways, NAT, public/private subnets, route tables, Security Groups, and NACLs
* Virtual machine provisioning, migration, backup, and recovery
* Hyper-V to KVM platform migrations

### Application Platforms

* Apache HTTP Server
* Apache Tomcat
* MariaDB and MySQL
* Oracle Database
* Docker
* COTS application support
* Application deployment and upgrades
* SSL/TLS configuration
* Application and middleware troubleshooting

### Monitoring and Reliability

* Prometheus and Grafana
* Nagios
* Datadog
* Dynatrace
* Elasticsearch
* Splunk
* AWS CloudWatch
* Application Performance Monitoring
* Log analysis
* Incident response
* Root-cause analysis
* Performance monitoring and capacity planning
* 24x7 production operations

### Storage, Backup, and Recovery

* LVM, NFS, NAS, SAN, and RAID
* Rubrik
* NetBackup
* GoodSync
* AOMEI Backup & Replication
* Backup validation and recovery
* Storage capacity management
* Disaster-recovery runbooks

## Portfolio Projects

1. Ansible RHEL patching framework
2. Hyper-V to KVM migration framework
3. RHEL security-hardening automation
4. Linux vulnerability-audit toolkit
5. Apache and Tomcat operations
6. Linux observability and incident-response lab
7. AWS hybrid-infrastructure deployment
8. Highly available Linux application-infrastructure lab

## Engineering Approach

I approach infrastructure work using:

* Read-only discovery before making changes
* Development and test validation before production rollout
* Security-conscious automation
* Phased and controlled implementation
* Change control and documented approvals
* Backup and rollback planning
* Post-change infrastructure and application validation
* Root-cause analysis following production incidents
* Clear SOPs, runbooks, implementation plans, and technical documentation

## Professional Focus

I am interested in opportunities including:

* Senior Linux Engineer
* Senior Linux Infrastructure Engineer
* Senior Systems Engineer
* Cloud Infrastructure Engineer
* Platform Engineer
* Site Reliability Engineer
* DevOps Engineer
* DevSecOps Engineer

## Portfolio Notice

The projects published through this profile are sanitized lab implementations. All hostnames, addresses, accounts, credentials, organizations, and environment-specific values are fictional. This profile includes no confidential employer, customer, or production information.

## Featured Projects

### [Ansible RHEL Patching Framework](https://github.com/solonsah/ansible-rhel-patching)

A production-oriented Ansible framework for safely patching Red Hat Enterprise Linux systems using prechecks, controlled rolling batches, reboot management, post-patch validation, and automated syntax testing.

**Key capabilities:**

- Pre-patching validation and safety checks
- Controlled rolling updates to reduce operational risk
- Conditional reboot management
- Post-patching health verification
- Reusable Ansible role structure
- GitHub Actions automated syntax validation
- Sanitized lab inventory with documentation-only IP addresses

**Technologies:** Ansible, RHEL, YAML, Linux, GitHub Actions, Infrastructure as Code


[View the Ansible RHEL Patching Framework project](https://github.com/solonsah/ansible-rhel-patching)


### [Hyper-V to KVM Migration Framework](https://github.com/solonsah/hyperv-to-kvm-migration)

A structured and safety-focused framework for migrating RHEL virtual machines from Microsoft Hyper-V to KVM/libvirt.

**Key capabilities:**

- Pre-migration source, guest, storage, and network checks
- RHEL guest preparation for VirtIO compatibility
- Virtual disk conversion planning and validation
- KVM/libvirt host-readiness checks
- Post-migration system and application validation
- Documented rollback and recovery controls
- Automated ShellCheck validation with GitHub Actions

**Technologies:** RHEL, Hyper-V, KVM, QEMU, libvirt, Bash, ShellCheck, GitHub Actions

[View the Hyper-V to KVM Migration Framework](https://github.com/solonsah/hyperv-to-kvm-migration)


### [Secure AWS Web Infrastructure](https://github.com/solonsah/aws-secure-web-infrastructure)

A modular Terraform project that models a secure and highly available AWS web tier across two Availability Zones.

**Key capabilities:**

- Reusable networking, security, and compute modules
- Public load-balancer and private application subnets
- HTTPS-only public ingress
- No direct inbound SSH access
- EC2 Auto Scaling and load-balancer health checks
- Required EC2 Instance Metadata Service Version 2
- Encrypted EBS root volumes
- Cost-aware networking design
- Automated Terraform formatting and validation

**Technologies:** AWS, Terraform, VPC, EC2, Auto Scaling, Application Load Balancer, Security Groups, EBS, GitHub Actions

[View the Secure AWS Web Infrastructure project](https://github.com/solonsah/aws-secure-web-infrastructure)


### [Linux Vulnerability Audit](https://github.com/solonsah/linux-vulnerability-audit)

A safety-focused Linux auditing toolkit for discovering vulnerable and unsupported software versions.

- Read-only Linux software discovery
- RPM package and version inventory
- Log4j, Tomcat, OpenSSL, and Java detection
- Bash and Ansible-based auditing
- CSV reporting with sensitive output excluded from Git
- Automated ShellCheck, YAML, and Ansible validation

**Technologies:** Linux, Bash, Ansible, YAML, ShellCheck, GitHub Actions

[View the Linux Vulnerability Audit project](https://github.com/solonsah/linux-vulnerability-audit)


### [Apache Tomcat Operations](https://github.com/solonsah/apache-tomcat-operations)

A production-oriented framework for safely managing, validating, securing, and upgrading Apache Tomcat on Linux.

- Read-only Tomcat and Java discovery
- Bash and Ansible operational prechecks
- Security and configuration baseline
- Side-by-side upgrade planning
- Defined validation and rollback controls
- Automated ShellCheck, YAML, and Ansible validation

**Technologies:** Apache Tomcat, Linux, Java, Bash, Ansible, YAML, ShellCheck, GitHub Actions

[View the Apache Tomcat Operations project](https://github.com/solonsah/apache-tomcat-operations)

### [Linux Observability Lab](https://github.com/solonsah/linux-observability-lab)

A practical Linux observability lab for monitoring system health, performance, logs, and service availability.

- Prometheus and Node Exporter monitoring design
- Grafana dashboard for core Linux health indicators
- CPU, memory, filesystem, availability, and systemd alerts
- Read-only Bash and Ansible operational checks
- Alert-response and escalation runbook
- Automated ShellCheck, YAML, JSON, Prometheus, and Ansible validation

**Technologies:** Linux, Prometheus, PromQL, Grafana, Node Exporter, Bash, Ansible, YAML, JSON, GitHub Actions

[View the Linux Observability Lab project](https://github.com/solonsah/linux-observability-lab)

### [AWS Hybrid Infrastructure](https://github.com/solonsah/aws-hybrid-infrastructure)

A modular Terraform framework for secure hybrid connectivity between simulated on-premises networks and highly available AWS infrastructure.

Key capabilities:

- Multi-AZ VPC with segmented public and private subnets
- Optional highly available NAT gateway design
- Optional AWS Site-to-Site VPN connectivity
- Restricted ingress and egress security-group rules
- Optional VPC Flow Logs with least-privilege IAM
- Cost-aware defaults and deployment-safety controls
- Automated Terraform formatting and validation
- Sanitized configuration with no credentials or workplace data

Technologies: Terraform, HCL, AWS VPC, Site-to-Site VPN, IAM, CloudWatch Logs, PowerShell, GitHub Actions

[View the AWS Hybrid Infrastructure project](https://github.com/solonsah/aws-hybrid-infrastructure)

### [RHEL Security Hardening](https://github.com/solonsah/rhel-security-hardening)

An audit-first Ansible framework for applying STIG-aligned security controls to RHEL systems with explicit approval gates, configuration backups, post-change validation, and protected rollback.

**Key capabilities:**

- Audits SELinux, OpenSSH, auditd, firewalld, and password-policy settings
- Keeps all remediation control families disabled by default
- Requires change approval, recovery access, and SSH-key confirmation
- Processes one host at a time to limit operational impact
- Validates SSH configuration before reloading the service
- Provides timestamped backups and controlled rollback
- Runs automated YAML, Ansible lint, and syntax validation in GitHub Actions

**Technologies:** Ansible, YAML, Bash, RHEL, SELinux, OpenSSH, auditd, firewalld, GitHub Actions

[View the RHEL Security Hardening project](https://github.com/solonsah/rhel-security-hardening)


