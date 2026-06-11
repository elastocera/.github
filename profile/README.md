# Elastocera

**Cloud-native infrastructure tooling built from real operational problems.**

These are systems engineered during platform engineering and consulting work to solve recurring challenges with the highest signal-to-noise possible: documentation that stays in sync with reality, operational toolkits that survive contact with production, and analysis tooling that turns raw inventory into migration decisions. The bias is toward consistency, repeatability, and fast iteration over one-off scripts.

> Hosting: this repository lives on elastocera (private GitHub org) as an interim arrangement. See [GOVERNANCE.md](GOVERNANCE.md) for details.

## Projects

**[rvtma](https://github.com/orgs/elastocera/packages/container/package/rvtma)**  
RVTools Migration Analyzer. Converts RVTools inventory exports into complete migration blueprints for moves from VMware vSphere to OpenShift Virtualization or any KubeVirt-based target. Supports pre-sales scoping, VMA, cluster sizing, and wave planning. Generates PDF, XLSX, and YAML reports tailored to the technical, operational, and executive stakeholders involved at each phase.
[#rvtools-migration-analyzer](https://redhat.enterprise.slack.com/archives/C094CNJRXQD)

**[ovtools](https://github.com/orgs/elastocera/packages/container/package/ovtools)**  
Web-based inventory and operational visibility tool for OpenShift Virtualization. Built for teams migrating from VMware that need centralized visibility into VMs, nodes, and cluster health while preserving OpenShift-native RBAC, namespaces, and multi-tenancy boundaries.
[#ovtools](https://redhat.enterprise.slack.com/archives/C0A4UQ00HT6)

**[safeshift-doc-gen](https://github.com/orgs/elastocera/packages/container/package/safeshift-doc-gen)**  
Audit-grade AsciiDoc/PDF documentation generator for OpenShift (OCP), Kubernetes, and RHACM-managed fleets. Live cluster or must-gather. Web UI, CLI, REST API, and batch mode for documenting every managed cluster in one run.
[#safe-shift-doc-gen](https://redhat.enterprise.slack.com/archives/C0A9KDAKJBG)

**[ai-health-check-tool](https://github.com/orgs/elastocera/packages/container/package/ai-health-check-tool)**  
AI-powered diagnostic tool for OpenShift, Kubernetes, ODF/Ceph, and Linux infrastructure. Reduces full health-check analysis from hours to minutes by collecting operational data, scoring it by category, and surfacing correlated issues across components. Outputs PDF reports, supports Gemini, Claude, Grok, OpenAI, and local Ollama, with automatic anonymization of sensitive data and a PatternFly 6 web interface.
[#ai-health-check-tool](https://redhat.enterprise.slack.com/archives/C092DAVQ2KC)

## Releases

Binaries for the tools are concentrated in one public repo: [elastocera/releases](https://github.com/elastocera/releases). Each release carries its tool prefix (`ssdg-v*`, `rvtma-v*`, `ovtools-v*`) and ships builds for macOS (arm64/amd64), Linux (arm64/amd64), and Windows.

## Research and Writing

Technical deep dives, post-mortems, and architecture analysis at [elastocera.com](https://elastocera.com).

---

Maintained by Andre Rocha.
