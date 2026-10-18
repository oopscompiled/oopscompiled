## ML Engineer

I build production ML and AI security systems where latency and reliability aren't an afterthought. My work sits at the intersection of **model internals** (fine-tuning, adversarial robustness, mechanistic interpretability) and **systems engineering** (eliminating Python bottlenecks with asynchronous Rust runtimes).

---

#### Engineering Focus
* **AI Security & Guardrails:** Pre-execution interception of prompt injections, tool-call abuse, and data exfiltration across multi-step agent trajectories under strict false-positive budgets (`≤0.8% FPR` at `97% recall`).
* **Low-Latency Inference:** Porting latency-critical RAG and guardrail pipelines to async Rust (`Candle`, `Tokio`, `PyO3`), graph optimization (`ONNX Runtime`), and post-training quantization to keep p95 latency sub-150ms.
* **Adversarial & Mechanistic Evaluation:** Fine-tuning open-weight LLMs and compact encoders (`SFT`, `QLoRA`, hard-negative mining), cost-sensitive threshold calibration, and probing model activations to understand *why* guardrails fail.
