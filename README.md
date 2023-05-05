Download Link: https://assignmentchef.com/product/solved-cse1321-assignment4-methods
<br>



<strong><u>Program 1:</u></strong> Design (pseudocode) and implement (source code) a program (name it MyRectangle) that defines the following 3 methods:

Method isValid() returns true if the sum of the width and height is <u>greater than</u> 30

Method Area() returns the area of the rectangle if it is a valid rectangle

Method Perimeter() returns the perimeter of the rectangle if it is a valid rectangle







The main method of MyRectangle prompts the user to enter the width and height of a rectangle and uses MyRectangle methods to print out a message followed by the area and perimeter if the rectangle is valid. Otherwise, it prints out only the message “This is invalid rectangle. Try again.”.  <u>Note</u> that method isvalid() is used to validate the input before attempting to compute the area and perimeter.




Document your code and properly label the input prompt and the outputs as shown below.

<u> </u>

<u>Sample run 1:</u>




Entered width:  4

Entered height: 5

This is invalid rectangle. Try again




<u>Sample run 2:</u>




Entered width:  20

Entered height: 15

Area:           300

Perimeter:      70




<u>Sample run 3:</u>




Entered width:  10

Entered height: 5

This is invalid rectangle. Try again.




<u>Sample run 4:</u>




Entered width:  30

Entered height: 6

Area:           180

Perimeter:      72













<strong><u>Program 2:</u></strong> Design (pseudocode) and implement (source code) a program (name it FeetMeters) to display a conversion tables for feet and meter as show below. Document your code and properly.










<table>

 <tbody>

  <tr>

   <td width="90"><strong>Feet</strong></td>

   <td width="84"><strong>Meter</strong></td>

  </tr>

  <tr>

   <td width="90">1.0</td>

   <td width="84">0.305</td>

  </tr>

  <tr>

   <td width="90">2.0</td>

   <td width="84">0.610</td>

  </tr>

  <tr>

   <td width="90">3.0</td>

   <td width="84">0.915</td>

  </tr>

  <tr>

   <td width="90"><strong>. . .</strong></td>

   <td width="84"><strong>. . .</strong></td>

  </tr>

  <tr>

   <td width="90">19.0</td>

   <td width="84">5.7.95</td>

  </tr>

  <tr>

   <td width="90">20.0</td>

   <td width="84">6.100</td>

  </tr>

 </tbody>

</table>







<table>

 <tbody>

  <tr>

   <td width="90"><strong>Meter</strong></td>

   <td width="84"><strong>Feet</strong></td>

  </tr>

  <tr>

   <td width="90">1.0</td>

   <td width="84">3.279</td>

  </tr>

  <tr>

   <td width="90">2.0</td>

   <td width="84">6.558</td>

  </tr>

  <tr>

   <td width="90">3.0</td>

   <td width="84">9.837</td>

  </tr>

  <tr>

   <td width="90"><strong>. . .</strong></td>

   <td width="84"><strong>. . .</strong></td>

  </tr>

  <tr>

   <td width="90">19.0</td>

   <td width="84">62.301</td>

  </tr>

  <tr>

   <td width="90">20.0</td>

   <td width="84">65.574</td>

  </tr>

 </tbody>

</table>







The program defines the following methods:




Method feetToMeter() converts from feet to meter.  (formula: meter = 0.305 * feet)

Method meterToFeet() converts from meter to feet.   (formula: feet = 3.279 * meter)




The main method calls these methods to produce the display the output in tabular format. Document your code and format the outputs as shown above.







<strong><u>Program 3:</u></strong> Design (pseudocode) and implement (source code) a program (name it PrintTableSeries) to display the following table for the following series:




sum(i) = 1/2 + 2/3 + 3/4 + 4/5 + … i/(i+1)







<table>

 <tbody>

  <tr>

   <td width="54"><strong>i</strong></td>

   <td width="96"><strong>Sum(i)</strong></td>

  </tr>

  <tr>

   <td width="54">1</td>

   <td width="96">0.5000</td>

  </tr>

  <tr>

   <td width="54">2</td>

   <td width="96">1.1667</td>

  </tr>

  <tr>

   <td width="54">3</td>

   <td width="96">1.1960</td>

  </tr>

  <tr>

   <td width="54">. . .</td>

   <td width="96"> </td>

  </tr>

 </tbody>

</table>




The program defines the following methods:




Method displaySums()print the table as shown above.




The main method prompts the user to enter an integer value, say n, and then calls method displaySums()to display the table for i = 1 to n. Document your code and format the outputs as shown above.







<strong><u>Program 4</u></strong><strong><u>:</u></strong>  A palindromic prime number is a number that is both prime number and a palindrome number. For example, 131, 313, and 757 are palindromic prime numbers. Design (pseudocode) and implement (source code) a program (name it PalindromicPrime) to display the first 50 palindromic prime numbers, 10 per line separated by one space. The program defines the following methods:




Method isPalindome() to check if  a number is palindrome or not.

Method isPrime() to check if a number is prime or not.




In the main method, use a loop structure to invokes these methods and print out the palindromic primes. Document your code and properly format the outputs as shown below.




<u>Output format (each x is a palindromic prime number):</u>




x x x x x x x x x x

x x x x x x x x x x

x x x x x x x x x x

x x x x x x x x x x

x x x x x x x x x x




Hint: Use modulus and division by 10 to reverse the number.


