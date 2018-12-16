# README
Baseball Players Dataset Visualization 
====
Summary：
----
This is the final project for Udacity Data Analyst Nanodegree Certificate.I chose the baseball dataset, which contains the following information for 1157 players: left and right hand usage, height, weight, hit rate, and home base score.<br>

Design:
----
1、First draft:<br>
  The visual goal is to explore the factors affecting the hit rate and the total score. The advantage of the scatter plot is that it is convenient to judge whether there is some correlation between the two variables, so I created a scatter plot, each point represents a player. . The retinal variable of scatter size is used as the visual coding of the sequenced data, and the size of the scatter indicates the hit rate or the full score. The color is used as the stereotype visual code, and the color of the scatter represents the case where the player uses the left and right hands. The horizontal and vertical coordinates are the height and weight of each player. On the layout, I made the title and canvas occupy the center of the page, and arranged the position of the button and the legend in the blank space to make the overall layout clear.<br>

2、Second draft<br>
  Changes were made based on feedback from the first draft. It is still a scatter plot. The horizontal and vertical coordinates are the height and weight of each player. The size of the scatter indicates the hit rate or the total score. The color of the scatter represents the situation where the player uses the left and right hands. The difference is that all players are not displayed at the same time. In the case of a button, you can click on the button to select the player data for each left-hand, right-hand or both hands, so that the page is no longer confusing.<br>

3、Final draft<br>
  Abandoning the practice of using the size of the circle to indicate the hit rate or the total score. The horizontal and vertical coordinates are the most important visual codes, so I put the hit rate or the full score on the ordinate so that the reader can clearly perceive the shot. The size of the rate or total score. The influence factor height and weight are placed on the abscissa, and the color of the scatter is used to represent the player's use of the left and right hands. Through such display, the influence of height, weight, left and right hands on the hit rate or the total score can be clearly seen.<br>

Feedback：
----
  For first draft:<br>
1、Putting all the things you want to show together, the visualization is very confusing, not very suitable, especially for newcomers who are just beginning to touch the web. The best way is to progressively express ideas or stories.<br>

  for second draft：<br>
1、The bubble chart should put the data that needs the most contrast on the horizontal and vertical coordinates. For the hit rate, the value of the hit rate is too small and the change is not obvious. The circle in the figure cannot compare the difference, and most of the scattered points are almost the same size. , indicating that the type of chart you choose is not necessarily the best<br>
2、Did not see the special relationship, I feel nothing to discover. Also did not understand the meaning of the color representation? ? I didn’t forget the left-hander’s right-hander’s thought, it’s best to mark it.<br>

Visualization Explanation:
----
There is no obvious correlation between the total score and the hitting rate as well as the baseball player's left and right hand usage, weight or height. The players' batting average is concentrated in [0.2, 0.3], and most of them are right-handed.<br>

References:
----
1、https://blog.csdn.net/npf_java/article/details/49185225  大量 D3.js 示例<br>
2、https://blog.csdn.net/u014711869/article/details/78789482/ 可视化工具–D3–基础图表的绘制（line）<br>
3、https://bl.ocks.org/mbostock/3887118<br>
4、https://bl.ocks.org/mbostock/4063269<br>
