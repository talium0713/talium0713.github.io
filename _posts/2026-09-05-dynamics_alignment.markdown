---
layout: post
title:  "Learning Robust Visuomotor Policies via Dynamics Alignment"
date:   2026-09-05 20:20:00 +00:00
image: images/dynamics_alignment.png
categories: ['International Conference']
author: "Dohyeok Lee"
authors: "Dohyeok Lee, Jung Min Lee, Munkyung Kim, Seokhun Ju, Jin Woo Koo, Kyungjae Lee, Dohyeong Kim, <b>Taehyun Cho</b>, Jungwoo Lee"
venue: CoRL 2026
paper:
arxiv: https://arxiv.org/abs/2510.27114
slides:
code:
---
Behavior cloning methods for robot learning generalize poorly beyond the support of expert demonstrations, and video prediction models learn action-agnostic dynamics that cannot distinguish between different control inputs. We propose a Dynamics-Aligned Flow Matching Policy (DAP) that integrates dynamics prediction directly into the flow matching process of the policy, so that the policy and dynamics models provide mutual corrective feedback during action generation. This enables self-correction and yields visuomotor policies that generalize more robustly than baseline methods on real-world manipulation tasks.
