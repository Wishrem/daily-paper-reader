<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-23
- 运行时间：2026-06-23 22:25:52 UTC
- 运行状态：成功
- 本次总论文数：23
- 精读区：12
- 速读区：11

### 今日简报（AI）
今日推荐23篇论文，精读12篇，其中《UltraQuant: 4-bit KV Caching for Context-Heavy Agents》获满分10分。  
最值得关注：4-bit KV缓存优化上下文密集型智能体，以及MoE结构聚合与可微最优传输方法。  
建议优先精读UltraQuant，并关注DAG-MoE和DOT-MoE对MoE架构的创新。
- 详情：[/202606/23/README](/202606/23/README)

### 精读区论文标签
1. [UltraQuant: 4-bit KV Caching for Context-Heavy Agents](/202606/23/2606.20474v1-ultraquant-4-bit-kv-caching-for-context-heavy-agents)  
   标签：评分：10.0/10、query:ai-infra
   evidence：直接针对LLM智能体的4位KV缓存压缩
2. [UltraQuant: 4-bit KV Caching for Context-Heavy Agents](/202606/23/2606.20474v2-ultraquant-4-bit-kv-caching-for-context-heavy-agents)  
   标签：评分：10.0/10、query:ai-infra
   evidence：针对上下文密集型智能体的4比特KV缓存压缩
3. [Keyless Attention: Value-Space Routing and Value-Only Caching for Efficient Transformers](/202606/23/2606.21848v1-keyless-attention-value-space-routing-and-value-only-caching-for-efficient-transformers)  
   标签：评分：10.0/10、query:ai-infra
   evidence：Keyless Attention通过仅值缓存将KV缓存减少50%
4. [Geometry-Aware Online Scheduling for LLM Serving: From Theoretical Bound to System Practice](/202606/23/2606.22327v1-geometry-aware-online-scheduling-for-llm-serving-from-theoretical-bound-to-system-practice)  
   标签：评分：10.0/10、query:ai-infra
   evidence：LLM推理中KV缓存内存管理的几何感知调度
5. [SMEPilot: Characterizing and Optimizing LLM Inference with Scalable Matrix Extensions](/202606/23/2606.16332v1-smepilot-characterizing-and-optimizing-llm-inference-with-scalable-matrix-extensions)  
   标签：评分：9.0/10、query:ai-infra
   evidence：利用SME和CPU异构计算优化LLM推理
6. [Tangram: Hiding GPU Heterogeneity for Efficient LLM Parallelization](/202606/23/2606.16907v1-tangram-hiding-gpu-heterogeneity-for-efficient-llm-parallelization)  
   标签：评分：9.0/10、query:ai-infra
   evidence：隐藏GPU异构性实现大语言模型并行化，支持高效异构混合推理
7. [Grouped Query Experts: Mixture-of-Experts on GQA Self-Attention](/202606/23/2606.20945v1-grouped-query-experts-mixture-of-experts-on-gqa-self-attention)  
   标签：评分：9.0/10、query:ai-infra
   evidence：在分组查询注意力上应用MoE，优化通信与计算
8. [Recency/Frequency Adaptive KV Caching for Large Language Model Serving](/202606/23/2606.21238v1-recencyfrequency-adaptive-kv-caching-for-large-language-model-serving)  
   标签：评分：9.0/10、query:ai-infra
   evidence：自适应KV缓存管理提升命中率和降低延迟
9. [Fast-TurboQuant: A Multiplier-Free Online Vector Quantization Approach](/202606/23/2606.21448v1-fast-turboquant-a-multiplier-free-online-vector-quantization-approach)  
   标签：评分：9.0/10、query:ai-infra
   evidence：面向大语言模型的无乘法器键值缓存量化方法
10. [BatchGen: An Architecture for Scalable and Efficient Batch Inference](/202606/23/2606.21712v1-batchgen-an-architecture-for-scalable-and-efficient-batch-inference)  
   标签：评分：9.0/10、query:ai-infra
   evidence：批推理架构用于AI基础设施加速
11. [ASAP: A Disaggregated and Asynchronous Inference System for MoE Prefill](/202606/23/2606.22541v1-asap-a-disaggregated-and-asynchronous-inference-system-for-moe-prefill)  
   标签：评分：9.0/10、query:ai-infra
   evidence：针对MoE预填充的异步推理系统，减少同步阻塞
