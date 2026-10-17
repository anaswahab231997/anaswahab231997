# Anas Wahab
### Applied AI Systems & Workflow Automation Builder
**Location:** Mumbai / Pune / Kolkata, India • **Email:** [anas@ainexlifyagencies.com](mailto:anas@ainexlifyagencies.com) • **LinkedIn:** [linkedin.com/in/anaswahab97](https://linkedin.com/in/anaswahab97) • **GitHub:** [github.com/anaswahab231997](https://github.com/anaswahab231997)

---

### 🧭 Overview
I build fault-tolerant autonomous agent pipelines, deterministic data extraction engines, and high-throughput workflow infrastructure. My focus is engineering production reliability into non-deterministic LLM applications—enforcing strict schema validation, atomic idempotency, and graceful failure handling.

- ⚡ **Upstream Open Source:** Contributor to [BerriAI/litellm](https://github.com/BerriAI/litellm) (PR #42490 — enterprise OAuth token proxy security).
- 🛡️ **Zero-Hallucination Systems:** Architecting AST-validated pipelines with dynamic Pydantic enums and mathematical invariant checks.
- 🔄 **Event-Driven Architecture:** Building asynchronous workers with Redis/PostgreSQL check-and-claim patterns, rate limiting, and dead-letter queues.

---

### 🛠️ Core Engineering Stack

| Domain | Technologies & Systems |
| :--- | :--- |
| **Languages & Runtimes** | Python (FastAPI, asyncio, Pydantic v2), Node.js / TypeScript, SQL (PostgreSQL) |
| **AI Infrastructure & Gateways** | LiteLLM Proxy, Google Gemini API, Claude API, OpenAI API, Structured Outputs |
| **Data & Storage** | Supabase (PostgreSQL, pgvector, Row-Level Security), Redis (Distributed Locks), SQLite |
| **Workflow & Integration** | n8n (Queue Mode), Webhook Gateways, Twilio Communications, Shopify APIs, REST/GraphQL |
| **Frontend & Operational UI** | HTMX, Tailwind CSS, Jinja2, Netlify, Chrome DevTools |

---

### 📌 Featured Systems & Repositories

#### 1. [The Invisible Accountant](https://github.com/anaswahab231997/invisible-accountant)
*Autonomous UK financial document extraction & HMRC MTD compliance engine.*
- **Reliability:** Uses dynamic Pydantic enums strictly constrained to client Chart of Accounts to eliminate category hallucination; verifies mathematical checksums on all line items.
- **Fault-Tolerance:** Implements `asyncio.Semaphore` concurrency controls, two-phase idempotency locks, and human-in-the-loop escalation queues.
- `Python` • `FastAPI` • `Gemini API` • `SQLite/PostgreSQL` • `Pydantic v2` • `pytest`

#### 2. [Speed To Lead™](https://github.com/anaswahab231997/speed-to-lead)
*Real-time inbound lead qualification engine and webhook dispatcher.*
- **Velocity & Safety:** Processes and qualifies inbound webform leads in sub-25 seconds with automated intent scoring, calendar dispatch, and atomic Redis deduplication locks to prevent double-messaging.
- `Node.js` • `Twilio` • `Claude API` • `Airtable/PostgreSQL` • `Webhooks`

#### 3. [LiteLLM Upstream Contributions](https://github.com/anaswahab231997/litellm)
*Upstream contributions and configuration patterns for the LiteLLM AI Gateway.*
- **Security Fix:** [PR #42490](https://github.com/BerriAI/litellm/pull/42490) — Scoped Anthropic OAuth credentials strictly to `api.anthropic.com`, eliminating multi-provider token leakage across proxy endpoints.
- `Python` • `LiteLLM` • `OAuth & Security` • `AI Gateway`

---

### 📫 Connect
- **Email:** [anas@ainexlifyagencies.com](mailto:anas@ainexlifyagencies.com)
- **LinkedIn:** [linkedin.com/in/anaswahab97](https://linkedin.com/in/anaswahab97)
- **Website:** [ainexlifyagencies.com](https://ainexlifyagencies.com)
