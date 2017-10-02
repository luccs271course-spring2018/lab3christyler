## TODO also try with a LinkedList - does it make any difference?
Using a linked list did not necessarily make a difference in the way the program ran, the results were still the same.
A linked list seems to be more efficient for manipulating data, whereas array lists are better for accessing data.

## TODO what happens if you use list.remove(77)?
Every value of 77 in the list would be removed and the index of each value would shift and adjust.



# TESTING
	                  Test
Size	              10	100	    1000	10000

addRemoveLinkedList	  53ms	56ms	65ms	54ms
addRemoveArrayList	  45ms	102ms	266ms	2s 433ms
ListAccessArrayList   51ms	26ms	30ms	49ms
ListAccessLinkedList  21ms	67ms	522ms	6s 574ms