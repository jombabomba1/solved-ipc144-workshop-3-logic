Download Link: https://assignmentchef.com/product/solved-ipc144-workshop-3-logic
<br>
In this workshop, you will code a C-language program that analyzes data logically.

<h1><u>LEARNING OUTCOMES </u></h1>

Upon successful completion of this workshop, you will have demonstrated the abilities:

<ul>

 <li>to create a simple interactive program</li>

 <li>to code a decision using a selection construct</li>

 <li>to code repetitive logic using an iteration construct</li>

 <li>to nest a logical block within another logical block</li>

 <li>to describe to your instructor what you have learned in completing this workshop</li>

</ul>

<h2>IN-LAB:</h2>

Download or clone workshop 3 (<strong>WS03</strong>) from <strong><u>https://github.com/Seneca-144100/IPCWorkshops</u></strong>

Code a program in <strong>temps.c</strong> that does the following:

<ol>

 <li>Before the declaration of main define NUMS as 3: #define NUMS 3</li>

</ol>




<ol start="2">

 <li>Print the title of the application.</li>

</ol>




&gt;—=== IPC Temperature Analyzer ===—&lt;




<ol start="3">

 <li>Using a <strong><em>for loop</em></strong>, prompt the user to enter the high and low values for each of <strong><em>NUMS</em></strong> The values entered must be between -40 and 40, and high must be greater than low.</li>

</ol>




Print the following messages:

<strong>&gt;</strong><strong>Enter the high value for day 1: </strong><strong>&lt; (or day 2, or day 3) </strong>* Read the high value.

<strong> </strong>

<strong>&gt;</strong><strong>Enter the low value for day 1: </strong><strong>&lt; (or day 2, or day 3) </strong>* Read the low value.

<strong><u>IMPORTANT</u></strong>:  You may only declare <strong>two (2) int type variables</strong> for the <u>high</u> and <u>low</u> values

<ol start="4">

 <li>Use a nested while (or do-while) loop to analyze the results, high must be greater than low, high must be less than 41, low must be greater than -41</li>

</ol>




*If any entry is incorrect, prompt the user to enter again until the entries pass the tests:




&gt; Incorrect values, temperatures must be in the range -40 to 40, high must be greater than low. &lt;




Then prompt again for the high and low temperatures for the day.




<strong>OUTPUT EXAMPLE WITH ERRORS HANDLED</strong> <em>(use this data for submission)</em>

—=== IPC Temperature Analyzer ===—

Enter the high value for day 1: <strong>8</strong>

Enter the low value for day 1: <strong>-2</strong>




Enter the high value for day 2: <strong>41</strong>




Enter the low value for day 2: <strong>-4</strong>




Incorrect values, temperatures must be in the range -40 to 40, high must be greater than low.




Enter the high value for day 2: <strong>9</strong>

Enter the low value for day 2: <strong>-4</strong>

Enter the high value for day 3: <strong>5</strong>




Enter the low value for day 3: <strong>11 </strong>




Incorrect values, temperatures must be in the range -40 to 40, high must be greater than low.




Enter the high value for day 3: <strong>11</strong>




Enter the low value for day 3: <strong>5 </strong>




<strong>IN_LAB SUBMISSION: </strong>

To test and demonstrate execution of your program use the same data as the output example above.

If not on matrix already, upload your <strong>temps.c</strong> to your matrix account. Compile and run your code and make sure everything works properly.

Then run the following script from your account: (replace profname.proflastname with your professors Seneca userid and <u>replace</u> <strong>NAA</strong> with <u>your</u> section)

<strong> </strong>

<strong>~profname.proflastname/submit 144w3/NAA_lab &lt;ENTER&gt;  </strong>and follow the instructions.




<h1>Please Note</h1>

<ul>

 <li>A successful submission does not guarantee full credit for this workshop.</li>

 <li>If the professor is not satisfied with your implementation, your professor may ask you to resubmit. Resubmissions will attract a penalty.</li>

</ul>




<h2>AT_HOME:</h2>

After completing the in_lab section, upgrade temps.c to do the following:

<ul>

 <li>Process a 4-day period using a <u>single</u> change to your in_lab code</li>

 <li>Display the highest temperature, and on which day it occurred</li>

 <li>Display the lowest temperature, and on which day it occurred</li>

 <li>Calculate and display the mean LOW temperature for the 4-day period</li>

 <li>Calculate and display the mean HIGH temperature for the 4-day period</li>

 <li>Calculate and display the mean OVERALL temperature for the 4-day period</li>

</ul>




<strong><u>Hints</u></strong>:  In order to do the above, you will need to declare more variables.

<ul>

 <li>Accumulate the low and high temperatures <u>independently</u></li>

 <li>Calculate averages <u>after</u> all the totals are known</li>

</ul>




<strong>OUTPUT EXAMPLE</strong>

—=== IPC Temperature Analyzer ===—

Enter the high value for day 1: <strong>8</strong>




Enter the low value for day 1: <strong>-2</strong>




Enter the high value for day 2: <strong>9</strong>




Enter the low value for day 2: <strong>-4</strong>




Enter the high value for day 3: <strong>5</strong>




Enter the low value for day 3: <strong>11</strong>




Incorrect values, temperatures must be in the range -40 to 40, high must be greater than low.




Enter the high value for day 3: <strong>11</strong>




Enter the low value for day 3: <strong>5</strong>




Enter the high value for day 4: <strong>10</strong>




Enter the low value for day 4: <strong>3 </strong>




The average (mean) LOW temperature was: 0.50

The average (mean) HIGH temperature was: 9.50

The average (mean) temperature was: 5.00

The highest temperature was 11, on day 3

The lowest temperature was -4, on day 2

<strong> </strong>

<h2>AT-HOME REFLECTION</h2>

Please provide answers to the following in a text file named <strong>reflect.txt</strong>.

In three or more paragraphs, explain what you learned while doing this workshop.  In <u>addition</u> to what you have learned, <strong>y</strong><strong>our answer should <u>at least include the</u> <u>following</u></strong>:




<ul>

 <li>How did pseudo-coding the solution beforehand help with the coding part? If you didn’t use pseudo code (or prepare some kind of an outlined answer), think about your experience and either justify your method or explain why it may have been better to plan ahead.</li>

 <li>There are 3 types of iteration constructs. What ones did you use in your program, and why?</li>

 <li>Describe how you tested your solution and what debugging method you applied to find and correct errors?</li>

</ul>




<strong>Reflections will be graded on clarity of thought, correctness, grammar and spelling. </strong>

<strong> </strong>

<strong><u>Note</u></strong><strong>:  </strong>when completing the workshop reflection it is a violation of academic policy to cut and paste content from the course notes or any other published source, or to copy the work of another student.

<strong> </strong>

<strong>AT_HOME SUBMISSION:</strong> <strong> </strong>

To test and demonstrate execution of your program use the same data as the output example above… (8, -2, 9, -4, 5, 11, 11, 5, 10, 3)

If not on matrix already, upload your <strong>temps.c</strong><strong> and</strong> <strong>reflect.txt </strong>to your matrix account. Compile and run your code and make sure everything works properly.

Then run the following script from your account: (replace profname.proflastname with your professors Seneca userid and <u>replace</u> <strong>NAA</strong> with <u>your</u> section)

<strong>~profname.proflastname/submit 144w3/NAA_home &lt;ENTER&gt; </strong>and follow the instructions.

<h1>Please Note</h1>

<ul>

 <li>A successful submission does not guarantee full credit for this workshop.</li>

 <li>If the professor is not satisfied with your implementation, your professor may ask you to resubmit. Resubmissions will attract a penalty.</li>

</ul>