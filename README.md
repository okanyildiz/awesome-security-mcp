<a id="awesome-security-mcp"></a>

<h1 align="center"><a href="https://modelcontextprotocol.io"><img src="assets/banner-mcp.png" alt="Awesome Security MCP"></a></h1>

<div align="center">


A curated list of Model Context Protocol (MCP) servers, clients, and resources for cybersecurity.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](CONTRIBUTING.md)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-blue.svg)](CONTRIBUTING.md)
[![GitHub stars](https://img.shields.io/github/stars/okanyildiz/awesome-security-mcp?style=social)](https://github.com/okanyildiz/awesome-security-mcp)

**🛡️ Security MCP • 🔌 Official Servers • 🌐 Popular Servers • 💻 Clients & Hosts • 🔐 Best Practices**

*Accuracy over coverage. Entries are checked for existence, description accuracy and maintenance status before merging.*

</div>

---

## 📑 Contents

- [Security-Specific MCP Servers](#security-specific-mcp-servers)
- [Official MCP Servers](#official-mcp-servers)
- [Security Platforms & Vendor MCP Servers](#security-platforms--vendor-mcp-servers)
- [MCP Clients & Hosts](#mcp-clients--hosts)
- [MCP Security Best Practices](#mcp-security-best-practices)
- [Learning Resources](#learning-resources)
- [How this list is verified](#how-this-list-is-verified)

---

## Security-Specific MCP Servers

MCP servers for security operations, forensics, OSINT, threat intelligence and penetration testing. Archived and deprecated entries are maintained separately in [ARCHIVED.md](ARCHIVED.md).

### Reconnaissance, OSINT, vulnerability testing and reverse engineering

- :new: [AbuseIPDB MCP (official)](https://www.abuseipdb.com/tutorial/abuseipdb-mcp) - First-party hosted and local MCP server for IP reputation and abuse reports ([source](https://github.com/AbuseIPDB/AbuseIPDB-MCP)); local server is beta/read-only.
- :new: [Acunetix MCP Server](https://github.com/McxM123/acunetix-mcp-server) - Manages targets, scans, vulnerabilities and reports through Acunetix/Invicti APIs (community).
- :star: [Binary Ninja MCP](https://github.com/fosdickio/binary_ninja_mcp) - Binary Ninja plugin, MCP server and bridge for decompilation, disassembly, cross-references, type manipulation and binary editing.
- :new: [Burp AI Agent / Custom AI Agent](https://github.com/six2dez/burp-ai-agent) - Community Burp Suite extension, now named Custom AI Agent, with MCP access, scoped targets, approval tiers and AI-assisted scanning.
- [Burp Suite MCP Server](https://portswigger.net/bappstore/9952290f04ed4f628e624d0aa9dccebc) - PortSwigger's Burp extension for web application security testing connects AI clients to Burp through Streamable HTTP, legacy SSE or a stdio proxy, with approval controls ([source](https://github.com/PortSwigger/mcp-server)).
- [Censys Platform MCP](https://docs.censys.com/docs/platform-mcp-server) - Censys-hosted Internet Map search, asset investigation, CVE research, query generation and attack-surface analysis.
- :new: [CVE MCP Server](https://github.com/mukul975/cve-mcp-server) - CVE research and triage across NVD, EPSS, CISA KEV, OSV and other vulnerability and threat-intelligence sources, with stdio and Streamable HTTP.
- :new: [Darknet MCP](https://github.com/badchars/darknet-mcp-server) - Sixty-six tools for breach, ransomware, Tor, malware-feed and blockchain intelligence, including HIBP and IntelX integrations; handles sensitive breach, credential and malware data.
- :new: [DeHashed MCP](https://github.com/jstjep00/dehashed-mcp) - Seventeen FastMCP tools covering DeHashed searches, balance and pagination, with stdio/HTTP and policy-based authorization; handles sensitive breach and credential data.
- :star: [GhidraMCP](https://github.com/LaurieWired/GhidraMCP) - Ghidra plugin and MCP bridge for reverse engineering, decompilation, symbols and program inspection.
- [GreyNoise MCP](https://github.com/GreyNoise-Intelligence/greynoise-mcp-server) - Vendor-maintained IP context, GNQL search and threat-intelligence investigation (small adoption so far).
- :star: [Have I Been Pwned MCP](https://haveibeenpwned.com/Docs/MCP) - Official hosted server for breach metadata, account/domain exposure, pastes, stealer logs and k-anonymity password-range queries; OAuth and applicable subscriptions protect non-public data.
- [HIBP MCP Server](https://github.com/darrenjrobinson/HIBP-MCP-Server) - Local npm/stdio alternative for HIBP breach, paste and password queries.
- :new: [IDA MCP (Hex-Rays)](https://github.com/HexRaysSA/ida-mcp) - Official Hex-Rays server for IDA 9.4+, supporting GUI and headless reverse engineering over stdio or Streamable HTTP.
- :star: [IDA Pro MCP](https://github.com/mrexodia/ida-pro-mcp) - Community IDA Pro reverse-engineering server with GUI and headless idalib modes; its README recommends the official Hex-Rays IDA MCP server instead.
- :star: [JADX AI MCP](https://github.com/zinja-coder/jadx-ai-mcp) - JADX plugin and MCP server for Android decompilation, code inspection, renaming, comments, cross-references and debugging.
- :new: [LeakIX MCP](https://github.com/LeakIX/leakix-mcp) - Official server exposing service/leak search, host and domain lookup, subdomains, quick recon, exposure reports and related-target discovery.
- :new: [Maltego MCP](https://github.com/lidless-labs/maltego-mcp) - Thirteen stdio tools for authoring Maltego .mtgx graphs and running WHOIS, DNS, ASN and crt.sh lookups; it writes Maltego graphs rather than remotely operating Maltego's commercial transform API.
- :star: [MetasploitMCP](https://github.com/GH05TCREW/MetasploitMCP) - Community implementation controlling Metasploit Framework penetration-testing and post-exploitation operations through MCP.
- [Nessus MCP Server](https://github.com/Cyreslab-AI/nessus-mcp-server) - Controls a Nessus instance through its REST API for vulnerability scanning and analysis (community).
- :new: [OpenVAS MCP](https://github.com/greenbone-hive/openvas-mcp) - Manages Greenbone/OpenVAS vulnerability-scanning targets, tasks, scans, reports and audits through a Rust GVM API gateway (vendor-maintained).
- :new: [OSINT Toolbox MCP](https://github.com/renkagod/osint-toolbox-mcp) - Seventeen stdio tools wrapping Sherlock, Maigret, Blackbird, Holehe, GHunt, theHarvester, SpiderFoot, Subfinder, PhoneInfoga and others, plus built-in crt.sh and Wayback lookups (Docker and uvx).
- :new: [Qualys MCP](https://github.com/nelssec/qualys-mcp) - Query Qualys vulnerability, cloud, endpoint, container and compliance data (community).
- :star: [radare2-mcp](https://github.com/radareorg/radare2-mcp) - Radare2 organization's server for disassembly and binary analysis, over stdio or HTTP MCP with optional authentication and sessions.
- :new: [Rapid7 bulk-export MCP](https://github.com/rapid7/rapid7-bulk-export-mcp) - Loads Rapid7 bulk exports into DuckDB for MCP-based vulnerability, asset, policy and remediation analysis (official, best-effort support).
- :new: [RedAmon](https://github.com/samugit83/redamon) - Self-hosted AI penetration-testing framework: attack-surface graphing, autonomous exploitation from a Kali sandbox with human approval gates, and auto-fix PRs; MCP both ways (plug in any MCP server as a tool, or drive RedAmon from Claude Code or your own agent).
- :new: [ReversingLabs Spectra Assure MCP](https://github.com/reversinglabs/rl-mcp-community) - Checks packages and manifests for malware, vulnerabilities, tampering and policy violations (official).
- :new: [SecurityTrails MCP](https://github.com/pipeworx-io/mcp-securitytrails) - Third-party hosted gateway plus an stdio bridge for SecurityTrails domain reconnaissance, subdomain enumeration, DNS history and WHOIS lookups, with shared Pipeworx meta-tools and no offline mode (experimental community).
- [Shodan MCP Server](https://github.com/Cyreslab-AI/shodan-mcp-server) - Shodan host/network reconnaissance, InternetDB, CVE lookup and alerting (community); the upstream Exploits API is no longer serving requests, so exploit lookup currently returns an error.
- :new: [Tenable.io MCP](https://github.com/polarpoint-io/tenable-mcp) - Exposes Tenable.io through pyTenable for vulnerability and exposure workflows (community).
- :new: [urlscan.io MCP](https://github.com/pipeworx-io/mcp-urlscan-io) - URL and phishing investigation through search, result retrieval, domain/IP convenience queries and scan submission, using a hosted MCP gateway or local stdio bridge (independent Pipeworx integration, not urlscan.io).
- :star: [user-scanner](https://github.com/kaifcodec/user-scanner) - Email and username OSINT suite with native stdio MCP tools for account discovery, profile enrichment and cross-scan pivots.
- :new: [VirusTotal MCP](https://github.com/VirusTotal/virustotal-mcp) - Retrieves file, URL, domain and IP intelligence and supports explicitly requested submissions through VTAI, locally or through hosted OAuth (created September 2026).
- [Wayback Machine MCP](https://github.com/Mearman/mcp-wayback-machine) - MCP server and CLI for OSINT and historical web investigation through CDX searches, snapshot retrieval/saving and snapshot comparison.
- [Wireshark MCP](https://github.com/khuynh22/mcp-wireshark) - Uses Wireshark/tshark for live capture, PCAP parsing, display filters, stream following and JSON export.
- :shield: [ZoomEye MCP](https://github.com/zoomeye-ai/mcp_zoomeye) - Official stdio server for ZoomEye dork-based Internet-asset search, with caching, pagination, Docker and PyPI installation.

### Bug bounty platforms

- :shield: [HackerOne GraphQL MCP Server](https://github.com/Hacker0x01/hackerone-graphql-mcp-server) - Exposes HackerOne's GraphQL API for bug-bounty program and vulnerability-report workflows, with configurable mutation access (official).
- :new: [Intigriti MCP](https://github.com/alpernae/intigriti-mcp) - Access Intigriti Researcher API bug-bounty programs, vulnerability submissions, scopes and researcher workflows (community).
- :new: [YesWeHack MCP](https://github.com/Miro-sh/yeswehack-mcp) - Read-only access to YesWeHack hunter accounts for bug-bounty program, scope and report review, including credential/TOTP authentication (community, read-only).

### Offensive security and penetration testing

- :star: [Metasploit MCP Server (msfmcpd)](https://github.com/rapid7/metasploit-framework/blob/master/docs/metasploit-framework.wiki/How-to-use-Metasploit-MCP-Server.md) - Rapid7's native msfmcpd with 16 tools, read-only by default and dangerous actions gated off.
- [MetasploitMCP](https://github.com/GH05TCREW/MetasploitMCP) - Community implementation controlling Metasploit Framework operations through MCP.

- :new: [AdStrike](https://github.com/capture0x/AdStrike) - MCP-enabled Active Directory attack framework for reconnaissance, enumeration, exploitation and lateral movement, with wrappers for Impacket, NetExec, Certipy, BloodHound, PowerView, Rubeus and related tooling (community).
- :star: [Atomic Red Team MCP](https://github.com/cyberbuff/atomic-red-team-mcp) - Searches, validates and executes Atomic Red Team tests, with execution gated by configuration (community).
- :new: [AutoPentest](https://github.com/bhavsec/autopentest-ai) - Agentic web-pentesting MCP server with 68+ tools, specialized agent roles and OWASP WSTG/PortSwigger workflow material.
- :star: [BloodHound MCP](https://github.com/mwnickerson/bloodhound_mcp) - Thirteen composite tools for BloodHound CE/Enterprise attack-path analysis, Cypher, ADCS, OpenGraph and collection uploads (community, not SpecterOps-maintained).
- :new: [Bolt](https://github.com/CyberStrikeus/bolt) - MCP server/plugin aggregator for reconnaissance, vulnerability scanning and penetration testing, with 33 tools including Amass, Subfinder, crt.sh, Waybackurls, Masscan, RustScan, Gobuster, FFUF, WPScan and Impacket (AGPL).
- :new: [Caldera standalone MCP](https://github.com/cowboy-samurai/caldera-mcp) - Standalone MCP control surface for the Caldera adversary-emulation platform (community, early).
- :shield: [Cobalt Strike MCP Server](https://github.com/Cobalt-Strike/cobaltstrike-mcp-server) - Official HTTP MCP server for beacon listing, command execution, artifacts, downloads, screenshots and team-server information, with command allow/ask/deny policy (requires commercial Cobalt Strike 4.13+).
- :new: [Cymulate MCP tools](https://github.com/lyonzin/cymulate-mcp-tools) - Broad Cymulate API coverage for BAS, exposure validation, ASM and purple teaming (community).
- :new: [Empire MCP Plugin](https://github.com/BC-SECURITY/Empire-MCP-Plugin) - Empire 7+ plugin exposing C2 and post-exploitation operations as MCP tools with a shared registry and audit trail (official BC Security / Empire ecosystem).
- :star: [evil-winrm-py MCP mode](https://github.com/adityatelange/evil-winrm-py/blob/main/docs/usage.md#mcp-server-mode) - Native Streamable HTTP mode exposing WinRM login, command execution, logout and session listing (the Python implementation, not native MCP in the original Ruby Evil-WinRM).
- :star: [HexStrike AI](https://github.com/0x4m4/hexstrike-ai) - FastMCP bridge to its HTTP security-tool API with 150+ tools, including Amass, Subfinder, Masscan, RustScan, Gobuster, Dirsearch, Feroxbuster, FFUF, Nikto, WPScan, NetExec, Responder, Evil-WinRM and ZAP.
- :shield: [Horizon3 NodeZero MCP](https://github.com/horizon3ai/h3-cli/tree/public/mcp) - NodeZero penetration-testing Find/Fix/Verify workflows through local stdio/SSE/HTTP or a managed server (official).
- [MCP ZAP Server](https://github.com/dtkmn/mcp-zap-server) - Streamable HTTP ZAP operator for guided spidering, active/passive scans, API imports, findings and reports, with authentication and target policies (independent of OWASP/ZAP).
- :new: [mcp-ffuf](https://github.com/samcsta/mcp-ffuf) - Dedicated stdio server for path, parameter and vhost fuzzing, with mandatory host scope and request/rate limits.
- :shield: [MITRE Caldera MCP](https://github.com/mitre/mcp) - Caldera plugin whose internal MCP servers support CTI ingestion, ability/adversary creation and operation execution (official MITRE; plugin architecture, not a simple standalone wrapper).
- :new: [Mythic MCP](https://github.com/nbaertsch/Mythic-MCP) - Go MCP server exposing 147 Mythic C2 tools over stdio or HTTP, including callbacks, tasks, payloads, listeners and files.
- :new: [NetExec MCP](https://github.com/mpgn/NetExec-mcp) - Drives all ten NetExec protocols and modules for network and Active Directory penetration testing, with fail-closed NXC_SCOPE, suggest/recon/loot/full modes and audit logging (community project by mpgn, not the Pennyw0rth organization).
- :star: [Pentest MCP (DMontgomery40)](https://github.com/DMontgomery40/pentest-mcp) - Scoped assessment server for Nmap, Gobuster, Nikto, Subfinder, HTTPX, FFUF, Nuclei, Hydra, John and Hashcat, with durable evidence, time/target gates and authenticated HTTP.
- :new: [PenTest OSINT MCP Server](https://github.com/Hackerobi/pentest-osint-mcp-server) - Dockerized MCP server combining 25+ OSINT tools, including Recon-ng, Amass, WhatWeb and h8mail with LeakCheck support (experimental).
- :new: [Pentest-AI](https://github.com/0xSteph/pentest-ai) - FastMCP server for AI-driven web testing and bug bounty workflows; separates oracle-verified findings from unproven candidates and provides replayable proof capsules.
- :new: [Pentester-MCP](https://github.com/halilkirazkaya/pentester-mcp) - Unified FastMCP server for penetration testing with 235 generated wrappers (Recon-ng, Dirsearch, Naabu, Certipy, Impacket, Responder, mitm6 and Arachni); broad but early, not every wrapper is battle-tested.
- :new: [ProjectDiscovery MCP](https://github.com/intelligent-ears/pd-tools-mcp) - Stdio wrappers for Subfinder, DNSX, Naabu, HTTPX, Katana and Nuclei, plus an orchestrated recon workflow (community, not ProjectDiscovery-official).
- [SafeBreach MCP](https://github.com/SafeBreach/safebreach-mcp) - Natural-language access to SafeBreach breach-and-attack-simulation console operations (official).
- :star: [Sliver native MCP](https://github.com/BishopFox/sliver/blob/master/docs/sliver-docs/pages/docs/md/MCP.md) - Bishop Fox's native stdio and HTTP/SSE server for listing sessions/beacons and remote filesystem operations (experimental, not full C2 coverage).
- :new: [sliver-mcp](https://github.com/x746b/sliver-mcp) - Community complement to native Sliver MCP with roughly 74 tools for execution, listeners, implants, armory, recon and intel (no audit log, allowlist or read-only mode).
- :new: [Wappalyzer MCP](https://github.com/wappalyzer/mcp) - Official local stdio server wrapping the Wappalyzer API for reconnaissance and technology fingerprinting: site and subdomain lookup, credit balance and technology/category resources (API key required).
- :new: [WhatWeb MCP](https://github.com/devkindhq/whatweb-mcp) - Dockerized stdio server for WhatWeb fingerprinting, scan status and stored results.
- :new: [WPScan MCP Server](https://github.com/sjinks/wpscan-mcp-server) - Stdio server for the WPScan.com API: plugin, theme, WordPress-core and vulnerability lookups (queries the vulnerability API, does not execute the WPScan CLI against a site).

### SIEM, detection, threat intelligence and DFIR

- :new: [Arkime MCP](https://github.com/lflare/arkime-mcp) - Community Arkime session and network-investigation access (55 read-only tools).
- :star: [Arkime native MCP endpoint](https://arkime.com/settings#mcp-settings) - Arkime 6.7+ native `POST /mcp` endpoint for network investigation through session search, aggregations and cont3xt lookups, off by default and gated by `mcpEnabled` plus the `mcpUser` role.
- :new: [BitSight MCP](https://github.com/TheSkeenAdvantage/mcp-bitisght) - BitSight third-party security-risk monitoring through company search, ratings, findings, details and monitored portfolios (community, early; `bitisght` typo is in the actual repo name).
- :new: [CAPE MCP](https://github.com/CAPESandbox/CAPE-mcp) - Small CAPESandbox-owned implementation for querying CAPE API v2 during malware analysis (experimental).
- :new: [Chainsaw MCP](https://github.com/jasonmull/ChainsawMCP) - Runs Chainsaw Windows event-log hunting against supplied evidence for AI-assisted triage (community, early).
- :new: [Cortex XSOAR MCP](https://github.com/jeremy-cayrasso/xsoar-mcp) - Incident management, integration commands, playbooks and indicator hunting; primarily XSOAR 6.x (community).
- :star: [CrowdStrike Falcon MCP](https://github.com/CrowdStrike/falcon-mcp) - Falcon detections, incidents, behaviors, threat intelligence and threat-hunting workflows (maintenance mode; new development moved to hosted CrowdStrike MCP).
- :new: [Darktrace MCP](https://github.com/nuoframework/darktrace-mcp) - Darktrace SOC investigation and incident-response tools (community, explicitly unofficial).
- :new: [Defender MCP](https://github.com/MenkW/Defender-MCP) - Microsoft Defender XDR incidents, alerts, machines, advanced hunting and threat intelligence (community).
- :new: [Devo MCP](https://github.com/robemmerson/devo-mcp) - LINQ queries, alert triage, investigations, log-source health and Activeboards; writes are opt-in (community).
- :new: [Elastic Security example app](https://github.com/elastic/example-mcp-app-security) - Interactive Elastic Security SOC dashboards inside MCP hosts (official reference/example app, not a production server).
- :new: [Exabeam MCP Server](https://github.com/vinaythupili/exabeam-mcp-server) - Exabeam event search, investigations, cases, timelines and risk context (community; an official hosted option also exists).
- :new: [ExtraHop agent MCP](https://github.com/ExtraHop/agent-mcp) - Searches ExtraHop threats, metrics, records and network telemetry; supports investigation and detection operations (official).
- [FalconFeeds MCP](https://github.com/Technisanct/falconfeeds-mcp) - IOCs, CVEs, TTPs, threat actors, threat feeds and feed imagery (official).
- [Fleet MCP](https://fleetdm.com/guides/fleet-mcp) - Fleet's endpoint-management MCP support for querying osquery data, host policies and vulnerabilities (experimental, per the official guide).
- :star: [Google Security Operations and Threat Intelligence MCP](https://github.com/google/mcp-security) - First-party servers for threat detection, investigation and hunting with Google SecOps/Chronicle, incident response with SecOps SOAR, threat-intelligence lookup with Google Threat Intelligence, and cloud-risk management with Security Command Center.
- :new: [Graylog MCP](https://github.com/jperelli/graylog-mcp) - Multi-instance Graylog log search and analysis for incident investigation through a stdio MCP server (community).
- :new: [Humio MCP](https://github.com/weihong-xu-hpe/humio-mcp) - Executes LogScale/Humio searches and retrieves dashboards across configured clusters for security-log investigation (community).
- :new: [IBM QRadar MCP](https://github.com/IBM/qradar-mcp) - Curated QRadar tools for offenses, AQL, reference data, assets, analytics, configuration and vulnerability data (official IBM).
- [Logz.io MCP Server](https://github.com/jklnr/logzio-mcp-server) - Open-source Logz.io log search, Lucene querying and statistics for incident investigation (community; official hosted option also exists).
- :new: [Malcolm MCP Server](https://github.com/nagameTW/mcp-server-malcolm) - Queries Malcolm's Zeek, Suricata, Arkime and NetBox data, read-only unless writes are explicitly enabled.
- :new: [Mecha Hayabusa](https://github.com/Yamato-Security/mecha-hayabusa) - Loads Hayabusa results for natural-language querying, DFIR timelines, event drill-down, IOC extraction and reports (official Yamato Security).
- [Microsoft Sentinel MCP](https://learn.microsoft.com/en-us/azure/sentinel/datalake/sentinel-mcp-get-started) - Microsoft-hosted security tool collections for Sentinel data exploration, hunting, graph analysis and triage; availability varies by collection.
- :new: [MISP MCP](https://github.com/MISP/misp-mcp) - MISP-owned, read-only threat-intelligence search across events, attributes, objects, tags, taxonomies, galaxies and feeds (created April 2026, small adoption so far).
- :star: [OpenCTI native MCP server](https://docs.opencti.io/latest/deployment/mcp-server/) - Official OpenCTI server for threat-intelligence search and knowledge-graph management through XTM One, available in Community Edition over Streamable HTTP, with read/write operations under the caller's permissions.
- :new: [OpenOSINT](https://github.com/OpenOSINT/OpenOSINT) - Open-source OSINT agent: 21 public-source tools behind natural-language chat, with an MCP server.
- :new: [osqueryi-mcp](https://github.com/mdfranz/osqueryi-mcp) - Local Go stdio server exposing host osquery tables and queries for endpoint investigation and threat hunting.
- :shield: [Panther MCP](https://github.com/panther-labs/mcp-panther) - Panther-maintained detection engineering, alert triage and data-lake/log investigation.
- [Security Onion MCP](https://github.com/Security-Onion-Solutions/securityonion-mcp) - Backend MCP server for querying Security Onion security events and retrieving alert-investigation playbooks through its authenticated API (official).
- [SecurityScorecard MCP](https://github.com/CallMarcus/security-scorecard-mcp) - SecurityScorecard issue triage, asset discovery, email-security checks and score analysis (community, explicitly unaffiliated).
- :new: [Securonix multi-SIEM MCP](https://github.com/JoaquinHernandez/soc-siem-mcp-) - Cross-SIEM hunting across Securonix, QRadar, Sentinel, Splunk and Wazuh (community, early).
- :star: [SentinelOne Purple MCP](https://github.com/Sentinel-One/purple-mcp) - Read-only Purple AI, PowerQuery events, alerts, vulnerabilities, misconfigurations, inventory and threat intel (official; distinct from Microsoft Sentinel).
- :new: [Sigma MCP Server](https://github.com/SigmaHQ/sigma-mcp-server) - SigmaHQ's server exposing pySigma functionality for detection engineering, including Sigma rule creation and validation, to MCP clients (created April 2026, small adoption so far).
- :new: [Splunk MCP Server](https://splunkbase.splunk.com/app/7931) - Splunk's supported app for SOC investigation and threat hunting through SPL execution/generation and Splunk data exploration ([CiscoDevNet repository](https://github.com/CiscoDevNet/Splunk-MCP-Server-official)) (Splunk Supported, beta).
- :new: [Splunk SOAR MCP](https://github.com/Ewiges-M/splunk-soar-mcp) - Playbook authoring/deployment, runs, containers, artifacts and case operations (community).
- :new: [Sumo Logic MCP](https://github.com/rajfirke/sumo-logic-mcp) - Log search plus monitors, alerts, dashboards, collectors, metrics, roles and lookup tables for security monitoring and incident investigation (community; official hosted option also exists).
- [TheHive MCP Server](https://github.com/gbrigandi/mcp-server-thehive) - Community TheHive alert, case, observable and incident-response operations.
- :new: [TheHiveMCP (StrangeBee)](https://github.com/StrangeBeeCorp/TheHiveMCP) - Official TheHiveMCP for alert, case, observable and incident-response operations, with a read-only default.
- :new: [ThreatConnect MCP](https://github.com/delonius22/threat_connect_mcp) - ThreatConnect v3 case management and intelligence tools with validated writes and read-only generic queries (community, early).
- [UpGuard MCP](https://github.com/leroylim/upguard-cyberrisk-mcp-server-nodejs) - UpGuard CyberRisk API integration for security-risk assessment and management (community).
- [Vectra AI MCP Server](https://github.com/vectra-ai-research/vectra-ai-mcp-server) - Threat investigation, security analysis, visualizations, reports, platform health and response actions (official Vectra).
- [Velociraptor MCP Server](https://github.com/socfortress/velociraptor-mcp-server) - Velociraptor DFIR querying and investigation workflows.
- :star: [Wazuh MCP Server](https://github.com/gbrigandi/mcp-server-wazuh) - Wazuh alert, agent, vulnerability and indexer/API access for security investigations.
- :new: [Windows Memory Forensics MCP](https://github.com/0xhackerfren/Windows-Memory-Forensics-MCP) - Memory-dump analysis through Volatility 3, MemProcFS, CLR/SOS and YARA (research/CTF proof of concept; not recommended for production forensic investigations).
- :new: [World Intelligence MCP](https://github.com/marc-shade/world-intel-mcp) - 160-tool MCP server for cyber-threat and geopolitical OSINT research using real-time global intelligence from free public APIs, with a Qdrant vector store for semantic search.

### Multi-tool security projects

- [Kali Linux MCP images](https://github.com/vxcontrol/kali-linux-image/tree/master/mcp) - Containerized MCP wrappers for penetration testing and security assessment with Nmap, Metasploit, Nuclei, SQLMap and Hashcat; Hydra and John are deliberately not included.
- :package: [mcp-kali-server](https://www.kali.org/tools/mcp-kali-server/) - Kali-packaged MCP-to-API bridge for running terminal commands and security tools. **Warning:** it runs raw commands, conflicting with the safeguards in Best Practices rule 10; isolate it and use only with explicit authorization.
- :new: [OSINT MCP Server](https://github.com/badchars/osint-mcp-server) - Multi-source OSINT covering Shodan, VirusTotal, Censys, SecurityTrails, DNS, WHOIS, certificate transparency and BGP.
- :new: [Tengu](https://github.com/rfunix/tengu) - Pentest MCP server integrating numerous tools including Nmap, Metasploit, SQLMap, Nuclei and Hydra.
- :new: [Threat Intel Toolkit](https://github.com/scottycwilsono/threat-intel-toolkit) - Combines AbuseIPDB, VirusTotal and Shodan IP-enrichment workflows.

[🔝 Back to top](#awesome-security-mcp)

---

## Official MCP Servers

Servers maintained in the [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) repository. For archived reference servers, see [ARCHIVED.md](ARCHIVED.md).

- :star: [Everything](https://github.com/modelcontextprotocol/servers/tree/main/src/everything) - Reference/test server demonstrating prompts, resources and tools.
- :star: [Fetch](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) - Fetches web content and converts it for efficient LLM consumption.
- :star: [Filesystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) - File operations restricted through configurable access controls.
- :star: [Git](https://github.com/modelcontextprotocol/servers/tree/main/src/git) - Reads, searches and manipulates Git repositories.
- :star: [Memory](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) - Knowledge-graph-based persistent memory.
- :star: [Sequential Thinking](https://github.com/modelcontextprotocol/servers/tree/main/src/sequentialthinking) - Dynamic, reflective problem-solving through structured thought sequences.
- :star: [Time](https://github.com/modelcontextprotocol/servers/tree/main/src/time) - Time and timezone conversion tools.

[🔝 Back to top](#awesome-security-mcp)

---

## Security Platforms & Vendor MCP Servers

Security-relevant community and vendor MCP servers. General-purpose database, collaboration, commerce, cloud and observability servers are intentionally excluded.

### Cloud & container security

- :new: [AWS SRA Verify MCP](https://github.com/awslabs/sra-verify-mcp) - Runs AWS Security Reference Architecture checks across organizations; covers 20 security-related services (official AWS).
- :star: [AWS Well-Architected Security MCP](https://github.com/awslabs/mcp/tree/main/src/well-architected-security-mcp-server) - Security-pillar assessment and findings across GuardDuty, Security Hub, Inspector and IAM Access Analyzer (official AWS).
- [Calico Whisker MCP](https://github.com/aadhilam/mcp-whisker-go) - Analyzes Calico Whisker flow logs, blocked flows and associated network policies (community).
- :new: [Cilium MCP](https://github.com/technoxi/cilium-mcp) - Kubernetes/Cilium/Hubble investigation, network-policy analysis and guarded actions (community, starter/early).
- :star: [Cloudflare One CASB MCP](https://github.com/cloudflare/mcp-server-cloudflare/tree/main/apps/cloudflare-one-casb) - Finds SaaS security misconfigurations through Cloudflare One CASB (official).
- :shield: [CrowdSec local MCP](https://github.com/crowdsecurity/crowdsec-local-mcp) - Generates, validates and deploys CrowdSec WAF rules and detection scenarios (official).
- :new: [Falco MCP](https://github.com/ritvikindupuri/FalcoMCP) - Falco/Falcosidekick alert triage, Kubernetes correlation, rule tuning and isolation-policy generation (community, early).
- [Netskope Private Access MCP](https://github.com/johnneerdael/privateaccess-mcp) - Manages Netskope NPA publishers, private apps, brokers, policies, SCIM, upgrades and alerts (community).
- :new: [Prisma Cloud MCP](https://github.com/Chichis/Prisma-Cloud-MCP) - Read-only alerts, asset search, compliance, vulnerabilities and policies (community, early).
- :new: [Wiz security tools (Cohere)](https://github.com/cohere-ai/cohere-security-toolkit/tree/main/wiz-security) - Eight Wiz tools for issue triage, toxic combinations, CVEs, posture, compliance and issue write-back (maintained by Cohere Security, not Wiz).
- :shield: [Zscaler MCP Server](https://github.com/zscaler/zscaler-mcp-server) - Manages multiple Zscaler products through MCP, with packaged deployment and client integrations (official).

### Identity & secrets

- :star: [Auth0 MCP](https://github.com/auth0/auth0-mcp-server) - Official Auth0 Management API integration for applications, Actions, logs and tenant administration.
- :shield: [HashiCorp Vault MCP](https://github.com/hashicorp/vault-mcp-server) - Official Vault secrets, mounts and PKI operations; requires a trusted local client and careful secret-exposure controls.
- :shield: [Okta MCP Server](https://github.com/okta/okta-mcp-server) - Okta-maintained self-hosted server for identity administration through Okta APIs.

### Application security (AppSec)

- :star: [Semgrep MCP](https://github.com/semgrep/semgrep) - Built into the maintained Semgrep CLI via `semgrep mcp`; lets coding agents run security scans directly.
- :shield: [Snyk MCP](https://github.com/snyk/studio-mcp) - Official `snyk mcp` integration for code, dependency, IaC, container, secret, SBOM and package-health scans.
- :new: [Snyk SAW MCP](https://github.com/snyk/saw-mcp) - Onboards DAST targets, configures authentication, runs scans and triages findings (official; Probely is now Snyk API & Web).
- [Socket MCP](https://github.com/SocketDev/socket-mcp) - Official Socket supply-chain security and package-risk analysis (early development, rapidly evolving).
- :star: [SonarQube MCP](https://github.com/SonarSource/sonarqube-mcp-server) - Official SonarQube code analysis, issue triage and security-hotspot review for AI agents (SONAR Source-Available License v1.0, limited to non-competitive purposes).
- :shield: [Trivy MCP](https://github.com/aquasecurity/trivy-mcp) - Aqua-maintained Trivy plugin for filesystem, repository and container vulnerability/misconfiguration scanning.

[🔝 Back to top](#awesome-security-mcp)

---

## MCP Clients & Hosts

Applications that consume MCP servers.

- :star: [ChatGPT](https://help.openai.com/en/articles/12584461-connecting-custom-mcp-servers-in-chatgpt) - Custom MCP connectors with workspace permission controls.
- :star: [Claude Code](https://code.claude.com/docs/en/mcp) - Local and remote MCP support in Anthropic's coding agent.
- :star: [Claude Desktop / Claude connectors](https://support.claude.com/en/articles/11175166-get-started-with-custom-connectors-using-remote-mcp) - Supports remote MCP connectors and local desktop server configurations.
- :star: [Cline](https://docs.cline.bot/mcp/mcp-overview) - VS Code coding agent with custom MCP server and marketplace support.
- :star: [Continue](https://docs.continue.dev/customize/mcp-tools) - Open-source VS Code/JetBrains agents with MCP tool configuration.
- :star: [Cursor](https://cursor.com/docs/mcp) - Built-in MCP support for local and remote servers through project/user configuration and marketplace integrations.
- :star: [Gemini CLI](https://geminicli.com/docs/tools/mcp-server/) - Local and remote MCP configuration in Google's CLI agent.
- :star: [goose](https://goose-docs.ai/) - Open-source MCP-native desktop/CLI agent, governed by the Agentic AI Foundation at the Linux Foundation (originally from Block).
- [Kimi Code](https://www.kimi.com/code/docs/en/kimi-code-cli/customization/mcp.html) - Supports stdio, Streamable HTTP and legacy HTTP+SSE, OAuth, project/user configuration, workspace trust and tool allow/block lists.
- :star: [Kiro](https://kiro.dev/docs/mcp/configuration/) - MCP configuration across Kiro IDE, CLI and web clients.
- [LibreChat](https://www.librechat.ai/docs/features/mcp) - Self-hosted chat/agent platform with configurable MCP servers, OAuth support and access controls.
- :star: [OpenAI Codex](https://learn.chatgpt.com/docs/extend/mcp?surface=cli) - Codex support for consuming external MCP servers.
- :star: [OpenCode](https://opencode.ai/docs/mcp-servers/) - Local and remote MCP support, including tools, prompts and resources.
- :star: [Roo Code](https://roocodeinc.github.io/Roo-Code/features/mcp/using-mcp-in-roo/) - VS Code agent supporting configured MCP servers and granular auto-approval settings.
- :star: [VS Code Copilot](https://code.visualstudio.com/docs/agent-customization/mcp-servers) - Adds MCP tools and data to Copilot agent workflows, with server management and enterprise controls.
- [Windsurf Cascade](https://docs.devin.ai/windsurf/plugins/cascade/mcp) - Connects Cascade to local and remote MCP servers.
- [Zed](https://zed.dev/docs/ai/mcp) - Supports MCP context servers and extensions; current documentation specifically calls out Tools and Prompts.

[🔝 Back to top](#awesome-security-mcp)

---

## MCP Security Best Practices

Primary references for the 2026-07-28 protocol revision: [MCP Security Best Practices](https://modelcontextprotocol.io/specification/2026-07-28/basic/security_best_practices), [MCP Authorization](https://modelcontextprotocol.io/specification/2026-07-28/basic/authorization), [MCP Transports](https://modelcontextprotocol.io/specification/2026-07-28/basic/transports), [Streamable HTTP](https://modelcontextprotocol.io/specification/2026-07-28/basic/transports/streamable-http), [OWASP MCP Security Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/MCP_Security_Cheat_Sheet.html), [Official MCP Registry](https://registry.modelcontextprotocol.io/) (a discovery mechanism, not a security certification).

1. **Treat tool metadata and results as untrusted input.** Tool descriptions, schemas, annotations, web pages, documents, issues, emails and returned data can carry indirect prompt injection. Cross-server tool shadowing and post-approval "rug pulls" are also risks. Filtering alone cannot establish safety; enforce authorization outside the model.
2. **Vet and pin servers and tool definitions.** Review source, publisher, exact install command, dependencies and tool schemas. Pin reviewed package versions and hashes, verify signatures where available, and re-review changed tool definitions. Do not equate registry presence or GitHub stars with trustworthiness.
3. **Default to least privilege and read-only operation.** Enable only required servers, toolsets and individual tools. Use read-only database roles, restricted OAuth scopes, project-scoped access, filesystem allowlists and narrowly scoped Kubernetes/cloud identities. Avoid wildcard auto-approval.
4. **Require risk-appropriate approval.** Show full arguments and require confirmation for writes, deletion, payments, credential changes, data sharing, command execution, scans, exploitation and other irreversible actions. Tool annotations such as `readOnlyHint` are hints, not enforcement.
5. **Handle secrets as credentials, not prompts.** Use OS credential stores or a secret manager, short-lived per-server tokens and minimal injected environment variables. Never place secrets in repositories, prompts, command arguments, URLs or logs. Rotate and revoke credentials independently for each server.
6. **Validate remote authorization correctly.** Use TLS and OAuth appropriately, validate token audience and issuer, and reject tokens not issued for the MCP server. Do not use token passthrough, and never place access tokens in URI query strings. To prevent confused-deputy attacks, MCP proxies using a static downstream client ID must require per-client consent before third-party authorization, exactly match registered redirect URIs and validate single-use `state`. Clients must allow only HTTP(S) authorization URLs, require HTTPS outside loopback development, reject `javascript:` and other dangerous schemes, and open URLs without invoking a shell to prevent XSS and command-injection RCE. Bind authorization responses to the expected authorization server and validate its issuer (`iss`, RFC 9207) to prevent mix-up attacks; PKCE alone does not prevent mix-up.
7. **Choose and harden the transport.** stdio avoids a listening network port but does not sandbox the child process; it inherits the permissions and environment granted by the host. In protocol version 2026-07-28, Streamable HTTP removed protocol-level sessions and the standalone GET stream; application state uses explicit handles that must be bound to the authenticated principal. Streamable HTTP mirrors request metadata into `Mcp-Method`, `Mcp-Name` and schema-designated `Mcp-Param-*` headers while the body remains authoritative. Servers MUST reject missing, malformed or mismatched headers with `400 Bad Request` and `HeaderMismatch`, decoding Base64-sentinel values before comparison. This duplicated metadata creates a header/body confusion and policy-bypass surface for gateways and WAFs: intermediaries must not route or authorize on headers without the required consistency checks. Require authentication where needed, validate Origin and Host, and bind local services to loopback. The old standalone HTTP+SSE transport is deprecated; current Streamable HTTP may still use request-scoped SSE.
8. **Sandbox local servers.** Run third-party servers with a dedicated unprivileged identity and restricted filesystem, process and network access. Containers are useful only when configured securely; do not mount sensitive directories, host credentials or the Docker socket unnecessarily.
9. **Constrain network and data exfiltration paths.** Apply egress allowlists, SSRF protections, URL validation, redirect checks, private-address blocking, timeouts, rate limits and output-size limits. Pay particular attention when one agent has access to private data, untrusted content and an outbound communication tool simultaneously.
10. **Add controls specific to offensive-security servers.** Run them only in isolated, explicitly authorized environments; use target allowlists, non-root identities, read-only defaults where possible, bounded scans, approval gates and complete audit logs. Avoid wrappers that expose unrestricted shell commands or arbitrary scanner arguments.
11. **Log without creating another secret store.** Record actor, server, tool, arguments, result status and timestamp, while redacting credentials and sensitive content. Monitor new tools, definition changes, unusual call frequency and cross-server data flows.
12. **Warn about submissions and samples.** VirusTotal and similar services may share submitted files or URLs with partners or the security community. A hash lookup is not permission to upload the underlying file; require explicit authorization for submissions involving internal code, documents, personal data or credentials.

[🔝 Back to top](#awesome-security-mcp)

---

## Learning Resources

### AI security skills & agents (not MCP servers)

- :new: [Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) - Community library of 817 structured cybersecurity skills for AI agents, mapped to six frameworks including MITRE ATT&CK (skills library, not an MCP server). Not affiliated with Anthropic PBC.
- :new: [Claude-OSINT](https://github.com/elementalsouls/Claude-OSINT) - Eight Claude skills for external recon (100+ recon capabilities, secret-regex patterns, dorks, read-only credential validators); a Claude skills pack, not an MCP server.
- :new: [Gate (Silicon Psyche Labs)](https://github.com/SiliconPsycheLabs/gate) - Claude Code plugin and Apache-2.0 Python library that checks every tool call, MCP tools included, against fixed Cedar rules before it runs (allow, refuse or ask the user), recording where each argument came from in a decision log; the plugin checks through a hosted service (API key, free tier) that receives prompts and tool outputs, while the library also runs locally (own project).
- :new: [hackingtool-plugin](https://github.com/AKCodez/hackingtool-plugin) - Claude Code plugin wrapping 183+ pentesting and OSINT tools from Z4nzu/hackingtool (plugin/skill wrapper, not an MCP server).

### MCP documentation, tools and directories

- 📚 [Awesome MCP Servers (wong2)](https://github.com/wong2/awesome-mcp-servers) - Community-curated list of MCP servers (another good discovery source).
- 🧭 [MCP Governance & community](https://github.com/modelcontextprotocol) - Steering-group repositories and community discussions.
- 🧪 [MCP Inspector](https://github.com/modelcontextprotocol/inspector) - Official testing/debugging UI and proxy for MCP servers.
- 📘 [MCP Specification](https://modelcontextprotocol.io/specification) - Protocol details, transports, authorization and security best practices.
- 📚 [MCP.so](https://mcp.so) - MCP server directory and ecosystem hub.
- 🗂️ [Official MCP Registry](https://registry.modelcontextprotocol.io/) - Server discovery (not a security certification).
- 🛡️ [OWASP MCP Security Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/MCP_Security_Cheat_Sheet.html) - Concise security checklist for MCP deployments.
- 📚 [Punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) - Large community list of MCP servers and clients.

[🔝 Back to top](#awesome-security-mcp)

---

## How this list is verified

Each review round checks primary links, project existence, publisher or official status, documented capabilities, security relevance, category fit and description accuracy against current project sources. Link sweeps identify dead URLs and redirects; GitHub metadata and vendor lifecycle notices inform the status labels defined in [CONTRIBUTING.md](CONTRIBUTING.md).

Editors remove duplicates and general-purpose entries, move archived or deprecated material to [ARCHIVED.md](ARCHIVED.md), and repeat accuracy and link checks after restructuring. Stars, activity and review status are point-in-time signals, not security endorsements; inclusion does not mean that a project's code has been audited.

[🔝 Back to top](#awesome-security-mcp)

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). One server per PR, verified links, honest descriptions, alphabetical order.

[🔝 Back to top](#awesome-security-mcp)
