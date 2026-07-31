```
██╗    ██╗ ██████╗ ██╗     ███████╗    ██╗  ██╗ █████╗  ██████╗██╗  ██╗██╗███╗   ██╗ ██████╗ 
██║    ██║██╔═══██╗██║     ██╔════╝    ██║  ██║██╔══██╗██╔════╝██║ ██╔╝██║████╗  ██║██╔════╝ 
██║ █╗ ██║██║   ██║██║     █████╗      ███████║███████║██║     █████╔╝ ██║██╔██╗ ██║██║  ███╗
██║███╗██║██║   ██║██║     ██╔══╝      ██╔══██║██╔══██║██║     ██╔═██╗ ██║██║╚██╗██║██║   ██║
╚███╔███╔╝╚██████╔╝███████╗██║         ██║  ██║██║  ██║╚██████╗██║  ██╗██║██║ ╚████║╚██████╔╝
 ╚══╝╚══╝  ╚═════╝ ╚══════╝╚═╝         ╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝╚═╝╚═╝  ╚═══╝ ╚═════╝ 
```

<h3 align="center">Matías Barrios · Sr. Pentest Operations Specialist @ Strike</h3>
<p align="center">
  <em>Offensive Security · Bug Bounty · Exploit Development · Argentina 🇦🇷</em>
</p>

<p align="center">
  <a href="https://profile.hackthebox.com/profile/019d0289-7980-737b-b2dd-48f7a5b1e2dc">🌐 HackTheBox</a> ·
  <a href="https://wolfhacking.com.ar">🌐 wolfhacking.com.ar</a> ·
  <a href="https://hackerone.com/galletitaconpate">HackerOne</a> ·
  <a href="https://www.linkedin.com/in/matiiieb">LinkedIn</a>
</p>

---

## whoami

```
$ cat about.txt

Name     : Matías Emanuel Barrios
Handle   : galletitaconpate / r4zk3r
Role     : Sr. Pentest Operations Specialist @ Strike
XP       : 6+ years · 500+ vulnerabilities exploited
Focus    : Web/API · Mobile (iOS/Android) · Active Directory · WiFi · Cloud
Location : Argentina
```

Offensive security practitioner specializing in complex vulnerability research across web, mobile, network and cloud environments. I break things professionally — and occasionally document how.

---

<!-- bug-bounty:start -->
## bug bounty

