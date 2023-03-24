# IT314 Software Engineering
# Name: Kanpariya Chintan Manishbhai
# ID: 202001463

--> Github Repository and Tool:

Github Repository: https://github.com/anantkaushik/Data-Structures-and-Algorithms

Tool used: Pylint

--> Perform Static analysis and understand errors

  1. https://github.com/anantkaushik/Data-Structures-and-Algorithms/blob/master/Data-Structures/Graphs/bfs.py
 
Output:
  ![image](https://user-images.githubusercontent.com/75677485/227485569-f45a13ee-d23c-479f-b219-72c90ea9759e.png)
  
  
  2. https://github.com/anantkaushik/Data-Structures-and-Algorithms/blob/master/Data-Structures/Queue/queue.py
 
Output:
  ![image](https://user-images.githubusercontent.com/75677485/227486952-c3f53723-a10a-4784-a372-520facd9f628.png)
  
  
  3. https://github.com/anantkaushik/Data-Structures-and-Algorithms/blob/master/Data-Structures/Stack/stack.py
 
Output:
  ![image](https://user-images.githubusercontent.com/75677485/227488618-30e10ad9-f8c0-4d23-a491-1f321eeb980c.png)
  
  4. https://github.com/anantkaushik/Data-Structures-and-Algorithms/blob/master/Algorithms/Searching/linear-search.py
 
Output:
  ![image](https://user-images.githubusercontent.com/75677485/227489148-865b0339-232a-4a72-bd25-65ec74ac108b.png)
  
  
  5. https://github.com/anantkaushik/Data-Structures-and-Algorithms/blob/master/Algorithms/Sorting/selection-sort.py
 
Output:
  ![image](https://user-images.githubusercontent.com/75677485/227489843-a84211f4-6443-4c1b-ae91-86ffc2ca8878.png)


--> Understanding of the Errors occured in above codes:
  
  1. C0303: Trailing whitespace (trailing-whitespace)  
  Trailing whitespace can cause a number of issues, such as making code harder to read, causing unintended line wrapping, and causing problems with version control systems. Therefore, it's generally considered best practice to avoid trailing whitespace in code files.   
  To fix this error, we should remove any trailing whitespace in the affected lines. 
 
   ![image](https://user-images.githubusercontent.com/75677485/227493118-51d66f51-cfdb-4446-b60c-161e1a07e430.png)  
   
  2. C0114: Missing module docstring (missing-module-docstring)  
  This indicates that neither the modules nor the functions have a docstring given. The docstring functions as a kind of comment or text description that the compiler ignores but which aids in explaining the function's or module's intended use to others. Writing docstrings is a wise move.  
  In the below image we can see that it doesn't define what is use of this module.
  
  ![image](https://user-images.githubusercontent.com/75677485/227494319-56874c32-8b8d-4979-9894-cf513ae59b5b.png)


  3. R1705: Unnecessary "else" after "return", remove the "else" and de-indent the code inside it (no-else-return)  
  This warning message usually suggests that there is no need to use an "else" statement after a "return" statement. Since the function will already have returned a value, the code inside the "else" block will never be executed.  
  To fix this warning message, you should remove the "else" statement and de-indent the code inside it.  
  
  ![image](https://user-images.githubusercontent.com/75677485/227495137-cadd279c-56ee-4e78-96ea-826117a56f3c.png)

  
  4. C0301: Line too long (119/100) (line-too-long)  
  This warning message is indicating that a particular line of code is too long, exceeding the recommended length of 100 characters. This can make the code harder to read and understand. For better code One line shouldn't contains more than 100 characters.
  To fix this warning message, we can break the line of code into multiple lines.  
  
  ![image](https://user-images.githubusercontent.com/75677485/227496190-0dc93ec7-8637-40ad-92a4-d4bfc77b2bc9.png)   
  
  5. C0103: Method name "selectionSort" doesn't conform to snake_case naming style (invalid-name)  
  This warning message is indicating that the name of a method, "selectionSort" in this case, does not conform to the recommended snake_case naming convention for method names in Python. The snake_case naming convention suggests that method names should be all lowercase, with words separated by underscores. For example, "selection_sort" would be the appropriate naming convention for this method.  
  
  ![image](https://user-images.githubusercontent.com/75677485/227497178-d070f741-b970-46da-af1e-d211b2b20cfa.png)







  


