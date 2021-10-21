# AML_project
## This repository contains the source code for the project of the AML course for the DSC PhD programme

## The project consists in imitating the behaviour of the operator of the Como lake Dam. We have a dataset of the operation of the dam over the 65 year (from 1946 to 2011. The datasets has daily granularity and contains the data about the lake level, water inflow and water demand for each day, as well as the water release, which is the feature controlled by the dam operator. Beign that the dam operators are human, and cannot easily formaliza what pushes them to release a certain amount of water each day, our goal is to analyze the data and recover the reward function (in a Reinfocement Learning framework) that pushes them to make certain decisions. So the project deals with modelling the problem as a RL problem, by identyfying the state and policy space (the action space isalready decided as the water release). Then we are gonna use this modelling, together with IRL algorithms to recover the reward function.
## The results of this project are described more in detail in the paper published in Machine LEarning (Springer) : https://rdcu.be/czWLt

## The project is divided in 2 parts
- Strictly Supervised Learning to model the state space (feature selection and engineering) and the policy space (model selection)
- Inverse Reinforcement Learning - Running Non-Stationary \Sigma-GIRL which contains multiple SL problems, together with non-convex optimization and a Dynamic Programmic algorithm


### The project is developped in the notebook : Como Water Dam Control
