# Hi, I'm JonneLiu 👋

**Construction business manager × AI practitioner — I turn real engineering workflows into working AI-assisted systems.**

Based in China. I manage construction projects and procurement by day, and build practical AI workflows with ChatGPT, Codex and Muse — not demos, but systems that run in production every day.

- 🏗️ Licensed Constructor (Class II) in both Building Engineering and M&E Engineering; Intermediate Engineer (Building)
- 🤖 Daily AI builder since 2025/2026: tender intelligence automation, a production vehicle-management system, document automation
- 🌏 Exploring AI-enabled cross-border trade (Amazon US validation in progress)
- 💬 Languages: Chinese (native); English — written communication with AI assistance
- 📫 Contact: via GitHub [@JonneLiu](https://github.com/JonneLiu)

## Featured AI projects

### 1. Tender Intelligence Automation （招标信息自动抓取与筛选）
Built with **Codex (GPT)** from May 2026, iterated continuously to Oct 2026.
- Started as *TenderWatch* MVP: Python (standard library), SQLite, web admin + WeChat mini-program skeleton, project scoring by qualifications / keywords / budget / region
- Evolved into a daily production crawler: multi-site tender & procurement scraping, **132 screening rules**, scheduled daily runs (macOS launchctl), Excel daily reports and e-mail delivery
- Human-in-the-loop by design: the system collects and screens; bid / no-bid decisions stay with people

### 2. Bid Pricing Decision System （投标报价决策系统）
Specified in **ChatGPT**, built locally with **Codex** (Jul 2026).
- Python + Streamlit + SQLite, Decimal-precision arithmetic; models Chinese tender evaluation rules: non-competitive fee deductions, high/low trimming, outlier elimination, benchmark-price modes, price scoring
- Monte Carlo simulation across competing bidders — outputs top-score probability and a recommended bid range
- Built like engineering: spec first, P0–P3 review list before iteration, staged V1→V2→V3 releases, exports (Excel/CSV/PDF/HTML) with formulas and parameters attached for audit

### 3. Vehicle Management System — in production for daily company use
Designed initially with **Codex**, then completed, merged and deployed with **Muse** to V1.1.3 (Oct 2026).
- Vehicle records, drivers, dispatch, fuel, maintenance, violations, and 30-day expiry reminders (insurance / inspection / licences)
- Deployed on Alibaba Cloud with Docker + Caddy HTTPS; custom domain with ICP filing completed (details withheld for privacy)
- Used daily by company staff, with role-based accounts administered in-house

### 4. AI workflows for construction business (ChatGPT / Codex / Muse)
Repeatable "input → AI extraction → professional review → deliverable" workflows for:
- Tender document analysis — key commercial terms, risk & clarification lists
- Bid-opening on-site calculation — photo of the handwritten bid record → OCR → average & benchmark price computed on the spot (20+ bidders; results flagged for human verification)
- Contract review — version comparison against the tender's contract template, payment terms, guarantees, liquidated-damages caps, variation-claim deadlines (a real eight-figure, 400-day contract reviewed clause by clause)
- Bills of quantities cross-checks — drawing vs. BOQ discrepancy lists
- Procurement — supplier quotation comparison, technical-parameter tables, Excel reports
- Document automation — e.g. staff ID photos → roster / Word documents via Python scripts (Codex, Jul 2026)
- Technical-bid image standardisation — a batch-processing instruction set for Codex covering 40+ chapters of construction-method statements: uniform typography, black-and-white, blind-bid compliance (no identity info in images), samples approved before batch runs, unrecognisable text flagged for humans — never guessed

### 5. Company operations system & AI automation blueprint (ChatGPT)
- Systematised the company's full workflow into a formal document: **12 stages, 48 work modules**, structured as dual tracks (bidding operations + project delivery)
- On top of it, a phased blueprint of 6 priority AI workflows (tendering, drawing/BOQ review, bid pricing, document generation, contract & variations, cost/profit monitoring) using ChatGPT + n8n + Dify + Excel + Python — a costed plan, clearly distinct from systems already in production

### 6. Cross-border trade validation (AI-assisted, English)
- Sourcing and negotiating with Alibaba suppliers in English with AI assistance; multi-supplier comparison on price, HS code, materials and lead time
- Landed-cost modelling (freight, duties, platform fees) and Amazon US (Individual + FBM) validation planning for a pet balcony safety-net product

## Core strengths

| Domain | What I bring |
|---|---|
| Construction business | Tendering, commercial terms, contracts, procurement, project coordination — from a contractor's operating perspective |
| AI application | Prompt-to-production workflow design; judging where AI helps, where human review is mandatory, and where it must not be trusted alone |
| Cross-functional coordination | Owners, designers, supervisors, suppliers and site teams |
| Supply chain | Building-materials sourcing and price/parameter negotiation in China |

**My positioning, honestly:** an engineering-business manager who applies AI to real work — not a full-time software engineer, and not an overseas licensed designer. AI output in my workflows always passes professional review before it is used.

---

## 中文版

中国的建筑企业管理者，也是 AI 实战使用者。我用 ChatGPT、Codex、Muse 把真实工程业务做成了每天在跑的系统：

- **招标情报自动化**（2026年5月起用 Codex 开发）：从 TenderWatch 原型（Python + SQLite + 小程序骨架）迭代为每日定时抓取、多站点筛选、132 条筛查规则、Excel 日报的生产系统；系统只做收集和筛选，投不投由人决定
- **投标报价决策系统**（ChatGPT 规划 + Codex 开发）：本地运行的报价系统，评标规则完整建模 + Monte Carlo 报价模拟 + 高精度计算与审查分级迭代
- **企业车辆管理系统**（Codex 初版设计 + Muse 完善部署）：已正式上线（V1.1.3，阿里云 + HTTPS + 完成备案），公司员工日常使用
- **工程商务 AI 工作流**：招标文件分析、开标现场照片 OCR 即时算分、合同逐条风险审查、清单与图纸疑点整理、采购比价、技术标图片批量标准化、文档自动化（资料输入 → AI提取 → 专业复核 → 成果交付）
- **经营体系与 AI 蓝图**：全流程 12 阶段 48 模块沉淀为制度文件，并规划 6 套优先 AI 自动化工作流
- **跨境贸易验证**：用 AI 做英文供应商询价谈判、多供应商比价与到岸成本测算，推进 Amazon 美国站验证

资质：建筑工程、机电工程双专业二级建造师，建筑工程中级工程师。
定位很明确：懂工程业务、用 AI 落地的管理者——不是专职软件工程师，AI 输出必须经专业复核才使用。

*Full résumé: [RESUME-CN.md](RESUME-CN.md) · Project details: [PROJECTS.md](PROJECTS.md)*
