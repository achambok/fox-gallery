# Gallery Project

A next-generation photo & file gallery platform designed to **disrupt Google One, Google Photos, OneDrive, Dropbox, and Apple Photos** by offering:

- ✅ **Ultra-low-cost pricing**
- ✅ **Built-in sovereign data controls**
- ✅ **Unlimited tiered storage at affordable rates**
- ✅ **GDPR & geo-compliant by design**

Built on a modular multi-agent architecture where all sub-agents report to the **Director** as the central orchestrator.

## 🎯 Vision
Capture market share from users frustrated with expensive storage upgrades and lack of control over their data.

## 🧠 Architecture
- **Orchestrator**: Director (main agent)
- **Sub-Agents**: 9 specialized experts
- **MCP Protocol**: Defined in `mcp/mcp-protocol.yaml`

## 🛠️ Tech Stack
See [`tech-stack.md`](./tech-stack.md)

## 📚 Agents
Each agent is defined in `/agents/` with:
- Role
- Tasks
- Tools & Tech
- Reporting Structure

💻 Frontend Expert – Builds the user interface and ensures a seamless, fast, and beautiful gallery experience.

### 🎯 Why This Role Is Essential
- **User Retention:** A slow or clunky UI drives users back to Google or Apple.
- **First Impressions:** Your app must feel premium, even if it's cheaper.
- **AI Search UX:** Tag-based search (e.g., “sunset”) needs intuitive UI.
- **Offline Access:** PWA support requires dedicated frontend work.
- **Brand Trust:** Polished UI = trustworthy product.
- **Marketing Alignment:** Landing pages, onboarding, and trials are frontend-heavy.

**Without a Frontend Expert, you risk:**
- Poor conversion from free to paid
- High churn due to bad UX
- Inability to compete visually with incumbents

## 📊 Strategy
See [`strategy.md`](./strategy.md) for competitive positioning and marketing roadmap.

## 🚀 Getting Started
1. Review `mcp-protocol.yaml`
2. Assign agent roles
3. Begin sprint planning
4. Use the architecture flow in `docs/architecture-flow.png`
