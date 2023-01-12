---
layout: main
---

# Publications

### Reinforcement-Learning Based Robotic Assembly of Fractured Objects Using Visual and Tactile Information

**<u>Xinchao Song\*</u>**, Nikolas Lamb\*, Sean Banerjee, Natasha Kholgade Banerjee. 2023 International Conference on Automation, Robotics and Applications (ICARA).

In this paper, we propose a reinforcement learning approach using two novel visual metrics, which we term pixel offset error and assembly error, to assemble complex fractured objects. Our approach does not place constraints on object geometry and estimates the assembly state of the constituent objects in real time. We show tightly assembled fractured and restored pairs in simulation and on real robots.

### Belief-Grounded Networks for Accelerated Robot Learning under Partial Observability

Hai Nguyen\*, Brett Daley\*, **<u>Xinchao Song</u>**, Chistopher Amato, and Robert Platt. 2020 Conference on Robot Learning (CoRL). [[website](https://sites.google.com/view/bgn-pomdp)]

<iframe class="list-video-right" width="400" height="225" src="https://www.youtube.com/embed/06OJReBYNls" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

We propose a method for policy learning under partial observability called the Belief-Grounded Network (BGN) in which an auxiliary belief-reconstruction loss incentivizes a neural network to concisely summarize its input history. Since the resulting policy is a function of the history rather than the belief, it can be executed easily at runtime. We compare BGN against several baselines on classic benchmark tasks as well as three novel robotic touch-sensing tasks. BGN outperforms all other tested methods and its learned policies work well when transferred onto a physical robot.

{:style="clear: left"}
&nbsp;

### Imitation Learning in POMDPs with Contacts

Hai Nguyen, **<u>Xinchao Song</u>**, Christopher Amato, and Robert Platt. *Robotics: Science and Systems: Reacting to Contact Workshop*. July 2020. [[pdf](http://mlab.ri.cmu.edu/reacting_contact_workshop/files/hai_nguyen.pdf)]

<iframe class="list-video-left" width="400" height="225" src="https://www.youtube.com/embed/OgJq-AVdJc0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

In this paper, we use the access to full states during training and imitation learning to train an intelligent agent that uses contacts to explore to solve a manipulation task. We formulate the problem as a partially observable decision process (POMDP) and solve it using imitation learning. We train a POMDP expert that solves the task while performing informative actions using contacts as well as an agent that acts on partial information by cloning this expert’s behavior. We test our method on a novel robotics domain and set up an experiment with a real robot.
