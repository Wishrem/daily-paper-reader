<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-25
- 运行时间：2026-06-25 22:10:55 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：6
- 速读区：11

### 今日简报（AI）
今日共推荐17篇论文，精读6篇、速读11篇，聚焦LLM推理效率与调度优化。  
最值得关注的两个方向：LLM服务几何感知在线调度（10分）与GB级缓存驻留推理（10分），速读推荐移动端NPU扩散LLM推理（8分）及MoE任务路由理论模型（8分）。  
建议优先精读两篇满分论文，深入理解LLM推理的系统级优化方法。
- 详情：[/202606/25/README](/202606/25/README)

### 精读区论文标签
1. [Geometry-Aware Online Scheduling for LLM Serving: From Theoretical Bound to System Practice](/202606/25/2606.22327v2-geometry-aware-online-scheduling-for-llm-serving-from-theoretical-bound-to-system-practice)  
   标签：评分：10.0/10、query:ai-infra
   evidence：KV缓存几何感知在线调度
2. [Cache-Resident LLM Inference in GB-Scale Last-Level Caches](/202606/25/2606.25353v1-cache-resident-llm-inference-in-gb-scale-last-level-caches)  
   标签：评分：10.0/10、query:ai-infra
   evidence：利用GB级末级缓存实现缓存驻留LLM推理，涉及KV缓存管理
3. [FoMoE: Breaking the Full-Replica Barrier with a Federation of MoEs](/202606/25/2606.19025v2-fomoe-breaking-the-full-replica-barrier-with-a-federation-of-moes)  
   标签：评分：9.0/10、query:ai-infra
   evidence：MoE联邦训练减少通信开销
4. [Grouped Query Experts: Mixture-of-Experts on GQA Self-Attention](/202606/25/2606.20945v2-grouped-query-experts-mixture-of-experts-on-gqa-self-attention)  
   标签：评分：9.0/10、query:ai-infra
   evidence：在分组查询注意力上应用专家混合以保持KV缓存优势
5. [Task-Aware Structured Memory for Dynamic Multi-modal In-Context Learning](/202606/25/2606.11853v1-task-aware-structured-memory-for-dynamic-multi-modal-in-context-learning)  
   标签：评分：8.0/10、query:ai-infra
   evidence：多模态LLM的KV缓存压缩
6. [Geometric and Stochastic Analysis of Discontinuities in Sparse Mixture-of-Experts](/202606/25/2606.19036v1-geometric-and-stochastic-analysis-of-discontinuities-in-sparse-mixture-of-experts)  
   标签：评分：8.0/10、query:ai-infra
   evidence：稀疏MoE不连续性的几何分析，与路由和通信优化相关

### 速读区论文标签
1. [Efficient On-Device Diffusion LLM Inference with Mobile NPU](/202606/25/2606.13740v1-efficient-on-device-diffusion-llm-inference-with-mobile-npu)  
   标签：评分：8.0/10、query:ai-infra
   evidence：利用移动NPU加速端侧扩散LLM推理
2. [A theoretical model for task routing in mixture-of-expert transformers](/202606/25/2606.14398v1-a-theoretical-model-for-task-routing-in-mixture-of-expert-transformers)  
   标签：评分：8.0/10、query:ai-infra
   evidence：混合专家模型中的任务路由理论模型，直接关联MoE通信优化
3. [A theoretical model for task routing in mixture-of-expert transformers](/202606/25/2606.14398v2-a-theoretical-model-for-task-routing-in-mixture-of-expert-transformers)  
   标签：评分：8.0/10、query:ai-infra
   evidence：MoE变压器中任务路由的理论模型
4. [MoECa: Aligning Feature Reuse with Expert Decomposition in Diffusion Transformers](/202606/25/2606.15615v1-moeca-aligning-feature-reuse-with-expert-decomposition-in-diffusion-transformers)  
   标签：评分：8.0/10、query:ai-infra
   evidence：针对扩散Transformer中混合专家模型的细粒度缓存，通过专家分支特征重用加速推理
5. [Complementary Attention Head Pruning for Efficient Transformers](/202606/25/2606.19150v1-complementary-attention-head-pruning-for-efficient-transformers)  
   标签：评分：7.0/10、query:ai-infra
   evidence：注意力头剪枝提升Transformer推理效率
6. [Learning What Not to Forget: Long-Horizon Agent Memory from a Few Kilobytes of Learning](/202606/25/2606.20954v1-learning-what-not-to-forget-long-horizon-agent-memory-from-a-few-kilobytes-of-learning)  
   标签：评分：7.0/10、query:ai-infra
   evidence：学习长期代理记忆中的相关性驱逐策略，可迁移至KV缓存驱逐
7. [SwarmX: Agentic Scheduling for Low-Latency Agentic Systems](/202606/25/2606.21401v1-swarmx-agentic-scheduling-for-low-latency-agentic-systems)  
   标签：评分：7.0/10、query:ai-infra
   evidence：AI智能体系统的低延迟服务调度
8. [Load Testing for Machine Learning Model Serving Systems at Scale](/202606/25/2606.22013v1-load-testing-for-machine-learning-model-serving-systems-at-scale)  
   标签：评分：7.0/10、query:ai-infra
   evidence：ML服务系统容量规划的负载测试框架
9. [Essential Subspace Merging for Multi-Task Learning](/202606/25/2606.19164v1-essential-subspace-merging-for-multi-task-learning)  
   标签：评分：6.0/10、query:ai-infra
   evidence：通过本质子空间分解减少模型合并时的任务干扰
10. [AdaMem: Learning What to Remember for Personalized Long-Horizon LLM Agents](/202606/25/2606.21144v1-adamem-learning-what-to-remember-for-personalized-long-horizon-llm-agents)  
   标签：评分：6.0/10、query:ai-infra
   evidence：通过学习选择性记忆减少LLM代理的推理成本
11. [Agent-Assisted Side-Channel Attacks on Non-Prefix KV Cache in RAG](/202606/25/2606.21842v1-agent-assisted-side-channel-attacks-on-non-prefix-kv-cache-in-rag)  
   标签：评分：6.0/10、query:ai-infra
   evidence：非前缀KV缓存侧信道攻击


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
