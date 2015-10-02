---
layout: post
title:  "20150924 - Throwing Coconuts"
date:   2015-09-24 18:52:55
categories: NumberTheory
---
 
There is a huge pile of coconuts on the beach, totally 1000 coconuts. A monkey, who has nothing better to do, picks up one of the coconuts and throws it into the ocean, and divides the remaining coconuts into two piles. Then it chooses one of the piles, throws one coconut from the pile to the ocean, and divides the remaining ones in the pile into two piles. The monkey continues: at each step, it chooses one of the piles with at least 3 coconuts, throws one of the coconuts into the ocean, and divide the remaining ones in the pile into two smaller piles, not necessarily equal in size. Question: is it possible to reach a situation that each of the piles on the beach contains exactly 3 coconuts?




### Solution <button>Show/Hide</button> 

<solution>

Solution One: Backtracking.  Assume the scenario of 3 coconuts per pile is reached.  One step before that, two piles are combined and one coconut is taken out of the ocean to form a 7-coconut pile.  Backtrack another step, either combine two 3-coconut piles or combine one pile of 3 and one pile of 7, then take back one coconut from the ocean, and a 7-coconut pile or a 11-coconut pile is formed. We can find the following pattern: no matter how the piles are combined, the number of coconuts in each pile always has a remainder 3 when divided by 4. If we keep backtracking to the beginning, the original pile of 1000 should also have a remainder 3 when divided by 4.  But this is obviously false, therefore the conclusion is "not possible".
<br> <Br>
Solution Two: The Method of Invariant. We look for a quantity that does not change during the whole process. At each step, one coconut is thrown away, and one pile is split into 2, so the number of coconuts decreases by 1 but the number of piles is increased by 1.  Thus the sum of the number of coconuts and the number of piles is unchanged (invariant). At the beginning, there are 1000 coconuts, in 1 pile, so the sum is 1001, and this number will never change. Assume the situation where each pile have 3 coconuts is reached. Let there be N piles, then the total number of coconuts plus the number of piles equals 3N+N=4N, which is a multiple of 4. But this number is supposed to equal 1001, which is NOT a multiple of 4, contradiction. Therefore the final answer is "not possible."

</solution>

