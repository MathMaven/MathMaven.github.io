---
layout: post
title: "20151002 - Count How Many Zeros"
date: 2015-10-02 13:37:35
categories: NumberTheory
author: Wyzdm
---
How many zeros are in all the numbers from 1 to 1000000?

### Solution <button>Show / Hide</button>

<solution>

<ol>
<li>First, take 1,000,000 out of the question. Just remember to add six zeros at the end. We are left with one through 999,999. Doing this problem by casework, there are five cases. The case number corresponds to the number of zeros that numbers in that case counts.</li><br/>

<li> <strong>Case one are all the numbers with one zero.</strong> The zero can go in five places. Take note that zeros can never go in the first place value of any number. The other place values each has nine choices, one through nine. So it's 1(Number of zeros in the case)*5(Number of ways the zeros can be put)*9^5(Number of ways the other numbers can be put in.)+4*9^4(5 digit numbers)+3*9^3+2*9^2+9.</li><br/>

<li><strong>Case two is with two zeros.</strong> So it's 2(5C2(10)*9^4+4C2(6)*9^3+3C2(3)*9^2+9).</li><br/>

<li><strong>Case three is with three zeros.</strong> So it's  3(5C3(10)*9^3+4C3(4)*9^2+9).</li><br/>
  
<li><strong>Case four are numbers with four zeros.</strong> So it's 4(5C4(5)*9^2+9).</li><br/>
  
<li><strong>Case five is with five zeros.</strong> So it's 5*9.</li><br/>

<li>Add all of them up plus the six from 1,000,000, you get <strong>488,895.</strong></li><br/>
</ol>
</p>
</solution>
