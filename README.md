17-8-21 Session 1
Problem
Search for a particular date in  a calendar
e.g. 17th August 2021

Approach 1 Linear Search
Search for the date by going page per page starting from 1st January
Complexity O(N)
Pseudocode
1 for each date in calendar
2   if date is 17 Aug
3   call date
4 else date + 1 day
5   go back to line 2
6 end

Approach 2 Binary Search
1 Pick up calendar
2 open middle of cal.
3 look at cal.
4 if 17 aug on page
5   call date
6 else if 17 aug is earlier in cal.(366)
7   open mid early half
8   go back to line 3
9 else if 17 aug is later in cal.
10  open mid later half
11  go back to line 3
12 else
13 quit

[Session1.pdf](https://github.com/Vein7900/Session-1/files/6999833/Session1.pdf)

