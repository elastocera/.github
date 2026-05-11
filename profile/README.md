# Elastocera

**Cloud-native infrastructure tooling built from real operational problems.**

These are systems engineered during platform engineering and consulting work to solve recurring challenges with the highest signal-to-noise possible: documentation that stays in sync with reality, operational toolkits that survive contact with production, and analysis tooling that turns raw inventory into migration decisions. The bias is toward consistency, repeatability, and fast iteration over one-off scripts.

> Hosting: this repository lives on elastocera (private GitHub org) as an interim arrangement. See [GOVERNANCE.md](GOVERNANCE.md) for details.

## Projects

**[rvtma](https://github.com/orgs/elastocera/packages/container/package/rvtma)**  
RVTools Migration Analyzer. Converts RVTools inventory exports into complete migration blueprints for moves from VMware vSphere to OpenShift Virtualization or any KubeVirt-based target. Supports pre-sales scoping, VMA, cluster sizing, and wave planning. Generates PDF, XLSX, and YAML reports tailored to the technical, operational, and executive stakeholders involved at each phase.

**[ovtools](https://github.com/orgs/elastocera/packages/container/package/ovtools)**  
Web-based inventory and operational visibility tool for OpenShift Virtualization. Built for teams migrating from VMware that need centralized visibility into VMs, nodes, and cluster health while preserving OpenShift-native RBAC, namespaces, and multi-tenancy boundaries.

**[safeshift-doc-gen](https://github.com/orgs/elastocera/packages/container/package/safeshift-doc-gen)**  
Generates AsciiDoc and PDF documentation for OpenShift clusters from live environments or must-gather archives. Exposes web UI, CLI, and API, and includes an RHACM batch mode to document all managed clusters in one run.

**[ai-health-check-tool](https://github.com/orgs/elastocera/packages/container/package/ai-health-check-tool)**  
AI-powered diagnostic tool for OpenShift, Kubernetes, ODF/Ceph, and Linux infrastructure. Reduces full health-check analysis from hours to minutes by collecting operational data, scoring it by category, and surfacing correlated issues across components. Outputs PDF reports, supports Gemini, Claude, Grok, OpenAI, and local Ollama, with automatic anonymization of sensitive data and a PatternFly 6 web interface.

## Research and Writing

Technical deep dives, post-mortems, and architecture analysis at [elastocera.com](https://elastocera.com).

---

Maintained by Andre Rocha.