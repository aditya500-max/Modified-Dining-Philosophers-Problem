# Modified-Dining-Philosophers-Problem
README FILE:


Dining Philosophers Problem in OS is a classical synchronization problem in the operating system. 
With the presence of more than one process and limited resources in the system the synchronization problem arises.
 If one resource is shared between more than one process at the same time then it can lead to data inconsistency.


In the 1st part(A),
we just have to do basic implementation of dining philosophers with 5 philosophers and 
try to implement it in such a way to avoid deadlock
condition, for this we have to work for 2 methods=

a)using semaphores

b)using strict ordering of resources

The Dining Philosopher Problem states that K philosophers seated around a circular table with one chopstick between each pair of philosophers. 
There is one chopstick between each philosopher. 
A philosopher may eat if he can pick up the two chopsticks adjacent to him. 
One chopstick may be picked up by any one of its adjacent followers but not both. 

process P[i]

 while true do

   {  THINK;
      PICKUP(fork[i], fork[i+1 mod 5]);
      EAT;
      PUTDOWN(fork[i],fork[i+1 mod 5])
   }



xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx---------xxxxxxxx---------------------xxxxxxxxx--------------xxxxxxxxxxxxxxxxxxxxxxxxxxxxx-----------------------xxxxxxxxxxxxxxxxxxxxxxxxxx
