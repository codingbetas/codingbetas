<div align="center">

# Himanshu Rathod

### Backend Engineer · AI Systems Developer

**I build scalable backends that don't fall over under load.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/himanshu-rathod-5815991bb)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:codewithhr@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/codingbetas)

<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=20&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=620&lines=5%2B+Deployed+Backends+in+Production+Style;Distributed+Locking+%7C+Celery+Pipelines+%7C+RBAC;FastAPI+%2B+PostgreSQL+%2B+Redis+%2B+Docker;Open+to+Backend+Engineering+Roles" />

</div>

---

## ⚡ TL;DR

- 🔧 **Backend Engineer** specializing in **Python + FastAPI**
- 🚀 Built and deployed **5+ production-style REST API backends** (all open source)
- 🧠 Solved **real concurrency problems** — Redis distributed locking, async Celery pipelines, RBAC
- 🤖 Integrated **ML models** (Random Forest, Isolation Forest) + **Google Gemini API** into live services
- 📍 **Available immediately** for Backend / AI-Backend roles

---

## 🛠 Tech Stack

| Layer | Technologies |
|---|---|
| **Languages** | Python · JavaScript · C++ |
| **Backend / APIs** | FastAPI · REST · JWT · OAuth2 · WebSockets · SQLAlchemy · Pydantic |
| **Async / Distributed** | Celery · Redis · Distributed Locking · Message Queues |
| **Databases** | PostgreSQL · SQL |
| **AI / ML** | Scikit-Learn · Random Forest · Isolation Forest · TF-IDF · NumPy · Pandas · Google Gemini API |
| **DevOps / Tools** | Docker · Docker Compose · Git · GitHub · Swagger/OpenAPI · Render · Vercel |
| **Concepts** | System Design · Distributed Systems · RBAC · OOP · DSA |

---

## 💼 Experience

### Backend Developer — Independent Projects
**Self-Directed · Remote** · `Jun 2024 – Present`

- Shipped **5+ production-style REST API backends** using Python / FastAPI — covering ML fraud detection, booking platforms, subscription management, and URL analytics
- Implemented **Redis distributed locking**, **Celery async pipelines**, **JWT + OAuth2**, **RBAC**, **Docker containerization**, and **Google Gemini AI integration** across live projects
- Every project is **deployed, documented, and open source**

---

## 🚀 Featured Projects

### 🗓 Beautician Booking Platform
`Python` · `FastAPI` · `Redis` · `PostgreSQL` · `JWT`

> **The hard problem:** Two users booking the same slot at the same millisecond.

- ✅ Solved with **Redis distributed locking** — prevents double-booking race conditions under concurrent load
- ✅ Designed a **5-state booking state machine** (Requested → Accepted → In Progress → Completed / Cancelled) with strict transition validation
- ✅ Implemented **RBAC** for 2 roles (user / beautician) with full JWT auth

🔗 [**View Code →**](https://github.com/codingbetas/beautician-booking)

---

### 🛡 FraudShield AI — Real-Time Fraud Detection
`Python` · `FastAPI` · `Scikit-Learn` · `Celery` · `Redis`

> **The hard problem:** ML inference is slow — it can't block an API request.

- ✅ Built a **dual-model ML backend** — Random Forest + Isolation Forest — for financial transaction fraud classification
- ✅ Designed a **Celery + Redis async pipeline** that decouples inference from the request cycle: API returns a `task_id` instantly, worker processes in the background
- ✅ Result: API stays responsive even under heavy ML load

🔗 [**View Code →**](https://github.com/codingbetas/fraudshield-ai)

---

### 🔗 SnapURL — URL Shortener with Analytics
`FastAPI` · `Next.js` · `PostgreSQL` · `Render` · `Vercel`

> **The hard problem:** Short links are easy. Tracking every click at scale isn't.

- ✅ Full-stack URL shortening platform with **IP logging**, **click analytics**, **custom aliases**, and **TTL-based expiration**
- ✅ Deployed live on **Render** (backend) + **Vercel** (frontend)

🔗 [**View Code →**](https://github.com/codingbetas/snapurl-url-shortener)

---

### 💳 SaaS Subscription Management System
`FastAPI` · `SQLAlchemy` · `PostgreSQL` · `JWT` · `OAuth2`

> **The hard problem:** Billing lifecycles are full of edge cases.

- ✅ Subscription lifecycle backend with plan upgrades, cancellations, and expiry tracking
- ✅ **Dual JWT + OAuth2** authentication
- ✅ Regex-based **CORS handling** for dynamic Vercel deployment URLs

🔗 [**View Code →**](https://github.com/codingbetas/saas-subscription-system)

---

## 🏗 Engineering Highlights

**Preventing Double-Booking Under Concurrency**

```
Client → API → Redis Lock (SETNX) → Validate State Transition → PostgreSQL Commit → Release Lock
```

*Race conditions handled at the lock layer — not patched after the fact.*

**Keeping APIs Fast When ML Is Slow**

```
Client → API (returns task_id) → Celery Queue → ML Worker (RF + Isolation Forest) → Redis Result Store
                                                                                          ↓
                                                                       Client polls /result/{task_id}
```

*Heavy inference never blocks the request cycle.*

## 🎓 Education

**B.Tech — Computer Science & Engineering**
Geetanjali Institute of Technical Studies, Rajasthan
**CGPA: 8.39 / 10.0** · First Division with Distinction · **2024**

**Relevant Coursework:** Data Structures & Algorithms · DBMS · Operating Systems · Computer Networks

---

<div align="center">

### 📬 Let's Build Something

**Open to Backend Engineer & AI-Backend roles — available for immediate joining.**

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/himanshu-rathod-5815991bb)
[![Email Me](https://img.shields.io/badge/Email_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:codewithhr@gmail.com)

*"Complexity is the enemy of reliability."*

</div>
