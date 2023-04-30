Download Link: https://assignmentchef.com/product/solved-csce221-homework-1
<br>
Write a C++ program to implement the Binary Search algorithm for searching a target element in a sorted vector. Your program should keep track of the number of comparisons used to find the target.

<ul>

 <li>To ensure the correctness of the algorithm the input data should be sorted in ascendingor descending order. An exception should be thrown when an input vector is unsorted.</li>

 <li>Test your program using vectors populated with consecutive (increasing or decreasing) integers in the ranges from 1 to powers of 2, that is, to these numbers:</li>

</ul>

1<em>, </em>2<em>, </em>4<em>, </em>8<em>, </em>16<em>, </em>32<em>, </em>64<em>, </em>128<em>, </em>256<em>, </em>512<em>, </em>1024<em>, </em>2048.

Select the target as the last integer in the vector.

<ul>

 <li>Tabulate the number of comparisons to find the target in each range.</li>

</ul>

I get the same number of comparisons for the increasing or decreasing values because I created two different binary search algorithms for the increasing or decreasing case.

<ul>

 <li>Plot the number of comparisons to find a target where the vector size <em>n </em>= 2<em><sup>k</sup></em>, <em>k </em>= 1<em>,</em>2<em>, . . . ,</em>11 in each increasing/decreasing case. You can use any graphical package (including a spreadsheet).</li>

</ul>




.

(a) Provide a mathematical formula/function which takes <em>n </em>as an argument, where <em>n </em>is the vector size and returns as its value the number of comparisons.Does your formula match the computed output for a given input? Justify your answer.How can you modify your formula/function if the largest number in a vector is not anexact power of two? Test your program using input in ranges from 1 to 2<em><sup>k </sup>−</em>1<em>, k </em>= 1<em>,</em>2<em>,</em>3<em>, . . . ,</em>11<em>.</em>

<ul>

 <li>Use Big-O asymptotic notation to classify this algorithm and justify your answer.</li>

 <li>Submit to CSNet an electronic copy of your code and results of all your experiments for grading.</li>

</ul>

<ol start="2">

 <li><strong>(R-4.7 p. 185)</strong> The number of operations executed by algorithms A and B is 8<em>n</em>log<em>n </em>and 2<em>n</em><sup>2</sup>, respectively. Determine <em>n</em><sub>0 </sub>such that A is better than B for <em>n ≥ n</em><sub>0</sub>.</li>

 <li><strong>(R-4.21 p. 186)</strong> Bill has an algorithm, <strong><em>find2D</em></strong>, to find an element <em>x </em>in an <em>n × n</em>array A. The algorithm <strong><em>find2D </em></strong>iterates over the rows of A, and calls the algorithm <strong><em>arrayFind</em></strong>, of code fragment 4.5, on each row, until <em>x </em>is found or it has searched all rows of A. What is the worst-case running time of <strong><em>find2D </em></strong>in terms of <em>n</em>? What is the worst-case running time of <strong><em>find2D </em></strong>in terms of <em>N</em>, where <em>N </em>is the total size of A? Would it be correct to say that<strong><em>find2D </em></strong>is a linear-time algorithm? Why or why not?</li>

</ol>




<ol start="2">

 <li><strong>(R-4.39 p. 188)</strong> Al and Bob are arguing about their algorithms.Al claims his <em>O</em>(<em>n</em>log<em>n</em>)time method is always faster than Bob’s O( <em>n</em><sup>2</sup>)-time method. To settle the issue, they perform a set of experiments. To Al’s dismay, they find that if <em>n &lt; </em>100, the O(<em>n</em><sup>2</sup>)-time algorithm runs faster, and only when <em>n ≥</em>100 then the O(<em>n</em>log<em>n</em>)-time one is better. Explain how this is possible.</li>

</ol>




<ol>

 <li>Find the running time functions for the algorithms below and write their classification using Big-O asymptotic notation. The running time function should provide a formula on the number of operations performed on the variabl<strong><em>e </em></strong><em>s<strong>.</strong></em></li>

</ol>