<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-05-25 ~ 2026-06-23
- 运行时间：2026-06-23 04:07:55 UTC
- 运行状态：成功
- 本次总论文数：40
- 精读区：29
- 速读区：11

### 今日简报（AI）
本月精读29篇，聚焦多任务MoE推理加速与长上下文KV缓存压缩两大方向。最值得关注的是任务感知分组的《Task-Aware Grouping》与嵌套路由的《NestedKV》，分别获满分10分和9分。建议后续重点跟进MoE专家复用和异构计算资源适配方案。
- 详情：[/20260525-20260623/README](/20260525-20260623/README)

### 精读区论文标签
1. [Beyond Task-Agnostic: Task-Aware Grouping for Communication-Efficient Multi-Task MoE Inference](/20260525-20260623/2606.01007v1-beyond-task-agnostic-task-aware-grouping-for-communication-efficient-multi-task-moe-inference)  
   标签：评分：10.0/10、query:ai-infra
   evidence：任务感知分组实现通信高效的多任务MoE推理
2. [NestedKV: Nested Memory Routing for Long-Context KV Cache Compression](/20260525-20260623/2605.26678v1-nestedkv-nested-memory-routing-for-long-context-kv-cache-compression)  
   标签：评分：9.0/10、query:ai-infra
   evidence：通过嵌套内存路由实现长上下文LLM的KV缓存压缩
3. [SiDP: Memory-Efficient Data Parallelism for Offline LLM Inference](/20260525-20260623/2605.28095v1-sidp-memory-efficient-data-parallelism-for-offline-llm-inference)  
   标签：评分：9.0/10、query:ai-infra
   evidence：面向离线LLM推理的内存高效数据并行方法释放GPU内存用于KV缓存
4. [How Far Can Disaggregation Go? A Design-Space Exploration of Attention-FFN Disaggregation for Efficient MoE LLM Serving](/20260525-20260623/2605.28302v1-how-far-can-disaggregation-go-a-design-space-exploration-of-attention-ffn-disaggregation-for-efficient-moe-llm-serving)  
   标签：评分：9.0/10、query:ai-infra
   evidence：探索注意力和FFN的异构分解以高效服务MoE
5. [Augmenting Attention with Exponentially Decaying Memory Improves Query-Aware KV Sparsity](/20260525-20260623/2605.28640v1-augmenting-attention-with-exponentially-decaying-memory-improves-query-aware-kv-sparsity)  
   标签：评分：9.0/10、query:ai-infra
   evidence：用指数衰减记忆增强注意力，改进查询感知的键值稀疏性
6. [Moment-KV: Momentum-Based Decode-Time KV Cache Compression for Long Generation](/20260525-20260623/2605.29873v1-moment-kv-momentum-based-decode-time-kv-cache-compression-for-long-generation)  
   标签：评分：9.0/10、query:ai-infra
   evidence：基于动量的解码阶段KV缓存压缩
7. [GRKV: Global Regression for Training-Free KV Cache Compression in Long-Context LLMs](/20260525-20260623/2605.31105v1-grkv-global-regression-for-training-free-kv-cache-compression-in-long-context-llms)  
   标签：评分：9.0/10、query:ai-infra
   evidence：通过全局回归进行KV缓存压缩
8. [WaveFilter: Enhancing the Long-Context Capability of Diffusion LLMs via Wavelet-Guided KV Cache Filtering](/20260525-20260623/2606.00724v1-wavefilter-enhancing-the-long-context-capability-of-diffusion-llms-via-wavelet-guided-kv-cache-filtering)  
   标签：评分：9.0/10、query:ai-infra
   evidence：扩散大语言模型的KV缓存过滤
9. [MomentKV: Closing the Directional Gap in KV Cache Eviction for Long-Context Inference](/20260525-20260623/2606.01563v1-momentkv-closing-the-directional-gap-in-kv-cache-eviction-for-long-context-inference)  
   标签：评分：9.0/10、query:ai-infra
   evidence：长上下文推理中的KV缓存驱逐
10. [KForge: LLM-Driven Cross-Platform Kernel Generation for AI Accelerators](/20260525-20260623/2606.02963v1-kforge-llm-driven-cross-platform-kernel-generation-for-ai-accelerators)  
   标签：评分：9.0/10、query:ai-infra
   evidence：利用LLM为异构AI加速器自动生成跨平台内核，实现异构混合推理
11. [Multi-Segment Attention: Enabling Efficient KV-Cache Management for Faster Large Language Model Serving](/20260525-20260623/2606.02964v1-multi-segment-attention-enabling-efficient-kv-cache-management-for-faster-large-language-model-serving)  
   标签：评分：9.0/10、query:ai-infra
   evidence：计算延迟感知的KV缓存管理与多段注意力
12. [Value-Aware Stochastic KV Cache Eviction for Reasoning Models](/20260525-20260623/2606.03928v1-value-aware-stochastic-kv-cache-eviction-for-reasoning-models)  
   标签：评分：9.0/10、query:ai-infra
   evidence：面向推理模型的值感知随机KV缓存淘汰
