# Navigating-the-Dynamics-of-Legged-Locomotion
In this project, I dove deep into one of the most exciting challenges in modern robotics: how to make a legged robot move with both stability and fluidity. To do this, I used the paper 'From centroidal to whole-body models for legged locomotion: a comparative analysis' as my roadmap, retracing the authors' steps to understand the logic behind their conclusions.

The core of my work was exploring the fundamental 'trade-off' in robotic control. On one hand, you have centroidal models, which simplify the robot by focusing on its center of mass—these are great for efficiency. On the other hand, you have whole-body models, which account for every single joint and the mass of every limb, offering much higher detail.

By replicating this comparative analysis, I was able to see firsthand how Model Predictive Control (MPC) behaves differently depending on which model you feed into it. It was fascinating to observe how a different mathematical abstraction can completely transform a robot's response: while a simplified model is incredibly fast and ideal for long-term planning, a full model provides pinpoint precision at the cost of being much more computationally heavy.

This experience gave me a much more intuitive grasp of robotic control. I no longer see it as just a set of formulas, but as a strategic choice. I’ve learned how to evaluate which model is best suited for a specific task, balancing the need for speed with the necessity for accuracy. It’s been a pivotal project that has truly shaped my understanding of robot dynamics.
