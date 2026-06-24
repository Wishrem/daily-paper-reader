<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-24
- 运行时间：2026-06-24 22:04:51 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：6
- 速读区：11

### 今日简报（AI）
今日推荐17篇论文，精读聚焦LLM在NPU系统的延迟预测与尾延迟感知调度，速读覆盖异构边缘部署、跨层值混合及MoE量化对齐。  
最值得关注的方向是LLM推理性能优化（NPU延迟建模与调度策略），以及边缘/雾环境下的高效服务方法。  
建议深入阅读两篇精读论文，并跟进异构边缘计算与模型量化融合的实践。
- 详情：[/202606/24/README](/202606/24/README)

### 精读区论文标签
1. [Latency Prediction for LLM Inference on NPU Systems](/202606/24/2606.18042v2-latency-prediction-for-llm-inference-on-npu-systems)  
   标签：评分：9.0/10、query:ai-infra
   evidence：面向NPU系统的LLM推理延迟预测，支持部署优化
2. [Beyond Prediction: Tail-Aware Scheduling for LLM Inference](/202606/24/2606.18431v1-beyond-prediction-tail-aware-scheduling-for-llm-inference)  
   标签：评分：9.0/10、query:ai-infra
   evidence：缓存感知抢断与KV缓存协同优化的调度框架
3. [Forget Without Compromise: Nexus Sampling for Streaming KV-Cache Eviction Under Fixed Budgets](/202606/24/2606.23961v1-forget-without-compromise-nexus-sampling-for-streaming-kv-cache-eviction-under-fixed-budgets)  
   标签：评分：9.0/10、query:ai-infra
   evidence：流式KV缓存淘汰方法
4. [CompressKV: Semantic-Retrieval-Guided KV-Cache Compression for Resource-Efficient Long-Context LLM Inference](/202606/24/2606.24467v1-compresskv-semantic-retrieval-guided-kv-cache-compression-for-resource-efficient-long-context-llm-inference)  
   标签：评分：9.0/10、query:ai-infra
   evidence：面向长上下文LLM推理的KV缓存压缩
5. [Demystifying Pipeline Parallelism: First Theory for PipeDream](/202606/24/2606.03498v1-demystifying-pipeline-parallelism-first-theory-for-pipedream)  
   标签：评分：8.0/10、query:ai-infra
   evidence：PipeDream流水线并行的首个理论分析
6. [MIVE: A Minimalist Integer Vector Engine for Softmax LayerNorm and RMSNorm Acceleration](/202606/24/2606.17781v1-mive-a-minimalist-integer-vector-engine-for-softmax-layernorm-and-rmsnorm-acceleration)  
   标签：评分：8.0/10、query:ai-infra
   evidence：针对LLM归一化操作的专用硬件加速引擎

### 速读区论文标签
1. [E2LLM: Towards Efficient LLM Serving in Heterogeneous Edge/Fog Environments](/202606/24/2606.03770v1-e2llm-towards-efficient-llm-serving-in-heterogeneous-edgefog-environments)  
   标签：评分：8.0/10、query:ai-infra
   evidence：在异构边缘/雾环境中高效部署LLM
2. [Depth-Attention: Cross-Layer Value Mixing for Language Models](/202606/24/2606.05014v1-depth-attention-cross-layer-value-mixing-for-language-models)  
   标签：评分：8.0/10、query:ai-infra
   evidence：通过跨层值混合改进注意力机制，涉及KV缓存重用
3. [Value-and-Structure Alignment for Routing-Consistent Quantization of Mixture-of-Experts Models](/202606/24/2606.05688v1-value-and-structure-alignment-for-routing-consistent-quantization-of-mixture-of-experts-models)  
   标签：评分：8.0/10、query:ai-infra
   evidence：面向MoE推理加速的路由一致性量化
4. [WhiFlash: Accelerating Speculative Decoding with Token-Level Cross-Paradigm Routing](/202606/24/2606.07710v1-whiflash-accelerating-speculative-decoding-with-token-level-cross-paradigm-routing)  
   标签：评分：8.0/10、query:ai-infra
   evidence：令牌级跨范式路由用于投机解码加速
5. [Towards Scalable Customization and Deployment of Multi-Agent Systems for Enterprise Applications](/202606/24/2606.18502v1-towards-scalable-customization-and-deployment-of-multi-agent-systems-for-enterprise-applications)  
   标签：评分：7.0/10、query:ai-infra
   evidence：基于推测解码的LLM服务推理优化
6. [Closing the Calibration Gap in Semantic Caching](/202606/24/2606.19719v2-closing-the-calibration-gap-in-semantic-caching)  
   标签：评分：7.0/10、query:ai-infra
   evidence：面向LLM推理的语义缓存，降低推理成本
7. [Breaking chains with trees: Deep learning with $\mathcal{O}(\log N)$ parallel time complexity](/202606/24/2606.21497v1-breaking-chains-with-trees-deep-learning-with-mathcalolog-n-parallel-time-complexity)  
   标签：评分：7.0/10、query:ai-infra
   evidence：层次块局部学习减少锁定和通信开销以支持并行训练
8. [StickyInvoc: Rethinking Task Models for High-throughput Workflows in the LLM Era](/202606/24/2606.22175v1-stickyinvoc-rethinking-task-models-for-high-throughput-workflows-in-the-llm-era)  
   标签：评分：7.0/10、query:ai-infra
   evidence：通过跨任务复用计算状态降低LLM推理开销
9. [ARIADNE: Agnostic Routing for Inference-time Adapter DyNamic sElection](/202606/24/2606.19079v1-ariadne-agnostic-routing-for-inference-time-adapter-dynamic-selection)  
   标签：评分：6.0/10、query:ai-infra
   evidence：推理时动态适配器路由加速
10. [Mix-QVLA: Task-Evidence-Aware Mixed-Precision Quantization of Vision-Language-Action Models](/202606/24/2606.19565v1-mix-qvla-task-evidence-aware-mixed-precision-quantization-of-vision-language-action-models)  
   标签：评分：6.0/10、query:ai-infra
   evidence：混合精度量化用于推理加速
11. [DPIFrame: A Dual-Level Parallelism Acceleration Framework for CTR Model Inference](/202606/24/2606.21101v1-dpiframe-a-dual-level-parallelism-acceleration-framework-for-ctr-model-inference)  
   标签：评分：6.0/10、query:ai-infra
   evidence：面向CTR模型推理的双层级并行加速框架


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