13. [LazyAttention: Efficient Retrieval-Augmented Generation with Deferred Positional Encoding](/20260525-20260623/2606.04302v1-lazyattention-efficient-retrieval-augmented-generation-with-deferred-positional-encoding)  
   标签：评分：9.0/10、query:ai-infra
   evidence：延迟位置编码实现位置无关的KV重用
14. [Cartridges at Scale: Training Modular KV Caches over Large Document Collections](/20260525-20260623/2606.04557v1-cartridges-at-scale-training-modular-kv-caches-over-large-document-collections)  
   标签：评分：9.0/10、query:ai-infra
   evidence：训练模块化可重用KV缓存以消除大型文档集合的预填充
15. [BIDENT: Heterogeneous Operator-level Mapping for Efficient Edge Inference](/20260525-20260623/2606.05271v1-bident-heterogeneous-operator-level-mapping-for-efficient-edge-inference)  
   标签：评分：9.0/10、query:ai-infra
   evidence：面向边缘推理的异构算子级映射
16. [Rethinking LoRA Memory Through the Lens of KV Cache Compression](/20260525-20260623/2606.05698v1-rethinking-lora-memory-through-the-lens-of-kv-cache-compression)  
   标签：评分：9.0/10、query:ai-infra
   evidence：KV缓存压缩与LoRA记忆交互研究
17. [QCFuse: Query-Aware Cache Fusion via Compressed View for Efficient RAG Serving](/20260525-20260623/2606.05875v1-qcfuse-query-aware-cache-fusion-via-compressed-view-for-efficient-rag-serving)  
   标签：评分：9.0/10、query:ai-infra
   evidence：面向RAG服务的查询感知KV缓存融合
18. [RedKnot: Efficient Long-Context LLM Serving with Head-Aware KV Reuse and SegPagedAttention](/20260525-20260623/2606.06256v1-redknot-efficient-long-context-llm-serving-with-head-aware-kv-reuse-and-segpagedattention)  
   标签：评分：9.0/10、query:ai-infra
   evidence：面向长上下文LLM服务的头意识KV重用与分段分页注意力
19. [Semantic Cache Distillation: Efficient State Transfer via Reuse and Selective Patching](/20260525-20260623/2606.07684v1-semantic-cache-distillation-efficient-state-transfer-via-reuse-and-selective-patching)  
   标签：评分：9.0/10、query:ai-infra
   evidence：KV缓存传输优化，用于解耦LLM推理
20. [Still: Amortized KV Cache Compaction in a Single Forward Pass](/20260525-20260623/2606.07878v1-still-amortized-kv-cache-compaction-in-a-single-forward-pass)  
   标签：评分：9.0/10、query:ai-infra
   evidence：面向LLM推理加速的KV缓存压缩方法
21. [BUDDY: BUdget-Driven DYnamic Depth Routing for Adaptive Large Language Model Inference](/20260525-20260623/2606.09514v1-buddy-budget-driven-dynamic-depth-routing-for-adaptive-large-language-model-inference)  
   标签：评分：9.0/10、query:ai-infra
   evidence：动态深度路由结合KV缓存重用，用于大模型推理加速
22. [End-to-End Context Compression at Scale](/20260525-20260623/2606.09659v1-end-to-end-context-compression-at-scale)  
   标签：评分：9.0/10、query:ai-infra
   evidence：端到端编码器-解码器上下文压缩，减少长上下文推理中KV缓存内存
23. [IntentKV: Cross-Turn Intent-Aware KV Cache Pruning for Agent Inference](/20260525-20260623/2606.09916v1-intentkv-cross-turn-intent-aware-kv-cache-pruning-for-agent-inference)  
   标签：评分：9.0/10、query:ai-infra
   evidence：跨轮次意图感知的KV缓存剪枝用于智能体推理
24. [PolyKV: Heterogeneous Retention and Allocation for KV Cache Compression](/20260525-20260623/2606.15157v1-polykv-heterogeneous-retention-and-allocation-for-kv-cache-compression)  
   标签：评分：9.0/10、query:ai-infra
   evidence：层间异构KV缓存压缩框架
25. [A Spatio-Temporal Expert Prefetching Framework for Efficient MoE-based LLM Inference](/20260525-20260623/2606.15453v1-a-spatio-temporal-expert-prefetching-framework-for-efficient-moe-based-llm-inference)  
   标签：评分：9.0/10、query:ai-infra
   evidence：专家预取减少MoE推理中的通信开销
26. [SwiftCache: Efficient LLM Serving for Multi-turn Conversations with Heterogeneous KV Cache Sharing](/20260525-20260623/2606.16135v1-swiftcache-efficient-llm-serving-for-multi-turn-conversations-with-heterogeneous-kv-cache-sharing)  
   标签：评分：9.0/10、query:ai-infra
   evidence：面向多轮对话的异构KV缓存共享
