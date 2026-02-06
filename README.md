# Selected AI Initiatives

This repository catalogs **specific, named AI initiatives** delivered across
products, platforms, and exploratory implementations.

Unlike the anonymized case studies documented elsewhere, the initiatives listed
here are intentionally attributed to their respective products, organizations,
or platforms to reflect **direct ownership, delivery responsibility, and hands-on
involvement**.

The initiatives span varying levels of maturity—from production systems to
learning-oriented implementations—but all represent work that moved beyond
analysis into **delivered capability**.

---

## Product & Platform Initiatives

### AceRoute — AI/ML Field Service Optimization Platform
**Type:** Product platform  
**Context:** Real-time routing and scheduling under live operational constraints  

AceRoute is an ML-driven field service optimization platform designed to improve
on-time arrivals, reduce dispatcher workload, and continuously adapt during live
execution.

Key characteristics:
- Real-time optimization with SLA and contractual constraints
- Autonomous decisioning bounded by human-on-the-loop dispatcher control
- Continuous re-optimization using traffic, technician skill, and delay signals
- Designed to operate under uncertainty without disrupting live operations

🔗 Organization: https://github.com/aceroute

---

### ProdWorks — Enterprise AI Consulting & Solution Delivery
**Type:** Consulting and solution initiatives  
**Context:** Discovery-led AI delivery for enterprise environments  

ProdWorks represents a collection of enterprise AI initiatives focused on
translating ambiguous business problems into governed, production-ready AI
systems.

Work across these initiatives includes:
- Analytical discovery and decision/value assessment
- AI operating model and autonomy boundary definition
- Governance-by-design and trust mechanisms
- Adoption, measurement, and value realization planning

🔗 Organization: https://github.com/ProdWorks

---

## Applied & Exploratory Initiatives

### Graph RAG with Neo4j — Beverage Domain Knowledge Graph
**Type:** Applied technical initiative  
**Context:** Structured domain modeling for retrieval-augmented generation  

This initiative explores Graph-based Retrieval Augmented Generation (RAG) using
Neo4j to model complex beverage hierarchies, attributes, and relationships.

Focus areas:
- Knowledge graph–driven retrieval over structured domains
- Explicit modeling of taxonomies, regions, and flavor attributes
- Combining graph traversal with LLM reasoning for higher-precision responses
- Evaluating when structured context outperforms embedding-only approaches

---

### Python AI Chatbot — Learning-Oriented Assistant
**Type:** Exploratory learning initiative  
**Context:** Controlled conversational AI for structured learning  

A Python-based AI chatbot designed to support guided learning use cases, with an
emphasis on intentional interaction design rather than open-ended conversation.

Focus areas:
- Prompt structuring and conversational guardrails
- Conversation state and learning progression management
- Reducing hallucination risk through constrained response patterns
- Designing AI assistance that supports learning objectives, not replacement

---

## How this repository fits into the broader view

This repository focuses on **what has been delivered and owned**.

- Analytical framing and discovery are documented in  
  `enterprise-ai-discovery-kit`
- Autonomy and decision boundaries are documented in  
  `agentic-decision-boundaries`
- Governance and control mechanisms are documented in  
  `ai-governance-by-design`
- Outcome behavior and tradeoffs are analyzed separately in anonymized  
  `enterprise-ai-case-studies`

Together, these repositories provide a system-level view of enterprise AI—from
analysis and design through delivery and real-world behavior.
