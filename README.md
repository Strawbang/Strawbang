![Djamel Bougouffa, full-stack engineer and consultant](./banner.svg)

I modernize legacy systems on client missions, and build my own products and open-source AI tooling.

**Currently** at [Ippon Technologies](https://www.ippon.tech) AI Lab, building legacy modernization tools in Rust.
**On mission** at SUEZ IWS, moving the Pléco extranet from Liferay to Angular micro-frontends.
**Writing** at [djamel-bougouffa.com](https://djamel-bougouffa.com) · **Reach me** at dbougouffa@gmail.com

## rustkit-ai

Five Rust crates I maintain to cut the token cost of AI coding agents. MIT, published on crates.io, works with Claude Code, Cursor, Windsurf and GitHub Copilot.

| Crate | | What it does |
|-------|--|--------------|
| **[tersify](https://github.com/rustkit-ai/tersify)** | [![crates.io](https://img.shields.io/crates/v/tersify?style=flat-square&color=F85D7F)](https://crates.io/crates/tersify) | Strips noise from code before it reaches the model. Up to 50% fewer tokens. |
| **[trimcp](https://github.com/rustkit-ai/trimcp)** | [![crates.io](https://img.shields.io/crates/v/trimcp?style=flat-square&color=F85D7F)](https://crates.io/crates/trimcp) | MCP proxy that compresses and caches tool output. 60 to 90% fewer tokens. |
| **[semtree](https://github.com/rustkit-ai/semtree)** | [![crates.io](https://img.shields.io/crates/v/semtree?style=flat-square&color=F85D7F)](https://crates.io/crates/semtree) | Searches a codebase by meaning instead of by string. tree-sitter plus embeddings. |
| **[semstore](https://github.com/rustkit-ai/semstore)** | [![crates.io](https://img.shields.io/crates/v/semstore?style=flat-square&color=F85D7F)](https://crates.io/crates/semstore) | Vector store for Rust. Embeds on device, no cloud API. |
| **[aimemo](https://github.com/rustkit-ai/aimemo)** | [![crates.io](https://img.shields.io/crates/v/aimemo?style=flat-square&color=F85D7F)](https://crates.io/crates/aimemo) | Keeps agent memory in sync across `CLAUDE.md`, `.cursor/rules` and friends. |

[github.com/rustkit-ai](https://github.com/rustkit-ai) · [rustkit-ai.github.io](https://rustkit-ai.github.io/)

## Other work

**[Consultant Tracking](https://github.com/strawbang/consultant-tracking)** · Time tracking for consulting firms. Angular 14, Spring Boot 3, hexagonal architecture, Docker Swarm.

Upstream contributions:

- **[tree-sitter/tree-sitter-rust](https://github.com/tree-sitter/tree-sitter-rust)** · Fixed the parsing of unary operators after the `..` range operator, where `..*a` was read as a binary expression instead of a prefix range.
- **[DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped)** · Added French documentation ([#66193](https://github.com/DefinitelyTyped/DefinitelyTyped/pull/66193))

## Stack

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

On the AI side: RAG pipelines, MCP servers, tree-sitter parsing and on-device embeddings.

## Experience

| Period | Role | Company |
|--------|------|---------|
| Mar 2026 – Present | Full-Stack Developer | SUEZ IWS (via Ippon) |
| Feb 2026 – Present | Software Engineer, AI Lab | Ippon Technologies |
| Nov 2025 – Feb 2026 | Software Engineer, R&D | Ippon Technologies |
| Jan 2025 – Apr 2025 | Full-Stack Software Engineer | SYSTRAN by ChapsVision |
| Mar 2022 – Mar 2024 | Fullstack Developer | Wemanity Group (METRO France) |
| Sep 2020 – Feb 2022 | Fullstack Developer | Ma Formation Médicale |

A few things I shipped along the way:

- Built the warehouse management system used by 93 METRO France sites.
- Deployed a self-hosted Rust RAG service on AWS with Terraform and GitLab OIDC.
- Moved MaFormation Médicale from PHP to JavaScript, cutting page load time by 40%.

Master's degree, Expert Web Architect, Institut F2I Paris (2021). Full details on my [portfolio](https://djamel-bougouffa.com/about/).

## Writing

<!-- PERSONAL-BLOG-LIST:START -->
- [AI Writes the Code Now, Which Is Exactly Why You Should Master Architecture](https://djamel-bougouffa.com/blog/why-developers-should-learn-architecture-ai-era/)
- [Hexagonal Architecture Is the Best Gift You Can Give an AI Agent](https://djamel-bougouffa.com/blog/hexagonal-architecture-ai-agents/)
- [Why I Left the AI IDE for the Terminal, and Built Tooling Around It](https://djamel-bougouffa.com/blog/why-i-left-the-ai-ide-for-the-terminal/)
- [Deploying a Self-Hosted RAG App on AWS with Terraform: Why I Chose EC2 Over Bedrock](https://djamel-bougouffa.com/blog/deploying-rust-rag-app-aws-terraform-ec2-bedrock/)
- [How Standardizing a Tech Stack Cut Product Creation Time by 80%](https://djamel-bougouffa.com/blog/stack-standardization-80-percent-faster/)
<!-- PERSONAL-BLOG-LIST:END -->

## Stats

<p align="center">
  <img alt="Djamel's GitHub stats" src="https://denvercoder1-github-readme-stats.vercel.app/api/?username=Strawbang&show_icons=true&include_all_commits=true&count_private=true&theme=react&hide_border=true&bg_color=1F222E&title_color=F85D7F&icon_color=F8D866" height="180px"/>
  <img alt="Djamel's top languages" src="https://denvercoder1-github-readme-stats.vercel.app/api/top-langs/?username=Strawbang&langs_count=8&layout=compact&theme=react&hide_border=true&bg_color=1F222E&title_color=F85D7F&icon_color=F8D866&hide=Jupyter%20Notebook,Roff" height="180px"/>
</p>

## Elsewhere

[GitHub](https://github.com/strawbang) · [LinkedIn](https://linkedin.com/in/djamel-bougouffa) · [dev.to](https://dev.to/strawbang) · [djamel-bougouffa.com](https://djamel-bougouffa.com)
