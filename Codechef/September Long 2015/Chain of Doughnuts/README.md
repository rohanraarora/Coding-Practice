#Chain of Doughnuts

There is new delicious item in Chef's menu - a doughnut chain. Doughnuts connected successively in line forming a chain.

_Chain of 3 doughnuts_

Chef has received an urgent order for making a chain of **N** doughnuts. He noticed that there are exactly**N** cooked doughnuts in the kitchen, some of which are already connected in chains. The only thing he needs to do is connect them in one chain.

He can cut one doughnut (from any position in a chain) into two halves and then use this cut doughnut to link two different chains.  
Help Chef determine the minimum number of cuts needed to complete the order.

#### Input

- The first line of the input contains an integer **T** denoting the number of test cases.
- The first line of each test case contains two integer **N** and **M** denoting the size of order and number of cooked chains respectively.
- The second line contains **M** space-separated integers **A

1**, **A

2**, ..., **A

M** denoting the size of the chains.

_It is guaranteed that **N** is equal to the sum of all **A

i**'s over **1&lt;=_i_&lt;=M**._

#### Output

For each test case, output a single line containing an integer corresponding to the number of cuts needed Chef to make the order.

#### Constraints and Subtasks

- **1** ≤ **T** ≤ **200**
- **1** ≤ **N** ≤ **2*10

9**
- **1** ≤ **A

i** ≤ **10

5**

**Subtask 1: 10 points**

- **1** ≤ **M** ≤ **2*10

4**
- **A

i = 1**

**Subtask 2: 30 points**

- **1** ≤ **M** ≤ **100**

**Subtask 3: 60 points**

- **1** ≤ **M** ≤ **2*10

4**

#### Example

**Input:**
2
11 3
4 3 4
6 3
3 2 1

**Output:**
2
1

#### Explanation

**Example 1:** We could cut 2 doughnut from any "chain" and use them to connect chains to the one.   
For example, let's cut it from the first chain. After this we will have chains of sizes 2, 3, 4 and two doughnuts that have been cut. So we could connect the first chain with second and second with third using these two doughnuts.

**Example 2:** We cut doughnut from the last "chain" and connect the first two chains.

_Image for second example. Yellow doughnut has been cut._