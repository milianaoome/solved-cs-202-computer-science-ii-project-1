Download Link: https://assignmentchef.com/product/solved-cs-202-computer-science-ii-project-1
<br>



<strong> </strong>




<strong>Objectives:  </strong>The two main objectives of this project is to test your ability to: a) use C++ I/O (console and file), and b) design, implement and test a solution to a given problem. In addition, a review of your knowledge of C-style strings and multi-dimensional arrays will be necessary. This project will also test your ability to create, compile and run a program in a Linux environment and establish your ability to upload your program and supporting documentation to WebCampus.




<strong>Description: </strong>

For this project you will write a program to: a) <strong>read-in</strong> the <strong>10 first names</strong> from a <strong>file</strong> (the file is a priori <u>known to have exactly 10</u> entries, of a <u>maximum length of 8 letters</u> each) into a <strong>twodimensional character array</strong>, b) <strong>output</strong> the names <strong>to the</strong> <strong>terminal </strong>with each one preceded by a

number indicating its<strong> original order</strong> in the list, c) <strong>sort</strong> the list of names, and then d) <strong>output the sorted</strong> names both <strong>to the terminal and to a file</strong>, again with each one preceded by its corresponding <strong>original order</strong> in the list. Although an example input file (Names.txt) is provided, for grading purposes your project will be tested against a file that we will supply but will not be provided to you beforehand. Our test file will be in the same format as the example input file.




<strong>The following minimum functionality and structure is required: </strong>

<ul>

 <li><strong>Ask the user</strong> for the input and output <strong>file names</strong>.</li>

 <li><strong>Read </strong>in the list of names from the desired <strong>input file</strong>.</li>

 <li><strong>Store</strong> the names list in a <strong>two-dimensional character array</strong></li>

</ul>

(Use character arrays (i.e., C-style) to hold your strings)

<ul>

 <li><strong>Print</strong> out the <strong>unsorted </strong>list of names to the<strong> terminal</strong>, preceded by their <strong>original order</strong> in the input file.</li>

 <li><strong>Sort </strong>the list of names alphabetically.</li>

 <li><strong>Print</strong> the list of <strong>sorted</strong> names to the <strong>terminal</strong>, preceded by their <strong>original order</strong> in the input file.</li>

 <li><strong>Write</strong> the list of <strong>sorted</strong> names to a different <strong>output file</strong> (e.g. SortedNames.txt), preceded by their <strong>original order</strong> in the input file.</li>

 <li>Write multiple functions.</li>

 <li>Write your own <strong>C-string copy</strong>, <strong>C-string compare</strong> (or other) functions as needed.</li>

</ul>

<strong>The following are a list of restrictions:  </strong>

<ul>

 <li>No usage of external libraries for C-string manipulation is allowed (e.g. &lt;cstring&gt; &lt;string.h&gt;), or any std::string libraries and data types.</li>

 <li>No libraries except &lt;iostream&gt; and &lt;fstream&gt; are allowed.</li>

 <li>No global variables or constants except: a) the fixed number of names, and b) the maximum C-string size.</li>

 <li>No usage of pointers or dynamic memory.</li>

</ul>







<strong>Example Input File </strong>(Names.txt) <strong>Contents:</strong> <strong> </strong>

Victor

Eve

Juliet

Hector

Danielle

Romeo

Oscar

June

Ares

Dannae




<strong> </strong>

<strong> </strong>

<strong>Example Output </strong>(to Terminal and/or File)<strong>:</strong> <strong> </strong>

Unsorted Data (Original Input Order and Name)

=============================

<ul>

 <li>Victor</li>

 <li>Eve</li>

 <li>Juliet</li>

 <li>Hector</li>

 <li>Danielle</li>

 <li>Romeo</li>

 <li>Oscar</li>

 <li>June 8 Ares</li>

</ul>

9 Dannae




Sorted Data (Original Input Order and Name)

===========================

8 Ares

4 Danielle

9 Dannae

1 Eve

3 Hector

2 Juliet

7 June

6 Oscar

5 Romeo 0 Victor  <strong>The completed project should have the following properties: </strong> Ø Written, compiled and tested using Linux.

<ul>

 <li>It must compile successfully using the g++ compiler on department machines. Instructions how to remotely connect to department machines are included in the Projects folder in WebCampus.</li>

 <li>The code must be commented and indented properly.</li>

</ul>

Header comments are required on all files and recommended for the rest of the program. Descriptions of functions commented properly.

<ul>

 <li>A one page (minimum) typed sheet documenting your code. This should include the overall purpose of the program, your design, problems (if any), and any changes you would make given more time.</li>

</ul>




<strong>Turn in:</strong> Compressed .cpp file and project documentation.










<strong>Submission Instructions: </strong>

<ul>

 <li>You will submit your work via WebCampus</li>

 <li>Name your code file proj1.cpp Ø If you have header file, name it proj1.h</li>

 <li>Compress your:

  <ol>

   <li>Source code</li>

   <li>Documentation</li>

  </ol></li>

</ul>

Do not include executable  Ø Name the compressed folder:

PA#_Lastname_Firstname.zip

([PA] stands for [ProjectAssignment], [#] is the Project number)  Example: PA1_Smith_John.zip























