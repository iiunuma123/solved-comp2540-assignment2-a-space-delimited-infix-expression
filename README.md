Download Link: https://assignmentchef.com/product/solved-comp2540-assignment2-a-space-delimited-infix-expression
<br>



For this assignment, you will write a computer program to evaluate arithmetic expressions represented as text (a space-delimited infix expression). For example, the string​ <strong>“1</strong>​ ​<strong>+</strong>​ ​<strong>2</strong>​ ​<strong>+</strong>​ ​<strong>(3</strong>​ ​<strong>*</strong>​ ​<strong>4)”</strong>​ ​would​ ​evaluate​ ​to​ ​<strong>15</strong>​.​ ​Your​ ​program​ ​should:

<ol>

 <li>Read​ ​arithmetic​ ​expressions​ ​in​ ​infix​ ​format​ from​ ​​input​ ​text​ ​file ​<strong>(</strong>​ ​<strong>10</strong>​ ​<strong>points) </strong></li>

 <li>Validate ​ the​ ​ infix​ ​ expression​ ​ <strong>(10 </strong>​ <strong>points)</strong>​</li>

 <li>Using Stack as ADT convert the infix expression into a postfix expression. ​<strong>(30 points) </strong></li>

 <li>Using​ ​Stack​ ​as​ ​ADT​ ​evaluate​ ​the​ ​postfix ​expression​​ ​from​ step​ ​ 3​ ​ <strong>(30</strong>​ ​ ​<strong>points) </strong></li>

 <li>Display the data in the stack before and after each pop and push operation ​<strong>(20 points) </strong></li>

</ol>




You must handle the unary negation operator. You may use built-in functions in C or Java to handle the power operator (e.g., 2^3 =8) The usual order of operations is in effect:

<ul>

 <li>Parentheses​ ​have​ ​higher​ ​precedence ​ evaluated​ ​ left-to-right​</li>

 <li>The ^ operator has higher precedence than unary negation operator, and other binary​ ​operators​ ​(*,​ ​/, ​ ​+,​ ​and​ ​-)</li>

 <li>The unary negation operator – has higher precedence than the binary operators, and​ ​is​ ​evaluated ​ right-to-left​ ​ (​ right-associative)</li>

 <li>The ​ *​ ​ and​​ /​ ​​have​ higher​​ ​precedence​ ​than​ ​+​ ​and ​</li>

 <li>All ​ binary​ ​ operators​ ​ are​ ​ ​evaluated ​ ​left-to-right​ ​(left-associative)</li>

</ul>




Your program must read n number of a space-delimited infix expression from an input text​ ​file​ ​and​ ​evaluate​ ​them,​ ​where​ ​each ​​line​ ​represents​ ​an​ ​infix​ ​expression.

<strong>Examples: </strong>

<strong><em>Input: </em></strong>

<strong>(</strong>​ ​<strong>25</strong>​<strong> +</strong>​ ​ <strong>30</strong>​ ​ <strong>)</strong>​ <strong> </strong>​<strong>*</strong>​​  <strong>2</strong>​ ​ <strong>^</strong>​​  <strong>(</strong>​ ​ <strong>2</strong>​ ​ <strong>+</strong>​ ​ <strong>1</strong>​​  <strong>)</strong>​

<strong>30</strong>​ ​<strong>/</strong>​ ​<strong>2 </strong>​ <strong>+</strong>​ ​ <strong>5</strong>​ ​ <strong>*</strong>​ ​ <strong>2</strong>​

<strong>-3</strong>​ ​<strong>^ </strong>​​<strong>2</strong>​ ​<strong>+</strong>​ ​<strong>10</strong>

<strong>(</strong>​ ​<strong>6</strong>​ ​<strong>+</strong>​ ​<strong>(</strong>​ ​<strong>–</strong>​ ​<strong>3</strong>​ ​<strong>)</strong>​ ​<strong>–</strong>​ ​<strong>1)</strong>




<strong><em>Output: </em></strong>

<strong>440 </strong>

<strong>25 </strong>

<strong>1 </strong>

<strong>2</strong>