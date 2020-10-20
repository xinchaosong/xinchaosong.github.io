---
layout: main
---

# Publications

### Belief-Grounded Networks for Accelerated Robot Learning under Partial Observability

Hai Nguyen, Brett Daley, <u>**Xinchao Song**</u>, Chistopher Amato, and Robert Platt. *Accepted by the 4th Annual Conference on Robot Learning*. November, 2020.

Many important robotics problems are partially observable in the sense that a single visual or force-feedback measurement is insufficient to reconstruct the state. Standard approaches involve learning a policy over beliefs or observation-action histories. However, both of these have drawbacks; it is expensive to track the belief online, and it is hard to learn policies directly over histories. We propose a method for policy learning under partial observability called the Belief-Grounded Network (BGN) in which an auxiliary belief-reconstruction loss incentivizes a neural network to concisely summarize its input history. Since the resulting policy is a function of the history rather than the belief, it can be executed easily at runtime. We compare BGN against several baselines on classic benchmark tasks as well as three novel robotic touch-sensing tasks. BGN outperforms all other tested methods and its learned policies work well when transferred onto a physical robot.

### Imitation Learning in POMDPs with Contacts

Hai Nguyen, **<u>Xinchao Song</u>**, Christopher Amato, and Robert Platt. *Robotics: Science and Systems: Reacting to Contact Workshop*. July 2020. [[pdf](http://mlab.ri.cmu.edu/reacting_contact_workshop/files/hai_nguyen.pdf)]

<iframe class="list-video-left" width="352" height="198" src="https://www.youtube.com/embed/OgJq-AVdJc0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

In this paper, we use the access to full states during training and imitation learning to train an intelligent agent that uses contacts to explore to solve a manipulation task. We formulate the problem as a partially observable decision process (POMDP) and solve it using imitation learning. We train a POMDP expert that solves the task while performing informative actions using contacts as well as an agent that acts on partial information by cloning this expert’s behavior. We test our method on a novel robotics domain and set up an experiment with a real robot.
