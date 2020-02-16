# Google Hash Code 2020 
 1,505,004,548 points.
 <img src="https://i.imgur.com/2udMoQ6.png"/>


## The solution
Here is our input slices: 2 5 6 8
<img src="https://i.imgur.com/sJm63LL.png"/>
- [x] Out target number of slices is 17.
Let's create our combination!
1. Let's start from the end. 8.
2. 8 is equal to 17? No. It's not even close.
3. Let's add previous number which is 6 to our 8. 6 + 8.
* 14 is equal to 17? No. But close.
4. Let's add 5 to 14. 19. Excessive!
* Now, Let's skip 5 and work with 2. 2 + 14 = 16.
* close, right? Do you have any combination which sum is closer? I guess, no!

Basically, it's what we do. Summing if more than enough skiping it!


## Problems | Disadvantages of this algroithm
Assume that we have to find for 15 not 16.
1. 8
2. 8 + 6 = 14 Will stop here since adding following numbers will not give us our desired result.

Here, if it will skip 6, we can get 8 + 5 which is 13 and then 13 + 2 = 15.
This is why we can't call this alrorithm "ideal"!


## Why C++
By comparing `computation time` C++ is the fastest language.
