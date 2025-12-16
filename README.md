We aim for this project to make three practical contributions.

First, and most importantly, we introduce a novel, customized step-wise training strategy in Unity for reinforcement learning–based simulation tasks. This progressive approach improves both training accuracy and efficiency and, while developed for this project, is broadly applicable to similar RL tasks and can be extended to ML and DL workflows in Anaconda- or PyCharm-based environments.

Second, the project provides a CPU-reproducible, hands-on entry point for beginners in reinforcement learning. It combines theoretical foundations of the PPO algorithm with practical demonstrations in real simulation scenarios, enabling intuitive understanding of RL behavior and potential.

Finally, we present a complete practical guide, covering Unity environment construction, RL deployment, and hyperparameter tuning, making the project a high-quality reference for developing Unity-based RL games or applications.

In this PPO simulation, hyperparameter tuning is performed under CPU-only and time-constrained settings, with a limited tuning scope that can be further optimized in future iterations. After the agent reaches stable learning behavior, fine-tuning focuses on learning rate decay, buffer size expansion, extrinsic reward configuration (strength = 1.0), early stopping, and observation/reward normalization, aiming to balance learning stability and model expressiveness.

A draft project report and a functional demonstration video@https://youtu.be/ECYaj3dLhb0 are also provided for reference. Thank you for your attention.

我们希望本项目能够在以下三个关键方面带来切实的贡献：

首先，也是最重要的一点，本项目在Unity引擎中引入了一种创新的、定制化的分阶段训练策略，专门面向基于Unity的强化学习仿真任务。该渐进式方法既提升了训练精度，也显著提高了训练效率。虽然此策略最初是针对本项目设计的，但其思路具备良好的通用性，可扩展至其他类似的强化学习项目，甚至适用于基于 Anaconda 或 PyCharm 环境的机器学习与深度学习工作流。

其次，本项目为强化学习初学者提供了一个可在个人 CPU 上复现的实践性入门案例。内容不仅涵盖 PPO 算法的理论基础，还通过真实仿真场景演示其实际运行机制，帮助学习者直观理解强化学习的优势与潜力。

最后，本项目提供了一份从Unity仿真环境搭建、强化学习算法部署到超参数调优的完整实践指南。因此，该项目也可作为一份高质量的入门参考，供有意使用 Unity 开发强化学习游戏或应用的研究者与开发者使用。

在本PPO仿真实验中，涉及以下RL超参数调优部分。由于实验在CPU上运行且时间有限，当前调整范围相对有限，期待后续在此基础上进一步优化与迭代。
当智能体学习行为趋于稳定后，进入关键超参数的精细调优阶段，以进一步提升模型性能与训练效率，主要包括：
1.	学习率调整
随训练进程逐步降低学习率，以实现更稳定、精细的梯度更新。
2.	经验缓冲区扩展
增大缓冲区容量，提升样本多样性，降低过拟合风险。
3.	奖励信号配置
采用 extrinsic 奖励信号，强度设为 1.0，以精细调节外部奖励对训练的影响。
4.	提前停止策略
结合最大训练步数与奖励阈值控制训练时长，在模型性能进入平台期时提前终止。
5.	归一化技术
启用观测值与奖励的归一化，提升训练稳定性与精度，尽管会略微增加计算开销。

上述调整旨在平衡学习稳定性与模型表达能力，对策略初步收敛后的进一步优化具有关键作用。
同时，我也提供了本项目的报告草稿与功能演示视频@https://youtu.be/ECYaj3dLhb0
仅供大家参考。感谢关注。
