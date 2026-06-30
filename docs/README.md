<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-30
- 运行时间：2026-06-30 22:08:57 UTC
- 运行状态：成功
- 本次总论文数：11
- 精读区：5
- 速读区：6

### 今日简报（AI）
今日共处理11篇论文，精读5篇、速读6篇，重点聚焦KV Cache优化与模型压缩。

最值得关注的两篇精读《Epiphany-Aware KV Cache Eviction Without the Attention Matrix》与《HARD-KV: Head-Adaptive Regularization for Decoding-time KV Compression》，均评分9.0，深入探讨了无需注意力矩阵的缓存驱逐策略及解码时自适应压缩方法。

建议优先研读这两篇KV Cache优化工作，对大模型推理加速有直接指导意义，后续可关注MoE剪枝与GPU调度方向。
- 详情：[/202606/30/README](/202606/30/README)

### 精读区论文标签
1. [Epiphany-Aware KV Cache Eviction Without the Attention Matrix](/202606/30/2606.26472v2-epiphany-aware-kv-cache-eviction-without-the-attention-matrix)  
   标签：评分：9.0/10、query:ai-infra
   evidence：KV缓存淘汰，无需注意力矩阵的模型内部表示变化得分
2. [HARD-KV: Head-Adaptive Regularization for Decoding-time KV Compression](/202606/30/2606.28831v1-hard-kv-head-adaptive-regularization-for-decoding-time-kv-compression)  
   标签：评分：9.0/10、query:ai-infra
   evidence：解码时KV缓存压缩中的头自适应正则化
3. [DiLaServe: High SLO Attainment Serving for Diffusion Language Models](/202606/30/2606.29094v1-dilaserve-high-slo-attainment-serving-for-diffusion-language-models)  
   标签：评分：9.0/10、query:ai-infra
   evidence：服务于扩散语言模型，涉及近似KV缓存机制
4. [Coverage-Driven KV Cache Eviction for Efficient and Improved Inference of LLM](/202606/30/2606.29563v1-coverage-driven-kv-cache-eviction-for-efficient-and-improved-inference-of-llm)  
   标签：评分：9.0/10、query:ai-infra
   evidence：覆盖度驱动的KV缓存淘汰，用于高效大模型推理
5. [Beyond Uniform Experts: Cost-Aware Expert Execution for Efficient Multi-Device MoE Inference](/202606/30/2606.29982v1-beyond-uniform-experts-cost-aware-expert-execution-for-efficient-multi-device-moe-inference)  
   标签：评分：9.0/10、query:ai-infra
   evidence：多设备MoE推理中的通信优化

### 速读区论文标签
1. [FlexMoE: One-for-All Nested Intra-Expert Pruning for MoE Language Models](/202606/30/2606.27866v1-flexmoe-one-for-all-nested-intra-expert-pruning-for-moe-language-models)  
   标签：评分：7.0/10、query:ai-infra
   evidence：MoE专家内剪枝以提升部署效率
2. [SMART-MIG: A Learning Framework for Scalable and Energy-Efficient GPU Scheduling](/202606/30/2606.29775v1-smart-mig-a-learning-framework-for-scalable-and-energy-efficient-gpu-scheduling)  
   标签：评分：7.0/10、query:ai-infra
   evidence：面向AI基础设施加速的GPU调度
3. [Lossy Compression for Sparse Aggregation](/202606/30/2606.30425v1-lossy-compression-for-sparse-aggregation)  
   标签：评分：7.0/10、query:ai-infra
   evidence：针对稀疏聚合的有损压缩减少分布式学习通信开销
4. [Nautilus: A Verifiable Hierarchical Federated Learning Framework for Vehicular-Edge-Cloud Systems](/202606/30/2606.23017v1-nautilus-a-verifiable-hierarchical-federated-learning-framework-for-vehicular-edge-cloud-systems)  
   标签：评分：6.0/10、query:ai-infra
   evidence：异构车-边-云系统中的可验证分层训练
5. [Nautilus: A Verifiable Hierarchical Federated Learning Framework for Vehicular-Edge-Cloud Systems](/202606/30/2606.23017v2-nautilus-a-verifiable-hierarchical-federated-learning-framework-for-vehicular-edge-cloud-systems)  
   标签：评分：6.0/10、query:ai-infra
   evidence：车-边-云系统中异构资源感知的联邦学习调度
6. [Multi-Block Diffusion Language Models](/202606/30/2606.29215v1-multi-block-diffusion-language-models)  
   标签：评分：6.0/10、query:ai-infra
   evidence：扩散语言模型中的KV缓存与并行解码


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
