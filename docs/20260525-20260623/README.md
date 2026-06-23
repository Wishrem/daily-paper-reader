# 日报 · 2026-05-25 ~ 2026-06-23

- 生成时间：2026-06-23 04:07:55 UTC
- 当次推荐总数：40
- 精读区：29
- 速读区：11

## 今日简报（AI）
本期日报精读40篇论文，聚焦MoE推理优化与KV缓存压缩两大前沿。推荐关注《任务感知分组MoE推理》与《长上下文KV缓存压缩》两篇高分工作。建议读者优先精读这些论文，把握通信高效推理与显存优化的核心思路。

## 精读区
1. [Beyond Task-Agnostic: Task-Aware Grouping for Communication-Efficient Multi-Task MoE Inference](/20260525-20260623/2606.01007v1-beyond-task-agnostic-task-aware-grouping-for-communication-efficient-multi-task-moe-inference) （10.0/10）
2. [NestedKV: Nested Memory Routing for Long-Context KV Cache Compression](/20260525-20260623/2605.26678v1-nestedkv-nested-memory-routing-for-long-context-kv-cache-compression) （9.0/10）
3. [SiDP: Memory-Efficient Data Parallelism for Offline LLM Inference](/20260525-20260623/2605.28095v1-sidp-memory-efficient-data-parallelism-for-offline-llm-inference) （9.0/10）
4. [How Far Can Disaggregation Go? A Design-Space Exploration of Attention-FFN Disaggregation for Efficient MoE LLM Serving](/20260525-20260623/2605.28302v1-how-far-can-disaggregation-go-a-design-space-exploration-of-attention-ffn-disaggregation-for-efficient-moe-llm-serving) （9.0/10）
5. [Augmenting Attention with Exponentially Decaying Memory Improves Query-Aware KV Sparsity](/20260525-20260623/2605.28640v1-augmenting-attention-with-exponentially-decaying-memory-improves-query-aware-kv-sparsity) （9.0/10）
6. [Moment-KV: Momentum-Based Decode-Time KV Cache Compression for Long Generation](/20260525-20260623/2605.29873v1-moment-kv-momentum-based-decode-time-kv-cache-compression-for-long-generation) （9.0/10）
7. [GRKV: Global Regression for Training-Free KV Cache Compression in Long-Context LLMs](/20260525-20260623/2605.31105v1-grkv-global-regression-for-training-free-kv-cache-compression-in-long-context-llms) （9.0/10）
8. [WaveFilter: Enhancing the Long-Context Capability of Diffusion LLMs via Wavelet-Guided KV Cache Filtering](/20260525-20260623/2606.00724v1-wavefilter-enhancing-the-long-context-capability-of-diffusion-llms-via-wavelet-guided-kv-cache-filtering) （9.0/10）
9. [MomentKV: Closing the Directional Gap in KV Cache Eviction for Long-Context Inference](/20260525-20260623/2606.01563v1-momentkv-closing-the-directional-gap-in-kv-cache-eviction-for-long-context-inference) （9.0/10）
10. [KForge: LLM-Driven Cross-Platform Kernel Generation for AI Accelerators](/20260525-20260623/2606.02963v1-kforge-llm-driven-cross-platform-kernel-generation-for-ai-accelerators) （9.0/10）
11. [Multi-Segment Attention: Enabling Efficient KV-Cache Management for Faster Large Language Model Serving](/20260525-20260623/2606.02964v1-multi-segment-attention-enabling-efficient-kv-cache-management-for-faster-large-language-model-serving) （9.0/10）
12. [Value-Aware Stochastic KV Cache Eviction for Reasoning Models](/20260525-20260623/2606.03928v1-value-aware-stochastic-kv-cache-eviction-for-reasoning-models) （9.0/10）
13. [LazyAttention: Efficient Retrieval-Augmented Generation with Deferred Positional Encoding](/20260525-20260623/2606.04302v1-lazyattention-efficient-retrieval-augmented-generation-with-deferred-positional-encoding) （9.0/10）
14. [Cartridges at Scale: Training Modular KV Caches over Large Document Collections](/20260525-20260623/2606.04557v1-cartridges-at-scale-training-modular-kv-caches-over-large-document-collections) （9.0/10）
15. [BIDENT: Heterogeneous Operator-level Mapping for Efficient Edge Inference](/20260525-20260623/2606.05271v1-bident-heterogeneous-operator-level-mapping-for-efficient-edge-inference) （9.0/10）
16. [Rethinking LoRA Memory Through the Lens of KV Cache Compression](/20260525-20260623/2606.05698v1-rethinking-lora-memory-through-the-lens-of-kv-cache-compression) （9.0/10）
17. [QCFuse: Query-Aware Cache Fusion via Compressed View for Efficient RAG Serving](/20260525-20260623/2606.05875v1-qcfuse-query-aware-cache-fusion-via-compressed-view-for-efficient-rag-serving) （9.0/10）
18. [RedKnot: Efficient Long-Context LLM Serving with Head-Aware KV Reuse and SegPagedAttention](/20260525-20260623/2606.06256v1-redknot-efficient-long-context-llm-serving-with-head-aware-kv-reuse-and-segpagedattention) （9.0/10）
19. [Semantic Cache Distillation: Efficient State Transfer via Reuse and Selective Patching](/20260525-20260623/2606.07684v1-semantic-cache-distillation-efficient-state-transfer-via-reuse-and-selective-patching) （9.0/10）
20. [Still: Amortized KV Cache Compaction in a Single Forward Pass](/20260525-20260623/2606.07878v1-still-amortized-kv-cache-compaction-in-a-single-forward-pass) （9.0/10）
21. [BUDDY: BUdget-Driven DYnamic Depth Routing for Adaptive Large Language Model Inference](/20260525-20260623/2606.09514v1-buddy-budget-driven-dynamic-depth-routing-for-adaptive-large-language-model-inference) （9.0/10）
22. [End-to-End Context Compression at Scale](/20260525-20260623/2606.09659v1-end-to-end-context-compression-at-scale) （9.0/10）
23. [IntentKV: Cross-Turn Intent-Aware KV Cache Pruning for Agent Inference](/20260525-20260623/2606.09916v1-intentkv-cross-turn-intent-aware-kv-cache-pruning-for-agent-inference) （9.0/10）
24. [PolyKV: Heterogeneous Retention and Allocation for KV Cache Compression](/20260525-20260623/2606.15157v1-polykv-heterogeneous-retention-and-allocation-for-kv-cache-compression) （9.0/10）
25. [A Spatio-Temporal Expert Prefetching Framework for Efficient MoE-based LLM Inference](/20260525-20260623/2606.15453v1-a-spatio-temporal-expert-prefetching-framework-for-efficient-moe-based-llm-inference) （9.0/10）
26. [SwiftCache: Efficient LLM Serving for Multi-turn Conversations with Heterogeneous KV Cache Sharing](/20260525-20260623/2606.16135v1-swiftcache-efficient-llm-serving-for-multi-turn-conversations-with-heterogeneous-kv-cache-sharing) （9.0/10）
27. [AnchorKV: Safety-Aware KV Cache Compression via Soft Penalty with a Refusal Anchor](/20260525-20260623/2606.17872v1-anchorkv-safety-aware-kv-cache-compression-via-soft-penalty-with-a-refusal-anchor) （9.0/10）
28. [ReMP: Low-Downtime Runtime Model-Parallelism Reconfiguration for LLM Serving](/20260525-20260623/2606.18741v1-remp-low-downtime-runtime-model-parallelism-reconfiguration-for-llm-serving) （9.0/10）
29. [Closing the Calibration Gap in Semantic Caching](/20260525-20260623/2606.19719v1-closing-the-calibration-gap-in-semantic-caching) （9.0/10）

