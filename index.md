## Deceptive Adversarial Attack for Air-Ground Swarm Competition

## <center> Abstract <center>
Exploring the ways that artificial intelligence systems can be vulnerable to adversarial attacks is crucial for their safe and widespread use in various industries. However, most existing work focuses on how to modify the victim’s observations or introduce perturbations in specific layers of the network structure, ignoring the constraints of not having access to the victim’s neural network in realistic scenarios. This poses new challenges for intelligent agents in adversarial settings where they cannot access the opponent’s model, such as in multi-agent competitive scenarios. In this paper, we propose a method for generating deceptive strategies that use the agent’s motion behavior to confuse the victim’s policy without requiring access to the victim’s policy model, to help teammates win in multi-agent swarm  competitions. A learning framework based on the reinforcement learning paradigm is established to teach agents how to generate corresponding deceptive actions. The proposed framework is tested on our own developed Heterogeneous Multi-agent Air-Ground simulation scenario, demonstrating the effectiveness of this type of attack. 

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
