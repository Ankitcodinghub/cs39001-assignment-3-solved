# cs39001-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CS39001 Assignment 3 Solved](https://www.ankitcodinghub.com/product/cs39001-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92926&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS39001 Assignment 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
AIM: To get proficient in handling arrays in MIPS, writing function subroutine in MIPS, allocating variables dynamically on the stack, passing parameters to functions by value, passing (local) arrays to functions by their addresses.

Question 1

Write a complete MIPS-32 program that –

<ol>
<li>Reads two 16-bit signed integers (encoded in 2’s complement form) with the prompt – “Enter first number:” and “Enter second number:”.</li>
<li>After the two input numbers are collected from the user, there should be sanity checking to ensure that they are within the proper numerical range.</li>
<li>Determine the product of these two numbers using the Booth’s Multi- plication Algorithm as depicted in Figure 1.</li>
</ol>
4. At the end of your program, print the calculated product with the message – “Product of the two numbers are: ”.

Your program should have a procedure call multiply booth, with the two in- put arguments available in registers $a0 and $a1, and the final product available in register $v0.

1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Question 2

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 1: Booth’s Algorithm

</div>
</div>
<div class="layoutArea">
<div class="column">
Write a complete MIPS-32 program that –

<ol>
<li>Reads an array of ten integers from the user (can also be negative). These numbers are collected from the input console using a loop and stored in the memory in an array called ‘array’. Do not store the numbers as scalars in ten different non-contiguous locations or in ten differ- ent registers.</li>
<li>Reads an integer ‘k’ with the prompt: “Enter the value of k: ”. Write a function named find k largest that finds the kth largest number in the above array. Your program should also check whether k &gt; n. In such case, your program should display proper error message.</li>
<li>Write a function named sort array in order to sort the input array before finding the kth largest number. You have to implement Algorithm 1 as given below to sort the array. Pass the address of the 1-D array and the required parameters while implementing the function. After sorting, print the sorted array on the console with a proper message.</li>
<li>Thereafter, print the kth largest number from the sorted array with suit- able messages.
2
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Algorithm 1 sort array (Sort the array denoted as A with n numbers)

<ol>
<li>1: &nbsp;forj=2ton</li>
<li>2: &nbsp;temp = A[j];</li>
<li>3: &nbsp;// Insert A[j] to the sorted
sequence A[1..j − 1]
</li>
<li>4: &nbsp;i = j − 1;</li>
<li>5: &nbsp;while i &gt; 0 and A[i] &gt; temp</li>
<li>6: &nbsp;A[i + 1] = A[i];</li>
<li>7: &nbsp;i = i − 1;</li>
<li>8: &nbsp;A[i + 1] = temp</li>
</ol>
Question 3

Write a complete MIPS-32 program that –

<ol>
<li>Prompts the user for four positive integers m, n, a r as “Enter four positive
integers m, n, a and r: ”.
</li>
<li>Allocates space for an m × n integer array A and an n × m integer array
B on the stack.
</li>
<li>Populates the array A in a row major fashion using a Geometric Progres-
sion (GP) series with initial value a and common ratio r.
</li>
<li>Print the elements of matrix A.</li>
<li>Computes the transpose matrix of the matrix A in the n × m matrix B.</li>
<li>Prints the elements of B finally.</li>
</ol>
Follow these implementation-level constraints while writing your code. Write the following functions:

<ol>
<li>“initStack” : Initialise the stack pointer ($sp) and frame pointer ($fp).</li>
<li>“pushToStack” : This function takes one argument as input (in $a0) and
push it to the stack.
</li>
<li>“mallocInStack” : This function allocates space for m × n (stored in $a0) memory locations (each of 4 bytes for each integer) in the stack and returns the first address ($v0).</li>
<li>“printMatrix” : This function takes three parameters- the positive integers m (in $a0), n (in $a1) and the address of a two-dimensional m × n integer array A (in $a2) storing the matrix in row major form. It prints the elements of A in a row major manner.</li>
<li>“transposeMatrix” : The function takes (positive) integers m and n and addresses of two integer arrays A and B. It is to compute the transpose matrix of the matrix A and store in the n × m matrix B.
3
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
If required, you can write additional functions as well, but with proper com- ments and descriptions.

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
