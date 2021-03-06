# <strong>Sorted Array</strong>
* ## Project Summary:
  An Assembly program that takes array of numbers from the user, sorts it with one of the three simple algorithms: Bubble Sort, Selection Sort, Insertion Sort (depending on the user desire) and prints the sorted array.
  
* * *
  
* ## Project Advantages:
	* Three types of sorting algorithms.
	* Choosing the method of sorting is based on the user desire.
	* The number of values is variable and determined by the user.
	* Handling for inputs such that the user can only enters integers.
	* The numbers can be sorted ascending or descending.

* * *

* ## Project Contributers:
	|Name|Role|Branch|
    |:---|:--:|:----:|
    |1. Mostafa Mahmoud Mostafa|Handling Input validation and representation|Input_branch|
    |2. Mohamed Ali Mohamed|Creating Bubble sort algorithm|Bubble_Sort|
    |3. Mohamed Hani Abo Elela|Creating Insertion Sort algorithm|Insertion_Sort|
    |4. Mahmoud Mohamed Abdelwahab|Creating Selection sort algorithm|selection_sort|
    |5. Mina Ashraf Fakhry|Handling  output after Sorting|master|
    
* * *

	
* ## Project Language:
	<p>Assembly Programming Language.</p> 	

* * *

* ## Project Description:
  <p>This project is a program takes a set of numbers from user to sort them ascending or descending based upon 
  the desire of the user. firstly the program asks the user to enter the number of elements, then the program
  asks him to enter the values of numbers. then the program asks the user to choose the sorting method because 
  the program supports three ways of sorting (Bubble Sort - Selection Sort - Insertion Sort).</p>
  
	* ### Bubble Sort Algorithm:
		* #### Idea:
			it works by repeatedly swapping the adjacent elements if they are in wrong order.
	
			![image](https://user-images.githubusercontent.com/76550923/103942137-95500580-5138-11eb-9338-bfe50df77a2e.png)
    
    	* #### Example: 
			![image](https://user-images.githubusercontent.com/76550923/103942433-0bed0300-5139-11eb-8a22-2ca20e19e3a6.png)
	
			![image](https://user-images.githubusercontent.com/76550923/103942498-27f0a480-5139-11eb-8b10-96c1310b3d56.png)
	
			![image](https://user-images.githubusercontent.com/76550923/103942592-50789e80-5139-11eb-99c6-74233562056c.png)
	
			![image](https://user-images.githubusercontent.com/76550923/103942619-59697000-5139-11eb-9e59-91ffe6db5a8f.png)
	
		* #### Java Code for the Bubble Sort algorithm:
			![Bubble sort](https://user-images.githubusercontent.com/76550923/104127750-8c477a00-536c-11eb-9e49-bce59785f560.JPG)
            
       * #### Time Complexity: 
			Time Complexity is O(n^2).
            
	* * *
    
	* ### Selection Sort Algorithm:
		* #### Idea:
	   		sorts an array by repeatedly finding the maximum element (considering ascending order) from unsorted part and putting it at the ending.

		* #### Example:
	
	   		![1](https://user-images.githubusercontent.com/47304558/104108466-7fc01480-52cd-11eb-9a38-d81ca8e23187.jpg)
	   
	    * #### Java Code for the algorithm:
	    
        	![code](https://user-images.githubusercontent.com/47304558/104109350-9e2a0e00-52d5-11eb-9926-911f4d78ad42.jpg)
            
        * #### Time Complexity: 
			Time Complexity is O(n^2).

	* * *
        
	* ### Insertion Sort Algorithm:
    	* #### Idea:
			In this sorting technique, we pick an element and then insert it in the appropriate position in ascending or descending order.

		* #### Example:
		
			![1](https://user-images.githubusercontent.com/48108210/104019934-1228c100-51c5-11eb-88bc-af0c4a9e2335.png)
		
			In pass 1, element arr[1] is inserted before arr[0], so that arr[0] and arr[1] are sorted.

			![2](https://user-images.githubusercontent.com/48108210/104020179-79467580-51c5-11eb-90e3-84c673ea73b3.png)
	
			In pass 2, element arr[2] is inserted before arr[0] or between arr[0] and arr[1] or after arr[1], 
		so that arr[0], arr[1] and arr[2] are sorted.

			![3](https://user-images.githubusercontent.com/48108210/104020414-dcd0a300-51c5-11eb-9e50-a1af15db08c1.png)
	
			![4](https://user-images.githubusercontent.com/48108210/104020591-202b1180-51c6-11eb-86fd-d410ed00bade.png)
	
			In a similar way the process is carried out n-1 times.

		* #### Java Code for the algorithm:

			![javacode](https://user-images.githubusercontent.com/48108210/104022566-22429f80-51c9-11eb-8917-b7d2a8647cbb.png)
            
		* #### Time Complexity: 
			Time Complexity is O(n^2).

* * *

* ## Project Testing:

	This is a video for testing the Project:

	[![Sorting Algorithm Project](https://img.youtube.com/vi/qIkmc0TuBUs/0.jpg)](https://www.youtube.com/watch?v=qIkmc0TuBUs)

* * *

* ## Project Tools:
	* Visual studio IDE.
	* MASM.

* * *

* ## External Library:
	* Irvine32.lib

* * *

* ## Project References: 
	* #### Playlists:
		* Learning git and github: https://www.youtube.com/watch?v=ACOiGZoqC8w&list=PLDoPjvoNmBAw4eOj58MZPakHjaO3frVMF.
	* #### Books:  
		* prentice_the_intel_microprocessors_8th_edition_013.                      
		* Assembly language for Intel-based computers by Kip R. Irvine.   
* * *

* ## Issues:
	* Irvine32 library handles input using function called ReadInt and in this function he takes the input as string then calls for another function called ParseInteger32 in this function he takes each digit as token so he takes the longest decimal number possible from the string and if the length of input string is 0 he assigns the EAX register with 0.

	* So if the user presses Enter in an input that accepts 0 as input i am forced to take it as valid input.
	* When the input is partially valid as the number has character in it Irvine gives me the longest valid number as previously stated and again i am forced to take the input as valid input.

