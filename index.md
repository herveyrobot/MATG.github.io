## Strategic Behavioral Deception in Heterogeneous Multi-Agent Systems for Enhanced Adversarial Efficiency

## <center> Abstract <center>
Adversarial attacks pose a significant threat to the safety and reliability of artificial intelligence, posing critical challenges to the deployment of AI in multi-agent systems. However, existing works focus on directly manipulating the victim's observations or neural networks, which is infeasible when the victim's model is not accessible. Although these attack schemes demonstrate effectiveness, their practicality is limited in numerous scenarios, and they do not sufficiently investigate the vulnerabilities arising from dynamic multi-agent interactions. To address this challenge, we propose a novel deceptive attack strategy where an adversarial agent learns deceptive behaviors to mislead the opponent's policy. Specifically, we train an adversarial agent to learn a deceptive policy, and embed this "deceptive" agent into our swarm by replacing one original agent. The deceptive agent aims to interfere with the opponent’s cooperative strategy by exhibiting misleading behaviors, effectively exploiting the opponent's policy weaknesses without requiring access to the opponent’s model. We evaluate the proposed approach in a simulated air-ground swarm competition scenario. Experimental results show that by replacing a single agent with our deceptive agent, the win rates of mainstream MARL algorithms such as IAC, MADDPG, and QMIX are increased by 11\% to 37\%, demonstrating the effectiveness of our deceptive adversarial behaviors. The proposed deceptive adversarial attack framework opens up new possibilities for studying the robustness and security of MARL algorithms in more realistic and challenging settings.

---

## Action Trajectory Summary
The swarm competition scenario is illustrated by the diagrams on the left. On the right, the diagrams depict the scenario where deceptive adversarial attackers join the competition.

### <center>Training Enviroment</center>
<center class="half">
    <img src="https://raw.githubusercontent.com/herveyrobot/HMAG.github.io/gh-pages/image/TRE-A1.gif" width="400"/> <img src="https://raw.githubusercontent.com/herveyrobot/HMAG.github.io/gh-pages/image/TRE-C.gif" width="400"/>
</center>
    
### <center>Test Enviroment-A </center>
<center class="half">
    <img src="https://raw.githubusercontent.com/herveyrobot/HMAG.github.io/gh-pages/image/TEEA-A-1.gif" width="400"/> <img src="https://raw.githubusercontent.com/herveyrobot/HMAG.github.io/gh-pages/image/TEEA-C1.gif" width="400"/>
</center>

### <center>Test Enviroment-B </center>
<center class="half">
    <img src="https://raw.githubusercontent.com/herveyrobot/HMAG.github.io/gh-pages/image/TEEB-A.gif" width="400"/> <img src="https://raw.githubusercontent.com/herveyrobot/HMAG.github.io/gh-pages/image/TEEB-C.gif" width="400"/>
</center>
    
---


## Video
<iframe height=450 width=800 src="//player.bilibili.com/player.html?aid=228588871&bvid=BV1Xh41157JE&cid=1128362355&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true">  </iframe>