| Platform | Stats |
|----------|-------|
| **HackerOne** · [`galletitaconpate`](https://hackerone.com/galletitaconpate) | 🎯 Signal **7.0** (95th pct) · Impact **21.0** (90th pct) · **421** rep · **28** credited · **12** thanks |
| **CyScope** · `r4zk3r` | 🏆 Rank **#7** · **638 pts** · **57 vulns** · **78%** accuracy · avg severity **6.59** |

### 🛡️ Security Research & Disclosures

*3 advisories · 2 sole credit · 1 co-credited.*

| ID | Target | Severity | Fixed in | Finding |
| :--- | :--- | :--- | :--- | :--- |
| [GHSA-j4rw-3r36-79pm](https://github.com/DefectDojo/django-DefectDojo/security/advisories/GHSA-j4rw-3r36-79pm) | DefectDojo | Moderate 5.4 | `3.1.100` | Missing authorization on questionnaire relink allows cross-product access to questionnaire responses |
| [GHSA-43f3-w9fq-8v5j](https://github.com/DefectDojo/django-DefectDojo/security/advisories/GHSA-43f3-w9fq-8v5j) | DefectDojo | Moderate 6.5 | `3.1.300` | Improper authorization allows account takeover by a delegated user manager |
| [GHSA-7w4m-r6wp-2c5r](https://github.com/DefectDojo/django-DefectDojo/security/advisories/GHSA-7w4m-r6wp-2c5r) | DefectDojo | Moderate 6.3 | `3.1.300` | Cross-product authorization gaps in the V3 Locations feature allow access to other products' location and endpoint data *(co-credited, 7 reporters)* |

<!-- bug-bounty:end -->

---

<!-- exploit-development:start -->
## exploit development

**115 reproduced exploits** across 101 products — every entry was actually run against the affected version, never copied from a writeup. 78 ship a runnable PoC; 42 are CVSS-critical.

→ **[galletitaconpate/verified-exploits](https://github.com/galletitaconpate/verified-exploits)** · [by CWE](https://github.com/galletitaconpate/verified-exploits/blob/main/INDEX_BY_CWE.md) · [by class](https://github.com/galletitaconpate/verified-exploits/blob/main/INDEX_BY_CLASS.md)

`2026` 9 · `2025` 23 · `≤2024` 83&nbsp;&nbsp;|&nbsp;&nbsp;RCE 56 · LPE 16 · Auth Bypass 9 · Path Traversal 7 · SQL Injection 6 · Info Disclosure 4

### 2026

| CVE | Target | Class | CVSS |
| :--- | :--- | :--- | :--- |
| [CVE-2026-29000](https://github.com/galletitaconpate/verified-exploits/tree/main/pac4j/AuthBypass%20-%20CVE-2026-29000) | pac4j | Auth Bypass | **10.0** |
| [CVE-2026-23744](https://github.com/galletitaconpate/verified-exploits/tree/main/MCPJam%20Inspector/RCE%20-%20CVE-2026-23744) | MCPJam Inspector | RCE | **9.8** |
| [CVE-2026-27944](https://github.com/galletitaconpate/verified-exploits/tree/main/Nginx-UI/AuthBypass%20-%20CVE-2026-27944) | Nginx-UI | Auth Bypass | **9.8** |
| [CVE-2026-33017](https://github.com/galletitaconpate/verified-exploits/tree/main/Langflow/RCE%20-%20CVE-2026-33017) | Langflow | RCE | **9.8** |
| [CVE-2026-33937](https://github.com/galletitaconpate/verified-exploits/tree/main/Handlebars.js/RCE%20-%20CVE-2026-33937) | Handlebars.js | RCE | **9.8** |
| [CVE-2026-63030](https://github.com/galletitaconpate/verified-exploits/tree/main/WordPress/SQLi%20-%20CVE-2026-63030) | WordPress | SQL Injection | **9.8** |
| [CVE-2026-4480](https://github.com/galletitaconpate/verified-exploits/tree/main/Samba/RCE%20-%20CVE-2026-4480) | Samba | RCE | **9.0** |
| [CVE-2026-26231](https://github.com/galletitaconpate/verified-exploits/tree/main/Gitea/AuthBypass%20-%20CVE-2026-26231) | Gitea | Auth Bypass | 8.5 |
| [CVE-2026-3888](https://github.com/galletitaconpate/verified-exploits/tree/main/snapd/LPE%20-%20CVE-2026-3888) | snapd | LPE | 7.8 |

### 2025 · top 10 of 23

| CVE | Target | Class | CVSS |
| :--- | :--- | :--- | :--- |
| [CVE-2025-32433](https://github.com/galletitaconpate/verified-exploits/tree/main/Erlang%20OTP%20SSH/RCE%20-%20CVE-2025-32433) | Erlang OTP SSH | RCE | **10.0** |
| [CVE-2025-47812](https://github.com/galletitaconpate/verified-exploits/tree/main/Wing%20FTP%20Server/RCE%20-%20CVE-2025-47812) | Wing FTP Server | RCE | **10.0** |
| [CVE-2025-55182](https://github.com/galletitaconpate/verified-exploits/tree/main/Next.js/RCE%20-%20CVE-2025-55182) | Next.js | RCE | **10.0** |
| [CVE-2025-49113](https://github.com/galletitaconpate/verified-exploits/tree/main/Roundcube%20Webmail/RCE%20-%20CVE-2025-49113) | Roundcube Webmail | RCE | **9.9** |
| [CVE-2025-24893](https://github.com/galletitaconpate/verified-exploits/tree/main/XWiki%20Platform/RCE%20-%20CVE-2025-24893) | XWiki Platform | RCE | **9.8** |
| [CVE-2025-31161](https://github.com/galletitaconpate/verified-exploits/tree/main/CrushFTP/AuthBypass%20-%20CVE-2025-31161) | CrushFTP | Auth Bypass | **9.8** |
| [CVE-2025-57819](https://github.com/galletitaconpate/verified-exploits/tree/main/FreePBX/SQLi%20-%20CVE-2025-57819) | FreePBX | SQL Injection | **9.8** |
| [CVE-2025-2304](https://github.com/galletitaconpate/verified-exploits/tree/main/Camaleon%20CMS/AuthBypass%20-%20CVE-2025-2304) | Camaleon CMS | Auth Bypass | **9.4** |
| [CVE-2025-4517](https://github.com/galletitaconpate/verified-exploits/tree/main/CPython/PathTraversal%20-%20CVE-2025-4517) | CPython | Path Traversal | **9.4** |
| [CVE-2025-9074](https://github.com/galletitaconpate/verified-exploits/tree/main/Docker%20Desktop/SSRF%20-%20CVE-2025-9074) | Docker Desktop | SSRF | **9.3** |

<details>
<summary><b>full archive — 96 more</b> (2025 remainder and earlier)</summary>

| CVE | Target | Class | CVSS |
| :--- | :--- | :--- | :--- |
| [CVE-2025-24367](https://github.com/galletitaconpate/verified-exploits/tree/main/Cacti/RCE%20-%20CVE-2025-24367) | Cacti | RCE | 8.8 |
| [CVE-2025-69212](https://github.com/galletitaconpate/verified-exploits/tree/main/OpenSTAManager/RCE%20-%20CVE-2025-69212) | OpenSTAManager | RCE | 8.8 |
| [CVE-2025-64512](https://github.com/galletitaconpate/verified-exploits/tree/main/pdfminer.six/RCE%20-%20CVE-2025-64512) | pdfminer.six | RCE | 8.6 |
| [CVE-2025-27591](https://github.com/galletitaconpate/verified-exploits/tree/main/below/LPE%20-%20CVE-2025-27591) | below | LPE | 7.8 |
| [CVE-2025-59341](https://github.com/galletitaconpate/verified-exploits/tree/main/esm.sh/LFI%20-%20CVE-2025-59341) | esm.sh | LFI | 7.7 |
| [CVE-2025-24071](https://github.com/galletitaconpate/verified-exploits/tree/main/Microsoft%20Windows%20File%20Explorer/AuthBypass%20-%20CVE-2025-24071) | Microsoft Windows File Explorer | Auth Bypass | 7.5 |
| [CVE-2025-24799](https://github.com/galletitaconpate/verified-exploits/tree/main/GLPI/SQLi%20-%20CVE-2025-24799) | GLPI | SQL Injection | 7.5 |
| [CVE-2025-60787](https://github.com/galletitaconpate/verified-exploits/tree/main/motionEye/RCE%20-%20CVE-2025-60787) | motionEye | RCE | 7.2 |
| [CVE-2025-0133](https://github.com/galletitaconpate/verified-exploits/tree/main/GlobalProtect/RXSS%20-%20CVE-2025-0133) | GlobalProtect | Reflected XSS | 6.9 |
| [CVE-2025-64714](https://github.com/galletitaconpate/verified-exploits/tree/main/PrivateBin/LFI%20-%20CVE-2025-64714) | PrivateBin | LFI | 5.8 |
| [CVE-2025-59474](https://github.com/galletitaconpate/verified-exploits/tree/main/Jenkins/CWE200%20-%20CVE-2025-59474) | Jenkins | Info Disclosure | 5.3 |
| [CVE-2025-32462](https://github.com/galletitaconpate/verified-exploits/tree/main/sudo/LPE%20-%20CVE-2025-32462) | sudo | LPE | 2.8 |
| [CVE-2025-61678](https://github.com/galletitaconpate/verified-exploits/tree/main/FreePBX/PathTraversal%20-%20CVE-2025-61678) | FreePBX | Path Traversal | — |
| [CVE-2024-51482](https://github.com/galletitaconpate/verified-exploits/tree/main/ZoneMinder/SQLi%20-%20CVE-2024-51482) | ZoneMinder | SQL Injection | **9.9** |
| [CVE-2024-9264](https://github.com/galletitaconpate/verified-exploits/tree/main/Grafana/RCE%20-%20CVE-2024-9264) | Grafana | RCE | **9.9** |
| [CVE-2024-3660](https://github.com/galletitaconpate/verified-exploits/tree/main/TensorFlow/RCE%20-%20CVE-2024-3660) | TensorFlow | RCE | **9.8** |
| [CVE-2024-53677](https://github.com/galletitaconpate/verified-exploits/tree/main/Apache%20Struts2/PathTraversal%20-%20CVE-2024-53677) | Apache Struts2 | Path Traversal | **9.8** |
| [CVE-2024-34070](https://github.com/galletitaconpate/verified-exploits/tree/main/Froxlor/RXSS%20-%20CVE-2024-34070) | Froxlor | Reflected XSS | **9.6** |
| [CVE-2024-23346](https://github.com/galletitaconpate/verified-exploits/tree/main/pymatgen/RCE%20-%20CVE-2024-23346) | pymatgen | RCE | **9.3** |
| [CVE-2024-28397](https://github.com/galletitaconpate/verified-exploits/tree/main/js2py/RCE%20-%20CVE-2024-28397) | js2py | RCE | 8.8 |
| [CVE-2024-4367](https://github.com/galletitaconpate/verified-exploits/tree/main/PDF.js/RCE%20-%20CVE-2024-4367) | PDF.js | RCE | 8.8 |
| [CVE-2024-48990](https://github.com/galletitaconpate/verified-exploits/tree/main/needrestart/LPE%20-%20CVE-2024-48990) | needrestart | LPE | 7.8 |
| [CVE-2024-49019](https://github.com/galletitaconpate/verified-exploits/tree/main/Microsoft%20AD%20CS/PrivEsc%20-%20CVE-2024-49019) | Microsoft AD CS | Priv Esc | 7.8 |
| [CVE-2024-41817](https://github.com/galletitaconpate/verified-exploits/tree/main/ImageMagick/RCE%20-%20CVE-2024-41817) | ImageMagick | RCE | 7.0 |
| [CVE-2024-23334](https://github.com/galletitaconpate/verified-exploits/tree/main/aiohttp/PathTraversal%20-%20CVE-2024-23334) | aiohttp | Path Traversal | 5.9 |
| [CVE-2024-47176](https://github.com/galletitaconpate/verified-exploits/tree/main/CUPS/RCE%20-%20CVE-2024-47176) | CUPS | RCE | 5.3 |
| [CVE-2023-46604](https://github.com/galletitaconpate/verified-exploits/tree/main/Apache%20ActiveMQ/RCE%20-%20CVE-2023-46604) | Apache ActiveMQ | RCE | **10.0** |
| [CVE-2023-0297](https://github.com/galletitaconpate/verified-exploits/tree/main/pyLoad/RCE%20-%20CVE-2023-0297) | pyLoad | RCE | **9.8** |
| [CVE-2023-30547](https://github.com/galletitaconpate/verified-exploits/tree/main/vm2/RCE%20-%20CVE-2023-30547) | vm2 | RCE | **9.8** |
| [CVE-2023-3452](https://github.com/galletitaconpate/verified-exploits/tree/main/WordPress%20Canto%20Plugin/RFI%20-%20CVE-2023-3452) | WordPress Canto Plugin | RFI | **9.8** |
| [CVE-2023-38646](https://github.com/galletitaconpate/verified-exploits/tree/main/Metabase/RCE%20-%20CVE-2023-38646) | Metabase | RCE | **9.8** |
| [CVE-2023-42793](https://github.com/galletitaconpate/verified-exploits/tree/main/JetBrains%20TeamCity/AuthBypass%20-%20CVE-2023-42793) | JetBrains TeamCity | Auth Bypass | **9.8** |
| [CVE-2023-43364](https://github.com/galletitaconpate/verified-exploits/tree/main/Searchor/RCE%20-%20CVE-2023-43364) | Searchor | RCE | **9.8** |
| [CVE-2023-51467](https://github.com/galletitaconpate/verified-exploits/tree/main/Apache%20OFBiz/RCE%20-%20CVE-2023-51467) | Apache OFBiz | RCE | **9.8** |
| [CVE-2023-30253](https://github.com/galletitaconpate/verified-exploits/tree/main/Dolibarr/RCE%20-%20CVE-2023-30253) | Dolibarr | RCE | 8.8 |
| [CVE-2023-50564](https://github.com/galletitaconpate/verified-exploits/tree/main/Pluck/RCE%20-%20CVE-2023-50564) | Pluck | RCE | 8.8 |
| [CVE-2023-4220](https://github.com/galletitaconpate/verified-exploits/tree/main/Chamilo%20LMS/RCE%20-%20CVE-2023-4220) | Chamilo LMS | RCE | 8.1 |
| [CVE-2023-0386](https://github.com/galletitaconpate/verified-exploits/tree/main/Linux%20Kernel/LPE%20-%20CVE-2023-0386) | Linux Kernel | LPE | 7.8 |
| [CVE-2023-49147](https://github.com/galletitaconpate/verified-exploits/tree/main/PDF24%20Creator/LPE%20-%20CVE-2023-49147) | PDF24 Creator | LPE | 7.8 |
| [CVE-2023-1326](https://github.com/galletitaconpate/verified-exploits/tree/main/apport/LPE%20-%20CVE-2023-1326) | apport | LPE | 7.7 |
| [CVE-2023-24249](https://github.com/galletitaconpate/verified-exploits/tree/main/laravel-admin/RCE%20-%20CVE-2023-24249) | laravel-admin | RCE | 7.2 |
| [CVE-2023-46818](https://github.com/galletitaconpate/verified-exploits/tree/main/ISPConfig/RCE%20-%20CVE-2023-46818) | ISPConfig | RCE | 7.2 |
| [CVE-2023-27163](https://github.com/galletitaconpate/verified-exploits/tree/main/request-baskets/SSRF%20-%20CVE-2023-27163) | request-baskets | SSRF | 6.5 |
| [CVE-2023-41425](https://github.com/galletitaconpate/verified-exploits/tree/main/WonderCMS/RCE%20-%20CVE-2023-41425) | WonderCMS | RCE | 6.1 |
| [CVE-2023-20052](https://github.com/galletitaconpate/verified-exploits/tree/main/ClamAV/XXE%20-%20CVE-2023-20052) | ClamAV | XXE | 5.3 |
| [CVE-2023-23752](https://github.com/galletitaconpate/verified-exploits/tree/main/Joomla/AuthBypass%20-%20CVE-2023-23752) | Joomla | Auth Bypass | 5.3 |
| [CVE-2023-44487](https://github.com/galletitaconpate/verified-exploits/tree/main/CVE-2023-44487) | HTTP/2 | DoS | 5.3 |
| [CVE-2023-40028](https://github.com/galletitaconpate/verified-exploits/tree/main/Ghost%20CMS/PathTraversal%20-%20CVE-2023-40028) | Ghost CMS | Path Traversal | 4.9 |
| [CVE-2023-26604](https://github.com/galletitaconpate/verified-exploits/tree/main/systemd/LPE%20-%20CVE-2023-26604) | systemd | LPE | — |
| [CVE-2023-32784](https://github.com/galletitaconpate/verified-exploits/tree/main/KeePass/InfoDisclosure%20-%20CVE-2023-32784) | KeePass | Info Disclosure | — |
| [CVE-2022-22963](https://github.com/galletitaconpate/verified-exploits/tree/main/Spring%20Cloud%20Function/RCE%20-%20CVE-2022-22963) | Spring Cloud Function | RCE | **9.8** |
| [CVE-2022-0944](https://github.com/galletitaconpate/verified-exploits/tree/main/SQLPad/SSTI%20-%20CVE-2022-0944) | SQLPad | SSTI | **9.1** |
| [CVE-2022-24439](https://github.com/galletitaconpate/verified-exploits/tree/main/GitPython/RCE%20-%20CVE-2022-24439) | GitPython | RCE | 8.1 |
| [CVE-2022-0847](https://github.com/galletitaconpate/verified-exploits/tree/main/Linux%20Kernel/CWE665%20-%20CVE-2022-0847) | Linux Kernel | Improper Init | 7.8 |
| [CVE-2022-37706](https://github.com/galletitaconpate/verified-exploits/tree/main/Enlightenment/LPE%20-%20CVE-2022-37706) | Enlightenment | LPE | 7.8 |
| [CVE-2022-4510](https://github.com/galletitaconpate/verified-exploits/tree/main/binwalk/PathTraversal%20-%20CVE-2022-4510) | binwalk | Path Traversal | 7.8 |
| [CVE-2022-44268](https://github.com/galletitaconpate/verified-exploits/tree/main/ImageMagick/FileRead%20-%20CVE-2022-44268) | ImageMagick | File Read | — |
| [CVE-2022-46169](https://github.com/galletitaconpate/verified-exploits/tree/main/Cacti/RCE%20-%20CVE-2022-46169) | Cacti | RCE | — |
| [CVE-2021-44967](https://github.com/galletitaconpate/verified-exploits/tree/main/LimeSurvey/RCE%20-%20CVE-2021-44967) | LimeSurvey | RCE | 8.8 |
| [CVE-2021-3493](https://github.com/galletitaconpate/verified-exploits/tree/main/Linux%20Kernel/LPE%20-%20CVE-2021-3493) | Linux Kernel | LPE | 7.8 |
| [CVE-2021-4034](https://github.com/galletitaconpate/verified-exploits/tree/main/polkit/LPE%20-%20CVE-2021-4034) | polkit | LPE | 7.8 |
| [CVE-2021-43798](https://github.com/galletitaconpate/verified-exploits/tree/main/Grafana/PathTraversal%20-%20CVE-2021-43798) | Grafana | Path Traversal | 7.5 |
| [CVE-2021-20323](https://github.com/galletitaconpate/verified-exploits/tree/main/Keycloak/RXSS%20-%20CVE-2021-20323) | Keycloak | Reflected XSS | 6.1 |
| [CVE-2021-41091](https://github.com/galletitaconpate/verified-exploits/tree/main/Moby/LPE%20-%20CVE-2021-41091) | Moby | LPE | 5.9 |
| [CVE-2020-5752](https://github.com/galletitaconpate/verified-exploits/tree/main/Druva%20inSync/LPE%20-%20CVE-2020-5752) | Druva inSync | LPE | 7.8 |
| [CVE-2020-27838](https://github.com/galletitaconpate/verified-exploits/tree/main/Keycloak/CWE200%20-%20CVE-2020-27838) | Keycloak | Info Disclosure | 6.5 |
| [CVE-2020-35572](https://github.com/galletitaconpate/verified-exploits/tree/main/Adminer/FileRead%20-%20CVE-2020-35572) | Adminer | File Read | 6.1 |
| [CVE-2020-10770](https://github.com/galletitaconpate/verified-exploits/tree/main/Keycloak/SSRF%20-%20CVE-2020-10770) | Keycloak | SSRF | 5.3 |
| [CVE-2019-15107](https://github.com/galletitaconpate/verified-exploits/tree/main/Webmin/RCE%20-%20CVE-2019-15107) | Webmin | RCE | **9.8** |
| [CVE-2019-16278](https://github.com/galletitaconpate/verified-exploits/tree/main/Nostromo%20%28nhttpd%29/RCE%20-%20CVE-2019-16278) | Nostromo (nhttpd) | RCE | **9.8** |
| [CVE-2019-25065](https://github.com/galletitaconpate/verified-exploits/tree/main/OpenNetAdmin/RCE%20-%20CVE-2019-25065) | OpenNetAdmin | RCE | **9.8** |
| [CVE-2019-12840](https://github.com/galletitaconpate/verified-exploits/tree/main/Webmin/RCE%20-%20CVE-2019-12840) | Webmin | RCE | 8.8 |
| [CVE-2019-14287](https://github.com/galletitaconpate/verified-exploits/tree/main/sudo/AuthBypass%20-%20CVE-2019-14287) | sudo | Auth Bypass | 8.8 |
| [CVE-2019-16113](https://github.com/galletitaconpate/verified-exploits/tree/main/Bludit/RCE%20-%20CVE-2019-16113) | Bludit | RCE | 8.8 |
| [CVE-2019-9053](https://github.com/galletitaconpate/verified-exploits/tree/main/CMS%20Made%20Simple/SQLi%20-%20CVE-2019-9053) | CMS Made Simple | SQL Injection | 8.1 |
| [CVE-2018-7600](https://github.com/galletitaconpate/verified-exploits/tree/main/Drupal/RCE%20-%20CVE-2018-7600) | Drupal | RCE | **9.8** |
| [CVE-2018-15133](https://github.com/galletitaconpate/verified-exploits/tree/main/Laravel/RCE%20-%20CVE-2018-15133) | Laravel | RCE | 8.1 |
| [CVE-2018-9276](https://github.com/galletitaconpate/verified-exploits/tree/main/Paessler%20PRTG%20Network%20Monitor/RCE%20-%20CVE-2018-9276) | Paessler PRTG Network Monitor | RCE | 7.2 |
| [CVE-2017-7269](https://github.com/galletitaconpate/verified-exploits/tree/main/Microsoft%20IIS/RCE%20-%20CVE-2017-7269) | Microsoft IIS | RCE | **9.8** |
| [CVE-2017-0144](https://github.com/galletitaconpate/verified-exploits/tree/main/Microsoft%20Windows%20SMBv1/RCE%20-%20CVE-2017-0144) | Microsoft Windows SMBv1 | RCE | 8.1 |
| [CVE-2017-16995](https://github.com/galletitaconpate/verified-exploits/tree/main/Linux%20Kernel/LPE%20-%20CVE-2017-16995) | Linux Kernel | LPE | 7.8 |
| [CVE-2016-0099](https://github.com/galletitaconpate/verified-exploits/tree/main/Microsoft%20Windows%20Secondary%20Logon/LPE%20-%20CVE-2016-0099) | Microsoft Windows Secondary Logon | LPE | 7.8 |
| [CVE-2015-1397](https://github.com/galletitaconpate/verified-exploits/tree/main/Magento/SQLi%20-%20CVE-2015-1397) | Magento | SQL Injection | `Medium` |
| [CVE-2015-1398](https://github.com/galletitaconpate/verified-exploits/tree/main/Magento/RCE%20-%20CVE-2015-1398) | Magento | RCE | `Medium` |
| [CVE-2015-6967](https://github.com/galletitaconpate/verified-exploits/tree/main/Nibbleblog/RCE%20-%20CVE-2015-6967) | Nibbleblog | RCE | `Medium` |
| [CVE-2014-6271](https://github.com/galletitaconpate/verified-exploits/tree/main/GNU%20Bash/RCE%20-%20CVE-2014-6271) | GNU Bash | RCE | **9.8** |
| [CVE-2014-6287](https://github.com/galletitaconpate/verified-exploits/tree/main/HFS%20%28HttpFileServer%29/RCE%20-%20CVE-2014-6287) | HFS (HttpFileServer) | RCE | **9.8** |
| [CVE-2014-0160](https://github.com/galletitaconpate/verified-exploits/tree/main/OpenSSL/InfoDisclosure%20-%20CVE-2014-0160) | OpenSSL | Info Disclosure | 7.5 |
| [CVE-2011-2523](https://github.com/galletitaconpate/verified-exploits/tree/main/vsftpd/RCE%20-%20CVE-2011-2523) | vsftpd | RCE | **9.8** |
| [CVE-2011-1249](https://github.com/galletitaconpate/verified-exploits/tree/main/Microsoft%20Windows%20AFD/LPE%20-%20CVE-2011-1249) | Microsoft Windows AFD | LPE | `High` |
| [CVE-2010-2075](https://github.com/galletitaconpate/verified-exploits/tree/main/UnrealIRCd/RCE%20-%20CVE-2010-2075) | UnrealIRCd | RCE | `High` |
| [CVE-2009-2265](https://github.com/galletitaconpate/verified-exploits/tree/main/Adobe%20ColdFusion/RCE%20-%20CVE-2009-2265) | Adobe ColdFusion | RCE | `High` |
| [CVE-2008-4250](https://github.com/galletitaconpate/verified-exploits/tree/main/Microsoft%20Windows%20Server%20Service/RCE%20-%20CVE-2008-4250) | Microsoft Windows Server Service | RCE | **9.8** |
| [CVE-2007-2447](https://github.com/galletitaconpate/verified-exploits/tree/main/Samba/RCE%20-%20CVE-2007-2447) | Samba | RCE | `Medium` |
| [ADV190005](https://github.com/galletitaconpate/verified-exploits/tree/main/ADV190005) | HTTP/2 | DoS | 7.5 |
| [ADV20210328-PHP-GIT-BACKDOOR](https://github.com/galletitaconpate/verified-exploits/tree/main/PHP/RCE%20-%20ADV20210328-PHP-GIT-BACKDOOR) | PHP | RCE | — |

</details>

<!-- exploit-development:end -->

---

<!-- certifications:start -->
## certifications

| Badge | Name | Status |
|-------|------|--------|
| 🟩 CPTS | [HTB Certified Penetration Testing Specialist](https://academy.hackthebox.com/achievement/badge/34f5ae2f-8b59-11f1-82d1-bea50ffe6cb4) | ✅ July 2026 |
| 🟩 CJCA | [HTB Certified Junior Cybersecurity Associate](https://academy.hackthebox.com/achievement/badge/e5289ccc-8698-11f1-82d1-bea50ffe6cb4) | ✅ July 2026 |
| 🟩 COAE | [HTB Certified Offensive AI Expert](https://academy.hackthebox.com/achievement/badge/5f61e864-73aa-11f1-82d1-bea50ffe6cb4) | ✅ June 2026 |
| 🟩 CWES | [HTB Certified Web Exploitation Specialist](https://academy.hackthebox.com/achievement/badge/be48e831-d1cd-11f0-9254-bea50ffe6cb4) | ✅ December 2025 |
| 🟩 CEHv12 | Certified Ethical Hacker (CEH v12) | ✅ December 2023 |
| 🟩 eWPT | Web Application Penetration Tester | ✅ February 2022 |
| 🟩 CS50-AI | CS50 Introduction to AI with Python | ✅ February 2022 |
| 🟩 PY-RESEARCH | Using Python for Research | ✅ February 2022 |
| 🟩 CYBERCRIME | Expert in Cybercrime and Cybersecurity Investigation | ✅ July 2022 |
| 🟩 eJPT | Junior Penetration Tester | ✅ May 2021 |
| 🟩 BURP-ADV | Advanced Burp Suite | ✅ November 2019 |
| 🟩 PY-ADV | Advanced Python | ✅ February 2019 |
| 🟩 QA-TESTER | Software Tester QA | ✅ June 2018 |
| 🟩 EH-PENTEST | Ethical Hacking and Pentesting | ✅ June 2018 |
| 🧪 Dante | HTB Pro Lab | ✅ June 2026 |
| 🧪 P.O.O. | HTB Pro Lab | ✅ June 2026 |
| 🧪 Mythical | HTB Pro Lab | ✅ June 2026 |
| 🧪 Unintended | HTB Pro Lab | ✅ Completed |
| 🟦 CWPE | HTB Wi-Fi Penetration Tester | 🔄 34.1% |
| 🟦 CWEE | HTB Certified Web Exploitation Expert | 🔄 19.2% |
| 🟦 CAPE | HTB Certified Active Directory Pentesting Expert | 🔄 14.2% |

<!-- certifications:end -->

---

## stack

```python
skills = {
    "web":     ["SQLi", "XSS", "IDOR", "XXE", "SSRF", "Auth bypass", "SSTI", "Deserialization"],
    "infra":   ["Active Directory", "Kerberos", "NTLM Relay", "ADCS", "Pivoting"],
    "mobile":  ["Android static/dynamic analysis", "iOS", "Frida", "MobSF"],
    "cloud":   ["AWS", "Azure", "GCP"],
    "wifi":    ["WPA/WPA2/WPA3", "WPS", "Evil Twin", "PMKID", "Corp 802.1X"],
    "ai_sec":  ["Prompt Injection", "LLM Output Attacks", "AI Evasion", "Model Privacy"],
    "tools":   ["Burp Suite", "Metasploit", "ffuf", "BloodHound", "Wireshark", "Sliver"],
    "code":    ["Python", "Bash", "JavaScript", "PowerShell", "C++"],
}
```

---

<p align="center">
  <sub>⚠️ All security research conducted with explicit authorization or within established bug bounty programs.</sub>
</p>

