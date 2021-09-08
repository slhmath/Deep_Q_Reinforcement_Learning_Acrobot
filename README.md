# Deep_Q_Reinforcement_Learning_Acrobot
We train a Deep Neural Network to estimate the optimal policy or Q(uality)-Values for an agent in the Acrobot-v1 system in OpenAI Gym.

The agents 'goal' is to swing its two limbs so that the lower limb breaches the horizontal bar directly above it. The first joint (corresponding to the gymnast's hands on the bar) is fixed and cannot exert torque, but the second joint (corresponding to the gymnast's waist) can.
Here is a sample of the agent performing during the training phase: 


<img src="https://github.com/slhmath/Deep_Q_Reinforcement_Learning_Acrobot/blob/main/DeepQ_Acrobot_Training.gif" width="200" height="200">


After training is complete, the Deep Q-Network has discovered an approximately optimal policy. Below are examples of how the trained agent peforms on the first 4 test runs:


<img src="https://github.com/slhmath/Deep_Q_Reinforcement_Learning_Acrobot/blob/main/Test_Run_1.gif" width="200" height="200">


(Run 1. Steps: 111)


<img src="https://github.com/slhmath/Deep_Q_Reinforcement_Learning_Acrobot/blob/main/Test_Run_2.gif" width="200" height="200">


(Run 2. Steps: 82)


<img src="https://github.com/slhmath/Deep_Q_Reinforcement_Learning_Acrobot/blob/main/Test_Run_3.gif" width="200" height="200">


(Run 3. Steps: 96)


<img src="https://github.com/slhmath/Deep_Q_Reinforcement_Learning_Acrobot/blob/main/Test_Run_4.gif" width="200" height="200">


(Run 4. Steps: 83)

