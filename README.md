# 2016-Election-Results-Simulation
Emulating 538's final forecast visualization for the 2016 presidential election (https://fivethirtyeight.com/features/the-media-has-a-probability-problem/). 
Originally done as part of an assignment for INFO 2950: Intro to Data Science at Cornell.

The election results dataset and some implementation suggestions were provided by Prof. Paul Ginsparg and the INFO 2950 teaching staff.

<b>Screenshot of my solution:<b> <br>
<img width="590" alt="screen shot 2018-06-07 at 10 45 30 am" src="https://user-images.githubusercontent.com/7096526/41107243-f53a6392-6a3f-11e8-9431-edfbd332e187.png">

Note: bar color signifies which candidate wins the election (red for Trump/blue for Clinton). Height of the bars = percent of simulations (out of 20000 simulations) in which a candidate won the popular vote by a certain margin (shown on the x-axis). This simulation takes into account the fact that a candidate can win the popular vote but lose the election due to the electoral college, which is the reason why there is a small percentage of simulations where Donald Trump wins (red colored bars), but Clinton has a higher popular vote margin (x-axis).
<br>

<b>Screenshot of 538's original:<b>

<img width="554" alt="screen shot 2018-06-07 at 9 36 51 am" src="https://user-images.githubusercontent.com/7096526/41105757-5ffc615c-6a3c-11e8-9e7b-da8936b424eb.png">


