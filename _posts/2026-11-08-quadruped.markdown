
---
layout: post
title: "Quadruped Locomotion"
date: 2026-11-08
categories: [projects]
image: /images/quadruped.gif
tech: "Python, JAX, Brax, MuJoCo, ROS 2"
code: https://github.com/divpr
---

Developed a quadruped locomotion policy using Proximal Policy
Optimization (PPO) with JAX, Brax, and MuJoCo.

Deployed the trained policy through ROS 2 for sim-to-sim
evaluation, achieving a velocity tracking mean absolute 
error of 0.058 m/s at a 1.0 m/s commanded velocity.
