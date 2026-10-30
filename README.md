# Anas Wahab
### Applied AI Systems & Workflow Automation Builder
**Location:** Mumbai / Kolkata, India • **Email:** [anas@ainexlifyagencies.com](mailto:anas@ainexlifyagencies.com) • **LinkedIn:** [linkedin.com/in/anaswahab97](https://linkedin.com/in/anaswahab97) • **GitHub:** [github.com/anaswahab231997](https://github.com/anaswahab231997)

---

### 🧭 Overview
I build fault-tolerant autonomous agent pipelines, deterministic data extraction engines, and event-driven workflow infrastructure. My focus is engineering production reliability into non-deterministic LLM applications—enforcing strict schema validation, atomic idempotency, and transactional data integrity.

- 🛡️ **Schema-Governed AI Pipelines:** Dynamic Pydantic validation constraining LLM outputs to strict ERP and accounting taxonomies at token generation.
- ⚡ **Transactional Event Systems:** Asynchronous workers, PostgreSQL `FOR UPDATE SKIP LOCKED`, sub-second webhook orchestration, and idempotency safeguards.
- 🔒 **Data Integrity & Security:** Entity-level SHA-256 deduplication, AES-256-GCM authenticated credential encryption, and human-in-the-loop audit queues.

---

### 🛠️ Core Engineering Stack

| Domain | Technologies & Systems |
| :--- | :--- |
| **Languages & Runtimes** | Python (FastAPI, asyncio, Pydantic v2), Node.js / Express, SQL (PostgreSQL) |
| **AI Infrastructure & Gateways** | Google Gemini API (`google-genai`), Claude API, Structured Outputs & Constrained Decoding |
| **Data & Storage** | PostgreSQL (`asyncpg`, transactional queuing via `SKIP LOCKED`), Supabase (Row-Level Security), Redis |
| **Workflow & Integration** | Webhook Gateways, n8n (Queue Mode), Twilio Communications, REST / WebSockets |
| **Frontend & Operational UI** | HTMX, Tailwind CSS, Jinja2, Server-Sent Events (SSE) |

---

### 📌 Featured Systems & Repositories

#### 1. [The Invisible Accountant](https://github.com/anaswahab231997/invisible-accountant)
*Autonomous UK financial document extraction & HMRC MTD compliance engine.*
- **Schema Enforcement:** Dynamically compiles runtime Pydantic enums constrained directly to the target Chart of Accounts to eliminate category hallucination at token generation.
- **Transactional Integrity:** Implements PostgreSQL `asyncpg` with `FOR UPDATE SKIP LOCKED` for atomic task dispatching, preventing distributed queue race conditions.
- **Audit Verification:** Verifies mathematical checksums (`abs((net + tax) - gross) <= 0.01`) across line items and flags discrepancies to a human-in-the-loop review dashboard.
- `Python 3.11+` • `FastAPI` • `Gemini API` • `PostgreSQL / asyncpg` • `Pydantic v2` • `HTMX`

#### 2. [Speed To Lead™](https://github.com/anaswahab231997/speed-to-lead)
*Real-time inbound lead qualification engine and webhook dispatcher powering [ainexlifyagencies.com](https://www.ainexlifyagencies.com).*
- **Edge Routing:** Ingests webhooks with immediate sub-100ms HTTP acknowledgment while continuing asynchronous downstream LLM qualification.
- **Resilient AI Gateway:** Implements multi-tier model failover (cascading from primary to fallback models) to handle upstream HTTP 429 / 503 rate limits gracefully.
- **Real-Time Delivery:** Streams live interaction tokens to client interfaces via Server-Sent Events (SSE).
- `Node.js` • `Express 5.x` • `Gemini API` • `Supabase / PostgreSQL` • `Twilio` • `SSE`

---

### 📫 Connect
- **Email:** [anas@ainexlifyagencies.com](mailto:anas@ainexlifyagencies.com)
- **LinkedIn:** [linkedin.com/in/anaswahab97](https://linkedin.com/in/anaswahab97)
- **Website:** [ainexlifyagencies.com](https://www.ainexlifyagencies.com)
