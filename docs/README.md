<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-07-03
- 运行时间：2026-07-03 21:35:17 UTC
- 运行状态：成功
- 本次总论文数：10
- 精读区：4
- 速读区：6

### 今日简报（AI）
今日阅读10篇论文，精读2篇高分LLM推理加速工作（HYPIC混合注意力缓存、Lynx渐进式量化KV传输），速读3篇涉及多智能体推理、视频训练与MoE剪枝。

最值得精读的是《HYPIC》与《Lynx》，它们分别从位置无关缓存和量化角度突破长上下文LLM服务的性能瓶颈。

建议普通读者关注混合注意力架构和KV缓存量化如何降低推理延迟，这是当前大模型落地实际场景的关键技术方向。
- 详情：[/202607/03/README](/202607/03/README)

### 精读区论文标签
1. [HYPIC: Accelerating Hybrid-Attention LLM Serving with Position-Independent Caching](/202607/03/2607.01299v1-hypic-accelerating-hybrid-attention-llm-serving-with-position-independent-caching)  
   标签：评分：9.0/10、query:ai-infra
   evidence：混合注意力LLM的位置无关缓存，直接加速KV缓存重用
2. [Lynx: Progressive Speculative Quantization for accelerating KV Transfer in Long-Context Inference](/202607/03/2607.01831v1-lynx-progressive-speculative-quantization-for-accelerating-kv-transfer-in-long-context-inference)  
   标签：评分：9.0/10、query:ai-infra
   evidence：渐进推测量化加速KV传输
3. [Mixture-of-Parallelisms: Towards Memory-Efficient Training Stack for Mixture-of-Experts Models](/202607/03/2607.01844v1-mixture-of-parallelisms-towards-memory-efficient-training-stack-for-mixture-of-experts-models)  
   标签：评分：9.0/10、query:ai-infra
   evidence：面向MoE模型的内存高效训练栈，结合并行和通信优化
4. [InduceKV: Fixed-Footprint Continual Adaptation of Multimodal LLMs via Inducing KV Memories](/202607/03/2607.02010v1-inducekv-fixed-footprint-continual-adaptation-of-multimodal-llms-via-inducing-kv-memories)  
   标签：评分：9.0/10、query:ai-infra
   evidence：通过诱导KV记忆实现固定占用下的多模态LLM持续适应

### 速读区论文标签
1. [Cache Merging as a Convergent Replicated State for Multi-Agent Latent Reasoning](/202607/03/2607.01308v1-cache-merging-as-a-convergent-replicated-state-for-multi-agent-latent-reasoning)  
   标签：评分：7.0/10、query:ai-infra
   evidence：用于多agent推理的KV缓存合并机制
2. [Arachne: Orchestrating Cascades for Efficient Text-to-Video Model Training](/202607/03/2607.01701v1-arachne-orchestrating-cascades-for-efficient-text-to-video-model-training)  
   标签：评分：7.0/10、query:ai-infra
   evidence：文本到视频模型训练中的并行优化
3. [Generic Expert Coverage for Pruning SparseMixture-of-Experts Language Models](/202607/03/2607.01710v1-generic-expert-coverage-for-pruning-sparsemixture-of-experts-language-models)  
   标签：评分：7.0/10、query:ai-infra
   evidence：使用通用语料库的覆盖感知MoE专家剪枝
4. [TF-MoE: Time-Frequency Mixture-of-Experts for Efficient Speech Separation](/202607/03/2606.29575v1-tf-moe-time-frequency-mixture-of-experts-for-efficient-speech-separation)  
   标签：评分：6.0/10、query:ai-infra
   evidence：混合专家模型在语音分离中的高效推理
5. [Hawk: Harnessing Hardware-Aware Knowledge for High-Performance NPU Kernel Generation](/202607/03/2607.01590v1-hawk-harnessing-hardware-aware-knowledge-for-high-performance-npu-kernel-generation)  
   标签：评分：6.0/10、query:ai-infra
   evidence：面向NPU的硬件感知内核生成，加速AI基础设施
6. [Embodied.cpp: A Portable Inference Runtime of Embodied AI Models on Heterogeneous Robots](/202607/03/2607.02501v1-embodiedcpp-a-portable-inference-runtime-of-embodied-ai-models-on-heterogeneous-robots)  
   标签：评分：6.0/10、query:ai-infra
   evidence：异构机器人上的便携推理运行时


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
