# MCP CVE catalogs and indexes

Projects that **catalog, index, or track** publicly disclosed CVEs and security advisories in the **Model Context Protocol (MCP)** ecosystem: official and third-party servers, SDKs, clients, gateways, and integrations.

For a **snapshot of official `modelcontextprotocol/*` advisories** (patched versions, GHSA IDs, severity), see [MCP CVEs and Advisories](mcp_cves_and_advisories.md).

---

## Contents

- [Dedicated MCP CVE and vulnerability catalogs](#dedicated-mcp-cve-and-vulnerability-catalogs)
- [Curated lists with CVE and advisory sections](#curated-lists-with-cve-and-advisory-sections)
- [Official per-repository advisory dashboards](#official-per-repository-advisory-dashboards)
- [Related CSA security resources](#related-csa-security-resources)
- [Not MCP CVE catalogs](#not-mcp-cve-catalogs)

---

## Dedicated MCP CVE and vulnerability catalogs

| Project | Link | One-line description |
| --- | --- | --- |
| **MCP CVE Project** | [vermava/mcp-cve-project](https://github.com/vermava/mcp-cve-project) | Curated index of **111+** published CVEs touching the MCP ecosystem, with per-CVE markdown summaries under `cves/`. |
| **Vulnerability Database** | [ModelContextProtocol-Security/vulnerability-db](https://github.com/ModelContextProtocol-Security/vulnerability-db) | CSA community database tracking CVEs, OSVs, GHSAs, and community findings in OSV-style JSON with reproduction-focused disclosure. |
| **The Vulnerable MCP Project** | [vineethsai/vulnerablemcp](https://github.com/vineethsai/vulnerablemcp) | Community vulnerability database (JSON + static site) covering MCP exploits, research, and incidents—many entries include CVE IDs. **Live:** [vulnerablemcp.info](https://vulnerablemcp.info) |

---

## Curated lists with CVE and advisory sections

| Project | Link | One-line description |
| --- | --- | --- |
| **Awesome Agentic MCP Security** (this repo) | [vermava/awesome-agentic-mcp-security](https://github.com/vermava/awesome-agentic-mcp-security) | Curated knowledge base; [mcp_cves_and_advisories.md](mcp_cves_and_advisories.md) mirrors official MCP org security dashboards and advisory snapshots. |
| **Awesome MCP Security** | [Puliczek/awesome-mcp-security](https://github.com/Puliczek/awesome-mcp-security) | Large community list with a chronological **articles/incidents** section (e.g. Inspector RCE, `mcp-remote` CVE-2025-6514)—not a structured CVE index. |
| **Awesome MCP Security** | [AIM-Intelligence/awesome-mcp-security](https://github.com/AIM-Intelligence/awesome-mcp-security) | Smaller curated list with vulnerability categories and links; companion to papers and tools, not a CVE database. |

---

## Official per-repository advisory dashboards

These are **source-of-truth** GitHub Security Advisory pages for the MCP reference implementation—not aggregated catalogs, but where many MCP CVEs are first published.

| Component | Security dashboard |
| --- | --- |
| Reference servers | [modelcontextprotocol/servers/security](https://github.com/modelcontextprotocol/servers/security) |
| MCP Inspector | [modelcontextprotocol/inspector/security](https://github.com/modelcontextprotocol/inspector/security) |
| Python SDK | [modelcontextprotocol/python-sdk/security](https://github.com/modelcontextprotocol/python-sdk/security) |
| TypeScript SDK | [modelcontextprotocol/typescript-sdk/security](https://github.com/modelcontextprotocol/typescript-sdk/security) |
| Go SDK | [modelcontextprotocol/go-sdk/security](https://github.com/modelcontextprotocol/go-sdk/security) |
| Java SDK | [modelcontextprotocol/java-sdk/security](https://github.com/modelcontextprotocol/java-sdk/security) |
| C# SDK | [modelcontextprotocol/csharp-sdk/security](https://github.com/modelcontextprotocol/csharp-sdk/security) |
| Rust SDK | [modelcontextprotocol/rust-sdk/security](https://github.com/modelcontextprotocol/rust-sdk/security) |

**Cross-ecosystem search:** [GitHub Advisory Database](https://github.com/advisories) (filter by product, CWE, or keyword such as `MCP`).

---

## Related CSA security resources

| Project | Link | One-line description |
| --- | --- | --- |
| **MCP Security hub** | [ModelContextProtocol-Security/modelcontextprotocol-security.io](https://github.com/ModelContextProtocol-Security/modelcontextprotocol-security.io) | Official CSA documentation site linking guidance, tools, and vulnerability resources. **Live:** [modelcontextprotocol-security.io](https://modelcontextprotocol-security.io) |
| **Audit Database** | [ModelContextProtocol-Security/audit-db](https://github.com/ModelContextProtocol-Security/audit-db) | Community MCP server **audit results** and security ratings; feeds findings into `vulnerability-db` but is not a CVE catalog itself. |
| **MCP Server Audit** | [ModelContextProtocol-Security/mcpserver-audit](https://github.com/ModelContextProtocol-Security/mcpserver-audit) | Tooling to assess MCP servers before use; can publish results to `audit-db` and `vulnerability-db`. |

---

## Not MCP CVE catalogs

These repos expose **general CVE or advisory lookup** via MCP tools. They help agents query NVD/OSV/CVE-Search—they do **not** maintain a catalog of MCP-specific CVEs.

| Project | Link | Note |
| --- | --- | --- |
| CVE-Search MCP | [roadwy/cve-search_mcp](https://github.com/roadwy/cve-search_mcp) | Queries a CVE-Search API instance. |
| CVE-Search MCP | [Arnabdaz/CVE-Search-MCP](https://github.com/Arnabdaz/CVE-Search-MCP) | CVE search optimized for PR review workflows. |
| CVE MCP Server | [mukul975/cve-mcp-server](https://github.com/mukul975/cve-mcp-server) | Multi-source CVE/threat-intel tools for agents. |
| GitHub Advisory MCP | [microsoft/github-advisory-mcp](https://github.com/microsoft/github-advisory-mcp) | Semantic search over GitHub's global advisory database. |
| EIP MCP | [exploitintel/eip-mcp](https://github.com/exploitintel/eip-mcp) | Aggregates NVD, KEV, OSV, ExploitDB, and related feeds. |
| VulnMCP | [vulnerability-lookup/VulnMCP](https://github.com/vulnerability-lookup/VulnMCP) | Skills for Vulnerability-Lookup API (severity, CWE, KEV). |

---

## How to use this page

| Goal | Start here |
| --- | --- |
| Largest **numbered CVE index** for MCP | [vermava/mcp-cve-project](https://github.com/vermava/mcp-cve-project) |
| **Standards-oriented** advisories (OSV/GHSA, reproduction detail) | [ModelContextProtocol-Security/vulnerability-db](https://github.com/ModelContextProtocol-Security/vulnerability-db) |
| **Broader incidents** (research, non-CVE, exploit writeups) | [vineethsai/vulnerablemcp](https://github.com/vineethsai/vulnerablemcp) |
| **Official MCP org** patched versions and GHSA links | [mcp_cves_and_advisories.md](mcp_cves_and_advisories.md) |

Contributions: add new catalog projects via pull request to this file; add individual CVE entries to [mcp-cve-project](https://github.com/vermava/mcp-cve-project) or the upstream database that owns the record.
