### Senior ML Engineer — Systems, Real-Time Risk & AI Security

I build fail-closed production ML systems where sub-150ms latency, extreme class imbalance, and adversarial pressure aren't an afterthought. My work sits at the intersection of **adversarial decision systems** (inline risk scoring, fraud/abuse detection, AI guardrails) and **high-performance inference** (eliminating Python runtime bottlenecks with asynchronous Rust).

#### Engineering Focus

- **Inline Risk, Fraud & AI Security:** Pre-execution interception of anomalous behavior, agent tool-call abuse, prompt injections, and data exfiltration. Designing real-time scoring engines that operate under strict false-positive budgets and asymmetric error costs.
- **High-Performance Inference & Systems:** Re-architecting Python-bound ML and RAG bottlenecks into high-concurrency async Rust runtimes (`Tokio`, `Candle`, `PyO3`), paired with graph optimization (`ONNX Runtime`) and post-training quantization (`AWQ`/`INT8`) to keep inline p95 latency sub-350ms.
- **Adversarial Robustness & Calibration:** Fine-tuning compact encoders and open-weight LLMs (`SFT`, `QLoRA`, hard-negative mining), cost-sensitive threshold calibration (`PR-AUC` / `Precision@Recall`), concept-drift monitoring, and probing model internals to understand *why* classifiers fail under distribution shift.
