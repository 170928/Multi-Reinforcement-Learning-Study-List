# Multi-Reinforcement-Learning-Study-List
Multi - Agent Reinforcement Learning Study List.


(1) Mulit-Agent Actor-Critic for Mixed cooperative-Competitve Environments - OpenAI

(2) Stabilising Experience Replay for Deep Multi-Agent Reinforcement Learning  
==> DQN을 개개의 agent에게 주는 것으로 학습하고자 할 때, Replay buffer가 사용될 수 없는 이유.  

(3) Multi-agent reinforcement learning : Independent vs. cooperative angetns   
==> DQN을 개개의 agent에게 주는 것으로 multi-agent를 구성하는 논문 , non-stationary 어려운점 제시  

(4) Prioritized experience replay   
==> policy network의 더 빠른 수렴성을 위해서 replay memory에 우선순위를 바꾸는 방법 제시  
==> TD 오류를 기반으로 샘플링 분포를 편향 시키는 (biases) replay memory를 만듭니다.  

(5) Deep recurrent q-learning for partially observalble mdps.
==> partially observable setting의 환경에서, agen들은 일반적으로 전체 행동 관찰, 또는 충분한 stastistic에 있어야 합니다.    
==> 이를 해결하기 위해서 Q-learning의 q-function을 RNN 을 사용해서 모델링한 논문입니다.  

(6) Off-envirionment reinforcement learning   
==> off-policy를 통해서 현재 가진것과 다른 policy에서 생성된 데이터를 사용할 수 있는 것 처럼, off-environment 기법을 통해서 다른 환경으로부터 모아진 데이터를 통해서 policy를 학습하는 것이 가능하다는 것을 보여주는 논문입니다.  

(7) Trust region policy optimization

### Inverse Reinforcement Learning

(1) Maximum entropy inverse reinforcement learning.   
> B. D. Ziebart, A. Maas, J. A. Bagnell, and A. K. Dey  
> In AAAI, AAAI’08, 2008

(2) Modeling interaction via the principle of maximum causal entropy.   
> B. D. Ziebart, J. A. Bagnell, and A. K. Dey    
> In ICML, pages 1255–1262, 2010.  

(3) Guided Cost Learning: Deep Inverse Optimal Control via Policy Optimization

### More Topics
https://medium.com/@yuxili/reinforcement-learning-in-nips-2018-967ab53ab211
  
> UC Berkely 의 강화학습 강의 사이트 입니다.  
http://rail.eecs.berkeley.edu/deeprlcourse/

https://m.blog.naver.com/PostView.nhn?blogId=atelierjpro&logNo=220981354861&proxyReferer=&proxyReferer=http%3A%2F%2Fblog.naver.com%2Fatelierjpro%3FRedirect%3DLog%26logNo%3D220981354861%26from%3DpostView


### Recommendation Site for Comprehensive mathematics
https://medium.com/@jonathan_hui/rl-deep-reinforcement-learning-series-833319a95530
