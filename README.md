Download Link: https://assignmentchef.com/product/solved-csf211-assignment1
<br>
<strong>A: Challenge Accepted!</strong>

After a mind numbing lockdown, you decide to step out of your house and have a jog in the park nearby. After a few laps around the park, you run into your old friend. He challenges you to find if a given string S contains the sub-string <strong>baab </strong>hidden in it, and wait for it, without using loops, arrays, strings, character pointers and only using recursion. Are you brave enough to accept the challenge?

<strong>Input</strong>

The first line of input contains a single integer N (1 ≤ N ≤ 500) denoting the number of characters in the string S. The following line contains a sequence of N lowercase a’s or b’s.

<strong>Output</strong>

If the given string S contains the sub-string <strong>baab</strong>, print “YES”, followed by the index at which it is found. In case, the sub-string is present more than once, print all indices at which it is found, in ascending order, in space separated fashion (see sample case for better clarity). If the sub-string is not found in the given string, just print “NO”. Note that the indices should be printed in 1-indexed order.

input 10 baababbaab

output

YES 1 7

input 17 baaaaaabbaaaaabaa

output NO

input 12 aabaabaabaab

output

YES 3 6 9

<strong>B: Palindrome?</strong>

In this problem, you are once again given a string S, and are asked to check if S is a palindrome. A palindrome is a string which reads the same left to right and right to left. The constraint is to solve this using only doubly-linked-lists. <em>Note that, no use of arrays or character pointers must be made to solve this problem and that this is case-sensitive palindrome.</em>

<strong>Input</strong>

The first line of input contains a single integer N (1 ≤ N ≤ 1000) denoting the number of characters in the string S. The following line contains a sequence of N lowercase and uppercase alphabets.

<strong>Output</strong>

Print “PALINDROME” if given string S is a palindrome or “NOT A PALINDROME” if it is not.

input 9 MaLaYaLaM

output PALINDROME

input 6 XOFfoX

output NOT A PALINDROME

input 4

KooK

output

PALINDROME

<strong>C: Dinner Time</strong>

With the advent of the 2020 batch, Mess-1 faces a grave shortage of seats in the mess. At dinner time, every minute a certain number of students either enter the mess or leave it (assume that, in a minute, students do not enter and leave simultaneously). After dinner, the mess manager is curious to know the maximum number of seats that were occupied during dinner time. As he is busy preparing for the upcoming Moonlight dinner, he asks you to help him out. Assume that the students are very lazy and occupy the first unoccupied seat (unoccupied seat with lowest index) they find.

<strong>Input</strong>

The first line contains a single non-zero integer T (1 ≤ T ≤ 500) denoting the number of minutes the mess is open for dinner. Each of the following T lines resembles either of the following query:

<ul>

 <li>E X: This statement denotes that X (0 <em>&lt; </em>X ≤ 5000) students enter the mess in that minute.</li>

 <li>L P <em>Y</em><sub>1</sub>, <em>Y</em><sub>2</sub>, <em>Y</em><sub>3 </sub>… <em>Y<sub>P</sub></em>: This statement denotes that P (0 <em>&lt; </em>P ≤ 5000) students leave the mess that minute from the seats numbered <em>Y</em><sub>1 </sub>to <em>Y<sub>P</sub></em>. It is guaranteed that the P will be less than or equal to the number of students in the mess at that minute.</li>

</ul>

Assume that the total number of students in campus are less than or equal to 5000 and seats are 1-indexed (see sample case for better clarity)

<strong>Output</strong>

Print a single integer N, denoting the maximum number of seats that were occupied during dinner time.

input 6

E 5

E 2

L 3 1 4 5

L 1 2

E 3

E 2

output

8

<strong>D: Amazon Shopping</strong>

With Amazon’s yearly sale going on, you wish to buy as many goods as your wish with you limited pocket money you have collected till date. As the sale time is running out, you decide to write a simple program that will help you buy as many goods as possible without exceeding your budget. <em>Hint: Think in terms of subsets and how subsets can visualized with binary numbers.</em>

<strong>Input</strong>

