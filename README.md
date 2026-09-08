# David-Eugen Petcu

**Software Engineering · Systems · Information Retrieval · AI/ML**

B.Sc. candidate in **Economic Cybernetics at the Bucharest University of Economic Studies (ASE)**  
Expected graduation: **July 2027**

I build software around performance, search & ranking, infrastructure, and applied AI — with a focus on understanding the systems underneath rather than treating them as black boxes.

Currently:
- **Incoming Business Platforms Intern @ Endava**
- **Technical Lead @ Bitdefender Academy**
- Based in **Bucharest, Romania**

---

## Featured Projects

### [Scalable Logo Clustering Engine](https://github.com/PetcuDavid/Scalable-Logo-Clustering-Engine)

**C++20 · Python · asyncio · DSU · Multithreading · CMake · GitHub Actions**

A scalable pipeline for extracting web assets and clustering visually similar logos using perceptual hashing.

I moved the CPU-bound similarity stage from Python to C++20, using **64-bit Hamming distance and Disjoint Set Union**, achieving a **67× speedup** over the Python baseline on multi-million-comparison benchmarks.

The project also includes:

- bounded-concurrency asynchronous asset extraction
- multithreaded similarity evaluation
- differential testing against the Python reference implementation
- GoogleTest / CTest
- AddressSanitizer and UndefinedBehaviorSanitizer
- cross-platform GitHub Actions CI

**Focus:** algorithms, performance engineering, concurrency, testing, systems programming

---

### [PRISM — Hybrid Search & Ranking](https://github.com/PetcuDavid/PRISM-Pipeline-for-Ranked-Intelligent-Search-Matching)

**Python · BM25 · Vector Search · Cross-Encoder Reranking · LLMs · scikit-learn**

A multi-stage information retrieval pipeline designed to improve ranking quality while controlling expensive model usage.

PRISM combines:

`Hard Filters → BM25 / Vector Retrieval → Cross-Encoder Reranking → Confidence Routing → LLM`

The pipeline uses three-state filtering to handle incomplete data and reranks the top candidates with a cross-encoder, reducing LLM calls by approximately **15×** compared with routing every candidate through the model.

**Focus:** information retrieval, ranking systems, semantic search, ML system design

---

### [Aegis — Private Cloud Infrastructure & Automation](https://github.com/PetcuDavid/Aegis-Infrastructure)

**Linux · Docker · Ansible · Bash · Networking · Security · Prometheus · Grafana**

A resource-efficient private cloud built on legacy hardware and automated through infrastructure-as-code.

The environment runs multiple containerized services with automated provisioning and hardened networking, while exposing **0 public inbound ports**.

**Focus:** Linux systems, infrastructure automation, networking, security, observability

---

## Experience

**Endava** — Incoming Business Platforms Intern  
`Sep 2026 – Dec 2026`

**Bitdefender Academy** — Technical Lead, Student Venture Program  
`Apr 2026 – Oct 2026`

Built embedded and application prototypes across **C++ / ESP32, C# and JavaScript**, and owned technical feasibility and architecture for a hardware-software product.

**Systematic Academy** — System Engineering Apprenticeship  
`Mar 2026 – Apr 2026`

Worked with **Kubernetes, Flux and GitOps workflows** and integrated tooling for structured LLM access to internal documentation.

---

## Other Work

### [Liveness Pulse](https://github.com/PetcuDavid/Liveness-Pulse-PoC)
Proof of concept exploring video-stream integrity and frequency-domain signal analysis using Python, OpenCV and FFT.

### [ASE GradeWatcher](https://github.com/PetcuDavid/ASE-GradeWatcher)
Python automation for detecting new academic results and sending real-time notifications.

### [Jewelry ERP — SQL Analytics](https://github.com/PetcuDavid/jewelry-erp-sql-analytics)
Oracle SQL / PL/SQL project covering relational database design, analytics and business logic.

---

## Research

🥈 **2nd Place — Annual Student Scientific Conference, ASE Bucharest, 2026**

**The "Guns vs. Butter" Dilemma in the New Era of Global Insecurity:  
The Impact of Rearmament on Capital Formation in NATO's Eastern Flank States**

[View the research project →](https://github.com/PetcuDavid/Guns-vs-Butter-Macroeconomics)

---

## Technical Toolbox

**Programming**  
`C++` · `Python` · `C` · `JavaScript` · `C#` · `SQL` · `Bash`

**Systems & Infrastructure**  
`Linux` · `Docker` · `Kubernetes` · `Ansible` · `Git` · `GitHub Actions` · `Flux`

**AI / ML / Information Retrieval**  
`BM25` · `Vector Search` · `Cross-Encoder Reranking` · `RAG` · `LLMs` · `scikit-learn`

**Concepts I work with**  
`Data Structures & Algorithms` · `Concurrency` · `Information Retrieval` · `Networking` · `Security` · `CI/CD`

---

## Contact

[LinkedIn](https://www.linkedin.com/in/david-petcu/) ·
[Email](mailto:petcudavid504@gmail.com)
