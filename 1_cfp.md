---
layout: page
title: Call for papers
---

Artificial Intelligence (AI) is becoming ubiquitous and moving from the cloud
directly into embedded devices. In both cases, the complexity of many AI
problems requires substantial computational resources. For this reason, we have
seen the emergence of dedicated hardware, particularly for that subset of AI
that is referred to as _deep learning_.
However, the range of AI techniques that could be employed in embedded
applications is vast and it is not limited to deep learning.
Autonomy applications such as driver-less cars and unmanned aerial vehicles span
all phases of the classical _Observe, Orient, Decide, and Act (OODA)_
loop. Architectures supporting these applications feature a situational
assessment process that populates and maintains an internal world model, and a
decision-making process that computes the best course of action to achieve the
goals of the system, taking into account the state of the world.
While deep learning has been successfully used to extract features from raw data
such as images and to classify entities, advanced _reasoning methods_ are
used to assess complex situations and to make predictions. Similarly, while deep
reinforcement learning shows promises for skill-level autonomy, other tasks such
as mission planning, long-term planning, and contingency management rely on
_action models_ and _planning algorithms_ that are based on logical
representations like Markov Decision Processes (MDP), Partial Observable Markov
Decision Processes (POMDP), and Hierarchical Task Networks (HTN).

Nowadays, reasoning and planning methods are implemented in
software. The algorithmic complexity of these methods, especially when dealing with models of the world that include uncertainty, is high.
Typically, application-specific software implementations are efficient
enough. Their applicability, however, is limited to specific environments and specific
goals, which is not the typical case for _autonomous and intelligent systems_.
Dealing with complex environments that are not known a priori, and being able to
accept wide-open goals requires these systems to reason and plan over generic
domains, which are represented formally using logical languages.
These requirements translate into algorithms that are computationally very
challenging. Hence, there is a demanding need not only for new algorithms for
domain-independent reasoning but also for novel hardware architectures that
can accelerate these algorithms compared to software execution.

The _Workshop on Accelerating Artificial Intelligence for Embedded Autonomy_
aims at gathering researchers and practitioners in the fields of autonomy, automated
reasoning, planning algorithms, and embedded systems to discuss the development
of novel hardware architectures that can accelerate the wide variety of AI
algorithms demanded by advanced autonomous and intelligent systems.
Topics of interest include hardware architectures and design methodologies to accelerate:  
*  Applications based on deep learning 
*  Skill-level and instinctive autonomy based on deep reinforcement learning
*  Storage and retrieval of facts in knowledge bases
*  Logical reasoning methods such as deduction
*  Search for classical planning algorithms and Hierarchical Task Networks (HTN)
*  Inference in probabilistic models such as Bayesian networks and probabilistic logic
*  Planning algorithms for Markov Decision Processes (MDP) and Partial Observable Markov Decision Processes (POMDP)

The workshop is not limited to any particular hardware implementation platform.
ASICs, FPGAs, and analog circuits, as well as heterogeneous platforms that
combine hardware accelerators with CPUs and GPUs are all within the scope of the
proposal. Similarly, emerging architectures such as those based on
neuromorphic computing and so-called non Von Neumann machines are also considered in scope.

### Important dates

* Submission deadline: July 1, 2019 
* Author notification: July 31, 2019
* Camera ready: August 30, 2019

### Submissions

Follow [this link](https://easychair.org/conferences/?conf=aaiea19) to submit your contribution.