The first line contains a single integer M (0 ≤ M ≤ 10<sup>9</sup>) that denotes your pocket money. The following line contains another integer N (1 ≤ N ≤ 25) denoting the number of goods that are for sale in Amazon. The last line of input contains N space-separated integers (0 ≤ <em>P<sub>i </sub></em>≤ 10<sup>9</sup>) denoting the prices of the goods for sale.

<strong>Output</strong>

Print a single integer X, denoting the maximum number of goods you can buy without exceeding your budget.

input 44

6

14 13 21 8 56 3

output 4

input 70

7

71 101 766 125 908 682 75

output

<h1><a name="_Toc8703"></a>0</h1>

<strong>E: Digital Design</strong>

In this problem, you will be implementing a simple shift register and some of its functions using a doubly-linked-list. <em>Note: You are not allowed to use any other data structure other than linkedlists for this problem. Further, you are not supposed to convert the given bit string to decimal and perform operations on it.</em>

<strong>Input</strong>

The first line contains a bit string B (1 ≤ |<em>B</em>| ≤ 1000) which denotes the initial content of the register. The second line contains a single integer T (1 ≤ T ≤ 100) denoting the number of queries. Each of the following T queries resemble either of the following:

<ul>

 <li>LR: This denotes that the content of the register has be left-rotated by one unit.</li>

 <li>RR: This denotes that the content of the register has be right-rotated by one unit.</li>

 <li>LS: This denotes that the content of the register has be left-shifted by one unit. (<em>empty space can be filled with 0</em>)</li>

 <li>RS: This denotes that the content of the register has be right-shifted by one unit. (<em>empty space can be filled with 0</em>)</li>

 <li>INC: This denotes that the content of the register has be incremented by 1.</li>

 <li>DEC: This denotes that the content of the register has be decremented by 1.</li>

</ul>

<strong>Output</strong>

Print the content of the register after all operations have been performed. In case any out-carry is generated, you can ignore it.

input 11111001

4

LS

LS

LR INC

output 11001010

<strong>F: Koro-sensei and Primes</strong>

Koro-sensei has come up with a quite an eerie problem on primes for the students of class 3E. Given two numbers A and B, the students have to find the digit which occurs maximum number of times in the primes from A to B (both inclusive). As the class is getting ready for the annual school festival, they all turn to you, Karuma, for help.

<strong>Input</strong>

The only line of input contains two space-separated integers A and B (0 ≤ A ≤ B ≤ 10<sup>12</sup>, 0 ≤ B-A ≤ 10<sup>6</sup>)

<strong>Output</strong>

Print two space-separated integers X and Y with X denoting the digit that occurs maximum number of times in the primes from A to B and Y denoting the frequency of X.

input 37 101

output

7 7

input 2692 15859

output

1 1367

<strong>F: Tour de Goraq</strong>

Ash Ketchum, on his journey to be the Pokemon master, plans to tour the new archipelago Goraq. Goraq is a set of islands with a few of those islands being connected by long bridges. As part of his tour, Ash always starts from island 0, and tours all islands reachable from it before moving on to another cluster of islands. Help Ash figure out how many clusters of islands are present in the Goraq archipelago and along with number of islands per cluster. <em>Note: A cluster of islands is a set of islands that are reachable from one another, i.e. they form a connected component.</em>

<strong>Input</strong>

The first line of input contains two space-separated integers N (1 ≤ N ≤ 500) and M (0 ≤ M ≤

) denoting the number of islands in the archipelago and the number of bridges between those islands respectively. The following M lines contain two space-separated integers <em>U<sub>i </sub></em>and <em>V<sub>i </sub></em>(0 ≤ <em>U<sub>i</sub></em>, <em>V<sub>i </sub></em>≤ N-1) denoting an undirected bridge between islands <em>U<sub>i </sub></em>and <em>V<sub>i</sub></em>.

<strong>Output</strong>

In the first line, print a single integer X denoting the number of clusters in the archipelago and in the following line, print X space-separated integers denoting the number of islands per cluster (this can be printed in any order).

input 12 12

5 7

7 9

1 7

4 10

3 8

10 8

10 3

<a href="#_Toc8703">0                                                                                                                                                                                         2</a>

