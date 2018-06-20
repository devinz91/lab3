**TestList Class**

Q: list.remove(5); // what does this method do?
Removes object at position 5 and moves the remaining elements down one index
Q: list.remove(Integer.valueOf(5)); // what does this one do?
Removes integer 5 at the index it recedes.  

**TestList Class**

Q: i.remove(); // TODO what happens if you use list.remove(77)?
The test would fail since it would try to remove an object at index 77 

**TestPerformance Class**

// which of the two lists performs better as the size increases?

I noticed that the an ArrayList performs better. 

ArrayList

SIZE 10000 - 1.897 seconds

LinkedList

SIZE

10000 - 5.229 seconds



