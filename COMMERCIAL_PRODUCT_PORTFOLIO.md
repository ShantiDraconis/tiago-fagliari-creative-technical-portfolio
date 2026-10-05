# Commercial Product Portfolio

This catalog converts the repository estate into a small number of sellable products instead of publishing every research repository as an independent storefront item.

## Product line

### 1. Lean Audit Kit
Source: `lean-audit-kit`
Target: US$39 personal / US$99 commercial
Role: entry product.

### 2. Universal Proof Hub
Source: `universal-proof-hub`
Target: US$59 personal / US$129 commercial
Role: formal mathematics workspace.

### 3. MetaOS Developer Edition
Source: `metaos-operational-system`
Target: US$79 personal / US$149 commercial
Role: symbolic computation/research framework.

### 4. M-Core Research OS
Primary source: `M-Core`
Target: US$99 personal / US$199 commercial
Role: proof-engineering and research orchestration.

### 5. 0/0 Indeterminate Mathematics Bundle
Primary source: `0-0-FORMAL-SUITE`
Supporting sources may include indeterminate/algebra/metamathematics repositories after claim and license audit.
Target: US$49 personal / US$99 commercial.

### 6. Millennium Formal Research Suite
Primary source: `millennium-research-os`
Modules:
- `m-core-riemann`
- `m-core-p-vs-np`
- `m-core-hodge`
- `m-core-yang-mills`
- `m-core-beal`
- Navier–Stokes research/audit repositories selected at release time
- BSD research repositories selected at release time
Target: US$129 personal / US$249 commercial.

This product is a formal-research corpus/toolkit. OPEN_MATH must never be represented as a solved theorem unless the shipped frozen artifact genuinely contains and audits the required producer.

### 7. Horizon Prime Framework
Source: `horizon-prime---framework`
Target: US$39 personal / US$89 commercial.

### 8. Indus Operational Mathematics
Source: `indus-operational-mathematics`
Target: US$49 personal / US$99 commercial.

### 9. The Proof Log
Source: `The-Proof-Log`
Target: US$29 personal / US$59 commercial.

### 10. Complete Research Vault
Curated releases of the above products only.
Target: US$299 personal/research bundle; commercial tiers can be priced separately.
Do not include personal evidence repositories, secrets, unrelated drafts, third-party content without redistribution rights, or raw working history.

## Repositories that should not become independent Gumroad products by default

Tiny stubs, duplicate Millennium lanes, single-purpose experiments, empty repositories, private evidence/admin repositories, and speculative branches should be mapped into one of the products above or excluded.

## Universal Gumroad gate

A product can be marked `GUMROAD_READY` only after:
1. ownership and third-party rights audit;
2. explicit customer-facing license/EULA;
3. secret/private-data scan;
4. clean build/reproduction;
5. claim audit;
6. quickstart and example;
7. version/tag/changelog;
8. release archive + checksum;
9. screenshots/demo;
10. storefront copy based on the frozen release.

## Commercial architecture

Development repositories remain private research workspaces.
Frozen release commits generate sanitized distribution archives.
Gumroad receives the archive and customer documentation, not the mutable research history.
