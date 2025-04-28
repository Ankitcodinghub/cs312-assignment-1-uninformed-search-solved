# cs312-assignment-1-uninformed-search-solved
**TO GET THIS SOLUTION VISIT:** [CS312 Assignment 1-Uninformed Search Solved](https://www.ankitcodinghub.com/product/cs-312-artificial-intelligence-laboratory-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117802&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS312 Assignment 1-Uninformed Search Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
&nbsp;

Task 1: Uninformed Search

Teach Pacman how to intelligently find his food! The objective of this task is to simulate breadth-first search, depth-first search, and DFID in the state space. The state-space consists of an m x n grid. The start state is (0,0). The goal state is the position of (*) in the grid. The Pacman is allowed to move UP, DOWN, LEFT and RIGHT (except for boundary).

Compare the above search methods on two accounts:

1. Length of the path (from the initial state to the goal state) that each algorithm finds

2. Number of states explored (visited) during the search.

(The length of the path and the number of visited states are two different things). Also, analyzing whether or not the result depends on the order in which the neighbors of each node are added into the list should be done.

The format of the report can be as follows:

1. Pseudo Code for MoveGen() and GoalTest()

2. Results (include table, plots if applicable)

3. Dependence of results on the order of neighbors added

Input format:

&lt;ALGORITHM CODE&gt; // 0 for bfs, 1 for dfs, 2 for dfid

&lt;MAZE of m x n size&gt;

Output format:

&lt;Number of states explored&gt;

&lt;Length of path found&gt; &lt;Maze with path formed with 0s&gt;

Evaluation Criteria:

Correctness: 30

Report: 15

Code Quality: 5

Note

Sample Input 1: 0

+–+–+–+–+ |||

+ + + + + |||

+–+–+ +–+ |||

+ + +–+ +

|| *

+–+–+–+–+

Sample Output 1:

42

24

0–+–+–+–+ 00 |0000| |

+0 +0 +0 + + |0000 |0 |

+–+–+0 +–+

| |0000 |

+ + +–+0 +

| | 000

+–+–+–+–+

To test your solutions, you can generate more mazes from here. (Put the type of maze as text.)
