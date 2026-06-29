<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-29
- 运行时间：2026-06-29 21:23:50 UTC
- 运行状态：成功
- 本次总论文数：8
- 精读区：6
- 速读区：2

### 今日简报（AI）
1) 今日共推荐8篇论文，精读6篇，其中两篇聚焦于MoE模型的高效推理与稀疏化优化，评分均达9.0/10。
2) 最值得关注的方向是多LLM系统服务（CrossPool通过KV缓存与权重分离提升冷启动效率）以及免训练的滑动窗口注意力适配方法（NLL-Guided层选择策略）。
3) 建议优先阅读这两篇高分论文，了解如何在不增加训练成本的前提下提升MoE模型的推理速度与内存利用效率。
- 详情：[/202606/29/README](/202606/29/README)

### 精读区论文标签
1. [CrossPool: Efficient Multi-LLM Serving for Cold MoE Models through KV-Cache and Weight Disaggregation](/202606/29/2606.24506v2-crosspool-efficient-multi-llm-serving-for-cold-moe-models-through-kv-cache-and-weight-disaggregation)  
   标签：评分：9.0/10、query:ai-infra
   evidence：针对冷门MoE模型的KV缓存池化与权重解耦
2. [NLL-Guided Full-Attention Layer Selection for Training-Free Sliding-Window Adaptation](/202606/29/2606.27791v1-nll-guided-full-attention-layer-selection-for-training-free-sliding-window-adaptation)  
   标签：评分：9.0/10、query:ai-infra
   evidence：无训练注意力层选择以优化KV缓存使用
3. [SARA: Unlocking Multilingual Knowledge in Mixture-of-Experts via Semantically Anchored Routing Alignment](/202606/29/2606.25821v1-sara-unlocking-multilingual-knowledge-in-mixture-of-experts-via-semantically-anchored-routing-alignment)  
   标签：评分：8.0/10、query:ai-infra
   evidence：混合专家模型路由对齐提升跨语言通信效率
4. [Bifocal Diffusion Language Models: Asymmetric Bidirectional Context for Parallel Generation](/202606/29/2606.27732v1-bifocal-diffusion-language-models-asymmetric-bidirectional-context-for-parallel-generation)  
   标签：评分：8.0/10、query:ai-infra
   evidence：解决扩散LLM中KV缓存不兼容问题，提出不对称双向上下文
5. [End-to-End Dynamic Sparsity for Resource-Adaptive LLM Inference](/202606/29/2606.27743v1-end-to-end-dynamic-sparsity-for-resource-adaptive-llm-inference)  
   标签：评分：8.0/10、query:ai-infra
   evidence：针对动态云基础设施的资源自适应推理
6. [Phase Matters: Characterizing Heterogeneous Vision-Language Inference on a Mobile SoC](/202606/29/2606.27906v1-phase-matters-characterizing-heterogeneous-vision-language-inference-on-a-mobile-soc)  
   标签：评分：8.0/10、query:ai-infra
   evidence：移动SoC上异构视觉语言推理特征化

### 速读区论文标签
1. [Optimizing Teacher-Student Partitioning for Scalable Knowledge Distillation on HPC Systems](/202606/29/2606.27797v1-optimizing-teacher-student-partitioning-for-scalable-knowledge-distillation-on-hpc-systems)  
   标签：评分：6.0/10、query:ai-infra
   evidence：HPC感知的师生分区方法提升知识蒸馏吞吐量
2. [FlexMoE: One-for-All Nested Intra-Expert Pruning for MoE Language Models](/202606/29/2606.27866v1-flexmoe-one-for-all-nested-intra-expert-pruning-for-moe-language-models)  
   标签：评分：6.0/10、query:ai-infra
   evidence：MoE语言模型的嵌套专家内剪枝，降低部署开销


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
