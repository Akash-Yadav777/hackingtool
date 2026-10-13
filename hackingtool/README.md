<div align="center">

# HackingTool

**All-in-One Hacking Tool for Security Researchers & Pentesters**

[![License](https://img.shields.io/github/license/Z4nzu/hackingtool?style=flat-square)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Version](https://img.shields.io/badge/version-2.0.0-brightgreen?style=flat-square)](#)
[![Platform](https://img.shields.io/badge/platform-Linux%20%7C%20Kali%20%7C%20Parrot%20%7C%20macOS-informational?style=flat-square)](#)
[![Stars](https://img.shields.io/github/stars/Z4nzu/hackingtool?style=flat-square)](https://github.com/Z4nzu/hackingtool/stargazers)
[![Forks](https://img.shields.io/github/forks/Z4nzu/hackingtool?style=flat-square)](https://github.com/Z4nzu/hackingtool/network/members)
[![Issues](https://img.shields.io/github/issues/Z4nzu/hackingtool?style=flat-square)](https://github.com/Z4nzu/hackingtool/issues)
[![Last Commit](https://img.shields.io/github/last-commit/Z4nzu/hackingtool?style=flat-square)](https://github.com/Z4nzu/hackingtool/commits/master)

</div>

---

## What's New in v2.0.0

- Python 3.10+ required — all Python 2 code removed
- OS-aware menus — Linux-only tools are hidden automatically on macOS
- Archived tools (Python 2, unmaintained) shown in a separate sub-menu
- All `os.chdir()` bugs fixed — tools install to `~/.hackingtool/tools/`
- No more `sudo git clone` — tools install to user home, no root needed
- 22 new modern tools added across 6 categories
- Rich terminal UI with shared theme — no more 32 different console instances
- Iterative menus — no more recursion stack overflow on deep navigation
- Docker image builds locally — no unverified external images
- `requirements.txt` cleaned — removed unused flask/boxes/lolcat/requests

---

## Menu

- [Anonymously Hiding Tools](#anonymously-hiding-tools)
- [Information gathering tools](#information-gathering-tools)
- [Wordlist Generator](#wordlist-generator)
- [Wireless attack tools](#wireless-attack-tools)
- [SQL Injection Tools](#sql-injection-tools)
- [Phishing attack tools](#phishing-attack-tools)
- [Web Attack tools](#web-attack-tools)
- [Post exploitation tools](#post-exploitation-tools)
- [Forensic tools](#forensic-tools)
- [Payload creation tools](#payload-creation-tools)
- [Exploit framework](#exploit-framework)
- [Reverse engineering tools](#reverse-engineering-tools)
- [DDOS Attack Tools](#ddos-attack-tools)
- [Remote Administrator Tools (RAT)](#remote-administrator-tools--rat-)
- [XSS Attack Tools](#xss-attack-tools)
- [Steganography Tools](#steganography-tools)
- [Active Directory Tools](#active-directory-tools)
- [Cloud Security Tools](#cloud-security-tools)
- [Mobile Security Tools](#mobile-security-tools)
- [Other tools](#other-tools)
    - [SocialMedia Bruteforce](#socialmedia-bruteforce)
    - [Android Hacking tools](#android-hacking-tools)
    - [IDN Homograph Attack](#idn-homograph-attack)
    - [Email Verify tools](#email-verify-tools)
    - [Hash cracking tools](#hash-cracking-tools)
    - [Wifi Deauthenticate](#wifi-deauthenticate)
    - [SocialMedia Finder](#socialmedia-finder)
    - [Payload Injector](#payload-injector)
    - [Web crawling](#web-crawling)
    - [Mix tools](#mix-tools)


---

## Tools

### Anonymously Hiding Tools
- [Anonymously Surf](https://github.com/Und3rf10w/kali-anonsurf)
- [Multitor](https://github.com/trimstray/multitor)
### Information gathering tools
- [Network Map (nmap)](https://github.com/nmap/nmap)
- [Dracnmap](https://github.com/Screetsec/Dracnmap)
- Port scanning
- Host to IP 
- [Xerosploit](https://github.com/LionSec/xerosploit)
- [RED HAWK (All In One Scanning)](https://github.com/Tuhinshubhra/RED_HAWK)
- [ReconSpider(For All Scanning)](https://github.com/bhavsec/reconspider)
- IsItDown (Check Website Down/Up)
- [Infoga - Email OSINT](https://github.com/m4ll0k/Infoga)
- [ReconDog](https://github.com/s0md3v/ReconDog)
- [Striker](https://github.com/s0md3v/Striker)
- [SecretFinder (like API & etc)](https://github.com/m4ll0k/SecretFinder)
- [Find Info Using Shodan](https://github.com/m4ll0k/Shodanfy.py)
- [Port Scanner - rang3r](https://github.com/floriankunushevci/rang3r)
- [Breacher](https://github.com/s0md3v/Breacher)
- [theHarvester (OSINT)](https://github.com/laramies/theHarvester)
- [Amass (Attack Surface Mapping)](https://github.com/owasp-amass/amass)
- [Masscan (Fast Port Scanner)](https://github.com/robertdavidgraham/masscan)
- [RustScan (Modern Port Scanner)](https://github.com/RustScan/RustScan)
- [Holehe (Email → Social Accounts)](https://github.com/megadose/holehe)
- [Maigret (Username OSINT)](https://github.com/soxoj/maigret)
- [httpx (HTTP Toolkit)](https://github.com/projectdiscovery/httpx)
- [SpiderFoot (OSINT Automation)](https://github.com/smicallef/spiderfoot)
- [Subfinder (Subdomain Enumeration)](https://github.com/projectdiscovery/subfinder)
- [TruffleHog (Secret Scanner)](https://github.com/trufflesecurity/trufflehog)
- [Gitleaks (Git Secret Scanner)](https://github.com/gitleaks/gitleaks)
### Wordlist Generator
- [Cupp](https://github.com/Mebus/cupp)
- [WordlistCreator](https://github.com/Z4nzu/wlcreator)
- [Goblin WordGenerator](https://github.com/UndeadSec/GoblinWordGenerator.git)
- [Password list (1.4 Billion Clear Text Password)](https://github.com/Viralmaniar/SMWYG-Show-Me-What-You-Got)
- [Hashcat (Password Cracker)](https://github.com/hashcat/hashcat)
- [John the Ripper](https://github.com/openwall/john)
- [haiti (Hash Type Identifier)](https://github.com/noraj/haiti)
### Wireless attack tools
- [WiFi-Pumpkin](https://github.com/P0cL4bs/wifipumpkin3)
- [pixiewps](https://github.com/wiire/pixiewps)
- [Bluetooth Honeypot GUI Framework](https://github.com/andrewmichaelsmith/bluepot)
- [Fluxion](https://github.com/FluxionNetwork/fluxion)
- [Wifiphisher](https://github.com/wifiphisher/wifiphisher)
- [Wifite](https://github.com/derv82/wifite2)
- [EvilTwin](https://github.com/Z4nzu/fakeap)
- [Fastssh](https://github.com/Z4nzu/fastssh)
- Howmanypeople
- [Airgeddon (Wireless Attack Suite)](https://github.com/v1s1t0r1sh3r3/airgeddon)
- [hcxdumptool (PMKID Capture)](https://github.com/ZerBea/hcxdumptool)
- [hcxtools (PMKID/Hash Conversion)](https://github.com/ZerBea/hcxtools)
- [Bettercap (Network/WiFi/BLE MITM)](https://github.com/bettercap/bettercap)
### SQL Injection Tools
- [Sqlmap tool](https://github.com/sqlmapproject/sqlmap)
- [NoSqlMap](https://github.com/codingo/NoSQLMap)
- [Damn Small SQLi Scanner](https://github.com/stamparm/DSSS)
- [Explo](https://github.com/dtag-dev-sec/explo)
- [Blisqy - Exploit Time-based blind-SQL injection](https://github.com/JohnTroony/Blisqy)
- [Leviathan - Wide Range Mass Audit Toolkit](https://github.com/leviathan-framework/leviathan)
- [SQLScan](https://github.com/Cvar1984/sqlscan)
### Phishing attack tools
- [Autophisher RK](https://github.com/CodingRanjith/autophisher)
- [Pyphisher](https://github.com/KasRoudra/PyPhisher)
- [AdvPhishing](https://github.com/Ignitetch/AdvPhishing)
- [Setoolkit](https://github.com/trustedsec/social-engineer-toolkit)
- [SocialFish](https://github.com/UndeadSec/SocialFish)
- [HiddenEye](https://github.com/Morsmalleo/HiddenEye)
- [Evilginx3](https://github.com/kgretzky/evilginx2)
- [I-See_You](https://github.com/Viralmaniar/I-See-You)
- [SayCheese](https://github.com/hangetzzu/saycheese)
- [QR Code Jacking](https://github.com/cryptedwolf/ohmyqr)
- [BlackEye](https://github.com/An0nUD4Y/blackeye)
- [ShellPhish](https://github.com/An0nUD4Y/shellphish)
- [Thanos](https://github.com/TridevReddy/Thanos)
- [QRLJacking](https://github.com/OWASP/QRLJacking)
- [BlackPhish](https://github.com/iinc0gnit0/BlackPhish)
- [Maskphish](https://github.com/jaykali/maskphish)
- [dnstwist](https://github.com/elceef/dnstwist)
### Web Attack tools
- [Web2Attack](https://github.com/santatic/web2attack)
- Skipfish
- [SubDomain Finder](https://github.com/aboul3la/Sublist3r)
- [CheckURL](https://github.com/UndeadSec/checkURL)
- [Blazy(Also Find ClickJacking)](https://github.com/UltimateHackers/Blazy)
- [Sub-Domain TakeOver](https://github.com/edoardottt/takeover)
- [Dirb](https://gitlab.com/kalilinux/packages/dirb)
- [Nuclei (Vulnerability Scanner)](https://github.com/projectdiscovery/nuclei)
- [ffuf (Web Fuzzer)](https://github.com/ffuf/ffuf)
- [Feroxbuster (Directory Brute Force)](https://github.com/epi052/feroxbuster)
- [Nikto (Web Server Scanner)](https://github.com/sullo/nikto)
- [wafw00f (WAF Detector)](https://github.com/EnableSecurity/wafw00f)
- [Katana (Web Crawler)](https://github.com/projectdiscovery/katana)
- [Gobuster (Dir/DNS/Vhost Brute Force)](https://github.com/OJ/gobuster)
- [Dirsearch (Web Path Discovery)](https://github.com/maurosoria/dirsearch)
- [OWASP ZAP (Web App Scanner)](https://github.com/zaproxy/zaproxy)
- [testssl.sh (TLS/SSL Checker)](https://github.com/drwetter/testssl.sh)
- [Arjun (HTTP Parameter Discovery)](https://github.com/s0md3v/Arjun)
- [Caido (Web Security Auditing)](https://github.com/caido/caido)
- [mitmproxy (Intercepting Proxy)](https://github.com/mitmproxy/mitmproxy)
### Post exploitation tools
- [Vegile - Ghost In The Shell](https://github.com/Screetsec/Vegile)
- [Chrome Keylogger](https://github.com/UndeadSec/HeraKeylogger)
- [pwncat-cs (Reverse Shell Handler)](https://github.com/calebstewart/pwncat)
- [Sliver (C2 Framework)](https://github.com/BishopFox/sliver)
- [Havoc (C2 Framework)](https://github.com/HavocFramework/Havoc)
- [PEASS-ng — LinPEAS/WinPEAS (Priv Esc)](https://github.com/peass-ng/PEASS-ng)
- [Ligolo-ng (Tunneling/Pivoting)](https://github.com/nicocha30/ligolo-ng)
- [Chisel (HTTP Tunnel)](https://github.com/jpillora/chisel)
- [Evil-WinRM (Windows Remote Shell)](https://github.com/Hackplayers/evil-winrm)
- [Mythic (C2 Platform)](https://github.com/its-a-feature/Mythic)
### Forensic tools
- Autopsy
- Wireshark
- [Bulk extractor](https://github.com/simsong/bulk_extractor)
- [Disk Clone and ISO Image Acquire](https://guymager.sourceforge.io/)
- [Toolsley](https://www.toolsley.com/)
- [Volatility 3 (Memory Forensics)](https://github.com/volatilityfoundation/volatility3)
- [Binwalk (Firmware Analysis)](https://github.com/ReFirmLabs/binwalk)
- [pspy (Process Monitor — No Root)](https://github.com/DominicBreuker/pspy)
### Payload creation tools
- [The FatRat](https://github.com/Screetsec/TheFatRat)
- [Brutal](https://github.com/Screetsec/Brutal)
- [Stitch](https://nathanlopez.github.io/Stitch)
- [MSFvenom Payload Creator](https://github.com/g0tmi1k/msfpc)
- [Venom Shellcode Generator](https://github.com/r00t-3xp10it/venom)
- [Spycam](https://github.com/indexnotfound404/spycam)
- [Mob-Droid](https://github.com/kinghacker0/Mob-Droid)
- [Enigma](https://github.com/UndeadSec/Enigma)
### Exploit framework
- [RouterSploit](https://github.com/threat9/routersploit)
- [WebSploit](https://github.com/The404Hacking/websploit )
- [Commix](https://github.com/commixproject/commix)
- [Web2Attack](https://github.com/santatic/web2attack)
### Reverse engineering tools
- [Androguard](https://github.com/androguard/androguard )
- [Apk2Gold](https://github.com/lxdvs/apk2gold )
- [JadX](https://github.com/skylot/jadx)
- [Ghidra (NSA Reverse Engineering)](https://github.com/NationalSecurityAgency/ghidra)
- [Radare2 (RE Framework)](https://github.com/radareorg/radare2)
### DDOS Attack Tools
- [DDoS](https://github.com/the-deepnet/ddos)
- SlowLoris
- [Asyncrone | Multifunction SYN Flood DDoS Weapon](https://github.com/fatihsnsy/aSYNcrone)
- [UFOnet](https://github.com/epsylon/ufonet)
- [GoldenEye](https://github.com/jseidl/GoldenEye)
- [SaphyraDDoS](https://github.com/anonymous24x7/Saphyra-DDoS)
### Remote Administrator Tools (RAT)
- [Pyshell](https://github.com/knassar702/pyshell)
### XSS Attack Tools
- [DalFox (Finder of XSS)](https://github.com/hahwul/dalfox)
- [XSS Payload Generator](https://github.com/capture0x/XSS-LOADER.git)
- [Extended XSS Searcher and Finder](https://github.com/Damian89/extended-xss-search)
- [XSS-Freak](https://github.com/PR0PH3CY33/XSS-Freak)
- [XSpear](https://github.com/hahwul/XSpear)
- [XSSCon](https://github.com/menkrep1337/XSSCon)
- [XanXSS](https://github.com/Ekultek/XanXSS)
- [Advanced XSS Detection Suite](https://github.com/UltimateHackers/XSStrike)
- [RVuln](https://github.com/iinc0gnit0/RVuln)
### Steganography Tools
- SteganoHide
- StegnoCracker
- [StegoCracker](https://github.com/W1LDN16H7/StegoCracker)
- [Whitespace](https://github.com/beardog108/snow10)
### Active Directory Tools
- [BloodHound (AD Attack Paths)](https://github.com/BloodHoundAD/BloodHound)
- [NetExec — nxc (Network Pentesting)](https://github.com/Pennyw0rth/NetExec)
- [Impacket (Network Protocol Tools)](https://github.com/fortra/impacket)
- [Responder (LLMNR/NBT-NS Poisoner)](https://github.com/lgandx/Responder)
- [Certipy (AD Certificate Abuse)](https://github.com/ly4k/Certipy)
- [Kerbrute (Kerberos Brute Force)](https://github.com/ropnop/kerbrute)
### Cloud Security Tools
- [Prowler (Cloud Security Scanner)](https://github.com/prowler-cloud/prowler)
- [ScoutSuite (Multi-Cloud Auditing)](https://github.com/nccgroup/ScoutSuite)
- [Pacu (AWS Exploitation Framework)](https://github.com/RhinoSecurityLabs/pacu)
- [Trivy (Container/K8s Scanner)](https://github.com/aquasecurity/trivy)
### Mobile Security Tools
- [MobSF (Mobile Security Framework)](https://github.com/MobSF/Mobile-Security-Framework-MobSF)
- [Frida (Dynamic Instrumentation)](https://github.com/frida/frida)
- [Objection (Mobile Runtime Exploration)](https://github.com/sensepost/objection)
### Other tools
#### SocialMedia Bruteforce
- [Instagram Attack](https://github.com/chinoogawa/instaBrute)
- [AllinOne SocialMedia Attack](https://github.com/Matrix07ksa/Brute_Force)
- [Facebook Attack](https://github.com/Matrix07ksa/Brute_Force)
- [Application Checker](https://github.com/jakuta-tech/underhanded)
#### Android Hacking tools
- [Keydroid](https://github.com/F4dl0/keydroid)
- [MySMS](https://github.com/papusingh2sms/mysms)
- [Lockphish (Grab target LOCK PIN)](https://github.com/JasonJerry/lockphish)
- [DroidCam (Capture Image)](https://github.com/kinghacker0/WishFish)
- [EvilApp (Hijack Session)](https://github.com/crypticterminal/EvilApp)
- [HatCloud(Bypass CloudFlare for IP)](https://github.com/HatBashBR/HatCloud)
#### IDN Homograph Attack
- [EvilURL](https://github.com/UndeadSec/EvilURL)
#### Email Verify tools
- [Knockmail](https://github.com/heywoodlh/KnockMail)
#### Hash cracking tools
- [Hash Buster](https://github.com/s0md3v/Hash-Buster)
#### Wifi Deauthenticate
- [WifiJammer-NG](https://github.com/MisterBianco/wifijammer-ng)
- [KawaiiDeauther](https://github.com/aryanrtm/KawaiiDeauther)
#### SocialMedia Finder
- [Find SocialMedia By Facial Recognation System](https://github.com/Greenwolf/social_mapper)
- [Find SocialMedia By UserName](https://github.com/xHak9x/finduser)
- [Sherlock](https://github.com/sherlock-project/sherlock)
- [SocialScan | Username or Email](https://github.com/iojw/socialscan)
#### Payload Injector
- [Debinject](https://github.com/UndeadSec/Debinject)
- [Pixload](https://github.com/chinarulezzz/pixload)
#### Web crawling
- [Gospider](https://github.com/jaeles-project/gospider)
#### Mix tools
- Terminal Multiplexer
- [Crivo](https://github.com/GMDSantana/crivo)


---

## Contributing — Add a New Tool

Want a tool included? **Raise an Issue or open a PR** using the templates below.

### Issue (Tool Request)

> Title format: `[Tool Request] ToolName — Category`
> Example: `[Tool Request] Subfinder — Information Gathering`

Use the **Tool Request** issue template and fill in all required fields:
tool name, GitHub URL, category, supported OS, install command, and why it should be added.

### Pull Request

> Title format: `[New Tool] ToolName — Category`
> Example: `[New Tool] Subfinder — Information Gathering`

Use the **PR template** checklist. Key requirements:

1. Add your tool class to the correct `tools/*.py` file
2. Set `TITLE`, `DESCRIPTION`, `INSTALL_COMMANDS`, `RUN_COMMANDS`, `PROJECT_URL`
3. Set `SUPPORTED_OS = ["linux"]` or `["linux", "macos"]` appropriately
4. Add the instance to the `TOOLS` list in the collection class
5. Test install and run locally before submitting

Issues or PRs that don't follow the title format may be closed without review.

---

## Installation

### One-liner (recommended)

```bash
curl -sSL https://raw.githubusercontent.com/Z4nzu/hackingtool/master/install.sh | sudo bash
```

This handles everything — installs prerequisites, clones the repo, sets up a venv, and creates the `hackingtool` command.

### Manual install

```bash
git clone https://github.com/Z4nzu/hackingtool.git
cd hackingtool
sudo python3 install.py   # detects local source, copies instead of re-cloning
```

Then run:
```bash
hackingtool
```

## Docker

### Step 1 — Clone the repository

```bash
git clone https://github.com/Z4nzu/hackingtool.git
cd hackingtool
```

### Step 2 — Build the image

```bash
docker build -t hackingtool .
```

> First build takes a few minutes (Kali base + apt packages). Subsequent builds are fast thanks to BuildKit layer caching.

### Step 3 — Run

**Option A — Direct (no Compose):**
```bash
docker run -it --rm hackingtool
```

**Option B — With Docker Compose (recommended):**
```bash
# Start in background
docker compose up -d

# Open an interactive shell
docker exec -it hackingtool bash

# Then launch the tool inside the container
python3 hackingtool.py
```

**Option C — Dev mode (live source mount, changes reflected without rebuild):**
```bash
docker compose --profile dev up
docker exec -it hackingtool-dev bash
```

### Stopping

```bash
docker compose down        # stop and remove container
docker compose down -v     # also remove the tools data volume
```

## Requirements

- Python 3.10+
- Linux (Kali, Parrot, Ubuntu) or macOS
- Go 1.21+ (for nuclei, ffuf, amass, httpx, katana, dalfox)
- Ruby (for haiti)

```bash
pip install -r requirements.txt
```

---

## Star History

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=Z4nzu/hackingtool&type=Date&theme=dark" />
  <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=Z4nzu/hackingtool&type=Date" />
  <img alt="HackingTool Star History Chart" src="https://api.star-history.com/svg?repos=Z4nzu/hackingtool&type=Date" />
</picture>

---

## Social

[![Twitter](https://img.shields.io/twitter/url?color=%231DA1F2&label=follow&logo=twitter&logoColor=%231DA1F2&style=flat-square&url=https%3A%2F%2Ftwitter.com%2F_Zinzu07)](https://twitter.com/_Zinzu07)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&link=https://github.com/Z4nzu/)](https://github.com/Z4nzu/)

> **Please don't use for illegal activity.**
> Thanks to all original authors of the tools included in hackingtool.

Your favourite tool is not listed? [Suggest it here](https://github.com/Z4nzu/hackingtool/issues/new?template=tool_request.md)
