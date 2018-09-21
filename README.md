# Multi-Reinforcement-Learning-Study-List
Multi - Agent Reinforcement Learning Study List 


(1) Mulit-Agent Actor-Critic for Mixed cooperative-Competitve Environments - OpenAI

(2) Stabilising Experience Replay for Deep Multi-Agent Reinforcement Learning
==> DQN을 개개의 agent에게 주는 것으로 학습하고자 할 때, Replay buffer가 사용될 수 없는 이유.

(3) Multi-agent reinforcement learning : Independent vs. cooperative angetns 
==> DQN을 개개의 agent에게 주는 것으로 multi-agent를 구성하는 논문 , non-stationary 어려운점 제시

(4) Prioritized experience replay 
==> policy network의 더 빠른 수렴성을 위해서 replay memory에 우선순위를 바꾸는 방법 제시
==> TD 오류를 기반으로 샘플링 분포를 편향 시키는 (biases ) replay memory를 만듭니다.

(5) Deep recurrent q-learning for partially observalble mdps.
==> partially observable setting의 환경에서, agen들은 일반적으로 전체 행동 관찰, 또는 충분한 stastistic에 있어야 합니다.  
==> 이를 해결하기 위해서 Q-learning의 q-function을 RNN 을 사용해서 모델링한 논문입니다.
