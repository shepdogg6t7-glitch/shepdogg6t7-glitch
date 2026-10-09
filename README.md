# Kelvin Shepherd

**Aspiring SOC Analyst** | Home lab builder | Networking + Security Operations

I'm building a portfolio of hands-on projects in security operations and
networking — SIEM deployment, endpoint monitoring, network design, and
incident response. Currently targeting SOC Analyst and junior security
engineering roles.

## Professional Background

I bring 28+ years of combined experience as a Navy Corpsman and Certified Peer Specialist, including Veteran-centered work in a Department of Veterans Affairs clinical setting. My work included active listening, mentorship and advocacy, helping Veterans navigate services, supporting wellness goals, facilitating groups, and using trained communication and de-escalation during difficult situations. I also worked as part of an interdisciplinary care team and followed professional ethics, confidentiality, and boundaries.

I’m making a career switch into IT and building hands-on cybersecurity experience through home labs in SIEM operations, networking, Linux security, and GRC. My previous work informs how I approach that learning: listen carefully, assess what’s happening, communicate clearly, follow appropriate processes, and involve the right people when something needs escalation. Healthcare and peer-support crisis work is not cybersecurity incident response; those are distinct kinds of experience.

---

## 🎯 Featured Projects

### 🛡️ [Wazuh Home Lab](https://github.com/shepdogg6t7-glitch/wazuh-home-lab)

A full Wazuh SIEM deployment in Docker on WSL 2, with a monitored Ubuntu
endpoint, automated backups, and a documented credential-hardening process.

- **Deployed:** Wazuh 4.9.0 (Indexer, Manager, Dashboard) on Docker
- **Onboarded:** Ubuntu 22.04 endpoint as a Wazuh agent
- **Hardened:** Rotated default credentials using `securityadmin.sh`; documented three real failure modes
- **Backed up:** Scripted backup of 14 Docker volumes to external storage
- **Documented:** 6 milestones + screenshots in a structured `docs/` folder

`Docker` `Wazuh` `SIEM` `Ubuntu` `WSL 2` `Security Operations`

---

### 🌐 [Lone Star Logistics — Multi-Site Network](https://github.com/shepdogg6t7-glitch/Lone-Star-Logistics-Network-Upgrade-Cisco-Packet-Tracer)

A three-site hub-and-spoke network designed in Cisco Packet Tracer, with
a deliberate troubleshooting exercise that simulates a real support ticket.

- **Designed:** Hub-and-spoke topology across three sites
- **Configured:** Static routing, DHCP relay (`ip helper-address`), and OSPF Area 0
- **Diagnosed:** Broken spoke-to-spoke path using extended ping and traceroute
- **Documented:** 8 technical docs + 16 curated screenshots
- **Included:** Interview prep Q&A drawn from the project

`Cisco` `Packet Tracer` `Routing` `DHCP` `OSPF` `Networking`

---

## 🧊 Cybersecurity Iceberg: Project Overlap

This is a guide to topics my projects touch—not a claim of expertise. One project
can overlap several areas; the examples below point to work or artifacts in each
repository. Study materials are labeled separately from hands-on labs.

