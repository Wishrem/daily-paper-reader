<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-07-07
- 运行时间：2026-07-07 22:08:44 UTC
- 运行状态：成功
- 本次总论文数：18
- 精读区：7
- 速读区：11

### 今日简报（AI）
今日精选18篇论文，重点精读KV缓存量化与混合扩散语言模型方向。
高分推荐：《GSRQ》实现亚1比特KV缓存量化，《Training Hybrid Block Diffusion》探索部分双向训练新范式。
普通读者可关注Agentic应用的工作流感知服务层（8.0分）及自推测加速推理方法（SPORK，8.0分）。
- 详情：[/202607/07/README](/202607/07/README)

### 精读区论文标签
1. [GSRQ: Gain-Shape Residual Quantization for Sub-1-bit KV Cache](/202607/07/2607.01065v1-gsrq-gain-shape-residual-quantization-for-sub-1-bit-kv-cache)  
   标签：评分：9.0/10、query:ai-infra
   evidence：使用增益-形状K均值实现低于1比特的KV缓存量化
2. [Training Hybrid Block Diffusion Language Models with Partial Bidirectionality](/202607/07/2607.02805v1-training-hybrid-block-diffusion-language-models-with-partial-bidirectionality)  
   标签：评分：9.0/10、query:ai-infra
   evidence：直接解决大语言模型推理中的KV缓存内存瓶颈
3. [ELiTeFormer: An Efficient Transformer for FPGAs](/202607/07/2607.03652v1-eliteformer-an-efficient-transformer-for-fpgas)  
   标签：评分：9.0/10、query:ai-infra
   evidence：LLM的KV缓存压缩与FPGA部署
4. [BrownoutMoE: Structure-Aware Expert Grouping for Efficient and Accurate LLM Web-based Services](/202607/07/2607.04164v1-brownoutmoe-structure-aware-expert-grouping-for-efficient-and-accurate-llm-web-based-services)  
   标签：评分：9.0/10、query:ai-infra
   evidence：MoE模型中的专家分组与通信优化
5. [Nemotron-Labs-3-Puzzle-75B-A9B: Compressing Hybrid MoE LLMs](/202607/07/2607.04371v1-nemotron-labs-3-puzzle-75b-a9b-compressing-hybrid-moe-llms)  
   标签：评分：9.0/10、query:ai-infra
   evidence：MoE大模型压缩加速推理
6. [KVpop -- Key-Value Cache Compression with Predictive Online Pruning](/202607/07/2607.05061v1-kvpop----key-value-cache-compression-with-predictive-online-pruning)  
   标签：评分：9.0/10、query:ai-infra
   evidence：KV缓存预测性在线剪枝压缩
7. [Communication-Aware Placement and Pruning for Efficient Mixture-of-Experts Inference](/202607/07/2607.05116v1-communication-aware-placement-and-pruning-for-efficient-mixture-of-experts-inference)  
   标签：评分：9.0/10、query:ai-infra
   evidence：面向MoE推理的通信感知放置与剪枝

### 速读区论文标签
1. [A Workflow-Aware Serving Layer for Agentic Applications](/202607/07/2607.02942v1-a-workflow-aware-serving-layer-for-agentic-applications)  
   标签：评分：8.0/10、query:ai-infra
   evidence：面向智能体应用的异构后端工作流感知服务层
2. [HyperParallel-Mpipe: A Composable Algebra System for Optimizing MLLM Training over Supernode Clusters](/202607/07/2607.03229v1-hyperparallel-mpipe-a-composable-algebra-system-for-optimizing-mllm-training-over-supernode-clusters)  
   标签：评分：8.0/10、query:ai-infra
   evidence：使用调度代数为多模态大模型训练设计异构并行方案
3. [SPORK: Self-Speculative Forking to Accelerate Agentic LLM Inference](/202607/07/2607.03333v1-spork-self-speculative-forking-to-accelerate-agentic-llm-inference)  
   标签：评分：8.0/10、query:ai-infra
   evidence：无训练投机执行加速智能体LLM推理
4. [PLACEMEM: Toward a Compute-Aware Memory Plane for Lifelong Agents](/202607/07/2607.04089v1-placemem-toward-a-compute-aware-memory-plane-for-lifelong-agents)  
   标签：评分：8.0/10、query:ai-infra
   evidence：面向终身智能体的KV感知内存平面，使用版本化胶囊
5. [CoCoScale: Leveraging Layer-wise Scaling to Unlock the Potential of Online LLM Serving](/202607/07/2607.04181v1-cocoscale-leveraging-layer-wise-scaling-to-unlock-the-potential-of-online-llm-serving)  
   标签：评分：8.0/10、query:ai-infra
   evidence：针对在线LLM服务的层粒度缩放，解决工作负载倾斜和冷启动延迟问题
6. [Embodied.cpp: A Portable Inference Runtime of Embodied AI Models on Heterogeneous Robots](/202607/07/2607.02501v2-embodiedcpp-a-portable-inference-runtime-of-embodied-ai-models-on-heterogeneous-robots)  
   标签：评分：7.0/10、query:ai-infra
   evidence：面向异构机器人的可移植推理运行时，处理异构计算
7. [NKI-Agent: Domain-Specific Fine-Tuning and Agentic Tool Use for Neuron Kernel Generation](/202607/07/2607.04395v1-nki-agent-domain-specific-fine-tuning-and-agentic-tool-use-for-neuron-kernel-generation)  
   标签：评分：7.0/10、query:ai-infra
   evidence：自动生成新兴AI加速器的内核，直接加速AI基础设施
8. [Direct Model State Migration for Elastic Training of Large Language Models](/202607/07/2607.04749v1-direct-model-state-migration-for-elastic-training-of-large-language-models)  
   标签：评分：7.0/10、query:ai-infra
   evidence：弹性混合并行训练的状态迁移
9. [Can Model Merging Improve Aggregation in DiLoCo?](/202607/07/2607.03011v1-can-model-merging-improve-aggregation-in-diloco)  
   标签：评分：6.0/10、query:ai-infra
   evidence：模型合并技术改进分布式学习聚合，减少通信
10. [A Reconfigurable and Representation-Adaptive ISA-Based Architecture for Efficient DNN Acceleration](/202607/07/2607.04475v1-a-reconfigurable-and-representation-adaptive-isa-based-architecture-for-efficient-dnn-acceleration)  
   标签：评分：6.0/10、query:ai-infra
   evidence：基于可重构ISA的高效DNN加速架构
11. [Heaviside Continuity of Rolling Coefficients for Eliminating Epistemic Entropy in Large Language Models](/202607/07/2607.04562v1-heaviside-continuity-of-rolling-coefficients-for-eliminating-epistemic-entropy-in-large-language-models)  
   标签：评分：6.0/10、query:ai-infra
   evidence：使用Heaviside门控的LLM验证优先推理框架


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
