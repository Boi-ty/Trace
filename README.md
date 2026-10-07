
TRACE: AI-Powered Autonomous Application Security Testing Platform


🏆 Project Details

• Project Name: TRACE
• Hackathon: Sebaka Testing AI Hackathon 2026
• Pillars Covered: Software Quality Engineering — Application Security Testing
• Architecture: Multi-Agent Asynchronous Security Verification Platform
• Primary Target Baseline: OWASP Top 10 Compliance Framework

1. Executive Summary

TRACE is an AI-powered autonomous application security testing platform designed to bridge the gap between traditional vulnerability scanners and manual penetration testing. Traditional security tooling frequently overwhelms software development teams with thousands of raw, static, and often unverified warning strings.
TRACE operates under a distinct security testing lifecycle philosophy:
"Don't just report a vulnerability. Prove it. Don't just say it's fixed. Verify it."
TRACE decouples AI reasoning from environmental evidence. The system uses a network of autonomous agents to crawl applications, formulate exploit hypotheses, and execute real-time network interactions to prove exploitation. It then routes raw log evidence through a localized, zero-cost AI cognition layer to translate raw data anomalies into highly actionable developer remediation briefs.

2. Dynamic Platform Architecture (3x3 Core Suite)

TRACE coordinates three decoupled Master Agents, each governing specialized subagent validation modules to tackle core categories of the OWASP Top 10 framework:
text
TRACE Master Core Suite
│
├── 🛡️ 1. SENTINEL (Identity & Access Control Master) ───➔ OWASP A01: Broken Access Control & A07: Authentication
│      ├── Identity Validation Bot: Audits password complexity matrix and brute-force limits.
│      ├── Session Auditor: Inspects token randomness, cookie flags, and post-logout token lifecycle.
│      └── Access Enforcer: Tests for internal resource isolation boundaries and privilege escalation paths.
│
├── ⚙️ 2. HARDENBOT (Security Configuration Master) ──────➔ OWASP A02: Security Misconfiguration
│      ├── Default Surface Hunter: Scans for default factory profiles and unlinked background paths.
│      ├── Information Leak Scanner: Provokes server syntax crashes to audit for verbose text leaks.
│      └── Cloud Posture Inspector: Verifies open asset storage repositories and network port configurations.
│
└── 💥 3. PAYLOADPRO (Injection Master) ─────────────────➔ OWASP A05: Injection
       ├── Database Query Breaker: Fuzzes input fields with SQL/NoSQL escaping strings.
       ├── System Command Executor: Audits code pathways for OS command injection vectors.
       └── Script Injector: Explores form entry modules for Cross-Site Scripting (XSS) exposures.
Use code with caution.

3. Advanced Features for Real-World Security Quality Engineering

To evolve past static "marketing demos" and provide an enterprise-grade utility, TRACE features a controllable testing control grid:
• Attack Intensity Scope Selector (1-10): Throttles payload complexity dynamically. Lower tiers run fast, non-disruptive logic checks, while higher tiers (8-10) run aggressive multi-class database fuzzing strings.
• Pacing Rate Throttle Engine (req/sec): Controls the background request frequency to avoid disrupting target web application availability or triggering standard firewalls.
• AI Context Engineering Notes Layer: Permits human testers to feed high-level architectural clues (e.g., framework versions, token keys) directly into the AI prompt layer to drastically optimize scan-report accuracy.
• Compliance & Legal Consent Gateway: Enforces ethical boundaries by requiring explicit authorization validation before firing active network execution cycles.

4. Technical Stack & 0-Cost Local AI Cognition

• Frontend Interface: React (Vite) + Tailwind CSS providing a modern dashboard layout.
• Backend Processor: Node.js (TypeScript) + Express handling asynchronous request routing and HTTP state checking.
• Network Gateway: Axios handling cookie persistence and header adjustments.
• Cognition Core Layer: Ollama API parsing local Llama 3 (8B) models. TRACE achieves 100% data privacy and R0 infrastructure operational costs by evaluating exploits locally without calling paid third-party APIs.

5. Local Setup & Execution Guide


📋 Prerequisites

Ensure your local development environment has the following software packages active:
• Node.js (v18+) & npm
• Ollama Desktop
• Docker Desktop (Optional - for target sandboxes)

⚙️ Step-by-Step Installation


1. Setup the Local AI Cognition Layer

Open a terminal window and pull down the open-source threat analysis model:
bash
ollama run llama3
Use code with caution.
Ensure this process remains active in the background on port 11434.

2. Configure and Boot the TRACE Backend Engine

Navigate into the server code workspace, fetch the dependency trees, and run the developer compiler compiler tools:
bash
cd server
npm install
npm run dev
Use code with caution.
The server will boot and display an active hook connection listening on port 8000.

3. Launch the Frontend Dashboard Application

Open a secondary parallel terminal instance, jump into the client workspace directory, and trigger the development server:
bash
cd client
npm install
npm run dev
Use code with caution.
Open http://localhost:5173 inside your internet browser to access the TRACE control panel.

4. Safe Target Testing (0-Cost Sandbox)

Point the TRACE targeting tray directly at any authorized local server (e.g., http://localhost:3000) or a safe, community-approved online bounty playground like:
text
https://herokuapp.com
Use code with caution.
