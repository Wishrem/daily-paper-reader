<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-26
- 运行时间：2026-06-26 21:32:20 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：6
- 速读区：11

### 今日简报（AI）
今日推荐17篇论文，精读6篇，其中两篇在KV缓存压缩与长推理优化上获得满分评价。最值得关注的是Epiphany-Aware和Information-Aware两类KV缓存管理方法，均达到10分满分。建议优先阅读这两篇满分论文，并结合其他速读论文中的通信高效验证与子空间混合训练思路进行扩展。
- 详情：[/202606/26/README](/202606/26/README)

### 精读区论文标签
1. [Epiphany-Aware KV Cache Eviction Without the Attention Matrix](/202606/26/2606.26472v1-epiphany-aware-kv-cache-eviction-without-the-attention-matrix)  
   标签：评分：10.0/10、query:ai-infra
   evidence：EpiKV方法，无需注意力矩阵进行KV缓存淘汰，直接解决长推理序列中的KV缓存瓶颈
2. [Information-Aware KV Cache Compression for Long Reasoning](/202606/26/2606.26875v1-information-aware-kv-cache-compression-for-long-reasoning)  
   标签：评分：10.0/10、query:ai-infra
   evidence：基于前向影响度量的KV缓存压缩
3. [CrossPool: Efficient Multi-LLM Serving for Cold MoE Models through KV-Cache and Weight Disaggregation](/202606/26/2606.24506v1-crosspool-efficient-multi-llm-serving-for-cold-moe-models-through-kv-cache-and-weight-disaggregation)  
   标签：评分：9.0/10、query:ai-infra
   evidence：针对冷门MoE模型的KV缓存池化与权重分离
4. [Moebius: Serving Mixture-of-Expert Models with Seamless Runtime Parallelism Switch](/202606/26/2606.26607v1-moebius-serving-mixture-of-expert-models-with-seamless-runtime-parallelism-switch)  
   标签：评分：9.0/10、query:ai-infra
   evidence：MoE服务中TP与EP的运行时并行切换
5. [PersistentKV: Page-Aware Decode Scheduling for Long-Context LLM Serving on Commodity GPUs](/202606/26/2606.26666v1-persistentkv-page-aware-decode-scheduling-for-long-context-llm-serving-on-commodity-gpus)  
   标签：评分：9.0/10、query:ai-infra
   evidence：针对长上下文LLM的KV缓存解码调度
6. [A3C3: AI Algorithm and Accelerator Co-design, Co-search, and Co-generation](/202606/26/2606.20869v1-a3c3-ai-algorithm-and-accelerator-co-design-co-search-and-co-generation)  
   标签：评分：8.0/10、query:ai-infra
   evidence：联合优化AI算法和硬件加速器

### 速读区论文标签
1. [Communication-Efficient Verifiable Attention for LLM Inference](/202606/26/2606.16352v1-communication-efficient-verifiable-attention-for-llm-inference)  
   标签：评分：8.0/10、query:ai-infra
   evidence：通过将注意力计算卸载到GPU并减少TEE-GPU通信来实现通信高效的验证性LLM推理
2. [Mixtures of Subspaces for Bandwidth Efficient Context Parallel Training](/202606/26/2606.16384v1-mixtures-of-subspaces-for-bandwidth-efficient-context-parallel-training)  
   标签：评分：8.0/10、query:ai-infra
   evidence：通过子空间混合压缩实现带宽高效的上下文并行训练
3. [daVinci-kernel: Co-Evolving Skill Selection, Summarization, and Utilization via RL for GPU Kernel Optimization](/202606/26/2606.16497v1-davinci-kernel-co-evolving-skill-selection-summarization-and-utilization-via-rl-for-gpu-kernel-optimization)  
   标签：评分：8.0/10、query:ai-infra
   evidence：用强化学习框架优化GPU内核以加速AI基础设施
4. [Prefill/Decode-Aware Evaluation of LLM Inference on Emerging AI Accelerators](/202606/26/2606.17104v1-prefilldecode-aware-evaluation-of-llm-inference-on-emerging-ai-accelerators)  
   标签：评分：8.0/10、query:ai-infra
   evidence：针对LLM推理的Prefill/Decode阶段感知评估，比较GPU和新兴AI加速器
5. [FlowTrain: Flow-Based Decoupled Training for Industrial-Grade Vision-Language Models](/202606/26/2606.23087v1-flowtrain-flow-based-decoupled-training-for-industrial-grade-vision-language-models)  
   标签：评分：7.0/10、query:ai-infra
   evidence：通过统一内存池实现VLM异构模块的解耦训练
6. [Sol Video Inference Engine: Agent-Native Full-Stack Acceleration Framework for Efficient Video Generation](/202606/26/2606.23743v1-sol-video-inference-engine-agent-native-full-stack-acceleration-framework-for-efficient-video-generation)  
   标签：评分：7.0/10、query:ai-infra
   evidence：面向视频生成的端到端推理加速框架
7. [Decentralised AI Training and Inference with BlockTrain](/202606/26/2606.24722v1-decentralised-ai-training-and-inference-with-blocktrain)  
   标签：评分：7.0/10、query:ai-infra
   evidence：去中心化模型分割用于并行训练
8. [Efficient and Trainable Language Model Test-Time Scaling via Local Branch Routing](/202606/26/2606.25354v1-efficient-and-trainable-language-model-test-time-scaling-via-local-branch-routing)  
   标签：评分：7.0/10、query:ai-infra
   evidence：测试时缩放提升推理效率
9. [A3C3: AI Algorithm and Accelerator Co-design, Co-search, and Co-generation](/202606/26/2606.20869v2-a3c3-ai-algorithm-and-accelerator-co-design-co-search-and-co-generation)  
   标签：评分：6.0/10、query:ai-infra
   evidence：AI算法与加速器协同设计，用于基础设施加速
10. [Sol Video Inference Engine: Agent-Native Full-Stack Acceleration Framework for Efficient Video Generation](/202606/26/2606.23743v2-sol-video-inference-engine-agent-native-full-stack-acceleration-framework-for-efficient-video-generation)  
   标签：评分：6.0/10、query:ai-infra
   evidence：面向高效视频生成的端到端加速框架
11. [Power-Flexible AI Data Centers: A New Paradigm for Grid-Responsive Compute](/202606/26/2606.25098v1-power-flexible-ai-data-centers-a-new-paradigm-for-grid-responsive-compute)  
   标签：评分：6.0/10、query:ai-infra
   evidence：提出电力灵活的AI数据中心作为电网响应基础设施，通过负载调度实现效率提升


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
