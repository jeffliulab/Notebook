# Gymnasium

## Basic Usage

gymnasium（之前叫gym）：是OpenAI开发的一个Python库，用于开发和比较强化学习算法。它提供了标准化的环境接口。

Gymnasium (Simply "Gym") is a project that provides an API for all **single agent reinforcement learning** environment.

The core of Gym is `Env`, a high-level python class representing a Markov Decision Process.



## MuJoCo

MuJoCo：是一个物理引擎（Physics Engine），专注于机器人和物理模拟。它是一个独立的C/C++库，需要安装到系统中并添加到环境变量以便系统能找到它。

mujoco Python包：是MuJoCo的Python绑定，它允许Python代码与MuJoCo C/C++库交互。这就是为什么你需要安装这个包。

安装MuJoCo并添加到Path后，接着安装python包（pip install mujoco），就配置好了mujoco环境，可以使用gym下的不同environment了。