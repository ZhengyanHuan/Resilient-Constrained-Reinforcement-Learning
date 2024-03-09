# Resilient-Constrained-Reinforcement-Learning


Copyright (c) [2023] 
[The Authors of Resilient Constrained Reinforcement Learning]
All Rights Reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

==============================================================================

Acknowledgment

The code of generating random MDP transition dynamics 

https://github.com/jb3618columbia/Optimality-Guarantees-for-Policy-Gradient-Methods

The reference: Global Optimality Guarantees For Policy Gradient Methods, J. Bhandari and D. Russo

==============================================================================

## Description
 
Our proposed methods in the manuscript can be referred as follows:

(1) ResPG-PD  (Resilient Policy Gradient Primal-Dual) -------------------> Algorithm 1

(2) ResOPG-PD (Resilient Optimistic Policy Gradient Primal-Dual) --------> Algorithm 2

All of our computational results in the manuscript can be reproduced by, 
executing our Jupyter Notebook documents, accordingly. The requirements are: 

  Jupyter Notebook
  
  Python 3, NumPy, Matplotlib, Cvxopt, and SciPy. 

==============================================================================

Convergence performance of ResPG-PD and ResOPG-PD in policy search problem (Section D.1)

(1) Resilient_RL_PolicySearch.ipynb(sec:Plot reward, utility and relaxation vs iterations) ----------> Figure 3, Figure 11 and Figure 12


==============================================================================

Optimality gap of RPG-PD, OPG-PD, and dual methods in policy search problem (Section D.1)

(1) Resilient_RL_PolicySearch.ipynb(sec:Plot reward, utility, relaxation, policy optimality gaps) ---> Figure 2 and Figures 13-15


==============================================================================

Convergence performance of ResPG-PD and ResOPG-PD in policy search problem with different relaxation costs (Section D.1)

(1) Resilient_RL_PolicySearch.ipynb(sec:Reward, utility, relaxation vs alpha) -----------------------> Figure 4


==============================================================================

Convergence performance of ResPG-PD and ResOPG-PD in monitoring problem (small state space, Section D.2)

(1) Resilient_RL_Monitoring_D2.ipynb(sec:Plot reward, utility and relaxation vs iterations) ------------> Figure 6, Figure 16 and Figure 17


==============================================================================

Optimality gap of RPG-PD, OPG-PD, and dual methods in monitoring problem (small state space, Section D.2)

(1) Resilient_RL_Monitoring_D2.ipynb(sec:Plot reward, utility, relaxation optimality gaps) -------------> Figure 18-20


==============================================================================

Convergence performance of ResPG-PD and ResOPG-PD in monitoring problem (small state space, Section D.2) with different relaxation costs 
 
(1) Resilient_RL_Monitoring_D2.ipynb(sec:Reward, relaxation vs alpha) ----------------------------------> Figure 7

==============================================================================

Convergence performance of ResPG-PD and ResOPG-PD in monitoring problem (large state space, Section D.3)

(1) Resilient_RL_Monitoring_D3.ipynb(sec:Plot reward, utility and relaxation vs iterations) ------------> Figure 9, Figure 21 and Figure 22


==============================================================================
 
Optimality gap of RPG-PD, OPG-PD, and dual methods in monitoring problem (large state space, Section D.3)

(1) Resilient_RL_Monitoring_D3.ipynb(sec:Plot reward, utility, relaxation optimality gaps) -------------> Figure 23-25


==============================================================================

Convergence performance of ResPG-PD and ResOPG-PD in monitoring problem (large state space, Section D.2) with different relaxation costs 

(1) Resilient_RL_Monitoring_D3.ipynb(sec:Reward, relaxation vs alpha) ----------------------------------> Figure 10

==============================================================================

Policy of ResPG-PD and ResOPG-PD in monitoring problem (large state space, Section D.2)

(1) Resilient_RL_Monitoring_D3.ipynb(sec:Visualize the policy) ----------------------------------> Figure 8
