# Small Company Network Lab | آزمایشگاه شبکه شرکت کوچک

## 🇬🇧 English

### Overview
A small enterprise network lab built with PNETLab to practice Cisco networking technologies and CCNA concepts.

### Objectives
- Configure VLANs and trunk links.
- Implement Inter-VLAN Routing using Router-on-a-Stick.
- Configure DHCP for client networks.
- Implement Spanning Tree Protocol (STP).
- Configure EtherChannel using LACP.
- Implement OSPF dynamic routing.
- Configure Access Control Lists (ACLs).
- Implement NAT/PAT for external connectivity.
- Configure SSH and basic device hardening.
- Apply switch port security.
- Practice IPv6 addressing and network troubleshooting.

### Lab Environment
- **Simulator:** PNETLab
- **Network devices:** Cisco IOSv routers and switches
- **Clients:** Virtual PCs

### Repository Structure
- `Company_Network.unl` — PNETLab topology file.
- `configs/` — Router and switch configurations.
- `screenshots/` — Topology and verification screenshots.
- `docs/` — Network documentation and IP addressing plan.

### Verification and Troubleshooting
The lab includes connectivity and configuration checks using commands such as:

- `show ip interface brief`
- `show ip route`
- `show ip ospf neighbor`
- `show access-lists`
- `show ip nat statistics`
- `ping`

### Purpose
This project demonstrates practical networking skills for CCNA learning, troubleshooting practice, and a networking portfolio.

---

## 🇮🇷 فارسی

### معرفی پروژه
این پروژه یک آزمایشگاه شبکه برای شبیه‌سازی زیرساخت یک شرکت کوچک است که با استفاده از PNETLab و تجهیزات مجازی سیسکو پیاده‌سازی شده است. هدف آن تمرین مباحث CCNA و کسب تجربه عملی در پیکربندی و عیب‌یابی شبکه است.

### اهداف پروژه
- ایجاد و پیکربندی VLAN و لینک‌های Trunk.
- پیاده‌سازی مسیریابی بین VLANها با روش Router-on-a-Stick.
- راه‌اندازی DHCP برای اختصاص خودکار آدرس IP به کلاینت‌ها.
- پیاده‌سازی پروتکل STP برای جلوگیری از ایجاد Loop در لایه دوم.
- تجمیع لینک‌ها با EtherChannel و پروتکل LACP.
- پیکربندی مسیریابی پویا با OSPF.
- اعمال قوانین کنترلی با Access Control List (ACL).
- پیاده‌سازی NAT/PAT برای ارتباط با شبکه خارجی.
- راه‌اندازی SSH و افزایش امنیت تجهیزات.
- پیکربندی Port Security روی سوئیچ‌ها.
- تمرین آدرس‌دهی IPv6 و عیب‌یابی ارتباطات شبکه.

### محیط آزمایشگاه
- **شبیه‌ساز:** PNETLab
- **تجهیزات شبکه:** روترها و سوئیچ‌های مجازی Cisco IOSv
- **کلاینت‌ها:** کامپیوترهای مجازی VPCS

### ساختار مخزن
- `Company_Network.unl` — فایل توپولوژی پروژه در PNETLab.
- `configs/` — فایل تنظیمات روترها و سوئیچ‌ها.
- `screenshots/` — تصاویر توپولوژی و نتایج آزمایش‌ها.
- `docs/` — مستندات شبکه و طرح آدرس‌دهی IP.

### تست و عیب‌یابی
برای بررسی عملکرد شبکه از دستورهایی مانند موارد زیر استفاده شده است:

- `show ip interface brief` — بررسی وضعیت اینترفیس‌ها.
- `show ip route` — بررسی جدول مسیریابی.
- `show ip ospf neighbor` — بررسی همسایگی‌های OSPF.
- `show access-lists` — بررسی قوانین ACL.
- `show ip nat statistics` — بررسی وضعیت NAT.
- `ping` — آزمایش ارتباط بین تجهیزات.

### هدف نهایی
هدف این پروژه، تقویت مهارت‌های عملی شبکه، تمرین مباحث CCNA، مستندسازی سناریوهای واقعی و ایجاد یک نمونه‌کار قابل ارائه در رزومه و GitHub است.

---

**Author:** Mehdi Razmi

**Technologies:** Cisco IOSv, PNETLab, VLAN, STP, EtherChannel, OSPF, ACL, NAT/PAT, IPv6
