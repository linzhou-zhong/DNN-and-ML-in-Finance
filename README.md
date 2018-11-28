# **Overview**

## **Introduction**
This project is devided in two individual parts as **DNN in Financial Trading** and **DNN in Negotiation** as well.

## **Explanation**
**DNN in Financial Trading**

Implementing trading system based on deep learning approches, for any problem we have here (price prediction, trading strategy, risk management), using different varations of artificial neural networks(ANNs) or even deep neural networks(DNNs) and how well they can hanle with and outputing a wanted results.

**DNN in Negotiation**

The programs trains neural networks to hold negotiations in natural language, and allows reinforcement learning self play and rollout-based planning. 



## **Process Design**


## **More details of process design**

As the graphic above showing we plan to use two DNN processes to construct our project.
Using first DNN process to analyse dates of stocks and finally giving out a list of consequence for showing their parameters (ROi, Volatility Index, etc) which will be used by second DNN process.

When we turn to the second DNN process, two agents will be "imported" and play with roles between **Costumer** and **Trader**. During one dialogue, we plan to give adjusted values for each stocks (Because, each player dones not know its partener's strategie. For example, some custumers want to keep their stocks which have a small volatility index, but traders just want to take over the stocks with the highest ROI from custumer, that's why we give a adjusted values for each stock), the number of all stocks will limited between **X** to **Y**, and amount of stocks' values for both each player will equal to **Z**.

