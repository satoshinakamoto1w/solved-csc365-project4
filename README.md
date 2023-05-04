Download Link: https://assignmentchef.com/product/solved-csc365-project4
<br>
Q1. Create the precedence graph for the schedule: w​1(<sub>​ </sub>X), r​1(<sub>​ </sub>X), w​2(<sub>​ </sub>Y), r​3(<sub>​ </sub>X), w​1(<sub>​ </sub>Y), w​1(<sub>​ </sub>X). Based on the graph, determine whether the schedule is conflict-serializable.

Q2. What is the difference between serializable and conflict-serializable schedule. What is the relation between the two (is one of them a subset of the other)?

Q3. Consider the following schedule:

r​1(<sub>​ </sub>A);r​2(<sub>​ </sub>B);???;w​1(<sub>​ </sub>C);w​2(<sub>​ </sub>A);

What value for ??? will make the schedule not conflict-serializable. Give one such possible value.

Q4[. Consider the transactions ​<em>T</em>​1 and <sub>​ </sub>​<em>T</em>​2.<sub>​</sub>

<em>T</em>​1 :<sub>​</sub> ​<em>r</em>​1(<sub>​ </sub>​<em>A</em>​); ​<em>w</em>​1(<sub>​ </sub>​<em>A</em>​); ​<em>r</em>​1(<sub>​ </sub>​<em>B</em>​); ​<em>w</em>​1(<sub>​ </sub>​<em>B</em>​);

<em>T</em>​2 : <sub>​ </sub>​<em>r</em>​2(<sub>​ </sub>​<em>B</em>​); ​<em>w</em>​2(<sub>​ </sub>​<em>B</em>​); <em>r</em>​​2<sub>​</sub>( ​<em>A</em>​); ​<em>w</em>​2(<sub>​ </sub>​<em>A</em>​);

Give an example of a conflict-serializable schedule and non conflict-serializable schedule for the eight actions.

Q5 Are the following schedules conflict-serializable?

<ol>

 <li>​<em>r</em>​1(<sub>​ </sub>​<em>A</em>​); ​<em>w</em>​1(<sub>​ </sub>B); ​<em>r</em>​2(<sub>​ </sub>B); <em>w</em>​​2<sub>​</sub>( C);​<em> r</em>​3(<sub>​ </sub>C); ​<em>w</em>​3(<sub>​ </sub>A);</li>

 <li>​<em>w</em>​3(<sub>​ </sub>​<em>A</em>​); ​<em>r</em>​1(<sub>​ </sub>A); ​<em>w</em>​1(<sub>​ </sub>B); <em>r</em>​​2<sub>​</sub>( B);​<em> w</em>​2(<sub>​ </sub>C); ​<em>r</em>​3(<sub>​ </sub>C);</li>

</ol>

Create two triggers that work with the SQL tables from the lab 1.

<ol>

 <li>Create `update_balance_trigger` on the ​<strong>transaction</strong>​ The trigger will be used (triggered) to update the current balance of the credit card by adding the dollar amount of a transaction every time a tuple is inserted into the transaction table.</li>

 <li>Create `check_balance_trigger` on the ​<strong>credit card</strong>​ If a ​<strong>credit card</strong>​ tuple is updated, then the trigger should make sure that the new credit card balance is less than the new credit limit. If it is not, then you should signal the exception 12345.</li>

</ol>

Make sure your triggers work on the MySQL database. Submit only the code for the two triggers.