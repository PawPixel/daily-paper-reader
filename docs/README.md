<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-22
- 运行时间：2026-06-22 22:19:06 UTC
- 运行状态：成功
- 本次总论文数：15
- 精读区：6
- 速读区：9

### 今日简报（AI）
今日聚焦LLM推理中的策略蒸馏与自蒸馏稳定性，精读两篇高分论文分别提出有界幂变换和路径条件化方法。  
最值得关注方向：策略蒸馏的稳定化技术（PowerOPD）与token级信用定位（Localizing Credit），速读中的梯度视角和熵稳定性补充了理论支撑。  
建议下一步重点对比精读两文的实验设置，并参考速读中的优势重加权方法，以提升推理模型训练鲁棒性。
- 详情：[/202606/22/README](/202606/22/README)

### 精读区论文标签
1. [PowerOPD: Stabilizing On-Policy Distillation with Bounded Power Transformation](/202606/22/2606.17199v1-poweropd-stabilizing-on-policy-distillation-with-bounded-power-transformation)  
   标签：评分：10.0/10、query:on-policy
   evidence：通过有界幂变换稳定LLM的在策略蒸馏
2. [Localizing Credit at the Divergence: Path-Conditioned Self-Distillation for LLM Reasoning](/202606/22/2606.15576v1-localizing-credit-at-the-divergence-path-conditioned-self-distillation-for-llm-reasoning)  
   标签：评分：9.0/10、query:on-policy
   evidence：面向LLM推理的在策略自蒸馏
3. [On-Policy Distillation with Curriculum Turn-level Guidance for Multi-turn Agents](/202606/22/2606.15912v1-on-policy-distillation-with-curriculum-turn-level-guidance-for-multi-turn-agents)  
   标签：评分：9.0/10、query:on-policy
   evidence：基于课程指导的多轮智能体在策略蒸馏
4. [OmniOPSD: Rationale-Privileged On-Policy Self-Distillation for Affective Computing](/202606/22/2606.15920v1-omniopsd-rationale-privileged-on-policy-self-distillation-for-affective-computing)  
   标签：评分：9.0/10、query:on-policy
   evidence：在策略自我蒸馏用于情感计算中的多模态大语言模型
5. [Rethinking Reward Supervision: Rubric-Conditioned Self-Distillation](/202606/22/2606.19327v1-rethinking-reward-supervision-rubric-conditioned-self-distillation)  
   标签：评分：9.0/10、query:llm-papers
   evidence：基于评分标准的在策略自蒸馏用于LLM推理
6. [VIMPO: Value-Implicit Policy Optimization for LLMs](/202606/22/2606.20008v1-vimpo-value-implicit-policy-optimization-for-llms)  
   标签：评分：9.0/10、query:llm-papers
   evidence：通过无评论家策略优化改进LLM推理

### 速读区论文标签
1. [A Gradient Perspective on RLVR Stability and Winner Advantage Policy Optimization](/202606/22/2606.16154v1-a-gradient-perspective-on-rlvr-stability-and-winner-advantage-policy-optimization)  
   标签：评分：8.0/10、query:llm-papers
   evidence：RLVR稳定性分析与面向LLM推理的胜者优势策略优化
2. [STARE: Surprisal-Guided Token-Level Advantage Reweighting for Policy Entropy Stability](/202606/22/2606.19236v1-stare-surprisal-guided-token-level-advantage-reweighting-for-policy-entropy-stability)  
   标签：评分：8.0/10、query:llm-papers
   evidence：改善GRPO的熵稳定性以增强LLM推理
3. [Beyond Entropy: Learning from Token-Level Distributional Deviations for LLM Reasoning](/202606/22/2606.19771v1-beyond-entropy-learning-from-token-level-distributional-deviations-for-llm-reasoning)  
   标签：评分：8.0/10、query:llm-papers
   evidence：利用token级分布偏差改进LLM推理
4. [A First-Principles Derivation of LLM Policy Optimization: From Expected Reward to GRPO and Its Structural Extensions](/202606/22/2606.16733v1-a-first-principles-derivation-of-llm-policy-optimization-from-expected-reward-to-grpo-and-its-structural-extensions)  
   标签：评分：7.0/10、query:llm-papers
   evidence：从第一性原理全面综述LLM策略优化方法
5. [GD$^2$PO: Mitigating Multi-Reward Conflicts via Group-Dynamic reward-Decoupled Policy Optimization](/202606/22/2606.16771v1-gd2po-mitigating-multi-reward-conflicts-via-group-dynamic-reward-decoupled-policy-optimization)  
   标签：评分：7.0/10、query:llm-papers
   evidence：缓解LLM后训练RL中的多奖励冲突
6. [When in Doubt, Plan It Out: Committed Small Language Model Deliberation for Reactive Reinforcement Learning](/202606/22/2606.16995v1-when-in-doubt-plan-it-out-committed-small-language-model-deliberation-for-reactive-reinforcement-learning)  
   标签：评分：7.0/10、query:llm-papers
   evidence：结合小语言模型的混合强化学习架构提升推理和适应性
7. [Learning from Your Own Mistakes: Constructing Learnable Micro-Reflective Trajectories for Self-Distillation](/202606/22/2606.18844v1-learning-from-your-own-mistakes-constructing-learnable-micro-reflective-trajectories-for-self-distillation)  
   标签：评分：7.0/10、query:llm-papers
   evidence：通过轨迹增强的自我蒸馏提升LLM推理
8. [Skill-Guided Continuation Distillation for GUI Agents](/202606/22/2606.18890v1-skill-guided-continuation-distillation-for-gui-agents)  
   标签：评分：7.0/10、query:on-policy
   evidence：技能引导的延续蒸馏应对策略偏移
9. [Learning from Own Solutions: Self-Conditioned Credit Assignment for Reinforcement Learning with Verifiable Rewards](/202606/22/2606.18810v1-learning-from-own-solutions-self-conditioned-credit-assignment-for-reinforcement-learning-with-verifiable-rewards)  
   标签：评分：6.0/10、query:on-policy
   evidence：将对策略蒸馏作为基线方法进行讨论，并提出面向RLVR的自我条件信用分配


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
