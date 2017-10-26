#Why does FixedArrayQueue require an explicit constructor?

-It needs a contructor because size and capacity need to be defined before anything can be done to it. 

#What happens when you offer an item to a full FixedArrayQueue?

-It would return false because there would not be any room for that particular item.

#What happens when you poll an empty FixedArrayQueue?

-poll means to remove. If you try to poll an empty fixed array, it would be a "null" value because there's nothing there. 

#What is the time and (extra) space complexity of each of the FixedArrayQueue methods?

-offer: O(1)
-peek: O(1)
-poll: O(1)
-isEmpty: O(1)
-asList: O(n)
