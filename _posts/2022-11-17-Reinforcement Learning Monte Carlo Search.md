Explanation of Monte Carlo Tree Search Algorithm
https://www.youtube.com/watch?v=UXW2yZndl7U&ab_channel=JohnLevine
1) Tree Traversal

  N is the visits number of parent
  
  n is the visits number of child
  
  thus n and V will keep balance of exploration and expectation

2) Node Expansion

  If this node has been visited before, just return its value. Or else expand from this node.

3) Roll out

  Return value up to the parents. 
  The T is the sum of all values and N is the visit number. T/N is the average value.
  This is monte carlo method for average value.

This tree can be viewed as a model, which will produce data based on real data.


![image](https://user-images.githubusercontent.com/23403286/202428273-387de1ed-ab6a-44e5-8c99-3a60655a41c0.png)


![image](https://user-images.githubusercontent.com/23403286/202428388-5a565636-0044-4ab5-aa63-69e570fc6647.png)


![image](https://user-images.githubusercontent.com/23403286/202428535-83acc494-583e-4e8d-b426-31c45025880a.png)


![image](https://user-images.githubusercontent.com/23403286/202428617-7a8705a8-bace-41ba-a61d-27dfb1fcfc71.png)
