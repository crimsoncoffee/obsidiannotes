[[A Common-Sense Guide to Data Structures and Algorithms Level Up Your Core Programming Skills (Jay Wengrow.pdf]]

- Reading
	- contiguous set of empty cells for use in the program.
	- Since memory addresses are sequential a whenever a array is defined using the above. Just like raising the index finger when asked one does it instantly without going through all the index fingers in order to search which one is the index finger and then raise it. In the same vain, the computer when asked to raise read the value of the data at memory address *1044* it directly reads it and ones the array is defined all it has to do is add the index number we seek to the memory address which are sequential to achieve this.  Single step. There are 3 steps here adding to index number to the memory address of the first item of the array. And also remembering the memory address of the first array.
	- And once the list is sorted or something that process takes places again.
	
- Searching
	- inverse of the reading to find at what index is the some item in the array.
	- immediate access to all the memory address and their values but not the other way which values have what memory addresses and consequently indexes associated with them
	- For an array of size N. It will at the max take N **steps** to find the desired value's index and hence the memory address.
- Insertion
	- Since the computer allocates the contiguous memory addresses and remembers the address of the first element in the array and the and the length of the array. If the instruction is to insert at the end of the array then it will automatically. Then to get to last array that would be adding len-1 to the memory address and then inserting in the next memory address.
	- but the moment you introduce something as in between the array. The memory addresses are already pre-occupied and what you consequently adding additional steps in reassigning memory address for every including and after the index that you want to insert. Because the arrays were contiguous with
	- computer always keeps track of the array’s size.
	- **worst case scenario** is when we are inserting at the beginning of the array that will take N steps for reallocation of the memory addresses and 1 step for the same for the new date for a **N** element array
		- N  + 1
	- Operations that use this
- Deletion
	- In similar vain to insertion the number of steps that will take will be dependent on the where a deletion is happening.

[[A Common-Sense Guide to Data Structures and Algorithms Level Up Your Core Programming Skills (Jay Wengrow.pdf#page=36&selection=27,0,27,45|A Common-Sense Guide to Data Structures and Algorithms Level Up Your Core Programming Skills (Jay Wengrow, p.15]]
     