| Project | Overlapping areas | What I did / example evidence |
| --- | --- | --- |
| [Wazuh Home Lab](https://github.com/shepdogg6t7-glitch/wazuh-home-lab) | Security operations, SIEM, endpoint monitoring, incident triage | Deployed Wazuh in Docker, enrolled an Ubuntu agent, documented troubleshooting and credential hardening, and scripted volume backups. |
| [Linux Networking + GRC Labs](https://github.com/shepdogg6t7-glitch/shep_linux-netsec-grc-labs) | Network security, packet analysis, auditing, risk and controls | Saved lab outputs for `tcpdump` packet capture and `ufw` firewall checks; ran a Lynis/CIS audit, generated a CSV audit report, and mapped findings to a risk register and control frameworks. |
| [Lone Star Logistics — Multi-Site Network](https://github.com/shepdogg6t7-glitch/Lone-Star-Logistics-Network-Upgrade-Cisco-Packet-Tracer) | Network infrastructure, routing, troubleshooting | Designed a three-site Packet Tracer network with OSPF, static routes, and DHCP relay; used extended ping and traceroute to diagnose a simulated connectivity issue. |
| [Lone Star Logistics — GRC Portfolio](https://github.com/shepdogg6t7-glitch/lone-star-logistics-grc-portfolio) | Governance, risk, compliance, policies, incident response | Created a fictional-company case study with NIST CSF v2.0-mapped policies, a risk register, a CIS-based audit checklist, and an incident register. |
| Self-hosted infrastructure: [Docker + Portainer](https://github.com/shepdogg6t7-glitch/docker-portainer-homelab), [Uptime Kuma](https://github.com/shepdogg6t7-glitch/uptime-kuma-homelab), [Vaultwarden](https://github.com/shepdogg6t7-glitch/vaultwarden-homelab), [Nginx Proxy Manager](https://github.com/shepdogg6t7-glitch/nginx-proxy-manager-homelab) | Systems administration, service monitoring, password management, reverse proxy and HTTPS | Deployed containerized services through Portainer on WSL2: uptime checks and alerts, a self-hosted password manager, and domain routing with HTTPS certificate management. |
| [AtlasOps](https://github.com/shepdogg6t7-glitch/atlasops) | Technical breadth: document processing, semantic search, data systems | The repository covers a self-hostable document platform with PDF ingestion, vector search, and an event-driven pipeline. This shows software and infrastructure work, not cybersecurity evidence. |
| Study and learning: [Network+ N10-009 study guide](https://github.com/shepdogg6t7-glitch/N10-009-Domain2-Study), [Linux networking fundamentals](https://github.com/shepdogg6t7-glitch/k_r_shepherd_linux-networking-fundamentals) | Networking concepts and fundamentals | These repositories are study/learning materials, not evidence of completed practical labs. |

---

## 🛠️ Skills & Tools

**Security Operations:**
`Wazuh` `SIEM` `Log Analysis` `Endpoint Monitoring` `Incident Triage`

**Networking:**
`TCP/IP` `Static & Dynamic Routing` `OSPF` `DHCP` `VLANs` `Cisco IOS`

**Systems:**
`Linux (Ubuntu)` `Docker` `WSL 2` `Bash` `Windows 11`

**Governance & Risk:**
`GRC fundamentals` `NIST 800-53` `PCI DSS` `HIPAA`

---

## 📚 Learning & Certifications

- 🎓 **Cisco Networking Academy** — Getting Started with Cisco Packet Tracer
- 📖 **CompTIA Network+ (N10-009)** — Currently studying
- 📖 **Security+** — Planned next

---

## 📂 Other Repos

- [N10-009-Domain2-Study](https://github.com/shepdogg6t7-glitch/N10-009-Domain2-Study) — CompTIA Network+ study guide
- [lone-star-logistics-grc-portfolio](https://github.com/shepdogg6t7-glitch/lone-star-logistics-grc-portfolio) — GRC portfolio (Python)
- [k_r_shepherd_linux-networking-fundamentals](https://github.com/shepdogg6t7-glitch/k_r_shepherd_linux-networking-fundamentals) — Linux networking labs
- [shep_linux-netsec-grc-labs](https://github.com/shepdogg6t7-glitch/shep_linux-netsec-grc-labs) — Linux/netsec/GRC labs
- [docker-desktop-k8s-setup-log](https://github.com/shepdogg6t7-glitch/docker-desktop-k8s-setup-log) — Kubernetes setup notes

---

## 🏆 GitHub Achievement

**YOLO** — a GitHub achievement, not a certification or skill.

---

## 📫 Reach Me

- **GitHub:** [@shepdogg6t7-glitch](https://github.com/shepdogg6t7-glitch)
- **Based in:** Texas
- **Open to:** SOC Analyst roles, junior security engineering, IT security

---

*Building a home SOC, one project at a time.*
