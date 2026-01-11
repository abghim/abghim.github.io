---
layout: post
title: An Interesting Thought Experiment On Infinite Geometric Series
---
I want to introduce an interesting problem that gives rise to an important idea in mathematics. It is, actually, a common problem in middle school physics and mathematics.<!--more--->

Consider a messenger running back and forth between two armies advancing towards each other. The two armies are 10 kilometers apart, and they advance at the constant speed of 2 km/h. The messenger moves between the two armies at the constant speed of 10 km/h. We will calculate the total time \\(T\\) the messenger travels.

On the messenger's first trip, she and the army on the opposite side approach each other at the speed of \\(2+10=12\\) km/h. Because they have 10 kilometers between them, the first trip takes \\(10/12=\frac{5}{6}\\) hours. On her second trip, this time changing direction, she again approaches the other army at 12 km/h. But on this trip, she has only \\(\frac{20}{3}\\) km/h to cover! Her travel time is thus \\(\frac{5}{9}\\).

Continuing in this manner, the total travel time \\(T\\) is \\[T=\frac{5}{6}(1+\frac{2}{3}+\frac{2^2}{3^2}+\frac{2^3}{3^3}+...)\\]

But from the two armies' perspective, the total travel time is simply the time it takes for the two armies to meet. Because the two approach each other at the speed of \\(2+2=4\\) km/h, \\[T=10/4=\frac{5}{2}\\]

Then, is \\(T=\frac{5}{6}(1+\frac{2}{3}+\frac{2^2}{3^2}+\frac{2^3}{3^3}+...)= \frac{5}{2}\\)? Yes! The infinite geometric series formula shows that the left hand side is indeed \\(\frac{5}{6} \times \frac{1}{1-2/3} = \frac{5}{2}\\).