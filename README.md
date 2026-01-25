# Norman Herms

Junior Linux System Administrator | Homelab | Career Changer

12 Jahre Einzelhandel → IT Quereinsteiger seit Feb 2025

---

## Technische Fähigkeiten

**Linux Administration:**
- Debian Server aufsetzen und verwalten
- User-Management, SSH-Hardening (key-only, root disabled)
- System-Logs analysieren (journalctl, rsyslog)
- Firewall-Konfiguration (nftables, Default-Drop-Policy, fail2ban)
- Storage-Management (LVM, Partitionierung, fstab)

**Container & Virtualisierung:**
- Container betreiben (containerd/nerdctl, Compose)
- VMs erstellen und verwalten (KVM/libvirt)
- Multi-Service-Stacks (Datenbanken, Web-Apps, Reverse Proxy)

**Netzwerk:**
- WireGuard Full Mesh über WAN + Heimnetz (4 Nodes, NAT-Support)
- Bridge-Networking (systemd-networkd)
- Reverse Proxy (nginx, TLS/certbot)

**Monitoring & Observability:**
- Prometheus + Grafana
- Node Exporter (systemd services)
- Logging (rsyslog, journald)

**Sonstiges:**
- Backup-Strategien (Restic)
- Git (Workflows, Dokumentation)
- Bash-Scripting (Automatisierung)
- Technische Dokumentation (Runbooks, Checklisten)

---

## Homelab Infrastructure (seit Feb 2025)

### Produktiv

**Homelab (edge):**

- Debian 13, containerd, libvirt
- Services: AdGuard Home, Wiki.js, Tandoor, Anytype, Jellyfin, Audiobookshelf
- VMs: Home Assistant (HAOS)

**Staging-Cluster (4 Nodes):**

- [x] Baseline auf allen Nodes (SSH hardening, nftables, fail2ban, auditd)
- [x] WireGuard Full Mesh (10.99.99.0/24, NAT-Node-Support)
- [x] Monitoring Stack (Prometheus, Grafana, Node Exporter)
- [x] K3s Deployment
- [ ] DRBD Storage Replication (geplant)

**Hardware:**
- 1 Liter Mini PC (mirror) – K3s Worker, DRBD Secondary
- Netcup Root Server (prod) – K3s Worker, DRBD Primary
- Netcup Root Server (load) – K3s Control Plane
- Netcup VPS (dash) – Monitoring Node

---

## Repositories

**[knowledge-base](https://github.com/normanherms/knowledge-base) ** – Cheatbooks & Infrastructure-Dokumentation
- Cheatbooks: Linux Essentials, LPIC-1, Ansible, Git, Python
- Infrastructure: Cluster-Architektur, Netzwerk-Planung, Runbooks
- Iterationshistorie: 7 dokumentierte Cluster-Neuaufbauten (inkl. Fehler & Learnings)

---

## Lernweg

**Abgeschlossen:**
- Linux Essentials
- LPIC-1 (101)
- Git
- Ansible
- Python Grundkurs

**In Arbeit:**
- Bash Scripting
- Container und Virtualisierung
- Terraform
- K3s Cluster

---

## Standort & Kontakt

📍 Buxtehude (Hamburg-Umgebung)  
🎯 Suche: Junior System Administrator Position (Remote/Hamburg)  
💼 LinkedIn: https://linkedin.com/in/norman-herms

---

*Learning in public.*
