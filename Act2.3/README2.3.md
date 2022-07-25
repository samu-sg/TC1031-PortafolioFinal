### Act 2.3
1. Open the input file called "bitacora.txt", read it and store the data in a Doubly Linked List.  
Create a data structure (class) to store all the fields of the file.
2. It sorts the information in ascending order by date and time (including hours, minutes and seconds) for carrying out searches.  
Implement a Sort method for your Doubly Linked List based on the Merge Sort algorithm.
3. Ask the user for the start and end dates of the information search (the interval must be closed, i.e., include the values
that delimit it), clearly indicating the format required by your program (ex. Jun 01 00:22:36).  
Use the binary search algorithm to first find the start date of the range and then the end date of the range selected for the query.  
Verify that both dates are in the log, in case one of them is not, inform the user.
4. It stores in a file called "search_result.txt" the records corresponding to the search range and displays them on the screen.
5. Store in a file called "bitacora_ordenada.txt" the result of the ordering algorithm executed on the log.
6. 3 test cases are provided for you to verify your implementation: TestCasesAct1.3.zip Download TestCasesAct1.3.zip

Search for information and reflect, individually, on the importance and efficiency of the use of different linear data structures 
in a problem situation of this nature. Reflect on why in solving this challenge it is preferable to use a Doubly Linked List and not a Linked List.
Analyze the computational complexity of the basic operations of the data structure used in your implementation (insert, delete, search) and how this 
impacts the performance of your solution. Generates a document called "ReflexAct2.3.pdf".
