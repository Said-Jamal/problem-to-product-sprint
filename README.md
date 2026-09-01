# Problem-to-Product Sprint - Ctrl+Solve

This is our final project from the Problem-to-Product Sprint, a  program by Nijat Hajiyev (Nexus Adv). We are Ctrl+Solve: Said Jamalov and Laman Aghayeva.


## The problem

A worker starts a new batch. He checks the material by eye or by memory. Sometimes the material is not enough. The line stops. He tells the warehouse by phone. Nobody writes it down. Then everyone waits for material.

One number stayed in our heads: 0%.

No shortage was ever found early. Not once. Nobody checked the stock before the batch, so the problem always appeared at the last moment, when the worker was already at the machine, ready to work. And then the line stopped.

The average wait was 15 to 16 hours. Every time. The cost, over one year, came close to 2.22 million AZN.


## Where to start

The company has only two shops: Weaving and Dyeing. We had two data files about the shortages. The two files did not show the same numbers on every point. But on one thing, both files agreed.

The Dyeing shop is the biggest part of the problem. Around 60 to 63% of the total cost comes from this one shop only. This was the same in both files, so we trusted it.

We did not try to fix everything at the same time. We chose the shop with the biggest cost, and we started there. If we fix the biggest place first, we fix the biggest part of the problem.


## The maps

We did not start with a tool. We started with a map.

First we drew the AS-IS map: what really happens today. 16 steps, 4 lanes, and 4 rework loops. People doing the same work again and again.

Then we drew the TO-BE map: what we want instead. The idea is simple. The system checks the stock against a limit (daily use × delivery time + safety buffer). If the stock goes under that limit, an alert goes to the warehouse and the manager, before the batch starts.

16 steps became 10. 4 lanes became 3. 4 loops became 0.

The hard part was not the solution. The hard part was seeing the process honestly, with all its ugly loops. When we saw it clearly, the solution became easy.


## The prototype

We built a small working app to show the core loop: see the stock, see the alert, click to notify, see it in the log.

No AI in this version. Just a simple rule: if stock is below the limit, tell everyone at the same time. A rule is faster, cheaper, and easy to check. AI can come later, when we have real order history to learn from.

You can open the live demo here: https://claude.ai/public/artifacts/28004bb8-fa48-4568-9f9b-68037142128d



## Thanks

To Nijat HAJIYEV, for teaching this sprint and for the honest feedback. To the Nexus Adv team, for the method behind this work. And to each other, for finishing it together.


*This project was a training exercise. Numbers, names, and details are shared for learning purposes.*
