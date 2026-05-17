# StellarAgentKit Docs: AI Agent Integration Playbook

[![Stellar Wave 5](https://img.shields.io/badge/Drips_Wave-5-blueviolet?style=for-the-badge)](https://www.drips.network/wave)
[![Language: Markdown](https://img.shields.io/badge/Language-Markdown-092e20?style=for-the-badge&logo=markdown)](https://daringfireball.net/projects/markdown/)
[![Documentation: Docusaurus](https://img.shields.io/badge/Documentation-Docusaurus-green?style=for-the-badge&logo=docusaurus)](https://docusaurus.io/)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg?style=for-the-badge)](https://opensource.org/licenses/Apache-2.0)

**The comprehensive developer playbook and integration portal for StellarAgentKit. Features setup guides, AI framework configurations, security blueprints, and SDK references.**

---

# 🤖 Overview

`stellaragentkit-docs` contains the developer guides and technical specifications for building and running secure AI-on-chain agents using the StellarAgentKit suite. Configured as a high-performance Docusaurus portal, it walks developers through the mathematical and cryptographic boundaries that prevent agent compromise.

### Key Documentation Chapters:
1.  **AI Framework Integrations:** Comprehensive guides to hook the `stellaragentkit-sdk` into LangChain, Autogen, Eliza core, and CrewAI.
2.  **Smart Security Architecture:** Explanations of `AgentWallet` delegation models and `SpendingLimit` mathematical evaluations.
3.  **Local Development Environment:** Guides on deploying mock token markets, Soroban AMMs, and agent sandboxes locally.
4.  **SDK & Tool Reference:** Detailed specification tables for each AI tool (`send_payment`, `swap_tokens`, `delegate_votes`).

---

# 🏗️ Portal Structure

```text
stellaragentkit-docs/
├── docs/
│   ├── integration/      # LangChain, Autogen, and Eliza connection blueprints
│   ├── security/         # Spending limits and smart wallet cryptographics
│   └── tools/            # SDK reference guides and method specifications
├── package.json          # Portal dependency configurations
└── README.md             # You are here
```

---

# 🛠️ Serving Locally

### Run Development Portal
To serve the interactive developer portal locally:
1. **Clone the Repo:** `git clone https://github.com/stellaragentkit-phantom/stellaragentkit-docs.git`
2. **Install Dependencies:** `npm install`
3. **Start Portal:** `npm run start`
4. **Access in Browser:** `http://localhost:3000`

---

# 📄 License

This project is licensed under the **Apache License 2.0**.
