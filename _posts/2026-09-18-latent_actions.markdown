---
layout: post
title:  "Why Latent Actions Fail, and How to Prevent It"
date:   2026-09-18 20:21:00 +00:00
image: images/latent_actions.png
categories: ['International Conference']
author: "Jung Min Lee"
authors: "Jung Min Lee, <b>Taehyun Cho</b>, Li Zhao, Jungwoo Lee"
venue: NeurIPS 2026
paper: https://openreview.net/forum?id=LWmFD8ITV8
arxiv: https://arxiv.org/abs/2605.20223
slides:
code:
---
Latent action models (LAMs) learn action-like representations from unlabeled videos by compressing frame-to-frame changes, but in-the-wild frames also contain exogenous state such as background clutter that changes independently of the agent's actions. Extending a linear LAM framework to explicitly model exogenous state, we show that minimizing the standard reconstruction objective produces latent actions that encode exogenous information from the future observation, and that learning in a representation space focused on endogenous components is key to mitigating this interference. We further prove that previously proposed auxiliary objectives, such as action supervision, encourage latent actions to be consistent across exogenous states.
