# Most Profit Assigning Work LeetCode

LeetCode Q # 826.

You have n jobs and m workers. You are given three arrays: difficulty, profit, and worker where: difficulty[i] and profit[i] are the difficulty and the profit of the ith job, and worker[j] is the ability of jth worker (i.e., the jth worker can only complete a job with difficulty at most worker[j]). Every worker can be assigned at most one job, but one job can be completed multiple times.

For example, if three workers attempt the same job that pays $1, then the total profit will be $3. If a worker cannot complete any job, their profit is $0.</br>
Return the maximum profit we can achieve after assigning the workers to the jobs.

Example 1:

>Input: difficulty = [2,4,6,8,10], profit = [10,20,30,40,50], worker = [4,5,6,7]</br>
>Output: 100</br>
>Explanation: Workers are assigned jobs of difficulty [4,4,6,6] and they get a profit of [20,20,30,30] separately.

Example 2:

>Input: difficulty = [85,47,57], profit = [24,66,99], worker = [40,25,25]</br>
>Output: 0

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/xo-azeem/Most-Profit-Assigning-Work-LeetCode/assets/171427226/608e3f21-3719-4fd4-bcad-4dc284cfc53f)

  Time complexity: O(n log n).</br>Space complexity: O(n).
</div>
