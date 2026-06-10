<!--
  This is your GitHub PROFILE README.
  To make it show on your profile: create a repo named exactly `shaurya703`
  (github.com/new → repository name: shaurya703 → check "Add a README"),
  then replace its README.md with this file's contents.
-->

# Hi, I'm Shaurya 👋

I build complete, production-minded systems — and I like working across the whole
stack: a low-latency backend in Go, a real-time full-stack product, an end-to-end
ML service, and a data investigation that lands a concrete finding. Each project
below is finished, documented, and reproducible from a single command.

---

### 🔗 [linkforge](https://github.com/shaurya703/linkforge) · *Backend systems · Go*
A production-minded URL shortener focused on correctness and operational maturity.
> **~26,500 req/s on the redirect hot path at p99 ≈ 5.4 ms, 99.99% cache hit rate, zero errors** (single instance, Postgres + Redis).

Caching, Redis-backed rate limiting, async click analytics, observability, load-tested with k6.

---

### 📋 [devboard](https://github.com/shaurya703/devboard) · *Full-stack product · TypeScript*
A real-time Kanban tool (Trello/Linear-style) with live multi-client sync.
> **JWT refresh-rotation with reuse detection, optimistic drag-and-drop with rollback, typed end-to-end contracts — `docker compose up` and you're running.**

Socket.IO rooms, role-based sharing (owner/editor/viewer), activity log, React + Node.

---

### 🧮 [credit-risk-explainer](https://github.com/shaurya703/credit-risk-explainer) · *Machine learning · Python*
An end-to-end loan-default model that **explains every prediction** with SHAP.
> **Reproducible pipeline → calibrated XGBoost → FastAPI service → Streamlit dashboard**, with explainability as the headline feature, not an afterthought.

Honest handling of class imbalance, cost-based thresholding, calibration over raw accuracy.

---

### 📉 [hidden-mutual-fund-fees](https://github.com/shaurya703/hidden-mutual-fund-fees) · *Data analysis · Python*
Measuring what India's "Regular" mutual-fund plans quietly cost investors.
> **Across 1,084 matched funds, Direct beat Regular in 99% of cases — costing a typical equity SIP ~₹27 lakh over 20 years (18% of the corpus).** Paired Wilcoxon *p* ≈ 10⁻¹⁷⁶.

A clean, assumption-free measurement from official data — same portfolio, two share classes.

---

**Stack:** Go · TypeScript/React/Node · Python (scikit-learn, XGBoost, SHAP, FastAPI) · PostgreSQL · Redis · Docker

📫 kesar.rahulk@gmail.com
