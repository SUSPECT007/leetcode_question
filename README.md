# leetcode_question

ou are given two linked lists: list1 and list2 of sizes n and m respectively.

Remove list1's nodes from the ath node to the bth node, and put list2 in their place.

The blue edges and nodes in the following figure indicate the result:

![image](https://github.com/SUSPECT007/leetcode_question-solution/assets/103315098/efdae691-1182-4e37-8b39-b6168c7a0bfa)



Build the result list and return its head.



-


 

Example 1:

![image](https://github.com/SUSPECT007/leetcode_question-solution/assets/103315098/47a107b8-840d-40a2-84fd-6a576b8ed2c1)



Input: list1 = [10,1,13,6,9,5], a = 3, b = 4, list2 = [1000000,1000001,1000002]

Output: [10,1,13,1000000,1000001,1000002,5]

Explanation: We remove the nodes 3 and 4 and put the entire list2 in their place. The blue edges and nodes in the above figure indicate the result.



Example 2:


![image](https://github.com/SUSPECT007/leetcode_question-solution/assets/103315098/751fe803-f38a-4175-9560-d146c617f191)



Input: list1 = [0,1,2,3,4,5,6], a = 2, b = 5, list2 = [1000000,1000001,1000002,1000003,1000004]

Output: [0,1,1000000,1000001,1000002,1000003,1000004,6]

Explanation: The blue edges and nodes in the above figure indicate the result.




-



 

Constraints:

3 <= list1.length <= 104

1 <= a <= b < list1.length - 1

1 <= list2.length <= 104

https://leetcode.com/problems/merge-in-between-linked-lists/description/?envType=daily-question&envId=2024-03-20


solve leetcode diary
__