<a href="#_Toc8704">0                                                                                                                                                                                         6</a>

<a href="#_Toc8705">6                                                                                                                                                                                       11</a>

<a href="#_Toc8706">2                                                                                                                                                                                       11</a>




2 6

output 3

4 4 4

explanation

As you can observe, there are three clusters wiz. 1-5-7-9, 0-2-6-11, 4-10-8-3

<strong>H: Cost Difference</strong>

Let us define the cost of an array as the difference of sum of squares of elements at even indices and sum of cubes of elements at odd indices. In this problem, you need to find the array rotations with maximum and minimum cost and report the difference between those costs. <em>Sample array rotation: [7 1 -9 6 0 1] </em>→ <em>[1 7 1 -9 6 0]</em>

<strong>Input</strong>

The first line contains a single integer N (1 ≤ N ≤ 500) denoting the number of elements in the array. The following line contains a sequence of N space-separated integers (−10<sup>3 </sup>≤ <em>A<sub>i </sub></em>≤ 10<sup>3</sup>) denoting the array A given you.

<strong>Output</strong>

Print a single integer S denoting the difference between of costs of the maximum cost rotation and minimum cost rotation.

input 7

6 -1 8 -1 6 8 -4

output 1452

input 10

-5 67 12 -78 5 0 -6 100 6 -37

output 795506

input 5

8 8 8 8 8

output

<h1><a name="_Toc8704"></a>0</h1>

<strong>I: Reverse it!</strong>

In this problem, you are given a stream of positive numbers. You are expected to generate a singly-linked-list out of them and reverse it. <em>Note: You must not to store the numbers in any array and are supposed to completely reverse the list by reversing all the pointers, i.e. you must not create a new list to store the numbers in reversed order.</em>

<strong>Input</strong>

The only line of input contains a sequence of numbers A (0 ≤ <em>A<sub>i </sub></em>≤ 10<sup>9</sup>). It is assured that the final number in the sequence will be -1 which can be used to as a termination condition and the length of the sequence will be less than 5 · 10<sup>5</sup>.

<strong>Output</strong>

Print the linked list after reversing it, in space-separated format. Note that, you need not print the -1 at the end.

input

9 4 67 2 7 1 7 655 8 0 91 -1

output

91 0 8 655 7 1 7 2 67 4 9

input 78 -1

output 78

input

1 78 4 28 9 68 18 19 36 9 -1

output

9 36 19 18 68 9 28 4 78 1

<ol>

 <li><strong> Rangoli</strong></li>

</ol>

Roshni has drawn a new rangoli design (which can be visualized as an undirected graph) and wishes to colour it. But unfortunately, she has only two colours Red and Blue. She is very particular about her colouring scheme and wants the colour the vertices in the rangoli in such a way that the two vertices connected by an edge have different colour. As Roshni is still perfecting her rangoli design, help her generate a coloring scheme using only the Red and Blue colours available.

<strong>Input</strong>

The first line of input contains two space-separated integers N (1 ≤ N ≤ 500) and M (0 ≤ M ≤

) denoting the number of vertices and edges in the rangoli. The following M lines contain two space-separated integers <em>U<sub>i </sub></em>and <em>V<sub>i </sub></em>(0 ≤ <em>U<sub>i</sub></em>, <em>V<sub>i </sub></em>≤ N-1) denoting an undirected edge between vertices <em>U<sub>i </sub></em>and <em>V<sub>i </sub></em>in the rangoli.

<strong>Output</strong>

If coloring the rangoli with just two colours is not possible, print “NEED MORE COLOURS” else, print a sequence of N characters denoting the colouring scheme for the rangoli. Assume the 0<em><sup>th </sup></em>vertex is always coloured Red, in case a colouring scheme exists. (see sample case for clarity).

input

<h1><a name="_Toc8705"></a>6 6</h1>

0 1

<h1><a name="_Toc8706"></a>2 3</h1>

4 5

0 5

2 1

<ul>

 <li>3</li>

</ul>

output RBRBRB

input

<ul>

 <li>6</li>

 <li>1</li>

 <li>3</li>

</ul>

1 5

4 5

2 1

5 0

output

NEED MORE COLOURS