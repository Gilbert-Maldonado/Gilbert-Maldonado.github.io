---
layout: post
title: Week Seven
---

**What did I do this week?**
We had a test in this class and the difficulty of the test was fair. We were given enough time and the problems tested on knowledge of iterators, types, and other things. We had I think ninety minutes for the test and the test was given on Canvas.

**What's in your way?**
Nothing is in my way at the moment! Since the test is over I am waiting for the next project to be posted so that way I can start on that early.

**What will you do next week?**
The third project came out so I plan to start working on it after Downing has gone over the project details in class. The project is called Allocator and after taking a quick look it seems to me that we may have to create functions such as allocate and deallocate. I'll be looking forward to this next project!

**Quick Tip**
Something I learned in my Number Theory class. (Let me know if I made a mistake) There is a systematic way of finding the remainder of a very huge number. Let's do 5^(561) mod 18 for example.

Start off by finding 561 in binary.


561 = 2 * 280 + 1

280 = 2 * 140 + 0

140 = 2 *  70 + 0

 70 = 2 *  35 + 0
 
 35 = 2 *  17 + 1
 
 17 = 2 *   8 + 1
 
  8 = 2 *   4 + 0
  
  4 = 2 *   2 + 0
  
  2 = 2 *   1 + 0
  
  1 = 2 *   0 + 1
  

So 561 (base 10) is 1000110001 (base 2)

Then we find the remainder of 5^(2^(n)) where n is the number of digits in the binary representation. So we get as follows:
(Note: the equal signs following are not equal signs but the congruent sign.)

5     = 5 (mod 18)

5^2   = 25 = 7 (mod 18)

5^4   = 7^2 = 49 = 13 (mod 18)

5^8   = 13^2 = 169 = 7 (mod 18)

5^16  = 7^2 = 49 = 13 (mod 18)

5^32  = 13^2 = 169 = 7 (mod 18)

5^64  = 7^2 = 49 = 13 (mod 18)

5^128 = 13^2 = 169 = 7 (mod 18)

5^256 = 7^2 = 49 = 13 (mod 18)

5^512 = 13^2 = 169 = 7 (mod 18)


So then we have,

5^561 = 5^(2^0 + 2^4 + 2^5 + 2^9)

      = 5 * 5^16 * 5^32 * 5^512
      
(Substituting in congruences)

      = 5 * 13 * 7 * 7 (mod 18) = 3185 which is congruent to 17 (mod 18)
      
So we have that 5^561 is congruent to 17 (mod 18)

(The remainder is 17)
