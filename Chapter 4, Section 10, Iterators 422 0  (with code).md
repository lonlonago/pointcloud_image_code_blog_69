##  Python basics (a full set of nanny-level tutorials) 

###  Chapter IV 

![avatar]( b70a13623fe04b0cb8c6bb8a5a7f4721.png) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957455183
 ```  
Knowledge point (one-to-one correspondence with code): iterable in for variable: pass 

Iterable: iterable thing iterator: iterator str, list, tuple, dict, set, open () 

Iterable data types always provide something called an iterator. This iterator can help us get all the data in the data type one by one 

There are two ways to get the iterator: 1. iter () built-in function can directly get the iterator 2. iter () special method 

Getting data from an iterator: 1. next () built-in function 2. next () special method 

The iterator must be used in the for loop. So all non-iterable things cannot be used in the for loop. There must be __next__ in the for loop 

Summary: Iterators unify the work of traversing different data types 

The iterator itself is also iterable. The characteristics of the iterator itself: 1. It can only go forward and cannot be repeated. 2. Special memory saving. 3. Lazy mechanism 

