# MCP CVE catalogs and indexes

GitHub projects that **catalog, index, or track** CVEs and security advisories in the **Model Context Protocol (MCP)** ecosystem—servers, SDKs, clients, gateways, and integrations.

---

## Contents

- [MCP CVE catalogs and curated lists](#mcp-cve-catalogs-and-curated-lists)
- [Related CSA security resources](#related-csa-security-resources)
- [General CVE lookup via MCP (not MCP catalogs)](#general-cve-lookup-via-mcp-not-mcp-catalogs)

---

## MCP CVE catalogs and curated lists

| Project | Description |
| --- | --- |
| [vermava/mcp-cve-project](https://github.com/vermava/mcp-cve-project) | Curated index of **111+** published MCP-related CVEs with per-CVE markdown under `cves/`. |
| [ModelContextProtocol-Security/vulnerability-db](https://github.com/ModelContextProtocol-Security/vulnerability-db) | CSA community database (CVE, OSV, GHSA) in OSV-style JSON with reproduction-focused disclosure. **Site:** [modelcontextprotocol-security.io/vulnerability-db](https://modelcontextprotocol-security.io/vulnerability-db/) |
| [vineethsai/vulnerablemcp](https://github.com/vineethsai/vulnerablemcp) | Community database of MCP vulnerabilities, research, and exploits (JSON + static site). **Site:** [vulnerablemcp.info](https://vulnerablemcp.info) |
| [Puliczek/awesome-mcp-security](https://github.com/Puliczek/awesome-mcp-security) | Large community list with a chronological articles/incidents section (e.g. Inspector RCE, `mcp-remote` CVE-2025-6514)—not a structured CVE index. |
| [AIM-Intelligence/awesome-mcp-security](https://github.com/AIM-Intelligence/awesome-mcp-security) | Smaller list with vulnerability categories and links; companion to papers and tools, not a CVE database. |

---

## Related CSA security resources

| Project | Description |
| --- | --- |
| [ModelContextProtocol-Security/modelcontextprotocol-security.io](https://github.com/ModelContextProtocol-Security/modelcontextprotocol-security.io) | CSA documentation hub for MCP security guidance and tools. **Site:** [modelcontextprotocol-security.io](https://modelcontextprotocol-security.io) |
| [ModelContextProtocol-Security/audit-db](https://github.com/ModelContextProtocol-Security/audit-db) | Community MCP server audit results and ratings; feeds `vulnerability-db` but is not a CVE catalog. |
| [ModelContextProtocol-Security/mcpserver-audit](https://github.com/ModelContextProtocol-Security/mcpserver-audit) | Assess MCP servers before use; can publish to `audit-db` and `vulnerability-db`. |

---

## General CVE lookup via MCP (not MCP catalogs)

These expose **general** CVE or advisory lookup through MCP tools. They do not maintain a catalog of MCP-specific CVEs.

| Project | Description |
| --- | --- |
| [roadwy/cve-search_mcp](https://github.com/roadwy/cve-search_mcp) | Queries a CVE-Search API instance. |
| [Arnabdaz/CVE-Search-MCP](https://github.com/Arnabdaz/CVE-Search-MCP) | CVE search oriented to PR review workflows. |
| [mukul975/cve-mcp-server](https://github.com/mukul975/cve-mcp-server) | Multi-source CVE and threat-intel tools for agents. |
| [microsoft/github-advisory-mcp](https://github.com/microsoft/github-advisory-mcp) | Semantic search over GitHub's global advisory database. |
| [exploitintel/eip-mcp](https://github.com/exploitintel/eip-mcp) | Aggregates NVD, KEV, OSV, ExploitDB, and related feeds. |
| [vulnerability-lookup/VulnMCP](https://github.com/vulnerability-lookup/VulnMCP) | Vulnerability-Lookup API skills (severity, CWE, KEV). |

---

**Contributing:** Open a pull request to add catalog projects to this page. Submit individual CVE records to [mcp-cve-project](https://github.com/vermava/mcp-cve-project) or the upstream database that owns the advisory.
