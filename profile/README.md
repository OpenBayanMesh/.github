# OpenBayanMesh

**A Volunteer-Powered Open Data Mesh for the Philippines**  
*Empowering communities to host, govern, and serve Philippine public data transparently.*

---

## 🚀 What is OpenBayanMesh?

**OpenBayanMesh** is a groundbreaking, community-driven open data platform that enables volunteers, civic groups, and organizations to host and distribute Philippine government datasets through a resilient, decentralized mesh network.

Our mission is to make public data freely accessible, auditable, and sustainable—removing barriers posed by centralized infrastructure and empowering everyday Filipinos as stewards of national transparency.

OpenBayanMesh leverages the latest in distributed systems, open source technologies, and Infrastructure as Code to deliver real-time, reliable open data while ensuring cost-efficiency, security, and citizen empowerment.

---

## 🕸️ How Does OpenBayanMesh Work?

OpenBayanMesh is built on three core pillars:

### 1. **Volunteer Edge Nodes**
- Community members run Edge Nodes on their own machines (PCs, home servers, Raspberry Pi, etc.).
- Each Edge Node hosts official government datasets, powered by Docker Compose (Neo4j + NestJS API + Cloudflared).
- Edge Nodes securely connect to the network via Cloudflare Tunnel, making data available to all.

### 2. **Central Mesh Fabric**  
- A centrally managed API Gateway and Load Balancer (on Cloudflare) routes public requests to available, healthy volunteer nodes.
- Health checks and dynamic routing ensure high availability, security, and resilience—even if some nodes go offline.

### 3. **Git-Based Governance & Infrastructure as Code**
- Node registration and infrastructure changes are proposed via Pull Requests in public GitHub repositories.
- All infra (Cloudflare, network rules, etc.) is managed with Terraform for full auditability and reproducibility.
- Data submissions and infrastructure updates require community review and approval.

---

## 🏛️ Key Features

- **Philippine Government Data Hosting:** National budget, agency stats, procurement, transparency, LGU datasets and more.
- **Volunteer Ownership:** Anyone can run an Edge Node, register through GitHub, and power the data mesh.
- **Dynamic Availability:** Automated health checks & routing—never a single point of failure.
- **Open, Free, Sustainable:** Leverages free tiers of cloud resources (Cloudflare, Vercel, Neo4j AuraDB).
- **Transparent Governance:** All changes tracked via Git, open PRs, public audit trails.
- **Technically Modern:** Uses Docker, Terraform, GitHub Actions, serverless functions.
- **Community-Centric:** Documentation, onboarding, and dashboards designed for both technical and non-technical contributors.

---

## 🌐 Repository Structure

OpenBayanMesh is organized for clarity and maximum community engagement:

- [`openbayanmesh-nodes`](https://github.com/OpenBayanMesh/openbayanmesh-nodes): Register and approve new edge nodes
- [`openbayanmesh-infrastructure`](https://github.com/OpenBayanMesh/openbayanmesh-infrastructure): Terraform-powered network and infra management
- [`openbayanmesh-edge`](https://github.com/OpenBayanMesh/openbayanmesh-edge): Edge Node software (Docker Compose, APIs, setup)
- [`openbayanmesh-data`](https://github.com/OpenBayanMesh/openbayanmesh-data): Community-contributed government datasets
- [`openbayanmesh-dashboard`](https://github.com/OpenBayanMesh/openbayanmesh-dashboard): Public status board, documentation, and network health visualizations

---

## 💡 Get Involved

- **Run an Edge Node:** [Install Guide](link-to-wiki)
- **Contribute Data:** [Submit Dataset](link-to-data-PR)
- **Improve Infrastructure:** [Terraform Contributions](link-to-infra-repo)
- **Join Discussions:** [Community Forum](link-to-discussions)
- **Report Issues:** [GitHub Issues](link-to-issues)

---

## 🤝 Governance & Principles

OpenBayanMesh aligns with [BetterGov.ph](https://bettergov.ph)'s commitment to openness, accountability, and empowerment of citizens.  
All contributors agree to uphold transparency, auditability, and ethical use of public data.

- **Community First:** Volunteers are recognized, supported, and credited.
- **Openness:** All code, infra, and data contributions are public and open-source.
- **Security:** Sensitive credentials are managed off-repo; all traffic is encrypted.

---

## 📄 License

This project is licensed under the [Creative Commons CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/).

> **You are free to:**
> - Copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission.

**No copyright**—all code and data published in this organization are placed in the public domain to promote open civic innovation and public benefit.

*For more details, see the [`LICENSE`](LICENSE) file.*

---

## 👋 Contact & Social

- Official Website: [openbayanmesh.ph](https://openbayanmesh.ph) *(coming soon)*
- Twitter: [@OpenBayanMesh](https://twitter.com/openbayanmesh)
- Discord: [Join the Community](link-to-discord)
- Email: [help@openbayanmesh.ph](mailto:help@openbayanmesh.ph)

---

**OpenBayanMesh — "Powering Philippine Open Data Together"**
