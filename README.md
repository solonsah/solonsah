## Hi there 👋
# Solomon Nsah

## Senior Linux Infrastructure Engineer

I am a Senior Linux Infrastructure Engineer with eight-plus years of experience supporting Linux systems, automation, security hardening, virtualization, cloud infrastructure, monitoring, and production operations.

My work focuses on designing secure, reliable, repeatable, and well-documented infrastructure solutions. I have experience supporting physical, virtual, on-premises, and cloud-based environments.

## Technical Skills

- **Operating Systems:** Red Hat Enterprise Linux 7, 8 and 9; Windows Server
- **Automation:** Ansible, Bash, GitHub Actions
- **Virtualization:** KVM, QEMU, libvirt, VMware ESXi, Microsoft Hyper-V
- **Cloud Platforms:** AWS, Microsoft Azure
- **Linux Administration:** Systemd, LVM, XFS, SSH, firewalld, SELinux, DNF and YUM
- **Web and Application Servers:** Apache HTTP Server, Apache Tomcat
- **Databases:** MariaDB, MySQL
- **Monitoring:** Prometheus, Grafana, Datadog, Dynatrace, CloudWatch
- **Security:** STIG implementation, vulnerability remediation, system hardening
- **DevOps Tools:** Git, GitHub, VS Code

## Core Technical Skills

### Linux and Systems Administration

* Red Hat Enterprise Linux 7, 8, and 9
* Amazon Linux
* System installation, configuration, maintenance, and troubleshooting
* Package, kernel, service, process, and lifecycle management
* User, group, permissions, sudo, and SSH administration
* LVM, XFS, ext4, NFS, storage expansion, and filesystem recovery
* DNS, DHCP, routing, firewalld, iptables, and network troubleshooting

### Automation and Infrastructure as Code

* Ansible
* Bash scripting
* Terraform
* Cron and systemd automation
* Automated patching, configuration management, health checks, and reporting
* Repeatable deployment, validation, and rollback workflows

### Security and Compliance

* Security Technical Implementation Guides
* OpenSCAP and vulnerability remediation
* SELinux and auditd
* System hardening
* Identity and access management
* Role-based access control
* TLS and certificate management
* Vulnerability discovery, validation, and remediation

### Cloud and Virtualization

* Amazon Web Services
* Microsoft Azure
* KVM, QEMU, and libvirt
* VMware and Hyper-V
* EC2, EBS, S3, RDS, IAM, VPC, Route 53, and CloudWatch
* Virtual machine provisioning, migration, backup, and recovery

### Application Platforms

* Apache HTTP Server
* Apache Tomcat
* MariaDB and MySQL
* Docker and Kubernetes
* Application deployment, upgrades, TLS configuration, and troubleshooting

### Monitoring and Reliability

* Prometheus and Grafana
* Datadog
* Dynatrace
* Splunk
* AWS CloudWatch
* Incident response
* Root-cause analysis
* Performance monitoring and capacity planning

## Portfolio Projects

1. Ansible RHEL patching framework
2. Hyper-V to KVM migration framework
3. RHEL security-hardening automation
4. Linux vulnerability-audit toolkit
5. Apache and Tomcat operations
6. Linux observability and incident-response lab
7. AWS hybrid-infrastructure deployment
8. Highly available application-infrastructure lab

## Engineering Approach

I approach infrastructure work using:

* Read-only discovery before making changes
* Development and test validation before production rollout
* Security-conscious automation
* Phased and controlled implementation
* Change control and documented approvals
* Backup and rollback planning
* Post-change system and application validation
* Clear runbooks, implementation plans, and technical documentation

## Professional Focus

I am interested in opportunities including:

* Senior Linux Systems Engineer
* Senior Systems Administrator
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


