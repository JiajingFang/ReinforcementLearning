# ReinforcementLearning
## Install
```Python
pip install gym
```
## Q learning
![](https://github.com/JiajingFang/ReinforcementLearning/blob/main/image/Q_learning_formular.jpg)  
这里a和y是Q学习算法的参数。a被称为学习率，y被称为折扣因子，值的范围在0和1之间，有时等于1。y可以为零，而a则不能，因为损失应该以一定的学习率更新。这里的a表示与监督学习中使用的相同。y决定了我们希望给予未来奖励多少重要性。
<ol>
  <li>步骤1：使用全零和Q值将Q表初始化为任意常量。</li>
  <li>步骤2：让代理人对环境做出反应并探索行动。对于状态中的每个更改，请为当前状态（S）的所有可能操作中选择任意一个。</li>
  <li>步骤3：作为该动作（a）的结果，前进到下一个状态（S’）。</li>
  <li>步骤4：对于来自状态（S’）的所有可能动作，选择具有最高Q值的动作。</li>
  <li>步骤5：使用等式更新Q表值。</li>
  <li>步骤6：将下一个状态更改为当前状态。</li>
  <li>步骤7：如果达到目标状态，则结束并重复该过程。</li>
</ol>







