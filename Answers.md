## TODO also try with a LinkedList - does it make any difference?
Using a linked list did not necessarily make a difference in the way the program ran, the results were still the same.

## TODO what happens if you use list.remove(77)?
The method would throw an error, because list.remove(77) checks the index in a list, not the value itself. So it would be
running to find the index 77, which does not exist because the list is not that big.

## list.remove(5); // what does this method do?
Removes the list element stored at the specific index (in this case, 5) and returns the element that was removed.

## list.remove(Integer.valueOf(5)); // what does this one do?
Returns the integer object that has a value of 5 (not the index)

## which of the two lists performs better as the size increases?
A linked list seems to be more efficient for manipulating data however, whereas array lists are better for accessing data.
(See chart below)


## TESTING PERFORMANCE
	                  Test (at REPS = 1000000)
Size	              10	100	    1000	10000

addRemoveLinkedList	  53ms	56ms	65ms	54ms
addRemoveArrayList	  45ms	102ms	266ms	2s 433ms
ListAccessArrayList   51ms	26ms	30ms	49ms
ListAccessLinkedList  21ms	67ms	522ms	6s 574ms