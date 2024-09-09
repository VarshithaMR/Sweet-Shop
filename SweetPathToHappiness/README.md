# Problem Statement

Manu has n number of candies, with each candy having some sweetness factor. Manu has a sweet tooth and wants to maximise the sweetness he can get from the candies. The problem is, if Manu chooses a candy with a sweetness factor value of x, he can not have the candies with a sweetness factor value of x+1 and x-1.
Given an array of values denoting sweetness factors of candies, help Manu figure out the maximum sweetness he can get by choosing any number of candies.
Note : Manu can pick candy one by one

Input Format:
   Input contains an array of space separated integers (keep reading integers till you get value in input)

Output Format:
    Print the maximum sweetness he can acheived

Input: candies = [3,4,2]
Output: 6
Explanation: You can do the following:
- Eat candy with the sweetness factor of 4 to get 4 sweetness. Consequently, candy with the sweetness factor of 3 can not be eaten.
  candies = [2].
- Eat candy with the sweetness factor of 2 to get 2 sweetness. candies= [].
- You earn a total sweetness of 6.
  

Input: candies = [2,2,3,3,3,41
Output: 9
Explanation: You can do the following:
- Eat candy with sweetness factor of 3 to get 3 sweetness. All candies with sweetness factor 2's and 4's can not be eaten.
  candies = [3,3].
- Eat candy with the sweetness factor as
  3 to get 3 sweetness. candies = [3].
- Eat candy with the sweetness factor as
  3 to get 3 sweetness. candies = [].
  You earn a total sweetness of 9.
  
Constraints:
  1 <= total number of candies <= 2 * 10^4
  1 <= sweetness factor of a candy <= 10^4