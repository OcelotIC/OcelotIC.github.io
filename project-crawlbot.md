---
type: project
title: CrawlBot — Dual-Arm Robot Crawling on a Free-Floating Structure
description: Control and estimation stack for a dual-arm robot (2 × 7-DoF VISPA-class arms) that crawls across a free-floating orbital structure for in-orbit assembly. A 10 Hz centroidal NMPC bounds the reaction torque and momentum the robot transfers to the host's reaction wheels; a 100 Hz whole-body QP executes the plan under multibody and docking constraints. Validated in MuJoCo on a six-step traversal.
techs: Python, CasADi, IPOPT, Pinocchio, MuJoCo, qpOASES
repo: https://github.com/OcelotIC/CrawlBot_control
order: 0
---
