# The Hidden Layer of AI: Infrastructure Lessons Reference Kit

Welcome! This repository serves as the complete resource library, benchmarking template hub, and architectural reading list for the GHCI 2027 technical session: **"The Hidden Layer of AI: Infrastructure Lessons Every Engineer Should Know."**

---

## 📚 Foundational Reading List & References

All architectural methodologies, memory constraint equations, and optimization trade-offs discussed in this session are grounded in the following industry-standard literature and production documentation:

### 1. AI Engineering & Production Systems
* **AI Engineering** — Chip Huyen *(O'Reilly)*
* **Designing Machine Learning Systems** — Chip Huyen *(O'Reilly)*
* **Building Machine Learning Powered Applications** — Emmanuel Ameisen *(O'Reilly)*

### 2. Infrastructure & Systems Thinking
* **Chip War** — Chris Miller *(Simon & Schuster)*
* **The Coming Wave** — Mustafa Suleyman *(Penguin Random House)*
* **Systems Performance: Enterprise and the Cloud** — Brendan Gregg

### 3. Distributed Systems & Scalability
* **Designing Data-Intensive Applications** — Martin Kleppmann *(O'Reilly)*
* **Site Reliability Engineering (SRE) Handbook** — Google *(O'Reilly)*

### 4. High-Throughput Production Frameworks
* **NVIDIA Triton Inference Server** — [Documentation & GitHub](https://github.com/triton-inference-server/server)
* **vLLM Project & Research** — [High-Throughput LLM Serving Engine](https://vllm.ai/)
* **NVIDIA TensorRT Documentation** — [Deep Learning Inference Optimization](https://docs.nvidia.com/deeplearning/tensorrt/)

---

## 📁 Planned Toolkit Deliverables (Coming Post-Acceptance)
* `serving-configs/` - Production deployment boilerplate configs for vLLM and Triton.
* `benchmarking/` - Python scripts for estimating LLM model VRAM footprints and GPU memory limits.
