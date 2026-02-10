# Vishwas Bajaj

**Open-Source & Systems-Focused Computer Science Student**  
*Bitcoin Core–Adjacent Tooling*

📧 Email: vishwasbajaj.global@gmail.com  
🐙 GitHub: https://github.com/vishwas-droid  
🔗 LinkedIn: https://www.linkedin.com/in/vishwas-bajaj-09a6bb37a  

📄 **Resume**  
👉 [Download Resume (PDF)](https://github.com/vishwas-droid/about-me/raw/main/Vishwas_Bajaj_Resume_pdf.pdf)

---

## About

Open-source contributor focused on systems programming, Bitcoin Core,
testing, and long-term maintainability of production-grade software.
I prefer conservative, review-driven development with minimal diffs,
clear reasoning, and reproducible results.

---

## Skills

**Languages**  
C++, C, Python, Bash (POSIX)

**Core Computer Science**  
Data Structures, Algorithms, Operating Systems, Computer Networks, Concurrency

**Linux & Systems**  
Linux internals, system calls, POSIX APIs, processes, threads, IPC,
signals, file systems, sockets

**Bitcoin**  
Bitcoin architecture, UTXO model, transactions, scripts, blocks,
mining, mempool, consensus, Bitcoin Core

**Bitcoin Core Development**  
Codebase familiarity, build system, RPC interface, configuration,
functional tests

**Open Source Engineering**  
Git, GitHub, code reviews, patch writing, issue discussion, mailing lists

**Build & Tooling**  
Make, CMake, Autotools, GCC, Clang

**Debugging**  
GDB, Valgrind, strace, perf (basic)

**Testing**  
Unit tests, functional tests, regression tests

**Documentation**  
Technical writing, Markdown, design docs, clear commit messages

**Operating Systems**  
Linux (Arch, Debian, Ubuntu)

---

## Featured Projects


### Bitcoin Mempool Analyzer
**Python · Bitcoin Core · RPC · Regtest**

A correctness-first CLI tool for analyzing live Bitcoin Core mempool data.
The project connects to a local Bitcoin Core node via RPC and reports
transaction counts and fee-rate distribution in sat/vB without making
predictive assumptions.

**Key highlights:**
- Integrated directly with Bitcoin Core RPC (`getmempoolinfo`, `getrawmempool`)
- Computes fee rates in sat/vB from real mempool entries
- Designed with strict separation of concerns (CLI, analysis, RPC)
- Tested against a local Bitcoin Core node running in regtest mode
- Focused on transparency, reproducibility, and long-term maintainability

**Tech stack:**  
Python, Bitcoin Core, JSON-RPC, Regtest, CLI tooling

🔗 **Repository:** https://github.com/vishwas-droid/bitcoin-mempool-analyzer

### Bitcoin Fee Estimator 
https://github.com/vishwas-droid/bitcoin-fee-estimator

- Python-based CLI using Bitcoin Core RPC  
- Reads live mempool data and converts fees to sat/vB  
- Estimates fees based on confirmation targets  
- Built to understand fee markets and transaction inclusion

### Lightning Network Discord Tipping Bot  
https://github.com/vishwas-droid/ln-tipping-bot

- Discord bot enabling Lightning Network tipping  
- Implements BOLT11 invoice creation and payment flow  
- Modular separation of bot, database, and Lightning layers  
- Focused on real-world Lightning usage

---

## Open Source Contributions

### Astropy
- Stabilized datetime arithmetic tests using refined Hypothesis strategies  
- Eliminated flaky and nondeterministic edge cases in a large, mature codebase  
- Improved test robustness, clarity, and long-term maintainability  

**Selected Pull Requests**
- **PR #19178 (merged):** Stabilized datetime arithmetic tests by refining
  Hypothesis strategies and eliminating nondeterministic failures
  https://github.com/astropy/astropy/pull/19178
- **PRs #19240, #19243, #19245, #19252, #19253 (merged):**
  Documentation and test-quality improvements  

### Doxygen
- Documentation maintenance and archived link fixes  
- **PR #11947 (merged)**
- https://github.com/doxygen/doxygen/pull/11947

---

## Professional Experience

### Athena Blockchain Consulting LTD. (Dubai)
- Cloud system design for a financial application  
- Next.js deployment on AWS (Debian EC2, NGINX, Load Balancers)  
- CI pipelines using GitHub Actions  
- Managed onboarding documentation and collaborated on security audits  

### Technical GTM Freelancer (Tel Aviv, Israel)
- Authored 50+ pages of security-focused technical documentation  
- Ghostwrote CTO-level technical content on reachability analysis  
- Resolved Linux deployment issues using POSIX-compliant scripts  

### Chuku LLC. (Texas, USA)
- Security research on TP-Link WR-720N routers  
- Firmware dumping and UPnP protocol analysis  
- Protocol-level vulnerability research  

---

## Areas of Interest

- **Bitcoin Core Development:** Protocol-level changes, performance optimization,
  and long-term maintainability under strict backward-compatibility constraints.
- **Systems Programming:** C/C++ systems code, memory management, concurrency,
  and correctness-first, performance-critical development.
- **Distributed & P2P Systems:** Peer-to-peer networking, message propagation,
  fault tolerance, and decentralized consensus in adversarial environments.
- **Mempool & Transaction Handling:** Transaction validation, fee estimation,
  mempool policies, relay logic, and inclusion incentives.
- **Testing, Reliability & Security:** Eliminating flaky behavior, ensuring
  reproducible results, and maintaining protocol-level safety in production systems.
- **Open Source Engineering & Documentation:** Review-driven development,
  minimal diffs, clear commit messages, and maintainable technical documentation.

---

## Why Me

I work best in environments where correctness, clarity, and long-term
maintainability matter more than speed or short-term results.

My experience with mature open-source projects has trained me to read large
existing codebases, understand historical design decisions, and propose
small, well-scoped changes that are easy to review and validate. I value
maintainer feedback, conservative iteration, and changes that can be
confidently maintained years into the future.

---

## Interest in Bitcoin

My interest in Bitcoin is technical rather than financial. I am motivated by
how decentralized systems operate under strict constraints such as limited
block space, adversarial environments, and long-term backward compatibility.

Working with Bitcoin Core data through a fee estimator helped me understand
mempool dynamics, fee markets, and transaction inclusion trade-offs. Building
a Lightning Network tipping bot exposed me to real-world scalability
challenges, payment flows, invoice lifecycles, and failure modes in live
systems.

I am particularly interested in how conservative, correctness-focused
changes are designed, reviewed, tested, and maintained in production-critical
systems like Bitcoin Core.
