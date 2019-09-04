# Autopilot-TensorFlow
A TensorFlow implementation of this Nvidia paper with some changes. For a summary of the design process and FAQs, see this medium article I wrote.

## IMPORTANT
Absolutely, under NO circumstance, should one ever pilot a car using computer vision software trained with this code (or any home made software for that matter). It is extremely dangerous to use your own self-driving software in a car, even if you think you know what you're doing, not to mention it is quite illegal in most places and any accidents will land you in huge lawsuits.

This code is purely for research and statistics, absolutley NOT for application or testing of any sort.

## How to Use
Download the dataset and extract into the repository folder

Use python train.py to train the model

Use python run.py to run the model on a live webcam feed

Use python run_dataset.py to run the model on the dataset

To visualize training using Tensorboard use tensorboard --logdir=./logs, then open http://0.0.0.0:6006/ into your web browser.

## Acknowledged/Cited in
D. Qian et al., "End-to-End Learning Driver Policy using Moments Deep Neural Network," 2018 IEEE International Conference on Robotics and Biomimetics (ROBIO), Kuala Lumpur, Malaysia, 2018, pp. 1533-1538.

Pan, X., You, Y., Wang, Z., & Lu, C. (2017, September 26). Virtual to Real Reinforcement Learning for Autonomous Driving. Retrieved from https://arxiv.org/abs/1704.03952

https://medium.com/@maxdeutsch/how-to-build-a-self-driving-car-in-one-month-d52df48f5b07

https://mc.ai/self-driving-car-on-indian-roads/

http://on-demand.gputechconf.com/gtc/2018/presentation/s8748-simulate-and-validate-your-dnn-inference-with-catia-before-adas-industrial-deployment.pdf

https://www.ctolib.com/amp/cyanamous-Self-Driving-Car-.html