12. [SpotAttention: Plug-In Block-Sparse Routing for Pretrained Long-Context Transformers](/202606/23/2606.22874v1-spotattention-plug-in-block-sparse-routing-for-pretrained-long-context-transformers)  
   标签：评分：9.0/10、query:ai-infra
   evidence：通过块稀疏注意力路由降低KV缓存开销

### 速读区论文标签
1. [DAG-MoE: From Simple Mixture to Structural Aggregation in Mixture-of-Experts](/202606/23/2606.01062v1-dag-moe-from-simple-mixture-to-structural-aggregation-in-mixture-of-experts)  
   标签：评分：8.0/10、query:ai-infra
   evidence：解决MoE通信中的路由开销
2. [DOT-MoE: Differentiable Optimal Transport for MoEfication](/202606/23/2606.01666v1-dot-moe-differentiable-optimal-transport-for-moefication)  
   标签：评分：8.0/10、query:ai-infra
   evidence：利用可微最优传输将稠密模型转换为MoE
3. [Fast Transformer Inference on ARM-Based HMPSoCs](/202606/23/2606.02836v1-fast-transformer-inference-on-arm-based-hmpsocs)  
   标签：评分：8.0/10、query:ai-infra
   evidence：在异构ARM SoC上加速Transformer推理
4. [TGV-KV: Text-Grounded KV Eviction for Vision-Language Models](/202606/23/2606.03075v1-tgv-kv-text-grounded-kv-eviction-for-vision-language-models)  
   标签：评分：8.0/10、query:ai-infra
   evidence：面向视觉语言模型的KV缓存驱逐方法
5. [Stepwise Token Selection for Efficient Multimodal Large Language Models](/202606/23/2606.16067v1-stepwise-token-selection-for-efficient-multimodal-large-language-models)  
   标签：评分：7.0/10、query:ai-infra
   evidence：视觉标记剪枝以加速多模态大模型推理
6. [From Tokens to Regions: CUDA-Sensitive Instruction Tuning for GPU Kernel Generation](/202606/23/2606.16231v1-from-tokens-to-regions-cuda-sensitive-instruction-tuning-for-gpu-kernel-generation)  
   标签：评分：7.0/10、query:ai-infra
   evidence：CUDA内核生成以加速AI系统
7. [ADaPT: Token-Level Decoupling for Efficient Large Reasoning Models](/202606/23/2606.19919v1-adapt-token-level-decoupling-for-efficient-large-reasoning-models)  
   标签：评分：7.0/10、query:ai-infra
   evidence：面向大推理模型的token级双过程框架，降低计算成本
8. [Demystifying Numerical Instability in LLM Inference: Achieving Reproducible Inference for Mission-Critical Tasks with HEAL](/202606/23/2606.21023v1-demystifying-numerical-instability-in-llm-inference-achieving-reproducible-inference-for-mission-critical-tasks-with-heal)  
   标签：评分：7.0/10、query:ai-infra
   evidence：解决大模型推理在异构GPU上的输出不一致问题
9. [AIA: A 16nm Multicore SoC for Approximate Inference Acceleration Exploiting Non-normalized Knuth-Yao Sampling and Inter-Core Register Sharing](/202606/23/2606.16148v1-aia-a-16nm-multicore-soc-for-approximate-inference-acceleration-exploiting-non-normalized-knuth-yao-sampling-and-inter-core-register-sharing)  
   标签：评分：6.0/10、query:ai-infra
   evidence：用于近似推理加速的多核SoC
10. [SPRI: SVD-Partitioned Residual Initialization for Data-Constrained MoE Upcycling](/202606/23/2606.16456v1-spri-svd-partitioned-residual-initialization-for-data-constrained-moe-upcycling)  
   标签：评分：6.0/10、query:ai-infra
   evidence：数据受限下基于SVD分区残差的MoE升级初始化
11. [Online LLM Selection via Constrained Bandits with Time-Varying Demand](/202606/23/2606.17489v1-online-llm-selection-via-constrained-bandits-with-time-varying-demand)  
   标签：评分：6.0/10、query:ai-infra
   evidence：在资源约束下为异构边缘-云推理在线选择大语言模型


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
