
## Round 1
1. What is the time complexity of the algorithm 

F(n) {
  if (n >= 1) {
    F(n/2)
    F(n/2)
  }
}

2. Given below pyramid in the form of List<List<Integer>>. Return minPathSum from root to leaf node. 
  
     2
    3  4
   2  1  3
  5  7  6  2
  
 3. Design a game of chess
 
 ## Round 2
 
 1. In a distributed system where cache resider with each application server. How will you invalidate the cache. 
 2. Given a 2D matrix which is row and col wise sorted. Search for a element in it. 
 3. Puzzle - You are blind folded in a dark room. This room consist of N disks, N can be very large number. Each disk has one side as Red and other side as Green. Now in room there are 15 disks with Red side as up and remaining have green side up. You have to divide all disks in two sets such that both set will contain equal number of Red Disks. 
 
 ## Round 3
 
 1. Design a dependency resolver and task executor framework. Write full code of the application.  
 2. Extend the system in distributed scenario. 
 3. How will you design a system will low latency and high availability.
 
 ##  Round 4
 1. Design a image compression service. 
 2. Write a skip iterator such that it consists of following method.
    - skip(value of element)
    - hasNext() -> checks if still has elements to iterate - it has to skip elements being marked for skip and check if list reached to end. 
    - next() - return to the next element. 
