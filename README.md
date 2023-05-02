Download Link: https://assignmentchef.com/product/solved-comp2113-module6-self-review-exercise
<br>



<ol>

 <li>Write a single statement to accomplish each of following tasks:

  <ul>

   <li>Use a stream manipulator to ensure that floating-point values print in scientific notation for when using cout​ ​.</li>

   <li>Use a stream manipulator to set the fill character to ‘*’​ ​ for printing in field widths larger than the values being output using cout​   ​.</li>

   <li>Print 6789​ ​ right justified in an 8-digit field.</li>

  </ul></li>

</ol>




<ol start="2">

 <li>Write a C++ statement that uses the manipulator setfill​ ​ to output a line containing 40</li>

</ol>

pound signs, i.e., “########################################​ ​”.




<ol start="3">

 <li>Identify error(s), if any, in the following array declarations. If a statement is incorrect, provide the correct statement.

  <ul>

   <li>double weights[100];</li>

   <li>int age[0..80];</li>

   <li>int100 list[];</li>

   <li>double[50] salaries;</li>

  </ul></li>

</ol>




<ol start="4">

 <li>Correct the following code so that it correctly sets the value of each element of myList​ ​ to the index of the element.</li>

</ol>




int myList[10];

for (int i = 1; i &lt;= 10; i–) myList[i] = [i];




<ol start="5">

 <li>What is stored in list​ ​ after the following C++ code executes?</li>

</ol>




int list[10];

list[0] = 2; list[1] = 3;

for (int i = 2; i &lt; 10; i++)

{ list[i] = list[i – 1] + list[i – 2];  if (i &gt; 7) list[i] = 2 * list[i] – list[i – 2];

}

<ol start="6">

 <li>Determine whether the following array declarations are valid. If a declaration is valid, determine the size of the array.

  <ul>

   <li>int list[] = {18, 13, 14, 16};</li>

   <li>int x[10] = {1,7,5,3,2,8};</li>

   <li>double y[4] = { 2.0, 5.0, 8.0, 11.0, 14.0} ;</li>

   <li>int list[7] = {12, 13, , 14, 16, , 8};</li>

  </ul></li>

</ol>




<ol start="7">

 <li>Write a single statement for each of the following one-dimensional array operations:

  <ul>

   <li>Initialize the 10 elements of integer array counts​ ​ to zero.</li>

   <li>Add 1 to each of the 15 elements of the integer array bonus​ ​.</li>

   <li>Read 12 values for double​ ​ array scores​  ​ from the keyboard.</li>

  </ul></li>

</ol>

<ol start="8">

 <li>Write a code segment that finds the minimum and maximum values contained in a</li>

</ol>

99-element double​ ​ array w​ ​.




<ol start="9">

 <li>Write a code segment that finds the minimum and maximum values contained in a 4-by-6 int​ array t​ ​. (The declaration for t​ ​ is int t[4][6];​   ​)</li>

</ol>




10.Consider the following C++ code:




string str1; string str2; char ch; int index; cin &gt;&gt; str1; cin &gt;&gt; str2; cin &gt;&gt; index; ch = str1[index]; str1[index] = str2[index]; str2[index] = ch;

cout &lt;&lt; str1 &lt;&lt; ” ” &lt;&lt; str2 &lt;&lt; endl;




Answer the following questions:

<ul>

 <li>What is the output if the input is Hello There 2​ ​?</li>

 <li>What is the output if the input is Diamond Gold 0​ ​?</li>

 <li>What is the output if the input is C++ Java 1​ ​?</li>

</ul>




11.What is the output of the following C++ code?




string str1 = “Trip to Hawaii”; string str2 = “Summer or Fall”; string newStr;

newStr = str2 + ‘ ‘ + str1;

cout &lt;&lt; newStr &lt;&lt; endl;

cout &lt;&lt; str1 + ” in ” + str2 &lt;&lt; endl; cout &lt;&lt; newStr.length() &lt;&lt; endl; cout &lt;&lt; str1.find(‘H’) &lt;&lt; endl; cout &lt;&lt; str2.find(“or”) &lt;&lt; endl; cout &lt;&lt; newStr.substr(10, 19) &lt;&lt; endl;

cout &lt;&lt; newStr.replace(23, 6, “******”) &lt;&lt; endl;

string str = “C++ Programming”; cout &lt;&lt; str &lt;&lt; endl;

cout &lt;&lt; str.length() &lt;&lt; endl;

str[0] = ‘J’;

str[2] = ‘$’;




cout &lt;&lt; str &lt;&lt; endl;




12.Find the error(s) in each of the following, and explain how to correct it (them):

<ul>

 <li>string string1( 28 ); // construct string1</li>

 <li>string string2( ‘z’ ); // construct string2</li>

</ul>