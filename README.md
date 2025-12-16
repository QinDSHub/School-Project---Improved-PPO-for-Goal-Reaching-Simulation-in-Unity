<<<<<<< HEAD
This project presents a comprehensive overview of building a simulation environment in Unity and applying the Proximal Policy Optimization (PPO) algorithm from Unity’s built-in ML-Agents toolkit. 

We designed and implemented a goal-reaching simulation game in which the PPO-based chasing agent is trained to locate a target agent as quickly and accurately as
possible. 

A key contribution of our work is the introduction of a creative and customized stepwise training strategy, specifically designed to address the limitations of CPU-only training environments. 

This progressive training method enables effective learning under constrained computational resources. Additionally, the project offers practical suggestions for future optimization and reflects on the broader potential applications of reinforcement learning-based simulation games.

Contributions:
We hope this project contributes meaningfully to three key objectives.

First and foremost, the most significant contribution of our project is the introduction of a creative and customized step-wise training strategy in Unity engine, specifically tailored for Unity-based reinforcement learning simulation projects. This progressive approach not only improves training precision but also enhances training efficiency. While it was developed for our specific simulation, the strategy is broadly applicable to similar RL projects and can even be extended to Machine Learning and Deep Learning workflows within Anaconda-based or PyCharm-based environments.

Secondly, this project serves as an excellent hands-on entry point for beginners in reinforcement learning. It offers both theoretical insights into the Proximal Policy Optimization (PPO) algorithm and practical exposure to how PPO operates in real-world simulation scenarios—helping users better understand and appreciate the power of RL.

Finally, our project provides a comprehensive guide—from building the simulation environment in Unity to deploying the reinforcement learning algorithm and fine-tuning hyperparameters. As such, it can also serve as a valuable introductory project for anyone interested in developing reinforcement learning-based games or applications using Unity.

If further materials for study or research, pls take below references:

[1] A. Kumar, J. Fu, O. Nachum, G. Tucker, and S. Levine, "Stabilizing Off-Policy Q-Learning via Bootstrapping Error Reduction," Advances in Neural Information Processing Systems (NeurIPS), vol. 33, pp. 11794–11805, 2020.

[2] A. Juliani, V.-P. Berges, E. Teng, A. Cohen, J. Harper, C. Elion, Y. Gao, H. Henry, M. Mattar, and D. Lange, "Unity: A General Platform for Intelligent Agents," arXiv preprint arXiv:1809.02627, 2019.

[3] D. Burda, H. Edwards, A. Storkey, and O. Klimov, "Exploration by Random Network Distillation," arXiv preprint arXiv:1810.12894, 2019.

[4] Unity Technologies, "ML-Agents Toolkit," GitHub repository. [Online]. Available: https://github.com/Unity-Technologies/ml-agents. [Accessed: May 18, 2025].

[5] Unity Technologies, "ML-Agents Documentation." [Online]. Available: https://unity-technologies.github.io/ml-agents/. [Accessed: May 18, 2025].

[6] Unity Technologies, "ML-Agents Release 22 Branch." [Online]. Available: https://github.com/Unity-Technologies/ml-agents/tree/release_22. [Accessed: May 18, 2025].

[7] Unity Technologies, "Get Started with ML-Agents in Unity - Part 1: Setup & Installation," YouTube video, 2023. [Online]. Available: https://www.youtube.com/watch?v=bT3SV1SLqHA&list=PLWcLPdrF6kOnovZnG7VT86ffqdpOUcIUV&index=2. [Accessed: May 18, 2025].

[8] J. Schulman, F. Wolski, P. Dhariwal, A. Radford, and O. Klimov, "Proximal Policy Optimization Algorithms," Journal of Machine Learning Research, vol. 20, no. 1, pp. 1–52, 2019.

[9] A. Juliani, V.-P. Berges, E. Teng, A. Cohen, J. Harper, C. Elion, Y. Gao, H. Henry, M. Mattar, and D. Lange, "Unity: A General Platform for Intelligent Agents," arXiv preprint arXiv:1809.02627, updated 2020.

[10] S. Khadka and K. Tumer, "Evolution-Guided Policy Gradient in Reinforcement Learning," in Proc. AAAI Conference on Artificial Intelligence, 2020, pp. 1–8.

[11] J. Ibarz, M. Andrychowicz, M. Zhu, P. Wawrzyński, and W. Zaremba, "Reward Shaping for Reinforcement Learning: A Case Study of a 3D Environment," IEEE Transactions on Neural Networks and Learning Systems, vol. 32, no. 5, pp. 2058–2069, 2021.
=======
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
>>>>>>> 981f5bf (update)