27. [AnchorKV: Safety-Aware KV Cache Compression via Soft Penalty with a Refusal Anchor](/20260525-20260623/2606.17872v1-anchorkv-safety-aware-kv-cache-compression-via-soft-penalty-with-a-refusal-anchor)  
   标签：评分：9.0/10、query:ai-infra
   evidence：安全感知的KV缓存压缩，含拒绝锚点
28. [ReMP: Low-Downtime Runtime Model-Parallelism Reconfiguration for LLM Serving](/20260525-20260623/2606.18741v1-remp-low-downtime-runtime-model-parallelism-reconfiguration-for-llm-serving)  
   标签：评分：9.0/10、query:ai-infra
   evidence：LLM服务中的运行时模型并行度重配置
29. [Closing the Calibration Gap in Semantic Caching](/20260525-20260623/2606.19719v1-closing-the-calibration-gap-in-semantic-caching)  
   标签：评分：9.0/10、query:ai-infra
   evidence：语义缓存校准方法，直接改进KV缓存管理

### 速读区论文标签
1. [Bandwidth-Aware LLM Inference on Heterogeneous Many-Core Supercomputers](/20260525-20260623/2605.25655v1-bandwidth-aware-llm-inference-on-heterogeneous-many-core-supercomputers)  
   标签：评分：8.0/10、query:ai-infra
   evidence：面向异构众核处理器的LLM推理硬件软件协同设计
2. [Birkhoff Decompositions and Photonic Interconnects Wait! Don't Forget the Compute!](/20260525-20260623/2605.26845v1-birkhoff-decompositions-and-photonic-interconnects-wait-dont-forget-the-compute)  
   标签：评分：8.0/10、query:ai-infra
   evidence：MoE执行中全到全通信的电路调度
3. [ReMoE: Boosting Expert Reuse through Router Fine-Tuning in Memory-Constrained MoE LLM Inference](/20260525-20260623/2605.27081v1-remoe-boosting-expert-reuse-through-router-fine-tuning-in-memory-constrained-moe-llm-inference)  
   标签：评分：8.0/10、query:ai-infra
   evidence：提升内存受限MoE推理中的专家重用以加速服务
4. [Continual Model Routing in Evolving Model Hubs](/20260525-20260623/2605.28577v1-continual-model-routing-in-evolving-model-hubs)  
   标签：评分：8.0/10、query:ai-infra
   evidence：混合专家模型中的持续路由优化
5. [A general tensor-structured compression scheme for efficient large language models](/20260525-20260623/2605.25344v1-a-general-tensor-structured-compression-scheme-for-efficient-large-language-models)  
   标签：评分：7.0/10、query:ai-infra
   evidence：张量结构压缩方案MixT，降低LLM存储和计算开销
6. [BlockBatch: Multi-Scale Consensus Decoding for Efficient Diffusion Language Model Inference](/20260525-20260623/2605.29233v1-blockbatch-multi-scale-consensus-decoding-for-efficient-diffusion-language-model-inference)  
   标签：评分：7.0/10、query:ai-infra
   evidence：多尺度块解码加速扩散语言模型推理
7. [BlockBatch: Multi-Scale Consensus Decoding for Efficient Diffusion Language Model Inference](/20260525-20260623/2605.29233v2-blockbatch-multi-scale-consensus-decoding-for-efficient-diffusion-language-model-inference)  
   标签：评分：7.0/10、query:ai-infra
   evidence：扩散LLM推理中的KV缓存轨迹分析
8. [Efficient Diffusion LLMs via Temporal-Spatial Parallel Decoding and Confidence Extrapolation](/20260525-20260623/2605.30753v1-efficient-diffusion-llms-via-temporal-spatial-parallel-decoding-and-confidence-extrapolation)  
   标签：评分：7.0/10、query:ai-infra
   evidence：扩散大语言模型推理加速
9. [Addressing Variable Heterogeneity in Distributed Multimodal Training with Entrain](/20260525-20260623/2605.27918v1-addressing-variable-heterogeneity-in-distributed-multimodal-training-with-entrain)  
   标签：评分：6.0/10、query:ai-infra
   evidence：面向分布式多模态训练的静态模型并行
10. [elasticAI.explorer: Towards a Unified End-to-End Framework for Hardware-Aware Neural Architecture Search](/20260525-20260623/2605.30019v2-elasticaiexplorer-towards-a-unified-end-to-end-framework-for-hardware-aware-neural-architecture-search)  
   标签：评分：6.0/10、query:ai-infra
   evidence：硬件感知神经架构搜索框架，可用于AI基础设施加速
11. [Minimizing the Hidden Cost of Scales: Graph-Guided Ultra-Low-Bit Quantization for Large Language Models](/20260525-20260623/2606.05429v1-minimizing-the-hidden-cost-of-scales-graph-guided-ultra-low-bit-quantization-for-large-language-models)  
   标签：评分：6.0/10、query:ai-infra
   evidence：量化加速大语言模型推理


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