## 速读区
1. [Bandwidth-Aware LLM Inference on Heterogeneous Many-Core Supercomputers](/20260525-20260623/2605.25655v1-bandwidth-aware-llm-inference-on-heterogeneous-many-core-supercomputers) （8.0/10）
2. [Birkhoff Decompositions and Photonic Interconnects Wait! Don't Forget the Compute!](/20260525-20260623/2605.26845v1-birkhoff-decompositions-and-photonic-interconnects-wait-dont-forget-the-compute) （8.0/10）
3. [ReMoE: Boosting Expert Reuse through Router Fine-Tuning in Memory-Constrained MoE LLM Inference](/20260525-20260623/2605.27081v1-remoe-boosting-expert-reuse-through-router-fine-tuning-in-memory-constrained-moe-llm-inference) （8.0/10）
4. [Continual Model Routing in Evolving Model Hubs](/20260525-20260623/2605.28577v1-continual-model-routing-in-evolving-model-hubs) （8.0/10）
5. [A general tensor-structured compression scheme for efficient large language models](/20260525-20260623/2605.25344v1-a-general-tensor-structured-compression-scheme-for-efficient-large-language-models) （7.0/10）
6. [BlockBatch: Multi-Scale Consensus Decoding for Efficient Diffusion Language Model Inference](/20260525-20260623/2605.29233v1-blockbatch-multi-scale-consensus-decoding-for-efficient-diffusion-language-model-inference) （7.0/10）
7. [BlockBatch: Multi-Scale Consensus Decoding for Efficient Diffusion Language Model Inference](/20260525-20260623/2605.29233v2-blockbatch-multi-scale-consensus-decoding-for-efficient-diffusion-language-model-inference) （7.0/10）
8. [Efficient Diffusion LLMs via Temporal-Spatial Parallel Decoding and Confidence Extrapolation](/20260525-20260623/2605.30753v1-efficient-diffusion-llms-via-temporal-spatial-parallel-decoding-and-confidence-extrapolation) （7.0/10）
9. [Addressing Variable Heterogeneity in Distributed Multimodal Training with Entrain](/20260525-20260623/2605.27918v1-addressing-variable-heterogeneity-in-distributed-multimodal-training-with-entrain) （6.0/10）
10. [elasticAI.explorer: Towards a Unified End-to-End Framework for Hardware-Aware Neural Architecture Search](/20260525-20260623/2605.30019v2-elasticaiexplorer-towards-a-unified-end-to-end-framework-for-hardware-aware-neural-architecture-search) （6.0/10）
11. [Minimizing the Hidden Cost of Scales: Graph-Guided Ultra-Low-Bit Quantization for Large Language Models](/20260525-20260623/2606.05429v1-minimizing-the-hidden-cost-of-scales-graph-guided-ultra-low-bit-quantization-for-large-language-models) （6.0/10）

---
使用键盘方向键可在日报/论文之间快速切换。
