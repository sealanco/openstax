# ARITHMETIC: A Textbook for Math 01

3rd edition (2012) 

Anthony Weaver 

Department of Mathematics and Computer Science Bronx Community College

## Chapter 1 - Whole Numbers 

The natural numbers are the counting numbers: $1, 2, 3, 4, 5, 6, ...$ . The dots indicate that the sequence is infinite – counting can go on forever, since you can always get the next number by simply adding 1 to the previous number. In order to write numbers efficiently, and for other reasons, we also need the number 0. Later on, we will need the sequence of negative numbers $−1, −2, −3, −4, −5, −6, ...$ . Taken together, all these numbers are called the integers. 

It helps to visualize the integers laid out on a number line, with 0 in the middle, and the natural numbers increasing to the right. There are numbers between any two integers on the number line. In fact, every location on the line represents some number. Some locations represent fractions such as one-half (between 0 and 1) or four-thirds (between 1 and 2). Other locations represent numbers which cannot be expressed as fractions, such as π. (π is located between 3 and 4 and expresses the ratio of the circumference to the diameter of any circle.) 

​<svg width="100%" height="50" viewBox="0 0 550 50">
<line x1="0" y1="20" x2="550" y2="20" stroke="currentColor" stroke-width="2" />
<circle cx="25" cy="20" r="4" fill="red" /><text x="25" y="42" text-anchor="middle" font-size="20" fill="currentColor">-5</text>
<circle cx="75" cy="20" r="4" fill="red" /><text x="75" y="42" text-anchor="middle" font-size="20" fill="currentColor">-4</text>
<circle cx="125" cy="20" r="4" fill="red" /><text x="125" y="42" text-anchor="middle" font-size="20" fill="currentColor">-3</text>
<circle cx="175" cy="20" r="4" fill="red" /><text x="175" y="42" text-anchor="middle" font-size="20" fill="currentColor">-2</text>
<circle cx="225" cy="20" r="4" fill="red" /><text x="225" y="42" text-anchor="middle" font-size="20" fill="currentColor">-1</text>
<circle cx="275" cy="20" r="4" fill="red" /><text x="275" y="42" text-anchor="middle" font-size="20" fill="currentColor">0</text>
<circle cx="325" cy="20" r="4" fill="red" /><text x="325" y="42" text-anchor="middle" font-size="20" fill="currentColor">1</text>
<circle cx="375" cy="20" r="4" fill="red" /><text x="375" y="42" text-anchor="middle" font-size="20" fill="currentColor">2</text>
<circle cx="425" cy="20" r="4" fill="red" /><text x="425" y="42" text-anchor="middle" font-size="20" fill="currentColor">3</text>
<circle cx="475" cy="20" r="4" fill="red" /><text x="475" y="42" text-anchor="middle" font-size="20" fill="currentColor">4</text>
<circle cx="525" cy="20" r="4" fill="red" /><text x="525" y="42" text-anchor="middle" font-size="20" fill="currentColor">5</text>
</svg>

For now, we concentrate on the non-negative integers (including 0), which we call whole numbers. We need only ten symbols to write any whole number. These symbols are the digits 

$$0, 1, 2, 3, 4, 5, 6, 7, 8, 9.$$

We write larger whole numbers using a place-value system. The digit in the right-most place indicates how many ones the number contains, the digit in the second-from-right place indicates how many tens the number contains, the digit in the third-from-right place indicates how many hundreds the number contains, etc. 

#### Example 1 - Text:
```text
7 stands for 7 ones
72 stands for 7 tens + 2 ones
349 stands for 3 hundreds + 4 tens + 9 ones
6040 stands for 6 thousands + 0 hundreds + 4 tens + 0 ones
```

Notice that when you move left, the place value increases ten-fold. So if a number has five digits, the fifth-from-right place indicates how many ten-thousands the number contains. (Ten-thousand is ten times a thousand.) 

9 

#### 1.0.1 Exercises - Text:

```text
1. 35 stands for 3 tens + 5 ones

2. 209 stands for 2 hundreds + 0 tens + 9 ones

3. 9532 stands for 9 thousands + 5 hundreds + 3 tens + 2 ones

4. 21045 stands for 2 ten-thousands + 1 thousand + 0 hundreds + 4 tens + 5 ones
```

### 1.1 Adding Whole Numbers 

When we add two or more integers, the result is called the sum. We assume you know the sums of single-digit numbers. For practice, do the following example. 

Example 2. Fill in the missing squares in the digit-addition table below. For example, the number in the row labelled 3 and the column labelled 4 is the sum 3 + 4 = 7. 

<!-- Start of picture text -->
+ 0 1 2 3 4 5 6 7 8 90 0 1 2 3 4 5 6 7 8 9123 74567 1289<!-- End of picture text -->

Table 1.1: The digit addition table 

1. Do you notice any patterns or regularities in the digit-addition table? Can you explain them? 

2. Why is the second line from the top identical to the top line? 

3. What can you say about the left-most column and the second-from-left column? 

#### 1.1.1 Commutativity, Associativity, Identity 

The first question leads us to an important property of addition, namely, that for any two numbers x and y , 

x + y = y + x. 

Page 10 

In other words, the order in which two numbers are added does not effect the sum. This property of addition is called commutativity. 

The last two questions lead us to an important property of 0, namely, for any number x, 

<!-- Start of picture text -->
x + 0 = x = 0 + x.<!-- End of picture text -->

In other words, when 0 is added to any number, x, you get the identical number, x, again. Because of this property, 0 is called the additive identity. 

One final property of addition is expressed in the following equation 

<!-- Start of picture text -->
(x + y ) + z = x + (y + z),<!-- End of picture text -->

which says that if three numbers are added, it doesn’t matter how you “associate” the additions: you can add the first two numbers first, and then add the third to that, or, you could add the second two numbers first, and then add the first to that. This property of addition is called associativity. 

Example 3. Find the sum of 2, 3, and 5 by associating in two different ways. 

Solution. Associating 2 and 3, we calculate 

<!-- Start of picture text -->
(2 + 3) + 5 = 5 + 5 = 10.<!-- End of picture text -->

On the other hand, associating 3 and 5, we calculate 

<!-- Start of picture text -->
2 + (3 + 5) = 2 + 8 = 10.<!-- End of picture text -->

The sum is the same in both cases. 

#### 1.1.2 Multi-digit addition 

To add numbers with more than one digit, we line up the numbers vertically so that the ones places (right-most) are directly on top of each other, and all other places are similarly arranged. Then we add the digits in each place to obtain the sum. 

Example 4. Find the sum of 25 and 134. 

Solution. We line up the numbers vertically so that the 5 in the ones place of 25 is over the 4 in the ones place of 134. If we do this carefully, all the other places line up vertically, too. So there is a “ones” column, a “tens” column to the left of it, and a “hundreds” column to the left of that: 

<!-- Start of picture text -->
2 51 3 4<!-- End of picture text -->

Then we draw a line and add the digits in each column to get the sum: 

<!-- Start of picture text -->
2 5+ 1 3 41 5 9<!-- End of picture text -->

Page 11 

Sometimes we need to “carry” a digit from one place to the next higher place. For example, when adding 38 + 47, we first add the ones places, 8 + 7 = 15. But 15 has two digits: it stands for 1 ten + 5 ones. We “put down” the 5 in the ones place, and “carry” the 1 (standing for a ten) to the tens column. So we have: 

Example 5. Find the sum 

<!-- Start of picture text -->
3 8+ 4 7<!-- End of picture text -->

Solution. Put down the 5 in the ones place: 

<!-- Start of picture text -->
3 8+ 4 75<!-- End of picture text -->

and carry the 1 to the top of the tens column: 

<!-- Start of picture text -->
{1}3 8+ 4 75<!-- End of picture text -->

and finish the job by adding up the tens column, including the carried one: 

<!-- Start of picture text -->
{1}3 8+ 4 78 5<!-- End of picture text -->

The sum is 85. 

Since carrying alters the sum in the column immediately to the left of the one we are working on, in multi-digit addition, we always start with the right-most column and proceed leftward. 

#### 1.1.3 Exercises 

Find the sums, carrying where necessary. 

<!-- Start of picture text -->
1.<!-- End of picture text -->

<!-- Start of picture text -->
2 6+ 5 5<!-- End of picture text -->

Page 12 

##### 2. 

|3 8 3+4 7|
|---|

##### 3. 

|3 24 5+6 4|
|---|

4. 

||1 3|2 9 7 7|
|---|---|---|
|+4|5|0 3|

##### 5. 

<!-- Start of picture text -->
9 0 97 7 7+ 6 9 6 4<!-- End of picture text -->

6. 

<!-- Start of picture text -->
3 2 09 8 49 0 2+ 4 5 0 3<!-- End of picture text -->

Page 13 

|7.||
|---|---|
||99 9 9|
||9 0 2+9 5 0 2|
|8.||
||5 6 3 2 0|
||9 8 6 4|
||9 0 4|
||+6 5 0 3|
|9.||
||3 2 0 0 0|
||9 8 4 4|
||9 0 2|
||+4 5 0 3|
|10.||

||2|9|9 7|
|---|---|---|---|
||9|8|4 4|
|||2|0 5|
|+|5 4|9|0 8|

### 1.2 Subtracting Whole Numbers 

Another way to say that 5 + 2 = 7 is to say that 5 = 7 − 2. In words, “5 is the difference of 7 and 2,” or “5 is the result of taking away 2 from 7.” The operation of taking away one number from another, or finding their difference, is called subtraction. For now, we have to be careful that the number we take away is no larger than the number we start with: we cannot have 3 marbles and take 7 of them away! Later on, when we introduce negative numbers, we won’t have to worry about this. 

We assume you remember the differences of single-digit numbers. Just to make sure, do the following example. 

Example 6. Fill in the missing squares in the digit-subtraction table below. Here’s a start: the number in the row labelled 7 and the column labelled 2 is the difference 7 − 2 = 5. The digit in the row labelled 3 and the column labelled 3 is the difference 3 − 3 = 0. (Squares that have an asterisk (∗) will be filled in later with negative numbers.) 

Page 14 

|−|0|1|2|3|4|5|6|7|8|9|
|---|---|---|---|---|---|---|---|---|---|---|
|0||*|*|*|*|*|*|*|*|*|
|1|||*|*|*|*|*|*|*|*|
|2||||*|*|*|*|*|*|*|
|3||||0|*|*|*|*|*|*|
|4||||||*|*|*|*|*|
|5|||||||*|*|*|*|
|6||||||||*|*|*|
|7|||5||||||*|*|
|8||||||||||*|
|9||||||4|||||

Table 1.2: The digit subtraction table 

#### 1.2.1 Commutativity, Associativity, Identity 

When we study negative numbers, we will see that subtraction is not commutative. We can see by a simple example that subtraction is also not associative. 

Example 7. Verify that (7 − 4) − 2 is not equal to 7 − (4 − 2). 

Solution. Associating the 7 and 4, we get 

<!-- Start of picture text -->
(7 − 4) − 2 = 3 − 2 = 1,<!-- End of picture text -->

but associating the 4 and the 2, we get 

<!-- Start of picture text -->
7 − (4 − 2) = 7 − 2 = 5,<!-- End of picture text -->

a different answer. Until we establish an order of operations, we will avoid examples like this! 

It is true that 

<!-- Start of picture text -->
x − 0 = x<!-- End of picture text -->

for any number x. However, 0 is not an identity for subtraction, since 0 − x is not equal to 0 (unless x = 0). To make sense of 0 − x, we will need negative numbers. 

#### 1.2.2 Multi-digit subtractions 

To perform subtractions of multi-digit numbers, we need to distinguish the number “being diminished” from the number which is “doing the diminishing” (being taken away). The latter number is called the subtrahend, and the former, the minuend. For now, we take care that the subtrahend is no larger than the minuend. 

To set up the subtraction, we line the numbers up vertically, with the minuend over the subtrahend, and the ones places lined up on the right. 

Example 8. Find the difference of 196 and 43. 

Solution. The subtrahend is 43 (the smaller number), so it goes on the bottom. We line up the numbers vertically so that the 6 in the ones place of 196 is over the 3 in the ones place of 43. 

<!-- Start of picture text -->
1 9 6<!-- End of picture text -->

<!-- Start of picture text -->
4 3<!-- End of picture text -->

Then we draw a line and subtract the digits in each column, starting with the ones column and working right to left, to get the difference: 

Page 15 

<!-- Start of picture text -->
1 9 6− 4 31 5 3<!-- End of picture text -->

#### 1.2.3 Checking Subtractions 

Subtraction is the “opposite” of addition, so any subtraction problem can be restated in terms of addition. Using the previous example, and adding the difference to the subtrahend, we obtain 

<!-- Start of picture text -->
1 5 3+ 4 31 9 6<!-- End of picture text -->

which is the original minuend. In general, if subtraction has been performed correctly, adding the difference to the subtrahend returns the minuend. This gives us a good way to check subtractions. Example 9. Check whether the following subtraction is correct: 

<!-- Start of picture text -->
9 4− 5 13 3<!-- End of picture text -->

Solution. Adding the (supposed) difference to the subtrahend, we get 

<!-- Start of picture text -->
3 3+ 5 18 4<!-- End of picture text -->

which is not equal to the minuend (94). Thus the subtraction is incorrect. We leave it to you to fix it! 

#### 1.2.4 Borrowing 

Sometimes, when subtracting, we need to “borrow” a digit from a higher place and add its equivalent to a lower place. 

Example 10. Find the difference: 

<!-- Start of picture text -->
8 5− 4 6<!-- End of picture text -->

Solution. The digit subtraction in the ones column is not possible (we can’t take 6 from 5). Instead we remove or ”borrow” 1 ten from the tens place of the minuend, and convert it into 10 ones, which we add to the ones in the ones place of the minuend. The minuend is now represented as {7}{15}, 

Page 16 

standing for 7 tens + 15 ones. It looks funny (as if 15 were a digit), but it doesn’t change the value of the minuend, which is still 7 × 10 + 15 = 85. We represent the borrowing operation like this: 

<!-- Start of picture text -->
{7}{15}8 5− 4 6<!-- End of picture text -->

Ignoring the original minuend, we have 15 − 6 = 9 for the ones place, and 7 − 3 = 4 for the tens place, as follows: 

<!-- Start of picture text -->
{7}{15}8 5− 4 63 9<!-- End of picture text -->

The difference is 39. We can check this by verifying that the difference + the subtrahend = the original minuend: 

<!-- Start of picture text -->
3 9+ 4 68 5<!-- End of picture text -->

Sometimes you have to go more than one place to the left to borrow successfully. This happens when the next higher place has a 0 digit – there is nothing to borrow from. Example 11. Find the difference: 

<!-- Start of picture text -->
2 0 7− 6 9<!-- End of picture text -->

Solution. In the ones column we can’t take 9 from 7, so we need to borrow from a higher place. We can’t borrow from the tens place, because it has 0 tens. But we can borrow from the hundreds place. We borrow 1 hundred, and convert it into 9 tens and 10 ones. The minuend is now represented as {1}{9}{17}, standing for 1 hundred + 9 tens + 17 ones, (as if 17 were a digit). We represent the borrowing as before: 

<!-- Start of picture text -->
{1}{9}{17}2 0 7− 6 9<!-- End of picture text -->

Ignoring the original minuend, we have 17 − 9 = 8 for the ones place, 9 − 6 = 3 for the tens place, and 1 − 0 = 1 for the hundreds place: 

<!-- Start of picture text -->
{1}{9}{17}2 0 7− 6 91 3 8<!-- End of picture text -->

Page 17 

The difference is 138. To check, we verify that the difference + the subtrahend = the original minuend: 

<!-- Start of picture text -->
1 3 8+ 6 92 0 7<!-- End of picture text -->

(You may have noticed that the carrying you do in the addition check simply reverses the borrowing done in the original subtraction!) 

#### 1.2.5 Exercises 

Find the differences, borrowing where necessary. Check that the difference + the subtrahend = the minuend. 

|1.|
|---|

<!-- Start of picture text -->
9 4− 3 7<!-- End of picture text -->

2. 3. 

|2 −1|7 5 8 1|
|---|---|

|3 5 0−7 6|
|---|

|4.5.|
|---|

|5 −1|0 0 9 1|
|---|---|

|6 0 0−1 9 9|
|---|

Page 18 

6. 

<!-- Start of picture text -->
1 5 0 0− 1 1 9 1<!-- End of picture text -->

7. 

<!-- Start of picture text -->
5 6 7 8− 4 5 6 7<!-- End of picture text -->

8. 

<!-- Start of picture text -->
5 0 0 0 0− 4 9 9 9<!-- End of picture text -->

9. 

<!-- Start of picture text -->
8 0 1− 7 9 0<!-- End of picture text -->

10. 

<!-- Start of picture text -->
6 3 8 9− 9 9 9<!-- End of picture text -->

11. 

<!-- Start of picture text -->
5 0 0 0 0 0− 4 3 2 1 0<!-- End of picture text -->

12. 

<!-- Start of picture text -->
9 0 0 1 0 1 0− 1 1 1 1 1 1 1<!-- End of picture text -->

Page 19 

### 1.3 Multiplying Whole Numbers 

Multiplication is really just repeated addition. When we say “4 times 3 equals 12,” we can think of it as starting at 0 and adding 3 four times over: 

<!-- Start of picture text -->
0 + 3 + 3 + 3 + 3 = 12.<!-- End of picture text -->

We can leave out the 0, since 0 is the additive identity ( 0+3 = 3). Using the symbol × for multiplication, we write 

<!-- Start of picture text -->
3 + 3 + 3 + 3 = 4 × 3 = 12.<!-- End of picture text -->

The result of multiplying two or more numbers is called the product of the numbers. Instead of the × symbol, we often use a central dot (·) to indicate a product. Thus, for example, instead of 2 × 4 = 8, we can write 

<!-- Start of picture text -->
2 · 4 = 8.<!-- End of picture text -->

Example 12. We assume you remember the products of small whole numbers, so it should be easy for you to reproduce the partial multiplication table below. For example, the number in the row labelled 7 and the column labelled 5 is the product 7 · 5 = 35. 

|×|0|1|2|3|4|5|6|7|8|9|10|11|12|
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|0|0|0|0|0|0|0|0|0|0|0|0|0|0|
|1|0|1|2|3|4|5|6|7|8|9|10|11|12|
|2|0|2|4|6|8|10|12|14|16|18|20|22|24|
|3|0|3|6|9|12|15|18|21|24|27|30|33|36|
|4|0|4|8|12|16|20|24|28|32|36|40|44|48|
|5|0|5|10|15|20|25|30|35|40|45|50|55|60|
|6|0|6|12|18|24|30|36|42|48|54|60|66|72|
|7|0|7|14|21|28|35|42|49|56|63|70|77|84|
|8|0|8|16|24|32|40|48|56|64|72|80|88|96|
|9|0|9|18|27|36|45|54|63|72|81|90|99|108|
|10|0|10|20|30|40|50|60|70|80|90|100|110|120|
|11|0|11|22|33|44|55|66|77|88|99|110|121|132|
|12|0|12|24|36|48|60|72|84|96|108|120|132|144|

Table 1.3: Multiplication table 

1. Do you notice any patterns or regularities in the multiplication table? Can you explain them? 

2. Why does the second row from the top contain only 0’s? 

3. Why is the third row from the top identical to the first row? 

4. Is multiplication commutative? How can you tell from the table? 

Page 20 

#### 1.3.1 Commutativity, Associativity, Identity, the Zero Property 

An examination of the multiplication table leads us to an important property of 0, namely, when any number, N, is multiplied by 0, the product is 0: 

<!-- Start of picture text -->
0 · N = N · 0 = 0.<!-- End of picture text -->

It also shows us an important property of 1, namely, when any number, N, is multiplied by 1, the product is the identical number, x, again: 

<!-- Start of picture text -->
1 · N = N · 1 = N.<!-- End of picture text -->

For this reason, 1 is called the multiplicative identity. 

The following example should help you to see that multiplication is commutative. 

Example 13. The figure shows two ways of piling up twelve small squares. On the left, we have piled up 3 rows of 4 squares (3 × 4); on the right, we have piled up 4 rows of 3 squares (4 × 3). In both cases, of course, the total number of squares is the product 3 × 4 = 4 × 3 = 12. 

Figure 1.1: 3 × 4 = 4 × 3 = 12 

Examples like the following help you to see that multiplication is associative. 

Example 14. We can find the product 3 × 4 × 5 in two different ways. We could first associate 3 and 4, getting 

<!-- Start of picture text -->
(3 × 4) × 5 = 12 × 5 = 60,<!-- End of picture text -->

or we could first associate 4 and 5, getting 

<!-- Start of picture text -->
3 × (4 × 5) = 3 × 20 = 60.<!-- End of picture text -->

The product is the same in both cases. 

#### 1.3.2 Multi-digit multiplications 

To multiply numbers when one of them has more than one digit, we need to distinguish the number “being multiplied” from the number which is “doing the multiplying.” The latter number is called the multiplier, and the former, the multiplicand. It really makes no difference which number is called the multiplier and which the multiplicand (because multiplication is commutative!). But it saves space if we choose the multiplier to be the number with the fewest digits. 

To set up the multiplication, we line the numbers up vertically, with the multiplicand over the multiplier, and the ones places lined up on the right. 

Page 21 

Example 15. To multiply 232 by 3, we write 

<!-- Start of picture text -->
2 3 2× 3<!-- End of picture text -->

We multiply place-by-place, putting the products in the appropriate column. 3 × 2 ones is 6 ones, so we put 6 in the ones place 

<!-- Start of picture text -->
2 3 2× 36<!-- End of picture text -->

3 × 3 tens is 9 tens, so we put 9 in the tens place 

<!-- Start of picture text -->
2 3 2× 39 6<!-- End of picture text -->

Finally, 3 × 2 hundreds is 6 hundreds, so that we put down 6 in the hundreds place, and we are done: 

<!-- Start of picture text -->
2 3 2× 36 9 6<!-- End of picture text -->

Sometimes we need to carry a digit from one place to the next higher place, as in addition. For example, 4 × 5 = 20, a number with two digits. So we would “put down” the 0 in the current place, and “carry” the 2 to the column representing the next higher place, as in the next example. Example 16. Multiply 251 by 4. 

Solution. The steps are 

<!-- Start of picture text -->
2 5 1× 4<!-- End of picture text -->

For the ones place, 

<!-- Start of picture text -->
2 5 1× 44<!-- End of picture text -->

For the tens place, 4 × 5 = 20, so we put down the 0 in the tens place and carry the 2 to the hundreds column: 

<!-- Start of picture text -->
{2}2 5 1× 40 4<!-- End of picture text -->

Page 22 

For the hundreds place, 4 × 2 hundreds is 8 hundreds, to which we add the 2 hundreds that were carried. This gives us 10 hundreds, or 1 thousand. We put down 0 in the hundreds place, and 1 in the thousands place. 

<!-- Start of picture text -->
{2}2 5 1× 41 0 0 4<!-- End of picture text -->

The product of 251 and 4 is 1004. 

If the multiplier has more than one digit, the procedure is a little more complicated. We get partial products (one for each digit of the multiplier) which are added to yield the total product. Example 17. Consider the product 

<!-- Start of picture text -->
2 4× 3 2<!-- End of picture text -->

Since the multiplier stands for 3 tens + 2 ones, we can split the product into two partial products 

<!-- Start of picture text -->
2 4× 24 8<!-- End of picture text -->

and 

<!-- Start of picture text -->
2 4× 3<!-- End of picture text -->

Notice that in the second partial product the multiplier is in the tens column. This is almost exactly like having a 1-digit multiplier. The second partial product is obtained by simply putting down a 0 in the ones place and shifting the digit products one place to the left: 

<!-- Start of picture text -->
2 4× 37 2 0<!-- End of picture text -->

(Notice that we put down 2 and carried 1 when we performed the digit product 3 × 4 = 12.) The total product is the sum of the two partial products: 48 + 720 = 768. We can write the whole procedure compactly by aligning the two partial products vertically 

<!-- Start of picture text -->
2 4× 3 24 87 2 0<!-- End of picture text -->

Page 23 

and then performing the addition 

<!-- Start of picture text -->
2 4× 3 24 8+ 7 2 07 6 8<!-- End of picture text -->

Here’s another example. 

Example 18. Find the product of 29 and 135. 

Solution. We choose 29 as the multiplier since it has the fewest digits. 

<!-- Start of picture text -->
1 3 5× 2 9<!-- End of picture text -->

We use the 1-digit multiplier 9 to obtain the first partial product 

<!-- Start of picture text -->
{3}{4}1 3 5× 2 91 2 1 5<!-- End of picture text -->

Notice that we put down 5 and carried 4 to the tens place, and also put down 1 and carried 3 to the hundreds place. Next we use the 1-digit multiplier 2 (standing for 2 tens) to obtain the second partial product, shifted left by putting a 0 in the ones place 

<!-- Start of picture text -->
{1}1 3 5× 2 91 2 1 52 7 0 0<!-- End of picture text -->

(What carry did we perform?) Finally, we add the partial products to obtain the (total) product 

<!-- Start of picture text -->
1 3 5× 2 91 2 1 5+ 2 7 0 03 9 1 5<!-- End of picture text -->

Note that the whole procedure is compactly recorded in the last step, which is all that you need to write down. 

Page 24 

|1.3.3Exercises||
|---|---|
|Find the products.||
|1.||
||1 2 2×4|
|2.||
||8 3×5|
|3.||
||1 0 4|
||×7|
|4.||
||3 0 0 8|
||×9|
|5.||
||2 1 2|
||×4 3|
|6.||
||8 3×5 6|

Page 25 

7. 

<!-- Start of picture text -->
1 3 6× 2 7<!-- End of picture text -->

8. 

<!-- Start of picture text -->
3 0 8× 1 0 9<!-- End of picture text -->

9. 

<!-- Start of picture text -->
2 1 0 3× 4 4<!-- End of picture text -->

10. 

<!-- Start of picture text -->
8 3 7× 5 4<!-- End of picture text -->

### 1.4 Powers of Whole Numbers 

If we start with 1 and repeatedly multiply by 3, 4 times over, we get a number that is called the 4th power of 3, written 

<!-- Start of picture text -->
3 4 = 1 × 3 × 3 × 3 × 3.<!-- End of picture text -->

The factor of 1 is understood and usually omitted. Instead we simply write 

<!-- Start of picture text -->
3 4 = 3 × 3 × 3 × 3.<!-- End of picture text -->

In the expression 3<sup>4</sup> , 3 is called the base, and 4 the exponent (or power). Example 19. The 5th power of 2, or 2<sup>5</sup> , is the product 

<!-- Start of picture text -->
2 × 2 × 2 × 2 × 2 = 32.<!-- End of picture text -->

The 3rd power of 4, or 4<sup>3</sup> , is the product 

<!-- Start of picture text -->
4 × 4 × 4 = 64.<!-- End of picture text -->

We make the following definition in the cases where the exponent is 0. 

Page 26 

<!-- Start of picture text -->
For any nonzero number N,N 0 = 1.(0 0 is undefined.)<!-- End of picture text -->

This makes sense if you remember the harmless factor of 1 that is understood in every exponential expression. (You’ll see another justification when you study algebra.) 

Although 0<sup>0</sup> is undefined, expressions such as 0<sup>2</sup> , 0<sup>3</sup> , etc., with 0 base and nonzero exponent, make perfect sense (e.g., 0<sup>3</sup> = 0 × 0 × 0 = 0). Example 20. 17<sup>0</sup> = 1. 0<sup>5</sup> = 0. 0<sup>1</sup> = 0. 0<sup>0</sup> is undefined. 

#### 1.4.1 Squares and Cubes 

Certain powers are so familiar that they have special names. For example, the 2nd power is called the square and the 3rd power is called the cube. Thus 5<sup>2</sup> is read “5 squared,” and 7<sup>3</sup> is read as “7 cubed.” The source of these special names is geometric (see Section 1.8). The area of a square, x units on a side, is x<sup>2</sup> square units. This means that the square contains x<sup>2</sup> small squares, each one unit on a side. For example, the figure below shows a square 6 units on a side, with area 6<sup>2</sup> = 36 square units. 

<!-- Start of picture text -->
=<!-- End of picture text -->

Similarly, the volume of a cube, y units on a side, is y<sup>3</sup> cubic units. This means that the cube contains y<sup>3</sup> little cubes, each one unit on a side. For example, the volume of an ice cube that measures 2 cm (centimeters) on a side is 2<sup>3</sup> = 8 cubic centimeters. 

#### 1.4.2 Exercises 

1. Rewrite using an exponent: 8 × 8 × 8 × 8 

2. Rewrite using an exponent: 4 · 4 · 4 · 4 · 4 · 4 

3. Evaluate 2<sup>5</sup> 

4. Evaluate 9<sup>0</sup> 

5. Evaluate 0<sup>7</sup> 

6. Evaluate 5<sup>4</sup> 

7. Evaluate 10<sup>2</sup> 

Page 27 

##### 8. Evaluate 10<sup>3</sup> 

9. Complete the following table of squares: 

|0<sup>2 </sup>= 0|6<sup>2 </sup>=|12<sup>2 </sup>=|18<sup>2 </sup>=|
|---|---|---|---|
|1<sup>2 </sup>=|7<sup>2 </sup>= 49|13<sup>2 </sup>=|19<sup>2 </sup>=|
|2<sup>2 </sup>=|8<sup>2 </sup>=|14<sup>2 </sup>=|20<sup>2 </sup>=|
|3<sup>2 </sup>=|9<sup>2 </sup>=|15<sup>2 </sup>=|30<sup>2 </sup>=|
|4<sup>2 </sup>=|10<sup>2 </sup>=|16<sup>2 </sup>=|40<sup>2 </sup>=|
|5<sup>2 </sup>=|11<sup>2 </sup>=|17<sup>2 </sup>=|50<sup>2 </sup>=|

10. Complete the following table of cubes: 

|0<sup>3 </sup>=|3<sup>3 </sup>=|6<sup>3 </sup>=|9<sup>3 </sup>=|
|---|---|---|---|
|1<sup>3 </sup>=|4<sup>3 </sup>= 64|7<sup>3 </sup>=|10<sup>3 </sup>=|
|2<sup>3 </sup>=|5<sup>3 </sup>=|8<sup>3 </sup>=|100<sup>3 </sup>=|

#### 1.4.3 Square Roots 

If there is a number, whose square is the number n, we call it the square root of n, and symbolize it by 

<!-- Start of picture text -->
√n.<!-- End of picture text -->

For example, 2<sup>2</sup> = 4, so 2 is the square root of 4, and we write 

<!-- Start of picture text -->
√4 = 2.<!-- End of picture text -->

Similarly, 3<sup>2</sup> = 9, so 3 is the square root of 9, and we write 

<!-- Start of picture text -->
√9 = 3.<!-- End of picture text -->

Actually, every positive whole number has two square roots, one positive and one negative. The positive square root is called the principal square root, and, for now, when we say square root, we mean the principal one. 

A whole number whose square root is also a whole number is called a perfect square. The first few perfect squares are 1, 4, 9, 16, 25, 36, 49, 64, 81, 100, 121. Clearly, there are lots of whole numbers that are not perfect squares. But these numbers must have square roots. Using our geometric intuition, it is easy to believe that there are geometric squares whose areas are not perfect square numbers. For example, if we want to construct a square whose area is 5 square units, we could start with a square whose area is 4 square units, and steadily expand it on all sides until we get the desired square. 

<!-- Start of picture text -->
32 √5Area=4 Area = 5 Area = 9<!-- End of picture text -->

Page 28 

The side length of the middle square is a number which, when squared, yields 5, that is, √5. We can see that √5 is bigger than √4 = 2, and less than √9 = 3. 

In general, if a whole number lies between two perfect squares, its square root must lie between the two corresponding square roots. 

Example 21. Since 21 lies between the perfect squares 16 and 25, √21 must lie between √16 = 4 and √25 = 5. Example 22. Between what two consecutive whole numbers does √53 lie? 

Solution. Since 53 lies between the perfect squares 49 and 64, the square root √53 must lie between √49 = 7 and √64 = 8. 

#### 1.4.4 Exercises 

Find the square roots: 

1. √49 

2. √81 

3. √169 

4. √121 

5. √64 

Between what two consecutive whole numbers do the following square roots lie? 

##### 6. √19 

7. √75 

<!-- Start of picture text -->
8. √26<!-- End of picture text -->

9. √32 

10. Complete the square-root table: 

|√0 =||= 6|= 12|= 18|
|---|---|---|---|---|
|√1 =||= 7|= 13|= 19|
|√4 =||= 8|= 14|= 20|
|√9 =||= 9|= 15|= 30|
||= 4|= 10|= 16|= 40|
||= 5|= 11|= 17|= 50|

### 1.5 Division of Whole Numbers 

How many times does 23 “go into” 100? Put another way, starting with 100, how many times can we subtract 23 without obtaining a negative number? The answer is easily seen to be 4. Moreover, it is 

Page 29 

easy to see that there is something “left over,” namely, 8. Here are the computations: 

<!-- Start of picture text -->
1 0 0− 2 37 7− 2 35 4− 2 33 1− 2 38<!-- End of picture text -->

This operation (repeated subtraction) is called division. The number we start with (100 in the example) is called the dividend, and the number we repeatedly subtract (23 in the example) is called the divisor. We use the symbol ÷, and note that the dividend is written first: 

dividend ÷ divisor. 

#### 1.5.1 Quotient and Remainder 

Unlike the other three operations (addition, subtraction, multiplication), the result of a division of whole numbers consists of not one but two whole numbers: the number of subtractions performed (4 in the example), and the number left over (8 in the example). These two numbers are called the quotient and the remainder, respectively. 

Whole number divisions with remainder 0 are called exact. For example, 48 ÷ 6 has quotient 8 and remainder 0, so the division is exact and we can write 

<!-- Start of picture text -->
48 ÷ 6 = 8,<!-- End of picture text -->

with the understanding that the remainder is 0. Exact divisions can be restated in terms of multiplication. Subtracting 6 (8 times) from 48 yields exactly 0. On the other hand, starting at 0 and adding 6 (8 times) returns 48. Recalling that multiplication is a shorthand for this kind of repeated addition, we see that the two statements 

<!-- Start of picture text -->
48 ÷ 6 = 8 and 48 = 6 · 8<!-- End of picture text -->

say exactly the same thing. In general, 

<!-- Start of picture text -->
a ÷ b = c and a = b · c<!-- End of picture text -->

are equivalent statements. 

Example 23. Express the statement 72 = 8 · 9 as an exact division in two ways. 

Solution. We can get to 0 by starting at 72 and repeatedly subtracting 8 (9 times), or by repeatedly subtracting 8 (9 times). So, using the division symbol, we can write 

<!-- Start of picture text -->
72 ÷ 8 = 9<!-- End of picture text -->

or we can write 

<!-- Start of picture text -->
72 ÷ 9 = 8.<!-- End of picture text -->

Page 30 

Example 24. The division 63 ÷ 7 is exact. Express this fact using an appropriate multiplication. 

Solution. Since the quotient is 9 and the remainder is 0, we can write 

<!-- Start of picture text -->
63 ÷ 7 = 9 or 63 = 9 · 7.<!-- End of picture text -->

#### 1.5.2 Long Division 

Divisions with multi-digit divisors and/or dividends can get complicated, so we remind you of a standard way (long division) of organizing the computations. Here is what it looks like: 

<!-- Start of picture text -->
quotientdivisor dividend***************remainder<!-- End of picture text -->

The horizontal lines indicate subtractions of intermediate numbers; there is one subtraction for each digit in the quotient. For example, the fact that the division 100 ÷ 23 has quotient 4 and remainder 8 is expressed in the long division form as follows: 

<!-- Start of picture text -->
42 3 1 0 0− 9 28<!-- End of picture text -->

The 4 repeated subtractions of 23 are summarized as the single subtraction of 4 · 23 = 92. 

In long division, we try to estimate the number of repeated subtractions that will be needed, multiply this estimate by the divisor, and hope for a number that is close to, but not greater than, the dividend. It will be easy to see when our estimate is too large, and to adjust it downward. If it is too small, the result of the subtraction will be too big – there was actually “room” for further subtraction. Going back to our example, 100 ÷ 23, it is more or less clear that we will need more than 2 subtractions, since 23 × 2 = 46, which leaves a big remainder of 54 (bigger than the divisor, 23). 23 × 3 = 69, which also leaves a remainder that is too big. Since 23 × 5 = 115, which is bigger than the dividend, 100, we know that the best estimate for the quotient is 4. Now 23 × 4 = 92. We subtract 92 from 100, leaving the remainder 8, which is less than the divisor, as it should be. To check our calculations, we verify that 23 × 4 + 8 = 100. (In this check, the multiplication is done before the addition – this is the standard 

Page 31 

order of operations, which we will say more about later.) 

Let’s try another simple division problem. 

Example 25. Find the quotient and remainder of the division 162 ÷ 42. 

Solution. Putting the dividend and divisor into the long division form, we have 

<!-- Start of picture text -->
4 2 1 6 2<!-- End of picture text -->

Let’s estimate the number of subtractions that we’ll need to perform. 40 goes into 160 four times, so, perhaps four is a good guess. But 4 × 42 = 168, which is too big (bigger than the dividend). So we lower our estimate by 1. We get 3 × 42 = 126, which is less than the dividend, so this must be the right choice. 

<!-- Start of picture text -->
34 2 1 6 2−1 2 6<!-- End of picture text -->

Subtracting, we obtain the remainder 

<!-- Start of picture text -->
34 2 1 6 2−1 2 63 6<!-- End of picture text -->

which is less than the divisor, as it should be. Thus, the quotient is 3 and the remainder is 36. As a check, we verify that 3 × 42 + 36 = 162. (Multiplication before addition.) 

Page 32 

When the dividend is large, estimating the quotient is not so easy. The next example shows how to break the problem down by considering related, but smaller dividends. 

Example 26. Find the quotient and remainder of the division 3060 ÷ 15. 

Solution. If we read the dividend from the left, one digit at a time, we get, successively, the numbers 3, 30, 306, and 3060. Of course, according to the place-value system, these numbers stand for 3 thousands, 30 hundreds, etc., but we do not need to think this way. To find the left-most digit of the quotient, observe that the divisor, 15, does not “go into” 3, but it does go into 30 (2 times, exactly). To indicate this we put, for the first digit of the quotient, the digit 2, directly over the right-most digit (0) in 30: 

<!-- Start of picture text -->
21 5 3 0 6 0<!-- End of picture text -->

Now we compute the product 15 × 2 = 30 and subtract it from the initially selected part of the dividend, i.e., from 30: 

<!-- Start of picture text -->
21 5 3 0 6 0− 3 00<!-- End of picture text -->

In this case, we get a remainder of 0. But we are not done yet. We treat this intermediate remainder as if it were a new dividend. Does 15 “go into” 0? No – we need a larger dividend. To get one, we “bring down” the digit 6: 

<!-- Start of picture text -->
215 3060− 3006<!-- End of picture text -->

Now 06 = 6 (why?), and 15 does not go into 6. More precisely, it goes into it 0 times. We indicate this by putting a 0 directly above the digit 6 in the dividend: 

Page 33 

<!-- Start of picture text -->
2015 3060− 3006<!-- End of picture text -->

Then we bring down the next (and the last) digit (0) of the dividend: 

<!-- Start of picture text -->
2015 3060− 30060<!-- End of picture text -->

This gives us a new dividend of 060 = 60, and 15 goes into 60 four times. So we put down 4 above the final digit in the original dividend. 

<!-- Start of picture text -->
20415 3060− 30060<!-- End of picture text -->

Multiplying 15 by 4, we subtract this product from 60. This final difference is the remainder. 

Page 34 

<!-- Start of picture text -->
20415 3060− 30060−600<!-- End of picture text -->

We have reached the end of our dividend – there are no more digits to bring down. Hence, our division stops. The quotient is 204, and the remainder is 0. We check by verifying that 15× 204+0 = 3060. 

#### 1.5.3 Exercises 

Express each exact division as an equivalent multiplication. 

1. 88 ÷ 22 = 4 

2. 42 ÷ 6 = 7 3. 51 ÷ 17 = 3 

4. 168 ÷ 14 = 12 

5. 96 ÷ 12 = 8 

Find the quotient and remainder of each division. 

6. 37 ÷ 11 

7. 712 ÷ 101 

8. 3007 ÷ 110 

9. 3333 ÷ 111 

10. 3456 ÷ 241 

11. 457 ÷ 41 12. 578 ÷ 19 

13. 317 ÷ 21 14. 907 ÷ 201 15. 712 ÷ 21 

Page 35 

### 1.6 Order of operations 

We often do calculations that involve more than one operation. For example 

<!-- Start of picture text -->
1 + 2 × 3<!-- End of picture text -->

involves both addition and multiplication. Which do we do first? If we do the multiplication first, the result is 1 + 6 = 7, and if we do the addition first, the result is 3 × 3 = 9. Obviously, if we want the expression 

<!-- Start of picture text -->
1 + 2 × 3<!-- End of picture text -->

to have a definite and unambiguous meaning, we need a convention or agreement about the order of operations. It could have been otherwise, but the convention in this case is: 

multiplication before addition. 

With this convention, when I write 1 + 2 × 3, you know that I mean 7 (not 9). The precedence of multiplication can be made explicit using the grouping symbols () (parentheses): 

<!-- Start of picture text -->
1 + (2 × 3) = 1 + 6 = 7.<!-- End of picture text -->

If one of us insists that the addition be done first, we can do that by re-setting the parentheses: 

<!-- Start of picture text -->
(1 + 2) × 3 = 3 × 3 = 9.<!-- End of picture text -->

Thus grouping symbols can be used to force any desired order of operations. Common grouping symbols, besides parentheses, are brackets, [ ], and braces, {}. The square root symbol<sup>√</sup> is also a grouping symbol. For example 

<!-- Start of picture text -->
√4 + 5 = √9 = 3.<!-- End of picture text -->

The<sup>√</sup> symbol acts like a pair of parentheses, telling us to evaluate what is inside (in this case, the sum 4 + 5) first, before taking the square root. 

The order of operations is: 

1. operations within grouping symbols first; 

2. exponents and roots next; 

3. multiplications and divisions (in order of appearance) next; 

4. additions and subtractions (in order of appearance) last. 

“In order of appearance” means in order from left to right. Thus in the expression 

<!-- Start of picture text -->
2 + 5 − 3,<!-- End of picture text -->

the addition comes first, so it is evaluated first, 

<!-- Start of picture text -->
2 + 5 − 3 = 7 − 3 = 4,<!-- End of picture text -->

while in the expression 

<!-- Start of picture text -->
8 − 6 + 11,<!-- End of picture text -->

the subtraction is done first because it comes first, 

<!-- Start of picture text -->
8 − 6 + 11 = 2 + 11 = 13.<!-- End of picture text -->

Page 36 

Example 27. Evaluate 6 · 5 − 4 ÷ 2 + 2. 

Solution. All four operations appear here. There are no grouping symbols, exponents or roots. Following the order of operations, as well as the order of appearance, we do the computations in the following order: multiplication, division, subtraction, addition. The computations are as follows: 

<!-- Start of picture text -->
6 · 5 − 4 ÷ 2 + 2 =30 − 4 ÷ 2 + 2 =30 − 2 + 2 =28 + 2 =30<!-- End of picture text -->

In the next two examples, we use the same numbers and the same operations, but we insert grouping symbols to change the order of operations. As expected, this changes the final result. 

Example 28. Evaluate 6 · (5 − 4) ÷ 2 + 2. 

Solution. The grouping symbols force us to do the subtraction first. After that, the usual order of operations is followed. 

<!-- Start of picture text -->
6 · (5 − 4) ÷ 2 + 2 =6 · 1 ÷ 2 + 2 =6 ÷ 2 + 2 =3 + 2 =5<!-- End of picture text -->

Example 29. Evaluate 6 · 5 − 4 ÷ [2 + 2]. 

Solution. Now the grouping symbols (brackets) force us to do the addition first. 

<!-- Start of picture text -->
6 · 5 − 4 ÷ [2 + 2] =6 · 5 − 4 ÷ 4 =30 − 4 ÷ 4 =30 − 1 =29<!-- End of picture text -->

In the next example, there are grouping symbols within grouping symbols. The strategy here is to work from the inside outward. 

Example 30. Evaluate 6<sup>2</sup> − [3 + (3 − 1)]<sup>2</sup> . 

Page 37 

Solution. We have parentheses within brackets. The parentheses enclose up the innermost group, which is where we start. (That is what “from the inside outward” means.) Thus the first operation to be done is 3 − 1 = 2, yielding 

<!-- Start of picture text -->
6 2 − [3 + 2] 2 .<!-- End of picture text -->

Next, the bracketed group, [3 + 2] is evaluated, yielding 

<!-- Start of picture text -->
6 2 − 5 2 .<!-- End of picture text -->

At this point, there are no more grouping symbols, and the order of operations tells us to evaluate the expressions with exponents next, yielding 

<!-- Start of picture text -->
36 − 25.<!-- End of picture text -->

All that is left is the remaining subtraction, 

<!-- Start of picture text -->
36 − 25 = 11.<!-- End of picture text -->

Example 31. Evaluate �(11 − 5)<sup>2</sup> + (24 ÷ 2 − 4)<sup>2</sup> . 

Solution. We evaluate the two inner groups (11 − 5) and (24 ÷ 2 − 4) first. In the second group, division precedes subtraction, yielding 12 − 4 = 8. Thus the expression is reduced to 

<!-- Start of picture text -->
�6 2 + 8 2 .<!-- End of picture text -->

Next we evaluate the two expressions with exponents, obtaining 

<!-- Start of picture text -->
√36 + 64.<!-- End of picture text -->

Then, remembering that<sup>√</sup> is a grouping symbol, we evaluate the group 36 + 64 = 100, and finally, evaluate the square root 

<!-- Start of picture text -->
√100 = 10.<!-- End of picture text -->

#### 1.6.1 Exercises 

Evaluate the expressions using the correct order of operations. 

1. 6 + 16 ÷ 4 

2. 16 · 4 − 48 

3. 15 − 9 − 4 4. 2 · 6 + 2(√36 − 1) 5. 4 × 3 × 2 ÷ 8 − 3 6. (2 · 5)<sup>2</sup> 7.<sup>√</sup> 21 − 30 ÷ 6 8. [18 ÷ (9 ÷ 3)]<sup>2</sup> 9. 2 + 2 × 8 − (4 + 4 × 3) 

Page 38 

### 1.7 Average 

The average of 2 numbers is their sum, divided by 2. The average of 3 numbers is their sum, divided by 3. In general, the average of n numbers is their sum, divided by n. 

Example 32. Find the average of each of the following multi-sets of numbers. (A multi-set is a set in which the same number can appear more than once.) (a) {10, 12}; (b) {5, 6, 13}; (c) {8, 12, 9, 7, 14}. 

Solution. In each case, we take the sum of all the numbers in the multi-set, and then (following the order of operations), divide by number of numbers: 

<!-- Start of picture text -->
(a) (10 + 12) ÷ 2 = 11; (b) (5 + 6 + 13) ÷ 3 = 8; (c) (8 + 12 + 9 + 7 + 14) ÷ 5 = 10.<!-- End of picture text -->

The average of a multi-set of numbers is a description of the whole multi-set, in terms of only one number. If all the numbers in the multi-set were the same, the average would be that number. For example, the average of the multi-set {5, 5, 5} is 

<!-- Start of picture text -->
(5 + 5 + 5) ÷ 3 = 5,<!-- End of picture text -->

and the average of the multi-set {2, 2, 2, 2, 2, 2} is 

<!-- Start of picture text -->
(2 + 2 + 2 + 2 + 2 + 2) ÷ 6 = 2.<!-- End of picture text -->

This gives us another way to define the average of a multi-set of n numbers: it is that number which, added to itself n times, gives the same total sum as the sum of all the original numbers in the multi-set. 

#### 1.7.1 Exercises 

Find the average of each of the following multi-sets of numbers. 

1. {1, 2, 3, 4, 5, 6, 7} 

2. {13, 13, 19, 15} 

3. {206, 196, 204} 

4. {85, 81, 92} 

5. A baseball team had 7 games cancelled due to rain in the 2010 season. The number of cancelled games in the 2002-2009 seasons were 5, 6, 2, 10, 9, 4, 6, 5. What was the average number of cancelled games for the 2002-2010 seasons? 

6. Suppose the average of the multi-set {20, 22, N, 28} is 25, where N stands for an unknown number. Find the value of N. 

Page 39 

### 1.8 Perimeter, Area and the Pythagorean Theorem 

Squares and rectangles are examples of polygons – closed shapes that can be drawn on a flat surface, using segments of straight lines which do not cross each other. “Closed” means that the line segments form a boundary, with no gaps, which encloses a unique “inside” region, and separates it from the “outside” region. 

Example 33. Which of the following figures are polygons? 

<!-- Start of picture text -->
(a) (b) (c) (d) (e)<!-- End of picture text -->

Solution. (b) is not a polygon since not all of its sides are straight lines. (c) is not a polygon because it does not have a unique ”inside” region. (d) is not a polygon because it is not closed. 

There are two useful numerical quantities associated with a polygon: the perimeter, which is the length of its boundary, and the area, which is (roughly speaking) the “amount of space” it encloses. Perimeters are measured using standard units of length such as feet (ft), inches (in) , meters (m), centimeters (cm). Areas are measured using square units, such as square feet (ft<sup>2</sup> ), square inches (in<sup>2</sup> ), square meters (m<sup>2</sup> ), square centimeters (cm<sup>2</sup> ). 

To find the perimeter of a polygon, we simply find the sum of the lengths of its sides. 

Example 34. Find the perimeter of each polygon. Assume the lengths are measured in feet. 

<!-- Start of picture text -->
64 11(a) (b) 1 535 175<!-- End of picture text -->

Solution. Adding the lengths of the sides, we find that the perimeter of polygon (a) is 

<!-- Start of picture text -->
3 + 4 + 1 + 5 + 5 = 18 ft.<!-- End of picture text -->

Similarly, the perimeter of the polygon (b) is 

<!-- Start of picture text -->
7 + 5 + 6 + 1 + 1 + 1 = 21 ft.<!-- End of picture text -->

Page 40 

Finding the area of a polygon can be complicated, but it is quite simple if the polygon can be divided up into rectangles. A rectangle is a four-sided polygon with two pairs of opposite parallel sides, and “square” corners. The square corners – also known as right angles – imply that the paired opposite sides have the same length. The length of the shorter pair of sides is often called the width and denoted w , and the length of the longer pair is called the length and denoted l . 

<!-- Start of picture text -->
lwidth = w wlength = l<!-- End of picture text -->

The small squares in the corners are there to indicate that the polygon is a rectangle. 

Example 35. Estimate the area of the rectangle below, if the square in the upper left corner is 1 unit on a side. 

<!-- Start of picture text -->
l11width = w wlength = l<!-- End of picture text -->

Solution. If the corner square is 1 unit on a side, the area of the rectangle is the number of squares of that size that fit inside the rectangle. As the next figure shows, 21 such square units fit inside, in 3 rows of 7. The width (w ) is evidently 3 units, and the length (l ) 7 units. The area is the product 3 × 7 = 21 square units. 

<!-- Start of picture text -->
7width = 3 3length = 7<!-- End of picture text -->

The example illustrates a general fact: the area of a rectangle is the product of the length and 

Page 41 

the width. If A denotes the area, the formula is 

<!-- Start of picture text -->
A = l · w .<!-- End of picture text -->

It is also clear that the perimeter of a rectangle is the sum of twice the length and twice the width, since to travel all the way around the boundary of the rectangle, both the length and the width must be traversed twice. If P denotes the perimeter, the formula is 

<!-- Start of picture text -->
P = 2l + 2w .<!-- End of picture text -->

Example 36. In the figure below we have drawn an L-shaped polygon on a grid. Find the area and perimeter of the polygon. Take the unit of area to be one of the large squares of the grid, and assume these squares are 1 cm on a side. 

<!-- Start of picture text -->
98765432100 1 2 3 4 5 6 7 8<!-- End of picture text -->

Solution. Using the grid, it is easy to find the lengths of all six sides of the polygon. For example, the left-hand vertical side is 7 cm long (stretching from 1 to 8 on the scale at left), and the top side is 2 cm long. Continuing clockwise around the L-shape, we see that the side lengths are 

<!-- Start of picture text -->
7, 2, 5, 4, 2, 6 cm,<!-- End of picture text -->

respectively. From this, it follows easily that the perimeter P is given by the sum 

<!-- Start of picture text -->
7 + 2 + 5 + 4 + 2 + 6 = 26 cm.<!-- End of picture text -->

To find the area, we draw a line which divides the L-shape into two rectangles (labeled R1 and R2) in the figure below. (We could have drawn a different line to obtain a different division into two rectangles – do you see it?) 

Page 42 

<!-- Start of picture text -->
7 R1R2 22 4<!-- End of picture text -->

It is evident that R1 has length 7 cm and width 2 cm. So the area of R1 is 

<!-- Start of picture text -->
A1 = 2 · 7 = 14 cm 2 .<!-- End of picture text -->

Similarly, since the length of R2 is 4 cm and the width is 2 cm, the area of R2 is 

<!-- Start of picture text -->
A2 = 2 · 4 = 8 cm 2 .<!-- End of picture text -->

It is visually obvious that the total area A of the L-shaped polygon is the sum A1 + A2 of the areas of R1 and R2. Thus 

<!-- Start of picture text -->
A = 14 cm 2 + 8 cm 2 = 22 cm 2 .<!-- End of picture text -->

Using the grid, you can easily verify this result by counting the number of large squares inside the polygon. 

The grid is not necessary, as long as we are given enough side-lengths, and assume square corners. 

Example 37. Find the area and perimeter of the right-angled (square-cornered) polygon below. Assume the side lengths are measured in feet. 

Page 43 

<!-- Start of picture text -->
526315<!-- End of picture text -->

Solution. There are some missing side lengths (for example, the vertical side on the upper right), but the area can be determined without them, using subtraction. We can visualize the polygon as a large rectangle of length 6 ft. and width 5 ft, out of which a rectangular “bite,” of length 3 ft and width 2 ft, has been taken. 

<!-- Start of picture text -->
5263 “bite”15<!-- End of picture text -->

The area of the large rectangle (bite included) is 6 · 5 = 30 ft<sup>2</sup> , and the area of the bite alone is 3 · 2 = 6 ft<sup>2</sup> . Thus the area of the original polygon is 

<!-- Start of picture text -->
30 − 6 = 24 ft 2 .<!-- End of picture text -->

To find the perimeter, we need the missing side lengths. For the vertical side on the upper right, we reason as follows. The left edge is 6 ft, and so the total length of all the right vertical edges must also be 6 ft. The two known vertical edges on the right have lengths 1 and 3, and the unkown edge must 

Page 44 

make up the difference. So its length must be 

<!-- Start of picture text -->
6 − (1 + 3) = 2 ft.<!-- End of picture text -->

The other missing side (the short horizontal one) is 2 ft. Adding up all the side lengths, starting (arbitrarily) with the bottom edge and proceeding counter-clockwise, yields the perimeter: 

<!-- Start of picture text -->
5 + 1 + 2 + 3 + 2 + 2 + 5 + 6 = 26 ft.<!-- End of picture text -->

If we cut a rectangle in two by drawing a diagonal from one corner to the opposite corner, we get two right triangles, each having exactly the same size and shape, and therefore the same area. 

Right triangles are interesting in their own right, and we often consider them in isolation, without reference to the rectangle they came from. The side of a right triangle that is opposite the right angle (the longest side) is known as the hypotenuse. The two shorter sides are called the legs. In the figure below, the legs are labeled a and b, and the hypotenuse is labeled c. 

<!-- Start of picture text -->
cab<!-- End of picture text -->

A famous formula, called the Pythagorean theorem, states that, in any right triangle with legs of length a and b, and hypotenuse of length c, the following relation holds: 

<!-- Start of picture text -->
a 2 + b 2 = c 2 .<!-- End of picture text -->

We can use this to obtain a formula for the length of the hypotenuse of a right triangle in terms of the lengths of the legs. 

<!-- Start of picture text -->
c = �a 2 + b 2 .<!-- End of picture text -->

Page 45 

Since the area of a right triangle is exactly half the area of the rectangle it came from, it follows that the area of a right triangle is the product of the lengths of the legs, divided by 2. If A denotes the area, and the lengths of the legs are a and b as in the figure, the formula is 

<!-- Start of picture text -->
A = (a · b) ÷ 2.<!-- End of picture text -->

Example 38. Find the area and perimeter of a triangle whose legs have length 3 feet and 4 feet. 

Solution. Putting a = 4 and b = 3, we find the area using the formula 

<!-- Start of picture text -->
A = (a · b) ÷ 2 = (4 · 3) ÷ 2 = 12 ÷ 2 = 6 ft 2 .<!-- End of picture text -->

To find the perimeter, we first find the length of the hypotenuse using the formula 

<!-- Start of picture text -->
c = �a 2 + b 2 = �4 2 + 3 2 = √16 + 9 = √25 = 5 ft.<!-- End of picture text -->

Thus the perimeter is a + b + c = 4 ft +3 ft +5 ft = 12 ft. 

Now we can find the area and perimeter of any polygon that can be divided up into rectangles and right triangles. 

Example 39. Find the area and perimeter of the polygon below. The large squares of the grid measure 1 centimeter (cm) on a side. 

<!-- Start of picture text -->
432100 1 2 3 4 5 6 7 8 9 10<!-- End of picture text -->

Solution. Drawing two vertical lines, we can divide up the polygon into two right triangles, T1 and T2, and a rectangle, R. 

<!-- Start of picture text -->
432 R T2T1100 1 2 3 4 5 6 7 8 9 10<!-- End of picture text -->

Page 46 

The rectangle has length 6 cm and width 2 cm, so it has area 6 · 2 = 12 cm<sup>2</sup> . Both triangles have legs of length 1 and 2, so the area of each is (2 · 1) ÷ 2 = 1 cm<sup>2</sup> . Adding the three areas gives the total area of the polygon: 1 + 12 + 1 = 14 cm<sup>2</sup> . To find the perimeter, we use the Pythagorean theorem to find the lengths of the two slanted sides: 

Thus the perimeter is 

<!-- Start of picture text -->
c = �a 2 + b 2 = �1 2 + 2 2 = √5.√5 + 7 + √5 + 7 = 14 + 2√5 cm.<!-- End of picture text -->

Since √5 is not an integer, we do not simplify the expression further. But we can make the following estimate: Since √5 is between 2 and 3, 2√5 is between 4 and 6, and it follows that the perimeter is between 18 and 20 centimeters. 

#### 1.8.1 Exercises 

1. Find the area of a right triangle whose legs are 5 in and 12 in. 

2. Find the perimeter of the right triangle in the previous example. 

3. Find the area of a rectangle whose length is 8 ft and whose width is 7 feet. 

4. Find the perimeter of the rectangle in the previous example. 

5. Find the length of the diagonal of a square which is 2 cm on a side. Between what two whole numbers does the answer lie? 

6. Find the area and perimeter of the polygon below. 

<!-- Start of picture text -->
8765432100 1 2 3 4 5 6 7<!-- End of picture text -->

Page 47 

Page 48 

## Chapter 2 - Fractions and Mixed Numbers 

Fractions are expressions such as 

<!-- Start of picture text -->
3 aor more generally19 b ,<!-- End of picture text -->

where a and b are whole numbers, and b̸ = 0. The numbers a and b are called terms. The term on top is called the numerator, and the term on the bottom is called the denominator. The horizontal line in the middle is called the fraction bar. Sometimes to save space, we write fractions in one line, using a slash instead of the fraction bar, putting the numerator on the left and the denominator on the right: 

<!-- Start of picture text -->
ab = a/b.<!-- End of picture text -->

When reading a fraction out loud, we attach the suffix th or ths to the denominator, saying “a bths” for a/b. 

Example 40. The fractions 8<sup>1and</sup> 136<sup>arespoken“oneeighth,”and“sixthirteenths,”respectively.</sup> 

If the denominator is 2 or 3, we say “halves” or “thirds” (not twoths or threeths!), respectively. If the denominator is 4, we sometimes say “fourths,” and sometimes, ”quarters.” 

Example 41. 5/2 is spoken “five halves.” 4/3 is spoken “four thirds.” 3/4 is spoken “three fourths,” or “three quarters.” 

Sometimes, instead of using the th suffix, we just say “a over b.” Thus 4/9 can be spoken as “four ninths,” or just ”four over nine.” 

### 2.1 What fractions mean 

Fractions represent parts of a whole in a precise way. In the fraction a/b, the denominator b represents the number of equal parts into which the whole has been divided, and the numerator represents how many of those parts are being taken into account. For example, if a rectangle is divided up into 3 equal parts, and 2 of those parts are shaded, then the shaded portion represents<sup>2</sup> 3<sup>(two-thirds)ofthewhole</sup> rectangle. 

49 

<!-- Start of picture text -->
× ×× ×23<!-- End of picture text -->

We can divide any convenient figure into equal parts (not just a rectangle), to represent a fraction. For example, the circle below has been divided into 5 equal “wedges,” and three of them are shaded. So the picture represents the fraction<sup>3</sup> 5<sup>.</sup> 

Example 42. Use a square to represent the fraction 5/16. 

Solution. Since 16 is a perfect square, it’s easy to make a square 4 units on a side, and divide that into 16 small squares of equal size. Then we shade 5 of them (any 5 will do) to represent 5/16. 

### 2.2 Proper and Improper Fractions 

A fraction is called proper if its numerator is less than its denominator. A proper fraction represents less than one whole. An improper fraction has a numerator that is greater than or equal to the denominator and represents a number that is greater than (or equal to) one whole. 

Page 50 

Example 43. The figure below represents three fractions with denominator 9: the first one (2/9) is proper, representing a number less than 1. The other two are improper. The one in the middle (9/9) represents the whole number 1. The last (10/9) represents a number that is greater than 1. 

<!-- Start of picture text -->
2 9 109 9 = 1 9 = 1 + 9 1<!-- End of picture text -->

9/9 = 1 illustrates the general fact that the whole number 1 can be represented in infinitely many ways as a fraction – just take any fraction whose numerator and denominator are equal. For example, 

<!-- Start of picture text -->
1 = 2 2 = 9 9 = 159 159 .<!-- End of picture text -->

Intuitively, if an object is divided into equal parts, and all the parts are taken, then, in fact, the whole (1 whole) has been taken. 

<!-- Start of picture text -->
For any whole number a (except 0),aa = 1.<!-- End of picture text -->

Any whole number can be represented as a fraction. For example, to represent the whole number 3, we can think of three whole rectangles, each “divided” into 1 “part,” and write 

<!-- Start of picture text -->
3 = 31 .<!-- End of picture text -->

More generally, 

<!-- Start of picture text -->
For any whole number a (including 0),a = a1 .<!-- End of picture text -->

#### 2.2.1 Zero as Numerator and Denominator 

The whole number 0 can be written as a fraction in infinitely many ways: 

<!-- Start of picture text -->
0 = 0 for any non-zero b.b ,<!-- End of picture text -->

Page 51 

It is easy to understand why this is true: you can divide something into any number of equal pieces (say, b of them), but if you take none of them, you have taken an amount equal to 0 – no matter the value of b. Thus, 

<!-- Start of picture text -->
0 = 1 0 = 0 2 = 0 3 = ...<!-- End of picture text -->

So 0 can certainly be the numerator of a fraction. Can it be the denominator? The answer is no. Here is one way to think about it: does it make sense to divide something into 0 pieces? (1 piece, yes, but 0 pieces?) A related question is: Can 0 be the divisor in a division problem? If you think so, then answer this: how many times does 0 go into 7? Thinking back to our original definition of division as repeated subtraction, the question is “how many times can 0 be subtracted from 7 before we arrive at a negative number?” The answer is “as many times as you like!,” since subtracting 0 has no effect on 7, or any other number. For these reasons we attach no meaning to a fraction with denominator 0, saying, if it comes up, that it is undefined. 

<!-- Start of picture text -->
For any whole number n, including 0, the fraction n0 is un-defined.<!-- End of picture text -->

There is another reason why 0 cannot be the denominator of a fraction. Multiplication and division are mutually inverse operations, meaning that the equation b<sup>a= cis equivalent to the equation a = b ·c</sup> whenever b̸ = 0. Suppose we could assign a numerical value to the fraction 1/0, say, 0<sup>1=1.That</sup> would mean that 1 = 0 · 1. But of course, 0 · 1 = 0, so we arrive at 1 = 0, an obvious contradiction. 

#### 2.2.2 Exercises 

1. What improper fraction does the following picture represent? 

<!-- Start of picture text -->
+ +<!-- End of picture text -->

Use rectangles, circles, or squares to represent the following fractions. 

<!-- Start of picture text -->
2. 323. 344. 585. 1166. 437. 62<!-- End of picture text -->

8. Write five fractions which are equal to 1. 

Page 52 

9. Write five fractions which are equal to 0. 

10. Write 15 as a fraction. 

### 2.3 Mixed Numbers 

We have seen that an improper fraction represents either a whole number or a whole number plus a proper fraction. In the latter form, it is called a mixed number. Even though it is a sum, the + sign is omitted. Thus 

<!-- Start of picture text -->
3 12<!-- End of picture text -->

represents 3 “wholes” plus an extra<sup>1</sup> 2<sup>.</sup> 

#### 2.3.1 Converting an improper fraction into a mixed or whole number 

Suppose we have an improper fraction 

<!-- Start of picture text -->
numeratordenominator .<!-- End of picture text -->

To convert this to a mixed number, we simply perform the division 

##### numerator ÷ denominator, 

obtaining a quotient and a remainder. Then we use these to build the mixed number as follows: the quotient is the whole number part; the remainder over the divisor is the fractional part. Note that the fractional part obtained in this way is always proper, because the remainder is always smaller than the divisor. Summarizing: 

<!-- Start of picture text -->
denominatornumerator = quotientremainder divisor<!-- End of picture text -->

Example 44. Write the improper fraction 13/3 as a mixed number. 

Solution. Dividing 13 by 3 yields a quotient of 4 and a remainder of 1. The corresponding mixed number has whole number part 4 and fractional part 1/3. Thus 

<!-- Start of picture text -->
133 = 41 3 .<!-- End of picture text -->

If the remainder is 0, the mixed number is actually just a whole number. 

Example 45. Write the improper fraction 84/7 as a mixed number. 

Page 53 

Solution. Dividing 84 by 7 yields a quotient of 12 and a remainder of 0. Thus 

<!-- Start of picture text -->
847 = 120 7 = 12,<!-- End of picture text -->

a whole number. 

Here are some everyday uses of mixed numbers. 

Example 46. Five hikers want to share seven chocolate bars fairly. How many bars does each hiker get? 

Solution. For fairness, each of the five hikers should get the same amount: exactly one fifth of the chocolate. There are seven bars, so the amount (in chocolate bars) that each hiker should get is 

<!-- Start of picture text -->
57 = 12 5 .<!-- End of picture text -->

Each hiker gets 1<sup>2</sup> 5<sup>chocolatebars.</sup> 

Example 47. Julissa waited 5 minutes for the train on Monday, 2 minutes on Tuesday, and then 4, 8, and 3 minutes on Wednesday, Thursday, and Friday, respectively. What was her average wait time for the week? 

Solution. Recall that the average of a set of numbers is their sum, divided by the number of numbers. In this case, we want the average of the five numbers {5, 2, 4, 8, 3}, which is 

<!-- Start of picture text -->
5 + 2 + 4 + 8 + 3 = 225 5 = 42 5 .<!-- End of picture text -->

Her average wait time was 4<sup>2</sup> 5<sup>minutes.(Extra credit:how long is two fifths of a minute, in seconds?)</sup> 

#### 2.3.2 Exercises 

Convert the following improper fractions into mixed numbers: 

1.<sup>19</sup> 3 2.<sup>11</sup> 2 3.<sup>135</sup> 5 4.<sup>99</sup> 98 

5.<sup>77</sup> 5 

Use mixed numbers to answer the following questions: 

6. Three boys share four sandwiches fairly. How many sandwiches does each boy get? 

7. What is the average of the set of numbers {11, 14, 9, 12}? 

8. During the first seven days of January, Bill travels 31, 37, 46, 31, 77, 50 and 40 miles respectively. What is his average daily travel distance? 

Page 54 

#### 2.3.3 Converting a mixed or whole number to an improper fraction 

Sometimes we need to change a mixed number back into an improper fraction. The key fact, again, is that the fraction 

<!-- Start of picture text -->
aa<!-- End of picture text -->

is always equal to 1, for any number a except 0. For example, 

<!-- Start of picture text -->
33 = 1.<!-- End of picture text -->

Example 48. Convert the mixed number 2<sup>1</sup> 3<sup>toanimproperfraction,usingthefactthat</sup> 3<sup>3= 1.</sup> 

Solution. Think of the whole number 2 in the following way: 

<!-- Start of picture text -->
2 = 1 + 1 = 3 3 + 3 3 .<!-- End of picture text -->

It follows that the mixed number 2<sup>1</sup> 3<sup>canbewritten</sup> 

<!-- Start of picture text -->
33 + 3 3 + 1 3 .<!-- End of picture text -->

The figure below should make it clear that this sum is equal to the improper fraction 3<sup>7.</sup> 

<!-- Start of picture text -->
+ + = 731 = 3 1 = 3 13 3 3<!-- End of picture text -->

(The figure also demonstrates that fractions with the same denominator add up to a new fraction, with the same denominator, and a numerator which is the sum of all the old numerators. We’ll say more about adding fractions later. ) 

The procedure in the previous example is easily turned into a general formula. 

<!-- Start of picture text -->
The mixed number N  p q is equal to the improper fraction N · q q  + p .<!-- End of picture text -->

Remember to follow the order of operations (multiplication before addition) when evaluating N · q + p. Example 49. Convert the mixed number 8 3<sup>2intoanimproperfraction,usingtheboxedrule.</sup> 

Page 55 

Solution. 

<!-- Start of picture text -->
8 2 3 = 8 · 3 + 2 3 = 24 + 2 3 = 26 3 .<!-- End of picture text -->

Example 50. Write the whole number 8 as an improper fraction in three different ways. 

Solution. We can think of the whole number 8 as the “mixed” number 8<sup>0</sup> q<sup>foranynonzeroq.Bythe</sup> 

boxed rule, 

<!-- Start of picture text -->
8 = 8 · q + 0 = 8 · qq q .<!-- End of picture text -->

Picking three nonzero numbers for q, say, 2, 5 and 10, we get 

<!-- Start of picture text -->
8 = 8 · 2 = 16 8 = 8 · 5 = 40 and 8 = 8 · 10 = 802 2 , 5 5 , 10 10 .<!-- End of picture text -->

#### 2.3.4 Exercises 

Convert the mixed numbers into improper fractions: 

<!-- Start of picture text -->
1. 1 122. 8 133. 15 384. 5 345. 11 56Using N = N · q for any nonzero q, write three fractions equal to each given whole number:q6. 5<!-- End of picture text -->

7. 11 

8. 10 

Page 56 

### 2.4 Multiplication of Fractions 

Fractions are numbers in their own right, and we will recall how to add, subtract, multiply and divide them. We begin with multiplication, since it is one of the easiest operations to perform. 

We understand what it means to take, let’s say, a third of something: divide it into three pieces, and take one of the pieces. Similarly, to take three-fourths of something, divide it into four pieces, and take three of them. What if the “something” is itself a fraction? For example, what is three fourths of 2 3<sup>?Itissomefraction,butwhichone?</sup> 

We’ll try to make sense of this question by representing fractions as shaded portions of rectangles. Represent the fraction<sup>2</sup> 3<sup>usingarectangledividedinto3equalverticalparts,with2ofthemshaded.</sup> Divide the same rectangle into 4 equal horizontal parts, and shade 3 of them (using a different shading). The double-shaded portion represents the desired fraction,<sup>3</sup> 4<sup>of2</sup> 3<sup>.Bycounting,youcanseethatit</sup> consists of 6 out of 12 smaller rectangles. 

<!-- Start of picture text -->
× ×× ×23The pictures show that 3 4 of 3 2 is the fraction 12 6 .<!-- End of picture text -->

<!-- Start of picture text -->
× ×34 × ×× ×<!-- End of picture text -->

Example 51. What is one half of one third? 

Solution. Start with a rectangle divided into 3 equal vertical parts, and shade one of the parts, to represent the fraction 1/3. Then divide the whole rectangle horizontally into 2 equal parts, and shade one of the horizontal parts using a different shading. The rectangle is now cut into 2 · 3 = 6 equal parts, and the two shadings overlap in precisely 1 of the 6 parts. 

<!-- Start of picture text -->
× ×× ×13<!-- End of picture text -->

<!-- Start of picture text -->
× ×12× ×× ×12 · 1 3 = 1 6<!-- End of picture text -->

Thus 2<sup>1of1</sup> 3<sup>isthefraction</sup> 6<sup>1.</sup> 

The two examples illustrate a simple rule for finding a “fraction of a fraction,” or b<sup>aof</sup> d<sup>c.Thenew</sup> denominator is the product of the denominators of the two original fractions, since dividing a rectangle into b vertical parts and also d horizontal parts results in b · d smaller rectangular parts. Each of the 

Page 57 

a shaded vertical rectangles is divided into d parts of which c are differently shaded. Hence there are a · c doubly shaded smaller rectangles, so that a · c is the new numerator. The rule is 

<!-- Start of picture text -->
a c a · cof =b d b · d .<!-- End of picture text -->

We use this rule to define multiplication of fractions, replacing “of” by the multiplication symbol · (or ×): 

<!-- Start of picture text -->
ba · d c = b a  ·  ·  d  c<!-- End of picture text -->

In words: The product of two fractions is the product of the numerators over the product of the denominators. 

Example 52. Find the product<sup>3</sup> 8<sup>·5</sup> 7<sup>.</sup> 

Solution. Using the boxed rule, 

<!-- Start of picture text -->
38 · 5 7 = 3 8  ·  ·  5  7 = 56 15 .<!-- End of picture text -->

It is easy to see that fraction multiplication is just an expanded version of whole number multiplication, since every whole number is a fraction with denominator 1. Thus the boxed rule applies when one (or both!) of the multiplicands is a whole number. 

Example 53. What is two thirds of five? That is, find the product<sup>2</sup> 3<sup>· 5.</sup> 

Solution. Writing 5 as the fraction 5/1 and using the fraction multiplication rule, we get 

<!-- Start of picture text -->
23 · 5 1 = 2 3  ·  ·  5  1 = 10 3 .<!-- End of picture text -->

Example 54. One third of a twelve-member jury are women. How many women are on the jury? 

Solution. One third of twelve equals<sup>1</sup> 3<sup>·12</sup> 1<sup>=12</sup> 3<sup>= 4.Therearefourwomenonthejury.</sup> 

You may have noticed that in our very first example with rectangles, 

<!-- Start of picture text -->
34 · 2 3 = 12 6 ,<!-- End of picture text -->

exactly half of the rectangle ends up doubly-shaded (6 is half of 12). So it is correct (and simpler) to say that 

<!-- Start of picture text -->
34 · 2 3 = 2 1 .<!-- End of picture text -->

Does this contradict our rule? No, because 1/2 and 6/12 represent the same number. We’ll explain this, and examine some other technical details regarding the representation of fractions, in the next sections. Then we’ll continue with the arithmetic (division, addition, subtraction) of fractions. 

Page 58 

#### 2.4.1 Exercises 

Find the following products. (Just use the fraction product rule – no need to draw rectangles.) 

- 1 

- 1. 3<sup>·</sup> 7<sup>5</sup> 

2. One half of one half 

3. Two thirds of one third 3 

4. 4<sup>·</sup> 4<sup>3</sup> 

<!-- Start of picture text -->
5. 3 · 586.�32 �217.2 · 8 7 · 3<!-- End of picture text -->

### 2.5 Equivalent Fractions 

Fractions which look very different can represent the same number. For example, the fractions 

<!-- Start of picture text -->
2 5 64 , 10 , 12 , and 100 50<!-- End of picture text -->

all represent the number<sup>1</sup> 2<sup>.Whatpropertydoallthesefractionsshare?Eachhasadenominatorthat</sup> is exactly twice its numerator; the simplest fraction with this property is<sup>1</sup> 2<sup>.</sup> 

2<sup>.</sup> 

Fractions which represent the same number are called equivalent, and we use the equal sign to indicate this. Thus, for example, 

<!-- Start of picture text -->
12 = 100 50 .<!-- End of picture text -->

There is an easy way to tell when two fractions are equivalent. We give it here because it is so simple and pleasing, but we postpone the explanation until we discuss proportions. 

<!-- Start of picture text -->
aif (and only if) a · d = b · c.b = d c<!-- End of picture text -->

In words: two fractions are equivalent if (and only if) their cross-products are equal. A cross-product is the product of the numerator of one fraction and the denominator of the other. 

Starting with a given fraction, we can generate equivalent fractions easily, using the fact that 1 is the multiplicative identity, and that 

<!-- Start of picture text -->
1 = cc<!-- End of picture text -->

<!-- Start of picture text -->
for any non-zero c. Thenba = b a · 1 = b a · c c ,<!-- End of picture text -->

and so we have 

Page 59 

#### The Fundamental Property of Fractions: 

If we multiply both the numerator and denominator of a fraction by any nonzero c, then the new fraction is equivalent to the original one, and represents the same number: 

<!-- Start of picture text -->
ba = b a ·  ·  c  c .<!-- End of picture text -->

Example 55. Write two fractions equivalent to 3<sup>2.</sup> 

Solution. We use the fact that 

<!-- Start of picture text -->
23 = 3 2  ·  ·  c  c<!-- End of picture text -->

for any nonzero c. Picking two values for c, say, 6 and 7, we get two fractions equivalent to 2/3: 

<!-- Start of picture text -->
2 2and3 = 3 2  ·  ·  6  6 = 12 18 3 = 2 3  ·  ·  7  7 = 14 21 .<!-- End of picture text -->

Of course, other choices of c would have produced other fractions equivalent to 2/3. 

#### 2.5.1 Cancellation and Lowest Terms 

The boxed rule above produces equivalent fractions with higher (larger) terms. It is sometimes possible to go the other way, producing lower (smaller) terms. If both numerator and denominator have a common factor – a whole number greater than 1 which divides them both with zero remainder – we can “cancel” it by division. The two quotients become the terms of an equivalent fraction with lower terms. For example, the numerator and denominator of 24<sup>18havethecommonfactor6.Thus</sup> 

<!-- Start of picture text -->
2418 = 18 24  ÷  ÷  6  6 = 4 3 .<!-- End of picture text -->

In general, 

For any non-zero c, 

<!-- Start of picture text -->
ba = b a ÷  ÷  c  c .<!-- End of picture text -->

This method of obtaining lower terms is called cancellation or cancelling out. It is often indicated as follows: 

<!-- Start of picture text -->
> 318 18 = 324 = > 4 4 .24<!-- End of picture text -->

This is useful short-hand, but it has one disadvantage: the common factor (6, in this case) is not made visible. To ensure accuracy, you can show the common factor explicitly, before cancelling it. Thus, explicitly, 

<!-- Start of picture text -->
2418 = 4 3  ·  ·  6  6 = 3 · ��6 = 3 4 .4 · �6 �<!-- End of picture text -->

Page 60 

Example 56. Find lower terms for the fraction 70<sup>28.</sup> 

Solution. Since 7 is a common factor of the numerator and denominator, it can be cancelled, yielding 

<!-- Start of picture text -->
> 428 = 4 (cancelling 7).> 10 1070<!-- End of picture text -->

Still lower terms are possible, since 4 and 10 have the common factor 2: 

<!-- Start of picture text -->
> 24 = 2 (cancelling 2).> 5 510<!-- End of picture text -->

If the only common factor of the numerator and denominator is 1, then no further reduction is possible, and the fraction is said to be in lowest terms. For example, 2 and 5 have no common factor other than 1, so the fraction<sup>2</sup> 5<sup>,andalsotheimproper</sup> 2<sup>5,areinlowestterms.</sup> Example 57. Reduce the fraction 36<sup>24tolowestterms.</sup> 

Solution. A common factor of the numerator and denominator is 4, so we can reduce the terms as follows: 

<!-- Start of picture text -->
> 624 24 = 6 (cancelling 4);36 = > 9 936<!-- End of picture text -->

6 and 9 have the common factor 3, so we can further reduce 

<!-- Start of picture text -->
26 63 = 2 (cancelling 3).9 = �� 39� �<!-- End of picture text -->

It is clear that<sup>2</sup> 3<sup>isinlowestterms,since2and3havenocommonfactorotherthan1.</sup> Note that this reduction to lowest terms could have been accomplished in one step, had we realized, at the outset, that both 24 and 36 are divisible by 12: 

<!-- Start of picture text -->
> 224 24 = 2 (cancelling 12).36 = > 3 336<!-- End of picture text -->

Example 58. Reduce the fraction 39<sup>13tolowestterms.</sup> 

Solution. A common factor of the numerator and denominator is 13, so that 

<!-- Start of picture text -->
1339 = 3 1  ·  ·  13  13 = 1 3 .<!-- End of picture text -->

Example 59. Reduce the fraction<sup>15</sup> 3<sup>tolowestterms.</sup> Solution. 153<sup>=</sup> 1<sup>5= 5.</sup> 

Page 61 

#### 2.5.2 Exercises 

Using the rule b<sup>a=</sup> b<sup>a·</sup> ·<sup>c</sup> c<sup>foranynonzeroc,writefourfractionsequivalenttoeachgivenfraction:</sup> 

1.<sup>1</sup> 4 2.<sup>3</sup> 4 3.<sup>1</sup> 5 4.<sup>2</sup> 5 5.<sup>1</sup> 8 6.<sup>5</sup> 8 

Using cancellation, reduce each fraction to lowest terms. Convert improper fractions to mixed numbers. 7.<sup>12</sup> 8 8.<sup>12</sup> 18 9.<sup>20</sup> 45 10.<sup>84</sup> 60 54 11. 108 12.<sup>360</sup> 120 

### 2.6 Prime Factorization and the GCF 

Reducing a fraction to lowest terms requires recognizing a common factor (greater than 1) of the numerator and denominator. Doing it in one step requires finding and using the largest or greatest common factor. In this section, we develop a systematic way of finding the greatest common factor (GCF) of a set of numbers. 

A whole number greater than 1 is prime if it has no factors other than itself and 1. The first few prime numbers are 

2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, ... . 

The dots indicate that there are infinitely many larger primes. (This fact is not obvious but was proved more than two thousand years ago by Euclid.) The whole numbers greater than 1 which are not prime 

Page 62 

are called composite. (Note that 1 is a special case according to these definitions: it is neither prime nor composite!) The first few composite numbers are 

<!-- Start of picture text -->
4, 6, 8, 9, 10, 12, 14, 15, 16, 18, 20, 21, 22, 24, 25, 26, 27, 28, 30, ...<!-- End of picture text -->

How do we know that these numbers are composite? Because each has at least one factor, other than 1 and itself. For example, 15 has factors 3 and 5, that is, 15 = 3 · 5. 

Every composite whole number has a unique prime factorization, which is its expression as the product of its prime factors, listed in order of increasing size. For example: 

<!-- Start of picture text -->
4 = 2 · 2 = 2 26 = 2 · 38 = 2 · 2 · 2 = 2 39 = 3 · 3 = 3 210 = 2 · 512 = 2 · 2 · 3 = 2 2 · 314 = 2 · 715 = 3 · 516 = 2 · 2 · 2 · 2 = 2 4(2.1)<!-- End of picture text -->

To find prime factorizations, we use repeated division with prime divisors. Start by testing the number for divisibility by the smallest prime, 2 (a number is divisible by 2 if its final digit is even: 0, 2, 4, 6 or 8). If it is divisible by 2, we divide by 2 as many times as possible, until we arrive at a quotient which is no longer divisible by 2. We then repeat the procedure, starting with the last quotient obtained, and using the next larger prime, 3 (a number is divisible by 3 if the sum of its digits is divisible by 3 – did you know that?). Repeating again (if necessary) with the next larger prime, we eventually arrive at a quotient which is itself a prime number. At that point, we are almost finished. We collect all the primes that were used as divisors (if the same prime has been used more than once, it should be collected as many times), together with the final (prime) quotient. The product of all these numbers is the prime factorization. 

Example 60. Find the prime factorization of 300. 

Solution. 300, being even, is divisible by 2, so we start by dividing by 2. The steps are as follows: 

<!-- Start of picture text -->
300 ÷ 2 = 150;150 ÷ 2 = 75; 75 is not divisible by 2; move on to 375 ÷ 3 = 25; 25 is not divisible by 3; move on to 525 ÷ 5 = 5; 5 is a prime number; stop.<!-- End of picture text -->

The primes that were used as divisors were 2, 2, 3, 5. Note that 2 was used twice, so it is listed twice. The final prime quotient is 5. The prime factorization is the product of all those prime divisors and the final prime quotient: 

<!-- Start of picture text -->
300 = 2 · 2 · 3 · 5 · 5 or 2 2 · 3 · 5 2 .<!-- End of picture text -->

We can easily check our work by multiplying the prime factors and verifying that the product obtained is the original number. 

Page 63 

#### 2.6.1 Exercises 

Find the prime factorizations of the following numbers. Check the results by multiplication. 

1. 60 

2. 48 

3. 81 

4. 360 

5. 85 

6. 154 

7. Which of the numbers above is divisible by 3? 

#### 2.6.2 Finding the GCF 

Using prime factorizations, it is easy to find the greatest common factor of a set of numbers. 

Example 61. Find the greatest common factor (GCF) of the two-number set {a, b}, where a and b have the following prime factorizations. 

<!-- Start of picture text -->
a = 2 4 · 3 2 · 7 and b = 2 · 3 4 · 11.<!-- End of picture text -->

Solution. First, look for the common prime factors of a and b: they are 2 and 3. Note that 7 and 11 are not common, and therefore cannot be factors of the GCF. Now look at the powers (exponents) on 2 and 3. A small power of any prime is a factor of any larger power of the same prime. The smallest power of 2 that appears is 2 = 2<sup>1</sup> (in the factorization of b), and the smallest power of 3 that appears is 3<sup>2</sup> (in the factorization of a). It follows that the GCF is the product of the two smallest powers of 2 and 3. Thus 

<!-- Start of picture text -->
GCF{a, b} = 2 1 · 3 2 = 18.<!-- End of picture text -->

Notice that the actual values of a and b (which we could have determined by multiplication) were not used – only their prime factorizations. 

Here is a summary of the procedure: 

To find the GCF of a set of numbers: 

1. find the prime factorization of each number; 

2. determine the prime factors common to all the numbers; 

3. if there are no common prime factors, the GCF is 1; otherwise 

4. for each common prime factor, find the smallest exponent that appears on it; 

5. the GCF is the product of the common prime factors with the exponents found in step 4. 

Page 64 

Example 62. (a) Find the GCF of the set {60, 135, 150}. (b) Find the GCF of the subset {60, 150}. 

Solution. (a) Following the boxed procedure: 

1. the prime factorizations are 

<!-- Start of picture text -->
60 = 2 · 2 · 3 · 5 = 2 2 · 3 · 5135 = 3 · 3 · 3 · 5 = 3 3 · 5150 = 2 · 3 · 5 · 5 = 2 · 3 · 5 2<!-- End of picture text -->

2. the common prime factors are 3 and 5; 

3. (does not apply to this example); 

4. the smallest exponent on 3 is 1 (in the factorizations of 60 and 150); the smallest exponent on 5 is also 1 (in the factorizations of 60 and 135); 

5. the GCF is 3<sup>1</sup> · 5<sup>1</sup> = 15. 

(b) For the two-number subset {60, 150}, the common prime factors are 2, 3 and 5. The smallest exponent on all three factors is 1. So the GCF is 2<sup>1</sup> · 3<sup>1</sup> · 5<sup>1</sup> = 30. 

Can you explain why the GCF in part (b) is bigger than in part (a)? 

#### 2.6.3 Exercises 

Find the GCF of each of the following sets of numbers: 

1. {72, 48} 

2. {72, 48, 36} 

3. {72, 36} 

<!-- Start of picture text -->
4. {48, 36}<!-- End of picture text -->

<!-- Start of picture text -->
5. {36, 15}6. {36, 14}<!-- End of picture text -->

<!-- Start of picture text -->
7. {15, 14}<!-- End of picture text -->

#### 2.6.4 Cancelling the GCF for lowest terms 

Knowing that the GCF of {60, 150} = 30 allows us to reduce the fraction step: we simply cancel it out. Thus, 

15060<sup>tolowesttermsinone</sup> 

<!-- Start of picture text -->
* 260 60 = 2 (cancelling the GCF, 30).150 = � �� 150 � *� 5 5<!-- End of picture text -->

Recall that this is short-hand for 

<!-- Start of picture text -->
60 ÷ 30150 ÷ 30 = 5 2 .<!-- End of picture text -->

Page 65 

Example 63. Reduce 252<sup>168tolowesttermsbyfindingandcancellingtheGCF.</sup> 

Solution. The prime factorizations of the numerator and denominator are 

<!-- Start of picture text -->
168 = 2 3 · 3 · 7252 = 2 2 · 3 2 · 7.<!-- End of picture text -->

The smallest exponent on 2 is 2, and the smallest exponents on 3 and 7 are 1; it follows that the GCF is 2<sup>2</sup> · 3 · 7 = 84. Cancelling the GCF yields lowest terms: 

<!-- Start of picture text -->
168 168*� 2 = 2 (cancelling the GCF, 84).252 = � �� 252 � *� 3 3<!-- End of picture text -->

#### 2.6.5 Exercises 

Reduce each fraction to lowest terms by finding and cancelling the GCF of the numerator and denominator. Convert improper fractions to mixed numbers. 

1.<sup>36</sup> 72 

2.<sup>48</sup> 36 

3.<sup>14</sup> 48 

4.<sup>36</sup> 14 

5.<sup>14</sup> 15 

6.<sup>72</sup> 84 

- 48 

- 7. 180 

8.<sup>96</sup> 56 

9.<sup>105</sup> 147 

10.<sup>300</sup> 360 

Page 66 

### 2.7 Pre-cancelling when Multiplying Fractions 

In the fraction product 

<!-- Start of picture text -->
215 · 14 15 ,<!-- End of picture text -->

we could simply follow the rule that the product of fractions is the product of the numerators over the product of the denominators, 

<!-- Start of picture text -->
21 · 155 · 14 ,<!-- End of picture text -->

calculate the products in the numerator and denominator and, finally, reduce the resulting fraction to lowest terms by cancelling out the GCF. But there’s a short-cut: Since multiplication is commutative, we can reverse the order of multiplication in the numerator, obtaining 

<!-- Start of picture text -->
15 · 215 · 14 = 15 5 · 14 21 .<!-- End of picture text -->

The fractions on the right-hand side are easily reduced to lowest terms by cancelling the obvious GCFs (5 and 7, respectively) 

<!-- Start of picture text -->
> 3 > 315 21> 1 · >, 25 14<!-- End of picture text -->

leaving a simpler product 

<!-- Start of picture text -->
13 · 3 2 = 2 9 ,<!-- End of picture text -->

which has the further advantage that the solution,<sup>9</sup> 2<sup>,isalready inlowestterms.Thetrickofcancelling</sup> before multiplying – pre-cancellation – saves us from bigger numbers, 

<!-- Start of picture text -->
215 · 15 14 = 315 70 ,<!-- End of picture text -->

and the extra work of finding the GCF{315, 70} = 35 for cancellation: 

<!-- Start of picture text -->
�315 � *� 9 = 9 (cancelling 35),* 2 2�70 �<!-- End of picture text -->

The general rule is this: 

In a product of fractions, a factor which is common to one of the numerators and one of the denominators can be cancelled before multiplying. The numerator and denominator need not belong to the same fraction. 

Notice that pre-cancellation works with any number of factors. 

Example 64. Find the product 

<!-- Start of picture text -->
43 · 8 5 · 10 9 .<!-- End of picture text -->

Page 67 

Solution. The numerator of the first fraction (3) has a common factor with the denominator of the third fraction (9), so the product is equal to 

<!-- Start of picture text -->
> 13 = 14 · 8 5 · 10 > 3 4 · 8 5 · 10 3 .9<!-- End of picture text -->

Continuing on, the numerator of the second fraction (8) has a common factor with the denominator of the first fraction (4), so the product is equal to 

<!-- Start of picture text -->
> 21 · 8> 1 5 · 10 3 = 1 · 2 5 · 10 3 .4<!-- End of picture text -->

Finally, the numerator of the third fraction (10) has a common factor with the denominator of the second fraction (5), so (omitting the factor 1) the product is equal to 

<!-- Start of picture text -->
> 22 10·> 1 3 = 1 2 · 2 3 .5<!-- End of picture text -->

No further cancellation is possible. The final answer is now a simple product 

<!-- Start of picture text -->
12 · 2 3 = 4 3 = 11 3 ,<!-- End of picture text -->

which is already in lowest terms. These cancellations could have been done in a different order, or (carefully) all at once. 

Mixed numbers are multiplied by simply converting them into improper fractions. Example 65. Find the product 2 8<sup>3· 11</sup> 4<sup>· 22</sup> 3<sup>.Expresstheresultasamixednumber.</sup> 

Solution. Rewriting each mixed number as an improper fraction, we have the product 

Cancelling 8’s, we have 

<!-- Start of picture text -->
198 · 5 4 · 3 8 .194 · · 3 5 = 85 12 = 7 12 1 .<!-- End of picture text -->

Example 66. A gas tank with a 13<sup>1</sup> 2<sup>-galloncapacityisonlyonethirdfull.Howmuchgasisinthe</sup> tank? 

Solution. We need to find the product<sup>1</sup> 3<sup>· 131</sup> 2<sup>.Converting13</sup> 2<sup>1totheimproperfraction27</sup> 2<sup>,wehave</sup> 

Cancelling the common factor 3, 

<!-- Start of picture text -->
13 · 131 2 = 1 3 · 27 2 .> 91 27 91 · 2 = 2 .3� �<!-- End of picture text -->

Converting<sup>9</sup> 2<sup>toamixednumber,weconcludethatthetankcontains41</sup> 2<sup>gallonsofgas.</sup> 

Page 68 

#### 2.7.1 Exercises 

Find the products, using pre-cancellation where possible. Check that the answers are in lowest terms. Express any improper fractions as mixed numbers. 

1.<sup>4</sup> 5<sup>·</sup> 12<sup>7</sup> 

2.<sup>32</sup> 45<sup>·</sup> 16<sup>9·15</sup> 6 

<!-- Start of picture text -->
3. 12 · 8 5 · 2 3<!-- End of picture text -->

<!-- Start of picture text -->
94.22 · 12 21 · 24 7<!-- End of picture text -->

5.<sup>2</sup> 3<sup>of24.</sup> 

<!-- Start of picture text -->
6. 3 4 of 2 3 of 50.7. 2 23 · 13 4 .<!-- End of picture text -->

Use multiplication to answer the following questions. 

8. What is the area of a rectangle with length 2<sup>1</sup> 2<sup>feetandwidth2</sup> 10<sup>3feet?</sup> 

9. A 12 2<sup>1-gallonfishtankisonlythree-fifthsfull.Howmanygallonsofwatermustbeaddedtofillit</sup> up? 

10. 2<sup>2</sup> 3<sup>cups of beans are needed to make 4 bowls of chili.How many cups are needed to make 8 bowls?</sup> 1 bowl? 3 bowls? 

### 2.8 Adding and Subtracting Fractions 

If I eat a third of a pizza for lunch, and another third for dinner, then I have eaten two thirds in total. That is, 

<!-- Start of picture text -->
13 + 1 3 = 2 3 .<!-- End of picture text -->

Similar logic applies whenever we add two (or more) fractions with the same denominator – we simply add the numerators, while keeping the denominator fixed: 

<!-- Start of picture text -->
a.c + b c = a + c  b<!-- End of picture text -->

A very similar rule holds for subtraction of fractions with the same denominator: 

Page 69 

<!-- Start of picture text -->
a.c − b c = a − c b<!-- End of picture text -->

Fractions with the same denominator are called like fractions. 

Example 67. Here are three examples involving addition or subtraction of like fractions: 

<!-- Start of picture text -->
51 + 2 5 = 1 + 2 5 = 5 3137 − 2 7 = 13 − 7 2 = 11 7 = 14 77 = 28 − 5 8 = 7 − 8 5 8 = 1 4 .<!-- End of picture text -->

Notice that we reduced to lowest terms where necessary, and changed improper fractions to mixed numbers. 

#### 2.8.1 Exercises 

Add or subtract the like fractions as indicated. Reduce the final answers to lowest terms if necessary. Change improper fractions to mixed numbers. 

<!-- Start of picture text -->
1. 1 5 + 5 3 =2. 7 5 + 13 5 =3. 15 11 + 13 15 + 15 8 =4. 20 51 − 51 3 =55.13 − 13 4 =6. 11 25 + 25 9 − 25 3 =7. 109 − 117 7 =8. 13 2 − 2 1 =9. 10 7 + 7 6 − 11 7 =10. 11 25 − 25 2 + 25 8 =<!-- End of picture text -->

Page 70 

#### 2.8.2 Adding and Subtracting Unlike Fractions 

Here is the rule for adding any two fractions, like or unlike: 

<!-- Start of picture text -->
ba + d c = ad bd + bc<!-- End of picture text -->

Compared to the rule for multiplying fractions (Section 2.4), it looks a bit strange. But it is easily proved, using (yet again) the fact that 1 = b/b and 1 = d/d, for any nonzero b or d. 

<!-- Start of picture text -->
ba + d c = b a · d d + d c · b b= bd ad + bd bc= ad + bcbd<!-- End of picture text -->

<!-- Start of picture text -->
Example 68. Add 25 + 3 7 .<!-- End of picture text -->

Solution. Using the boxed rule, 

<!-- Start of picture text -->
25 + 3 7 = 2 · 7 + 5 5 · 7  · 3 = 14 + 15 35 = 35 19 .<!-- End of picture text -->

Example 69. Add<sup>15</sup> 16<sup>+19</sup> 24<sup>.</sup> 

Solution. Using the boxed rule, 

<!-- Start of picture text -->
1516 + 19 24 = 15 · 24 + 16 16 · 24  · 19 = 384 664 .<!-- End of picture text -->

Cancelling the GCF, 8, we obtain the sum in lowest terms,<sup>83</sup> 48<sup>.</sup> 

The rule works for like fractions too: 

Example 70. Use the boxed rule to show that 5<sup>4+</sup> 5<sup>3=7</sup> 5<sup>.</sup> Solution. 

<!-- Start of picture text -->
45 + 3 5 = 20 + 15 25 = 35 25 = 5 7 .<!-- End of picture text -->

Note that an extra factor of 5 was introduced, and then cancelled at the end. (A needless complication!) 

Page 71 

A disadvantage of the boxed is that it produces a fraction which may be far from lowest terms. Another disadvantage is that it doesn’t extend easily to sums of more than two fractions. To remedy these, we develop a method, somewhat analogous to pre-cancellation in multiplication, which produces the sum of any set of fractions in a form which is as close as possible to lowest terms. The idea is to replace each fraction by an equivalent fraction, each having the same (common) denominator, which is as small as possible. 

Example 71. Find the sum: 

<!-- Start of picture text -->
23 + 5 1 .<!-- End of picture text -->

Solution. Observe that 

<!-- Start of picture text -->
2 1and3 = 3 2  ·  ·  5  5 = 10 15 5 = 1 5  ·  ·  3  3 = 15 3 .It follows that32 + 1 5 = 10 15 + 15 3 .<!-- End of picture text -->

Now we have like fractions, and so 

<!-- Start of picture text -->
1015 + 15 3 = 10 + 3 15 = 13 15 .<!-- End of picture text -->

Since equivalent fractions represent the same number, we conclude that 

<!-- Start of picture text -->
32 + 1 5 = 15 13 .<!-- End of picture text -->

Why (and how) did we choose 15 as the common denominator? And how do we know it is the smallest common denominator we could have used? We could have chosen any number that is a multiple of both 3 and 5 (the two original denominators in the example). The multiples of 3 are 

<!-- Start of picture text -->
3, 6, 9, 12, 15, 18, 21, etc.,<!-- End of picture text -->

and the multiples of 5 are 

<!-- Start of picture text -->
5, 10, 15, 20, 25, 30, etc.,<!-- End of picture text -->

and it is easy to see that the smallest number that is a multiple of both – the least common multiple – is 15. 

#### 2.8.3 The LCM 

The method of listing small multiples is often the simplest way to find the least common multiple, or LCM, of a set of whole numbers. 

Example 72. Find the LCM{6, 10, 15}. 

Solution. The multiples of 6 are 

<!-- Start of picture text -->
6, 12, 18, 24, 30, 36, ... ,<!-- End of picture text -->

the multiples of 10 are 

<!-- Start of picture text -->
10, 20, 30, 40, ... ,<!-- End of picture text -->

and the multiples of 15 are 

<!-- Start of picture text -->
15, 30, 45, ... .<!-- End of picture text -->

It is evident that the smallest number which is a multiple of all three numbers is 30. 

Page 72 

The LCM can also be found using prime factorizations. This is useful when the numbers are rather large. 

Example 73. Find the LCM of the two-number set {a, b}, where a and b have the following prime factorizations. 

<!-- Start of picture text -->
a = 2 4 · 3 2 · 7 and b = 2 · 3 4 · 11.<!-- End of picture text -->

Solution. The LCM must be a multiple of both numbers, so that it must be divisible by the highest power of every prime factor that appears in any one of the factorizations. The prime factors of a and b are 2, 3, 7 and 11. The highest powers that appear are 

<!-- Start of picture text -->
2 4 , 3 4 , 7 1 , 11 1 .<!-- End of picture text -->

The LCM is the product of these powers: 

<!-- Start of picture text -->
LCM{a, b} = 2 4 · 3 4 · 7 · 11.<!-- End of picture text -->

This is a rather large number, but it is the smallest which is a multiple of both a and b. Notice that the actual values of a and b, and their LCM (which we could calculate by multiplication) were not needed – only their prime factorizations. 

Here is a summary of the procedure: 

To find the LCM of a set of numbers: 

1. find the prime factorization of each number; 

2. for each prime factor, find the largest exponent that appears on it in any of the factorizations; 

3. the LCM is the product of the prime factors with the exponents found in step 2. 

Compare this procedure with the procedure for finding the GCF of a set of numbers. There are similarities and significant differences. 

#### 2.8.4 Exercises 

Find the LCM of the following sets of numbers. Use the prime factorization method for larger numbers. 

1. LCM{25, 10} 

2. LCM{48, 60} 

3. LCM{10, 15, 25} 

4. LCM{8, 12} 

5. LCM{9, 6, 12} 

6. LCM{60, 168} 

Page 73 

7. LCM{51, 34, 17} 

8. LCM{15, 12} 

9. LCM{18, 8} 

10. LCM{3, 4, 5} 

11. LCM{4, 14} 

12. LCM{2, 5, 9} 

<!-- Start of picture text -->
13. LCM{3 2 · 5 2 · 11, 3 4 · 7 2 }<!-- End of picture text -->

#### 2.8.5 The LCD 

To add unlike fractions so that the sum is in lowest terms, we use the LCM of their denominators. This is such a frequent operation with fractions that it has its own name: the LCD or Least Common Denominator. 

Example 74. Find the LCD of the fractions 

<!-- Start of picture text -->
1 3 1and8 , 10 , 18 .<!-- End of picture text -->

Solution. The LCD of the fractions is the LCM of their denominators, 

<!-- Start of picture text -->
LCM{8, 10, 18}.<!-- End of picture text -->

Looking at the prime factorizations 

<!-- Start of picture text -->
8 = 2 3 , 10 = 2 · 5, 18 = 2 · 3 2 ,<!-- End of picture text -->

and taking the highest power of each prime that occurs, we see that the LCM is 

<!-- Start of picture text -->
2 3 · 3 2 · 5 = 360.<!-- End of picture text -->

This is LCD of the fractions. 

<!-- Start of picture text -->
Example 75. Find the sum of the unlike fractions 8 1 + 10 3 + 18 1 .<!-- End of picture text -->

Solution. The LCD is the LCM from the previous example: 360. Now we observe that 

<!-- Start of picture text -->
360 = 8 · 45 = 10 · 36 = 18 · 20.<!-- End of picture text -->

Thus 

It follows that 

<!-- Start of picture text -->
1 3 1and8 = 8 1  ·  ·  45  45 , 10 = 10 3 ·  ·  36  36 18 = 18 1 ·  ·  20  20 .1(2.2)8 + 10 3 + 18 1 = 1 8  ·  ·  45  45 + 10 3 ·  ·  36  36 + 18 1 ·  ·  20  20= 45 + 108 + 20360= 173360 .<!-- End of picture text -->

Since the 173 is not divisible by 2, 3, or 5, the fraction is in lowest terms. 

Page 74 

Practically the same method works for subtracting unlike fractions. 

Example 76. Find the difference 25<sup>14−</sup> 10<sup>2,usingtheLCD.Reducetolowestterms,ifnecessary.</sup> 

Solution. The LCD is LCM{25, 10} = 50. Now 50 = 25 · 2 = 10 · 5. So 

<!-- Start of picture text -->
14 2and25 = 25 14  ·  ·  2  2 = 28 50 , 10 = 10 2 ·  ·  5  5 = 50 10 .<!-- End of picture text -->

Thus, the difference of the two fractions is 

<!-- Start of picture text -->
2850 − 10 50 = 28 − 50 10 = 18 50 .<!-- End of picture text -->

The latter fraction is not in lowest terms, since the GCF of 18 and 50 is 2. Cancelling the GCF, we get 

<!-- Start of picture text -->
> 918 18 = 950 = > 25 25 .50<!-- End of picture text -->

Example 77. Subtract<sup>1</sup> 3<sup>−1</sup> 4<sup>,andreducetolowesttermsifnecessary.</sup> 

Solution. The LCD is 12. Changing both fractions to equivalent fractions with denominator 12, we get 

Thus, 

<!-- Start of picture text -->
1 1and3 = 3 1  ·  ·  4  4 = 12 4 4 = 4 1  ·  ·  3  3 = 12 3 .13 − 4 1 = 12 4 − 12 3 = 4 − 12 3 = 12 1 .<!-- End of picture text -->

The latter fraction is already in lowest terms, so we are done. 

Example 78. Find the sum<sup>4</sup> 5<sup>+</sup> 4<sup>3,reduceto lowestterms,and expresstheanswer as amixednumber.</sup> 

Solution. The LCD{4, 5} = 20, so that 

<!-- Start of picture text -->
45 + 4 3 = 4 5  ·  ·  4  4 + 4 3  ·  ·  5  5 = 16 20 + 15 20 = 20 31 = 111 20 .<!-- End of picture text -->

#### 2.8.6 Exercises 

Add or subtract the following fractions as indicated, reduce to lowest terms if necessary, and change improper fractions to mixed numbers. 

<!-- Start of picture text -->
1. 1 5 + 6 32. 7 5 + 13 33. 15 1 + 3 2<!-- End of picture text -->

Page 75 

<!-- Start of picture text -->
4. 15 + 2 05. 2 3 + 4 3 + 4 56. 11 15 + 13 257. 17 51 − 50 38. 5 3 − 13 49. 11 5 − 25 210. 11 7 − 17 1111. 3 2 − 12 112. 6 7 − 17 1113. 11 20 − 25 2<!-- End of picture text -->

### 2.9 Comparison of Fractions 

When two fractions have the same denominator, it is clear that the larger fraction is the one with the larger numerator. This suggests a simple way to compare any set of fractions: replace each fraction by an equivalent fraction having the LCD. Then the largest fraction is the one with the largest numerator, the second-largest is the one with the second-largest numerator, etc. 

<!-- Start of picture text -->
Example 79. Which is larger, 23 or 4 3 ?Solution. The LCD is 12,<!-- End of picture text -->

<!-- Start of picture text -->
2 3and3 = 12 8 , 4 = 12 9 .<!-- End of picture text -->

The larger of the two fractions with denominator 12 is the one with the larger numerator, 129<sup>.It follows</sup> that 4<sup>3islargerthan2</sup> 3<sup>.</sup> 

The inequality symbols < (less than) and > (greater than) are used to state size comparisons between numbers. For example, the inequalities 

<!-- Start of picture text -->
1 2 12 < 1, 3 > 2<!-- End of picture text -->

state that<sup>1</sup> 2<sup>isless than 1,and that2</sup> 3<sup>1is greaterthan 2.Visualizing thenumberline yields agoodrule</sup> of thumb: 

Page 76 

<!-- Start of picture text -->
“Left is Less”<!-- End of picture text -->

<!-- Start of picture text -->
M < N if M is left of N on the number line:M < N| | | | | | | | | | |−5 −4 −3 −2 −1 0 1 2 3 4 5<!-- End of picture text -->

It is a happy coincidence that the symbol < for “Less than” looks rather like the letter “L.” 

Numbers arranged in increasing order are written from left to right, separated by the < symbol. (This is the left-to-right ordering on the number line.) We can also arrange numbers in decreasing order, from left to right, separated by the > (“greater than”) symbol. 

Example 80. Arrange the fractions<sup>3</sup> 4<sup>, 2</sup> 3<sup>,and</sup> 9<sup>7inincreasingorder.</sup> 

Solution. LCD{3, 4, 9} = 36, and 

<!-- Start of picture text -->
34 = 27 36 32 = 24 36 97 = 28 36 .<!-- End of picture text -->

We are asked to arrange the fractions in increasing order, so we list them in increasing order of their numerators, separated by the inequality symbol <. Thus, 

<!-- Start of picture text -->
2436 < 27 36 < 36 28 .<!-- End of picture text -->

Now, going back to the equivalent fractions in lowest terms, we have 

<!-- Start of picture text -->
23 < 3 4 < 7 9 .<!-- End of picture text -->

<!-- Start of picture text -->
5 3 , 13 4 , 16 7 , and 12 11 in decreasing order.<!-- End of picture text -->

Example 81. Arrange the numbers 1 

Solution. Recall that a proper fraction is less than 1, so<sup>11</sup> 12<sup>is obviously the smallest of the four numbers</sup> (the others being mixed numbers greater than 1). To compare the other three numbers, it is enough to compare their fractional parts, because each has the same whole number part (1). To compare<sup>3</sup> 5<sup>,3</sup> 4<sup>,</sup> and 7<sup>6,wefindtheLCM{5, 4, 7}= 140,andwriteequivalentfractionswithdenominator140:</sup> 

<!-- Start of picture text -->
35 = 140 84 34 = 105 140 76 = 120 140 .<!-- End of picture text -->

In decreasing order, the numerators are 120 > 105 > 84. The corresponding ordering of the fractions is 

<!-- Start of picture text -->
76 > 3 4 > 3 5 ,<!-- End of picture text -->

Page 77 

and it follows that the corresponding order of the mixed numbers (each with whole number part 1) is 

<!-- Start of picture text -->
1 7 6 > 13 4 > 13 5 .<!-- End of picture text -->

Adjoining the smallest (proper) fraction<sup>11</sup> 12<sup>attheend,wehave,finally,thedecreasingorder</sup> 

<!-- Start of picture text -->
1 7 6 > 13 4 > 13 5 > 11 12 .<!-- End of picture text -->

#### 2.9.1 Exercises 

<!-- Start of picture text -->
1. Arrange in decreasing order: 4 9 , 3 8 , and 3 1 .2. Arrange in increasing order: 3 5 , 3 4 , and 5 7 .3. Is 12 5 of an inch more or less than 16 7 of an inch?4. Is 9 58 inches closer to 9 or 10 inches?5. A stock price changed from 5 58 to 53 4 . Did the price go up or down?<!-- End of picture text -->

### 2.10 Division of Fractions 

Our intuition is not very good when we think of dividing two fractions. How many times does<sup>2</sup> 3<sup>“go</sup> into”<sup>3</sup> 4<sup>,forexample?Equivalently,whatfractionresultsfromthedivisionproblem</sup> 

<!-- Start of picture text -->
43 ÷ 2 3 ?<!-- End of picture text -->

It is not at all obvious. We will derive a simple rule, but we’ll need an auxiliary concept. 

#### 2.10.1 Reciprocals 

Two non-zero numbers are reciprocal if their product is 1. Thus, if x and y are nonzero numbers, and if 

<!-- Start of picture text -->
x · y = 1,<!-- End of picture text -->

then x is the reciprocal of y , and, also, y is the reciprocal of x. 

The rule for multiplying fractions, together with obvious cancellations, shows that 

<!-- Start of picture text -->
1 > 1a a · b = 1 · b = 1b · b a = � 1 > 1 1 = 1.b · �a b · 1<!-- End of picture text -->

This means that 

Page 78 

The reciprocal of the fraction b<sup>aisthefractionb</sup> a<sup>.</sup> (both a and b nonzero) 

Since every whole number n can be written as the fraction<sup>n</sup> 1<sup>,wehavethefollowingspecialcase:</sup> 

The reciprocal of the whole number n (nonzero) is the fraction<sup>1</sup> n<sup>.</sup> 

Example 82. The reciprocal of 5 is 5<sup>1.Thereciprocalof</sup> 9<sup>1is9.Thereciprocalof3</sup> 8<sup>is8</sup> 3<sup>,or,expressed</sup> as a mixed number, 2<sup>2</sup> 3<sup>.</sup> 

We note some important facts and special cases: 

- the reciprocal of the reciprocal of a number is the number itself. For example, the reciprocal of 2/3 is 3/2, and in turn, the reciprocal of 3/2 is 2/3. 

- 1 is the only (positive) number that is its own reciprocal (since 1 = 1<sup>1.)</sup> 

- the reciprocal of a number less than 1 is a number greater than 1, and vice versa (since the reciprocal of a proper fraction is an improper fraction). 

- 0 has no reciprocal (since division by 0 is undefined). 

#### 2.10.2 Exercises 

Find the reciprocals of the following numbers. Change improper fractions to mixed or whole numbers. 

1.<sup>3</sup> 7 2. 11 3.<sup>14</sup> 5 1 4. 25 5.<sup>5</sup> 6 

#### 2.10.3 Division is Multiplication by the Reciprocal of the Divisor 

Consider again the division problem 

Using the LCD, this is equivalent to 

<!-- Start of picture text -->
34 ÷ 3 2 .<!-- End of picture text -->

<!-- Start of picture text -->
129 ÷ 12 8<!-- End of picture text -->

Page 79 

We want to know how many times 8 things of a certain size (1/12) go into 9 things of the same size. The actual denominator doesn’t really matter, only that it is the same for both fractions. In this form it seems obvious that the answer is the quotient of the numerators, 8<sup>9.</sup> 

Now, how were the numbers 9 and 8 obtained from the original fractions? Well, in writing equivalent fractions with the LCD, we computed the numerators as follows: 9 = 3 · 3 and 8 = 4 · 2. We have shown that 

<!-- Start of picture text -->
43 ÷ 2 3 = 3 4  ·  ·  3  2 = 4 3 · 3 2 .<!-- End of picture text -->

The original division turned into multiplication by the reciprocal of the divisor, and the LCD wasn’t actually needed. 

We have derived a simple rule: 

<!-- Start of picture text -->
ba ÷ d c = b a · d c<!-- End of picture text -->

In words: the quotient of two fractions is the product of the dividend and the reciprocal of the divisor. Example 83. Perform the division 125<sup>÷</sup> 6<sup>5.</sup> 

Solution. We convert the division into multiplication by the reciprocal of 6<sup>5.</sup> 

<!-- Start of picture text -->
125 ÷ 5 6 = 12 5 · 5 6= 3060= 1 (cancelling 30).2<!-- End of picture text -->

Example 84. What is<sup>3</sup> 7<sup>dividedby6?</sup> 

<!-- Start of picture text -->
37 ÷ 6 = 3 7 ÷ 6 1= 7 3 · 1 6= 342= 1 (cancelling 3).14<!-- End of picture text -->

We can divide mixed numbers, too, by simply converting them into improper fractions first. Example 85. Perform the division 2<sup>8</sup> 9<sup>÷ 1</sup> 2<sup>1.Expresstheresultasamixednumber.</sup> 

Solution. Converting mixed numbers to improper fractions, we have 

<!-- Start of picture text -->
2 8 9 ÷ 11 2 = 26 9 ÷ 2 3 .<!-- End of picture text -->

Page 80 

Now we convert the division into multiplication by the reciprocal of 2<sup>3:</sup> 

<!-- Start of picture text -->
= 26 9 · 3 2 .<!-- End of picture text -->

No pre-cancellation is possible, so 

<!-- Start of picture text -->
269 · · 3 2 = 52 27 = 125 27 ,<!-- End of picture text -->

where, at the last step, we converted the improper fraction into a mixed number. 

Example 86. How many books, each 1 4<sup>3inchthick,canfitona35inchbookshelf?</sup> 

Solution. The question calls for division, since we need to know how many times 1<sup>3</sup> 4<sup>“goesinto”35.</sup> 

<!-- Start of picture text -->
35 ÷ 1 3 4 = 35 1 ÷ 4 7 = 35 1 · 7 4 .<!-- End of picture text -->

Cancelling 7, we get 

<!-- Start of picture text -->
51 · 1 4 = 20 1 = 20.<!-- End of picture text -->

So, exactly 20 books will fit on the shelf. 

#### 2.10.4 Exercises 

Perform the divisions. Reduce to lowest terms, and change improper fractions to mixed numbers. 

<!-- Start of picture text -->
1. 15 ÷ 2 32. 15 ÷ 2383.15 ÷ 21 16<!-- End of picture text -->

<!-- Start of picture text -->
4. 10 1 2 ÷ 55 65. 78 ÷ 21 46. 10034 ÷ 17 50<!-- End of picture text -->

<!-- Start of picture text -->
7. 100 ÷ 33<!-- End of picture text -->

<!-- Start of picture text -->
8. 100 ÷ 53<!-- End of picture text -->

Use division to answer the following questions. 

9. How many 1<sup>1</sup> 2<sup>inchpiecescanbecutfromaboardthatis36incheslong?</sup> 

10. Seeds are sold in 2 2<sup>1-ounce packets.A gardener needs 32 ounces of seed.Howmany packets should</sup> he buy to be sure he has enough? 

Page 81 

### 2.11 Mixed Numbers and Mixed Units 

Mixed numbers can be added and subtracted by first converting them into improper fractions, and very often this is what we do. But a problem such as 

<!-- Start of picture text -->
75 1 2 + 593 4<!-- End of picture text -->

is not well-suited to this method. If we convert to improper fractions, the numerators of both fractions would be quite large and unwieldy. 

#### 2.11.1 Vertical Addition and Subtraction 

We can align mixed numbers vertically so that the fractional and whole number parts line-up, and then separately add the fraction and whole number columns. We must ensure that the resulting mixed number is in proper form (the fractional part must be a proper fraction), and this involves a procedure analogous to “carrying” in whole number addition. 

Example 87. Add 2<sup>1</sup> 2<sup>+ 63</sup> 4<sup>.</sup> 

Solution. We first align the whole number and fractional places vertically: 

<!-- Start of picture text -->
1223+ 64<!-- End of picture text -->

To add the fractional parts, we write them both with their LCD, which is 4. 

<!-- Start of picture text -->
2243+ 64<!-- End of picture text -->

Then we add the columns separately. 

<!-- Start of picture text -->
2243+ 64584<!-- End of picture text -->

The resulting mixed number, 8<sup>5</sup> 4<sup>, is not in proper form, because5</sup> 4<sup>= 11</sup> 4<sup>. So we leave the proper fractional</sup> part,<sup>1</sup> 4<sup>,in the fractions column,and carry the whole number part,1, over to the whole number column.</sup> (We indicate the carrying by writing {1} above the whole number column.) Then we recompute the 

Page 82 

whole number sum, obtaining the final answer in proper form: 

<!-- Start of picture text -->
{1}2243+ 64194<!-- End of picture text -->

To subtract mixed numbers, we sometimes need a “borrowing” procedure, analogous to the procedure we use when subtracting whole numbers. 

Example 88. Subtract 7 − 3<sup>2</sup> 5<sup>.</sup> 

Solution. Note that the whole number 7 is a mixed number with 0 fractional part, and we can represent 0 as a fraction using any convenient denominator. Here the convenient choice is 5. So we write 7 = 7<sup>0</sup> 5<sup>.</sup> Aligning whole number parts vertically, we have 

<!-- Start of picture text -->
0752− 35<!-- End of picture text -->

Now we see that the subtraction in the fractions place is not possible (we can’t take 2 fifths from 0 fifths), so we need to borrow 1 from the whole numbers column. 1 =<sup>n</sup> n<sup>foranyconvenientn(except</sup> 0), and in this example, it is convenient to write 1 =<sup>5</sup> 5<sup>.Borrowing1=5</sup> 5<sup>from7(reducingitto6),</sup> and adding 1 =<sup>5</sup> 5<sup>to</sup> 5<sup>0atthetopofthefractionscolumn,wehave</sup> 

<!-- Start of picture text -->
5652− 35335<!-- End of picture text -->

Both of the previous examples could have been done by first converting the mixed numbers into improper fractions. For example, 

<!-- Start of picture text -->
7 − 3 2 5 = 35 5 − 17 5 = 18 5 = 33 5 .<!-- End of picture text -->

Perhaps you find this easier. But here is an example that would involve much more work if we were to use that method. 

Example 89. Subtract 153 15<sup>2−674</sup> 9<sup>.</sup> 

Page 83 

Solution. The LCD{15, 9} = 45, and since 152<sup>=</sup> 45<sup>6and</sup> 9<sup>4=20</sup> 45<sup>,wewrite,inverticalform,</sup> 

<!-- Start of picture text -->
61534520− 6745<!-- End of picture text -->

The subtraction in the fractions column is not possible, so we borrow 1 from 153 (in the form<sup>45</sup> 45<sup>)and</sup> add it to 456<sup>,obtaining</sup> 

<!-- Start of picture text -->
511524520− 6745<!-- End of picture text -->

Now the subtraction in the fractions column is possible, and we obtain 

<!-- Start of picture text -->
511524520− 6745318545<!-- End of picture text -->

The fractional part is in lowest terms, and we are done. 

If we had done the previous example by first converting the mixed numbers into improper fractions, we would have had to work with rather large numerators: 

<!-- Start of picture text -->
6891 − 303545 45<!-- End of picture text -->

Not impossible, but the other method is easier! 

#### 2.11.2 Exercises 

Add or subtract the mixed numbers as indicated. Express the final answers as mixed numbers in proper form. 

<!-- Start of picture text -->
1. 1 13 + 2 12. 3 2 5 + 71 3 + 13 53. 1 15 + 104. 75 3 4 + 912 3<!-- End of picture text -->

Page 84 

<!-- Start of picture text -->
5. 12 11 15 − 213 206. 3 78 − 21 47. 1 2 3 − 1 13 48. 3 3 5 + 11 2 + 10 39. 1 7 1 − 3 710. 21 35 − 193 411. 3 67 − 12 1112. 5 11 20 − 44 5<!-- End of picture text -->

#### 2.11.3 Measurements in Mixed Units 

When a number results from a measurement, it is given in terms of a unit of measure, or unit for short. For example, if you use a standard ruler to measure the length of a table, the length is given in units of feet (ft). All 1-foot rulers are divided into 12 smaller units called inches (in), so that 

<!-- Start of picture text -->
1 ft = 12 in.<!-- End of picture text -->

More precise measurements can be given in terms of the mixed units feet-and-inches. For example, the length of your table might be 3 feet 6 inches or 3 ft 6 in. 

Other familiar examples of mixed units are hours-and-minutes, or hours-minutes-and-seconds. The abbreviations are hr, min and sec. Of course, 

<!-- Start of picture text -->
1 hr = 60 min and 1 min = 60 sec.<!-- End of picture text -->

Mixed units are just like mixed numbers, because the smaller units are simple fractions of the larger ones: 

<!-- Start of picture text -->
1 in = 1 1 min = 1 1 sec = 112 ft 60 hr 60 min.<!-- End of picture text -->

It follows that measurements in mixed units can be added and subtracted just like mixed numbers. The notion of proper form remains since, for example, a measurement of 

<!-- Start of picture text -->
4 ft 17 in<!-- End of picture text -->

makes sense, but is properly written as 

<!-- Start of picture text -->
5 ft 5 in,<!-- End of picture text -->

since any measurement of over 12 inches is at least 1 foot. Borrowing and carrying are sometimes needed, and are easily accomplished, as the next example shows. 

Page 85 

Example 90. Hugo and Hector go to separate movies that start at the same time. Hugo’s movie is 2 hours and 5 minutes long, while Hector’s is 1 hour and 43 minutes. How long will Hector have to wait, after his movie is over, for Hugo to come out? 

Solution. Hector’s waiting time is the difference in the lengths of the movies, 

<!-- Start of picture text -->
2 hr 5 min− 1 hr 43 min<!-- End of picture text -->

The subtraction in the minutes column can’t be done, so we borrow 1 hr = 60 min from the hours column, reducing the number of hours at the top of the hours column from 2 to 1, and increasing the number of minutes at the top of the minutes column from 5 min to 5 min + 60 min = 65 min. 

<!-- Start of picture text -->
1 hr 65 min− 1 hr 43 min0 hr 22 min<!-- End of picture text -->

Hector will have to wait 22 minutes. 

Here’s an example involving length measurements. 

Example 91. Two boards are laid end-to-end. One of the boards measures 6 ft 8 in, and the other measures 11 ft 10 in. What is the total length of the boards? Give your answer in proper form. 

Solution. We need to calculate the mixed-unit sum 

<!-- Start of picture text -->
6 ft 8 in+ 11 ft 10 in<!-- End of picture text -->

Adding the inches column, we obtain 18 in = 1 ft 6 in. So we put down 6 in in the inches column, and carry 1 ft to the top of the feet column: 

<!-- Start of picture text -->
{1 ft}6 ft 8 in+ 11 ft 10 in6 in<!-- End of picture text -->

We add up the feet column to obtain the final answer: 

<!-- Start of picture text -->
{1 ft}6 ft 8 in+ 11 ft 10 in18 ft 6 in<!-- End of picture text -->

The total length, in proper form, is 18 ft 6 in. 

Page 86 

#### 2.11.4 Exercises 

1. A carpenter cuts a 6 ft 7 in piece from a 9 ft 4 in board. What is the length of the leftover piece? 

2. Find the perimeter of the polygon: 

<!-- Start of picture text -->
4 ft 2 in6 ft 7 in4 ft 8 in3 ft 8 in 2 ft 6 in<!-- End of picture text -->

3. A film critic watched three movies. The first was 2 2<sup>1hrs,thesecond2hrs15min,andthelast1</sup> hr 45 min. (a) What was the total length of the movies? (b) What was the average length of the movies? 

### 2.12 Combined operations with fractions and mixed numbers 

Recall that when there is more than one operation to be performed in a calculation, we agree to follow the order of operations: 

1. operations within grouping symbols first; 

2. exponents and roots next; 

3. multiplications and divisions (in order of appearance) next; 

4. additions and subtractions (in order of appearance) last. 

We remind you that “in order of appearance” means in order from left to right, and that “grouping symbols” include parentheses, brackets, braces (curly brackets), the square root symbol, and the horizontal fraction line as in<sup>a+b</sup> c−d<sup>.</sup> 

Example 92. Calculate 2 −<sup>3</sup> 5<sup>+1</sup> 2<sup>.</sup> Solution. Subtraction comes first in the left-to-right order. Rewriting 2 as<sup>10</sup> 5<sup>,wehave</sup> 

<!-- Start of picture text -->
� 105 − 5 3 � + 1 2 = 5 7 + 1 2= 14 (LCD = 10)10 + 10 5= 1910= 1 910 .<!-- End of picture text -->

Page 87 

<!-- Start of picture text -->
Example 93. Calculate 2 − .� 35 + 2 1 �<!-- End of picture text -->

Solution. This differs from the previous example only in the parentheses, which force us to do the addition first. Rewriting<sup>3</sup> 5<sup>and</sup> 2<sup>1withtheLCD10,wehave</sup> 

<!-- Start of picture text -->
2 − = 2 − 11� 106 + 10 5 � 10= 10 20 − 10 11= 910 .<!-- End of picture text -->

<!-- Start of picture text -->
Example 94. Calculate + 1 2� 32 �2 3 · 10 1 .<!-- End of picture text -->

Solution. We evaluate the expression with an exponent first ((<sup>2</sup> 3<sup>)2=4</sup> 9<sup>),followedbythemixednumber</sup> multiplication, followed by the addition. 

<!-- Start of picture text -->
+ 1 2� 23 �2 3 · 10 1 = 9 4 + 12 3 · 10 1= 4 (converting the mixed number to an improper fraction)9 + 5 3 · 10 1= 9 4 + 30 5= 4 (cancelling 5)9 + 1 6= 8 (LCD = 18)18 + 18 3= 1118 .<!-- End of picture text -->

<!-- Start of picture text -->
Example 95. Calculate 1 4 1 · 2 3 − 11 6 ÷ 11 2 .<!-- End of picture text -->

Solution. The order of operations is multiplication, division, subtraction. We first convert mixed numbers into improper fractions, and change the division into multiplication by the reciprocal. 

<!-- Start of picture text -->
54 · 2 3 − 7 6 ÷ 2 3 = 10 12 − 7 6 · 2 3= 12 10 − 14 18= 5 (lowest terms)6 − 7 9= 15 (LCD = 18)18 − 14 18= 118 .<!-- End of picture text -->

Page 88 

Example 96. Calculate �1 + �2 + 1<sup>1</sup> . � 4<sup>·2</sup> 3<sup>−11</sup> 6<sup>÷ 11</sup> 2 ��� 

Solution. In this example we have so-called nested grouping symbols, that is, grouping symbols inside other grouping symbols. In this case, we must work “from the inside out.” This means we work within the innermost grouping symbols first. From the previous example we know that 

<!-- Start of picture text -->
1 1 4 · 2 3 − 11 6 ÷ 11 2 = 18 1 ,<!-- End of picture text -->

thus we get 

<!-- Start of picture text -->
�1 + �2 + 1 1� 4 · 2 3 − 11 6 ÷ 11 2 ���= �1 + �2 + = {1 + � 37 �} = 55� 181 ��� 18 18 = 3 18 1 .<!-- End of picture text -->

#### 2.12.1 Exercises 

Calculate, using the correct order of operations. Express improper fractions as mixed numbers. 

<!-- Start of picture text -->
1. 3 4 + 3 2 ÷ 4 92. 2 − 4 3 + 31 23. − 2� 43 + 31 2 �4. �8 1 4 − 12 3 � ÷ 1 35. 7 1 2 ÷ 3 5 + 17 8 · 22 56. + 2 4� 43 �2 5 · 11 4<!-- End of picture text -->

7. Find the perimeter of a rectangle with length 2<sup>1</sup> 2<sup>ftandwidth13</sup> 4<sup>ft.</sup> 

8. Julia has two closets. The floor of one is a square 3<sup>1</sup> 2<sup>ftonaside.Theflooroftheotherisa</sup> rectangle of width 3<sup>1</sup> 2<sup>ft and length 41</sup> 2<sup>ft.She wants toput squaretiles on thefloors of the closets.</sup> How much will it cost if the tiles are $5 per square foot? 

Page 89 

Page 90 

## Chapter 3 - Decimals and Percents 

Decimals are mixed numbers in which the proper fractional part has a denominator which is 10, or 100, or 1000, or, more generally, a power of 10. Here are some powers of 10: 

<!-- Start of picture text -->
10 0 = 110 1 = 1010 2 = 10010 3 = 100010 4 = 1000010 n = 1 followed by n 0’s.<!-- End of picture text -->

The number above and to the right of 10 is the exponent, or power, and indicates the number of times that 10 appears as a factor. Thus 

<!-- Start of picture text -->
10 3 = 10 × 10 × 10 = 1000,<!-- End of picture text -->

and so forth. 

Here are some examples of mixed numbers in which the denominator of the fractional part is a power of ten, together with their representations as decimals: 

<!-- Start of picture text -->
1 3 = 1.31021 37 = 21.3710013 21 = 13.0211000<!-- End of picture text -->

The decimal point (which looks like the period at the end of a sentence) separates the whole number part from the proper fractional part. The digits to the right of the decimal point represent the fractional part according to the following rule: 

- the digits to the right of the decimal point constitute the numerator; 

- the number of digits to the right of the decimal point is the power of 10 which constitutes the denominator. 

91 

There is no need to show the fraction bar. As we shall see, this makes computation very easy. There are some subtleties to watch out for, however. In the example 

<!-- Start of picture text -->
13 21 = 13.021,1000<!-- End of picture text -->

we had to use 021 to represent the numerator 21 because we need three digits to show that the denominator is 10<sup>3</sup> . 

### 3.1 Decimal place values 

In Chapter 1 we showed that any whole number can be written using just the digits 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, by using the place value system. Thus, you will recall that 

<!-- Start of picture text -->
4267 stands for 4 thousands + 2 hundreds + 6 tens + 7 ones.<!-- End of picture text -->

Using powers of 10, we can write this more compactly: 

<!-- Start of picture text -->
4267 = 4 × 10 3 + 2 × 10 2 + 6 × 10 1 + 7 × 10 0 .<!-- End of picture text -->

The decimal point allows us to adjoin more places (to the right of the decimal point), with place values less than 1. Thus 

23.59 stands for 2 tens + 3 ones + 5 tenths + 9 hundredths. 

The first place to the right of the decimal point has the place value 10<sup>1, or one tenth; the second place to</sup> the right of the decimal point has the place value 1001<sup>,oronehundredth,andsoforth.Moregenerally,</sup> 

<!-- Start of picture text -->
1The nth place to the right of the decimal point has the place value10 n .<!-- End of picture text -->

This is a continuation of the pattern we established in Chapter 1: as we move to the right, place values decrease ten-fold (by a factor of one tenth). If we adopt the convention that 

<!-- Start of picture text -->
110 −n =10 n ,<!-- End of picture text -->

then the sequence of place values, from left to right, is just the sequence of decreasing powers of ten: 

... , 10<sup>3</sup> , 10<sup>2</sup> , 10<sup>1</sup> , 10<sup>0</sup> (decimal point) 10<sup>−1</sup> , 10<sup>−2</sup> , 10<sup>−3</sup> , ... ... , thousands, hundreds, tens, ones (decimal point) tenths, hundredths, thousandths, ... 

Example 97. Name the digit in tens place, and the digit in the hundredths place, in the decimal 304.671. 

Solution. The tens (10<sup>1</sup> ) place is the second place to the left of the decimal point. The digit in that place is 0. The hundredths (10<sup>−2</sup> ) place is the second place to the right of the decimal point. The digit in that place is 7. 

Example 98. What is the digit in the ten-thousandths place of the decimal 0.00286? 

Solution. One ten-thousandth is 

1 1 10000<sup>=</sup> 10<sup>4 ,</sup> 

so the ten-thousandths place is the fourth place to the right of the decimal point. The digit in that place is 8. 

Page 92 

#### 3.1.1 Exercises 

1. 19.01 stands for 

2. 0.946 stands for 

3. 98.6 stands for 

4. Name the digit in the hundred-thousandths place in the decimal 1.870457. 

5. Express the following mixed numbers as decimals: 

   - (a) 2 100<sup>23</sup> 

      - 100 

(b) 1000237 

   - (c) 19 10<sup>7</sup> 

   - (d) 1000012<sup>.</sup> 

6. Express the following decimals as mixed numbers or proper fractions: 

   - (a) 14.3 

   - (b) 28.61 

   - (c) 100.1 

   - (d) 4.003 

### 3.2 Significant and Insignificant 0’s 

Decimals are read aloud in the following way: 

- read the whole number part; 

- read “and” for the decimal point; 

- read the digits to the right of the decimal point as if they represented a whole number; 

- append the place-name of the last decimal place. 

Example 99. (a) 1.13 is read aloud as “one and thirteen hundredths.” 

- (b) 31.045 is read aloud as “thirty-one and forty-five thousandths”. 

- (c) 48.006 is read aloud as “forty-eight and six thousandths.” 

In the decimal 48.006, the fractional part .006 stands for 0 tenths + 0 hundredths + 6 thousandths. Reading aloud, we simply say “six thousandths.” Nonetheless, the two 0’s in .006 are absolutely necessary. If we had written .6 instead of .006, we would have named a different fraction, namely, 106<sup>,ratherthan</sup> 10006<sup>.Ontheotherhand,inthedecmial006.23,thefirsttwo0’sareunnecessary,sincethewhole</sup> number 006 is just 6. In one instance the 0’s are crucial, and in the other, they are unnecessary. 

How do we know which 0’s are significant, and which are insignificant? We can precede any whole number or whole number part of a decimal by as many 0’s as we want, because these 0’s do not change the value of the number (as in 006 = 6). Similarly, we can follow the fractional part of a decimal with as many 0’s as we want, because these 0’s do not change the value of the number. For example, .98000 = .98 because .98000 = 9 × 10<sup>−1</sup> + 8 × 10<sup>−2</sup> + 0 × 10<sup>−3</sup> +0 × 10<sup>−4</sup> + 0 × 10<sup>−5</sup> . In these cases, the 0’s are insignificant. In contrast, internal 0’s hold a place and cannot be omitted. 

Page 93 

Example 100. 2.3004 is not equal to 2.304, or to 2.34, because the fractional parts, 100003004<sup>,</sup> 1000304<sup>,and</sup> 10034<sup>arenotequal.The0’sinthehundredthsandthousandthsplacesof42.3004aresignificant,and</sup> therefore cannot be omitted. 

- In a decimal, a 0 digit is insignificant, and may be omitted, if (and only if) 

   - it precedes the left-most non-zero digit of the whole number part; or 

   - it follows the right-most non-zero digit of the fractional part. 

All other 0’s are significant, and cannot be omitted. 

Example 101. In the decimal 0304.90800, the 0 between 3 and 4, and the 0 between 9 and 8 are significant; the others are insignificant. Thus 

<!-- Start of picture text -->
0304.90800 = 304.908.<!-- End of picture text -->

Example 102. Does 23400 contain any insignificant 0’s? 

Solution. 23400 is a whole number. The decimal point is not shown, but is “understood” to be at the rightmost end. It follows that the two 0’s in 23400 are internal, and therefore, significant. 

It is sometimes convenient to preserve or adjoin non-significant 0’s. For example, when a decimal represents a proper fraction, the whole number part is 0, but that 0, to the left of the decimal point, is often retained for emphasis or clarity, even though it is insignificant. Thus the proper fraction 10067<sup>= .67</sup> is often written as 0.67. 

### 3.3 Comparing Decimals 

Insignificant 0’s are also useful in comparing decimals as to size. Recall that when fractions have the same (common) denominator, the one with the largest numerator represents the largest number. It is very easy to find a common denominator for two or more decimals, because the number of decimal places to the right of the decimal point is all that is needed to determine the denominator: if there are n places to the right of the decimal point, the denominator is 10<sup>n</sup> . Given a set of decimals, we just find the one with the largest number of decimal places to the right of the decimal point, and use that number to determine the common denominator. There is no computation involved: we simply “pad out” the shorter decimals with insignificant 0’s to the right of the decimal place until all have the same number of decimal places. Then it is easy to tell which decimal has the largest numerator, and hence, which is largest. 

Example 103. Arrange the decimals in descending order, from largest to smallest: 0.102, 0.09876, 0.2. 

Solution. Of the three given decimals, 0.09876 is the longest, with 5 places to the right of the decimal point. So we pad out all three to 5 places, using insignificant 0’s: Thus 

<!-- Start of picture text -->
0.102 = 0.10200 (3.1)<!-- End of picture text -->

<!-- Start of picture text -->
0.09876 = 0.098760.2 = 0.20000<!-- End of picture text -->

Page 94 

In this form, the decimals have a common denominator of 10<sup>5</sup> = 100000: 

<!-- Start of picture text -->
98760.102 = 10200 0.09876 = 0.2 = 20000100000 100000 100000 .<!-- End of picture text -->

Now, it is easy to see which has the largest numerator, which the second-largest, and which the smallest. Hence we have 

0.2 > 0.102 > 0.09876. 

#### 3.3.1 Exercises 

Eliminate the insignificant 0’s in the following decimals. 

1. 210304.0900 

2. 00206.006070 

3. 210.00 

4. 21030900 

Arrange each group of decimals in descending order, from largest to smallest: 

5. 0.2, .009, .121. 

6. 1.31, 1.9, 1.224. 

7. 0.106, 0.5, 0.61. 

8. 9.104, 9.14, 9.137, 9.099. 

### 3.4 Rounding-off 

The numbers 

<!-- Start of picture text -->
0.1, 0.11, 0.111, 0.1111, 0.11111<!-- End of picture text -->

get closer and closer together (on the number line) as we move from left to right. After a few steps, they are almost too close together to visualize. The second number was obtained from the first by adding 1001<sup>,andthelastfromthesecond-to-lastbyaddingjust</sup> 1000001<sup>,averysmallquantityindeed.</sup> Such small quantities can be important in the sciences, but even in circumstances where precision is important, there is always a limit beyond which small differences become negligible – not worth worrying about. (For example, when your bank calculates the interest on your savings account, it calculates, but then ignores, amounts that are less than one half of one cent.) Being precise, but not overly precise, is the purpose of rounding-off numbers. 

To round off a number, we must first decide how precise to be. That means choosing the place whose value we consider the smallest worth worrying about. For example, in negotiating an annual salary, we would probably not argue about amounts less than $100, but in negotiating an hourly wage, we would be willing to argue about pennies. In the first instance, we would round off our dollar amounts to the nearest hundred, and in the second, to the nearest hundredth (cent). 

Page 95 

Example 104. $175 is closer to $200 than to $100, so, rounding to the nearest hundred, we say that an annual salary of $36, 175 is approximately $36, 200. We write 

36175 ≈ 36200 (to the nearest hundred). 

The symbol ≈ means “approximately equal to.” 

Example 105. 16.84 is closer to 16.80 than to 16.90, so, to the nearest tenth, 

<!-- Start of picture text -->
16.84 ≈ 16.8.<!-- End of picture text -->

Notice that we dropped the insignificant 0 in 16.80. 

Example 106. 0.135 is exactly halfway between 0.130 and 0.140, so, if we want to round to the nearest hundredth, it is not clear whether we should round “up” to 0.140, or “down” to 0.130. Here, we have to make up a rule. The convention is that “halfway is almost home,” so we round up. 

0.135 ≈ 0.14 (to the nearest hundredth), 

where, again, we have dropped the insignificant 0 in 0.140. 

Below is a summary of the procedure for rounding off a number expressed as a decimal to a given place, called the round-off place. 

To round off a decimal to a given place (the round-off place): 

1. Preserve the digit in the round-off place if the right-neighboring digit is less than 5; otherwise, increase the digit in the round-off place by 1; 

2. Replace all digits to the right of the round-off place by 0’s; 

3. Eliminate insignificant 0’s (except a 0 in the round-off place). 

Example 107. Round 26.03 to the nearest tenth. 

Solution. The round-off place is the tenths place, and the right-neighboring digit (3) is less than 5, so we preserve the digit in the round-off place (0) and replace all digits to the right (there is only one) with 0. We get 26.00. Here the exception in step 3 of the procedure applies: both the 0’s are insignificant, but we keep the 0 in the round-off place (otherwise it might seem as if we had rounded to the nearest unit). Thus 

26.03 ≈ 26.0 (to the nearest tenth) 

Example 108. Round 51 to the nearest hundred. 

Solution. The round off place (hundreds) doesn’t appear, but we can show it by adjoining an insignificant 0 on the left: 51 = 051. The right neighbor of the round-off digit is 5, so, by the “halfway” convention, we round the 0 in the round-off place up to 1, and replace all digits to the right with 0. We get 

<!-- Start of picture text -->
51 ≈ 100 (to the nearest hundred).<!-- End of picture text -->

Notice that the two 0’s in 100 are significant, and cannot be eliminated! 

Page 96 

One final remark about step 2 of the procedure. If the digit in the round-off place is 9, and we need to round up (to 10), we must carry the 1 to the left-neighboring place. 

Example 109. Round 6.597 to the nearest hundredth. 

Solution. The 9 in the round-off place has right-neighbor 7, which is greater than 5. So we increase 9 to 10, and carry the 1 to the (left-neighboring) tenths place: 

<!-- Start of picture text -->
6.597 ≈ 6.60 (to the nearest hundredth)<!-- End of picture text -->

Notice we preserved the insignificant 0, since it is in the round-off place. 

#### 3.4.1 Exercises 

Round off each number twice: (a) to the nearest ten; (b) to the nearest hundredth. 

1. 304.0900 

2. 96.075 

3. 115.497 

4. 100.0055 

5. 7.009 

### 3.5 Adding and Subtracting Decimals 

One of the advantages of decimals over ordinary fractions is ease of computation. The four operations (addition, subtraction, multiplication and division) are done almost exactly as with whole numbers. The only question is where to put the decimal point. 

Addition and subtraction are the easiest: we line up the numbers vertically, with the ones places aligned on top of eachother. This puts the decimal points in alignment as well. The decimal point in the sum is placed directly below the decimal points in the numbers being added. Carrying and borrowing are done as with whole numbers. 

Example 110. Find the sum of 96.8 and 342.03. 

Solution. Line up the numbers vertically so that the ones places (and hence the neighboring decimal points) are directly on top of eachother. 

<!-- Start of picture text -->
9 8 . 8+ 3 4 2 . 0 3<!-- End of picture text -->

For clarity, you can “pad out” the top number with an insignificant 0 so that both numbers have the same number of decimal places. (This is not strictly necessary: just remember that an empty place is occupied by a 0.) Place a decimal point, vertically aligned with the others, where the sum will go. 

<!-- Start of picture text -->
9 8 . 8 0+ 3 4 2 . 0 3<!-- End of picture text -->

Page 97 

As before, add the digits in each column starting from the right-most one, carrying when necessary: 

<!-- Start of picture text -->
9 8 . 8 0+ 3 4 2 . 0 34 4 0 . 8 3<!-- End of picture text -->

The sum is 440.83. 

Example 111. Find the sum of 804.09, 56.384, 107, and 0.205. 

Solution. Line up the numbers vertically at the decimal points (equivalently, at the ones place). In the whole number 107, the decimal point is understood to be directly to the right of the ones place. Add the columns from right to left, imagining 0’s in the empty places, and carrying when necessary. 

<!-- Start of picture text -->
8 0 4 . 0 95 6 . 3 8 41 0 7 .+ 0 . 2 0 59 6 7 . 6 7 9<!-- End of picture text -->

Subtraction follows the same vertical alignment rule. 

Example 112. Find the difference 50 − 4.706. 

Solution. The larger number, 50, goes on top. We fill it out with insignificant 0’s so that both the minuend and the subtrahend have the same number of decimal places. 

<!-- Start of picture text -->
5 0 . 0 0 0− 4 . 7 0 6<!-- End of picture text -->

Borrowing from the tens place of the subtrahend, we can write 

<!-- Start of picture text -->
50.000 = 5 tens + 0 ones + 0 tenths + etc.= 4 tens + 9 ones + 9 tenths + 9 hundredths + {10} thousandths= 49.99{10}<!-- End of picture text -->

Then our subtraction becomes 

<!-- Start of picture text -->
4 9 . 9 9 {10}− 4 . 7 0 64 5 . 2 9 4<!-- End of picture text -->

Page 98 

#### 3.5.1 Exercises 

Find the sums or differences: 

1. 680.48 + 56.09 

2. 804.09 + 5.8409 

3. 58.09 − 32.1 

4. 4.09 + 0.38409 

5. 14.093 − 6.39 

6. 100 − 23.441 

7. 830 − 16.61 

8. 80 − 56.384 

9. Verify the subtraction problems above by doing an appropriate addition. 

10. Find the sum of 64.09, 15.3, 4, and 9.09. 

11. The difference of 20 and the sum of 4.6 and 0.07 

### 3.6 Multiplying and Dividing Decimals by Powers of 10 

What happens when we multiply a whole number by 10? Ones become tens, tens become hundreds , hundreds become thousands , etc. For example, in the multiplication 

<!-- Start of picture text -->
234 × 10 = 2340,<!-- End of picture text -->

the 4 ones in 234 turn into the 4 tens in 2340, the 3 tens turn into 3 hundreds and so forth. (In the product, there are no longer any ones , and that fact must be recorded with a significant 0 in the ones place.) 

Remember that a whole number is a decimal, with the decimal point understood to be immediately to the right of the ones place. Making the decimal point explicit in our example, 

<!-- Start of picture text -->
234.0 × 10 = 2340.<!-- End of picture text -->

We can describe what happens this way: when we multiply by 10, all the digits shift one place to the left, including the insignificant 0 which was understood to be in the tenths place of the whole number 234. (In this description, we imagine the decimal point remaining fixed.) Similarly, if we multiply a whole number by 100, all the digits shift two places to the left, including the two insignificant 0’s which are understood to be in the tenths and hundredths places. Thus, 597 × 100 = 59 700, or, more explicitly, 

597.00 × 100 = 59 700. 

In general, if we multiply a whole number by any positive power of 10, say, by 10<sup>n</sup> , all the digits shift n places to the left, including the n insignificant 0’s understood to be in the n places to the right of the decimal point (while the decimal point remains fixed). Thus, for example, 

<!-- Start of picture text -->
281 × 10 4 = 2 810 000.<!-- End of picture text -->

Page 99 

If there are non-zero digits to the right of the decimal place, they shift in exactly the same way. Here are some examples: 

<!-- Start of picture text -->
38.623 × 100 = 3862.30.6 × 10 = 60.0031 × 1000 = 3.112.09 × 10 4 = 120 900100 × 10 2 = 10000.<!-- End of picture text -->

Note that insignificant 0’s have been omitted from the products. 

It is often convenient to imagine that, when multiplying by a power of 10, the digits remain fixed while the decimal point moves (to the right ). (Electronic calculators work this way, using a “floating” decimal point.) This description leads to a very easy rule for multiplying a decimal by a positive power of 10: 

To multiply a decimal by 10<sup>n</sup> , move the decimal point n places to the right. 

If we divide a decimal by 10, hundreds becomes tens , tens become ones, ones become tenths , tenths become hundredths , etc. The whole discussion above can be repeated, except that, in this case of division, digits shift to the right , or, equivalently, the decimal point moves to the left . The easy rule is 

To divide a decimal by 10<sup>n</sup> , move the decimal point n places to the left. 

Here are some examples: 

<!-- Start of picture text -->
623 ÷ 10 = 62.30.023 ÷ 100 = 0.00023480 ÷ 10 = 4837.5 ÷ 10 3 = 0.0375<!-- End of picture text -->

With the convention that 

<!-- Start of picture text -->
110 −n =10 n ,<!-- End of picture text -->

division by 10<sup>n</sup> can be thought of as multiplication by 10<sup>−n</sup> . For example, 

<!-- Start of picture text -->
5 ÷ 100 = 5 × 10 −2 = 0.056.5 ÷ 10 = 6.5 × 10 −1 = 0.6586.37 ÷ 10000 = 86.37 × 10 −4 = 0.0086378 ÷ 100000 = 8 × 10 −5 = 0.00008<!-- End of picture text -->

Notice that the left movement of the decimal point is indicated by the negative exponent. 

Page 100 

#### 3.6.1 Exercises 

Multiply or divide each decimal by the indicated power of 10. 

1. 6080.48 × 10 

2. 6080.48 ÷ 10 

3. 19 × 10<sup>−1</sup> 

4. 804.09 × 10<sup>2</sup> 

5. 804.09 ÷ 10<sup>2</sup> 

6. 0.0908 × 10<sup>3</sup> 

7. 0.0908 ÷ 10<sup>3</sup> 

8. 38 × 10<sup>−3</sup> 

9. 260804.09 × 10<sup>4</sup> 

10. 260804.09 ÷ 10<sup>5</sup> 

11. 48.3 × 10<sup>−3</sup> 

12. What is the value, in dollars, of 5 million pennies? 

### 3.7 Multiplication of general decimals 

We already know how to multiply and divide decimals when one of them is a power of 10. If neither factor is a power of ten, there is more to the process than just moving the decimal point. Consider the following example. 

Example 113. Multiply 0.3 × 0.07. 

Solution. Writing this as a product of ordinary fractions, we get 

<!-- Start of picture text -->
0.3 × 0.07 = 3 7 3 × 7 2110 × 100 = 10 × 100 = 1000 .<!-- End of picture text -->

The last fraction can be written 21 ÷ 10<sup>3</sup> , or 21 × 10<sup>−3</sup> which, from the results of the last section, is equal to 0.021. Thus, 

<!-- Start of picture text -->
0.3 × 0.07 = 0.021.<!-- End of picture text -->

Multiplication of two decimals always involves a whole number multiplication for the numerator (3 × 7 = 21 in the example) and a multiplication of powers of 10 for the denominator (10 × 100 = 10<sup>1</sup> × 10<sup>2</sup> = 1000 = 10<sup>3</sup> in the example). By looking back at the previous section, it is easy to see the product of two powers of 10 is itself a power of 10. Which power of 10? The rule is simple: 

<!-- Start of picture text -->
10 n × 10 m = 10 (n+m)<!-- End of picture text -->

Page 101 

This implies that the number of decimal places in the product of two (or more) decimals is the sum of the numbers of decimal places in the factors. Thus any set of decimals can be multiplied by following a two step procedure: 

To multiply two or more decimals: 

- Multiply the decimals as if they were whole numbers, ignoring the decimal points (this gives the numerator of the decimal fraction); 

- Add the number of decimal places in each factor (this gives the denominator of the decimal fraction by specifying the number of decimal places). 

Example 114. Find the product 21.02 × 0.004. 

Solution. Temporarily ignoring the decimal points, we multiply 2102 × 4 = 8408. Now 21.02 has two decimal places, and 0.004 has three. So the product will have 2+ 3 = 5 decimal places. In other words, 

<!-- Start of picture text -->
21.02 × 0.004 = 8408 ÷ 10 5 = 0.08408.<!-- End of picture text -->

Example 115. Find the product of 12, 0.3, and 0.004. 

Solution. Ignoring the decimal points, the product is 12 × 3 × 4 = 144. The numbers of decimal places in the three decimals are, left to right, 0, 1 and 3, which add up to 4. Thus, 

12 × 0.3 × 0.004 = 144 ÷ 10<sup>4</sup> = 0.0144. 

#### 3.7.1 Exercises 

Find the following products. 

1. 68.4 × 23 

2. 804 × 6.2 

3. 26.09 × 0.004 

4. 4.09 × 93 

5. 100 × 9.9 

6. 14.093 × 6.39 7. 64.9 × 0.345 

8. 0.0001 × 0.001 

9. 1000 × 0.053 

10. 6 × 0.9 × 0.02 × 0.001 

Page 102 

### 3.8 Division of a decimal by a whole number 

If the divisor is a whole number, the division procedure is almost exactly like the long division procedure for whole numbers. The only difference is this: a decimal point is placed where the quotient will go, vertically aligned with the decimal point in the dividend. For example, to set up the division 12.0342÷31, we write, as before 

<!-- Start of picture text -->
3 1 1 2 . 0 3 4 2<!-- End of picture text -->

Then we put a decimal point vertically aligned with the decimal point in the divisor, where the quotient will go: 

<!-- Start of picture text -->
.3 1 1 2 . 0 3 4 2<!-- End of picture text -->

Now the long division is performed with no further attention paid to the decimal point. In this example, since 31 is bigger than 12, we put 0 in the units place of the quotient. Continuing, we estimate that 31 goes into 120 3 times, so 3 is placed in the next (tenths) place in the quotient, and 3 × 31 is subtracted from 120 to yield 27. (Note that the decimal point between 2 and 0 is ignored at this point.) 

<!-- Start of picture text -->
0 . 33 1 1 2 . 0 3 4 2− 9 32 7<!-- End of picture text -->

We bring down the next digit in the dividend, which is 3, and start over with a new dividend of 273. We estimate that 31 goes into 273 8 times. 8 × 31 = 248, which is subtracted from 273 to yield 25. 

Page 103 

<!-- Start of picture text -->
0 . 3 83 1 1 2 . 0 3 4 2− 9 32 7 3− 2 4 82 5<!-- End of picture text -->

We bring down the next digit in the dividend, which is 4, and start over with a new dividend of 254, etc. The remaining steps are as follows. 

<!-- Start of picture text -->
0 . 3 8 8 23 1 1 2 . 0 3 4 2− 9 32 7 3− 2 4 82 5 4− 2 4 86 2− 6 20<!-- End of picture text -->

Thus, 12.0342 ÷ 31 = 0.3882, with 0 remainder. We can check the result by multiplication, of course: 31 × 0.3882 = 12.0342, as it should. 

In this example, the remainder was 0. In fact, because of the decimal point, we never need to write remainders again. The reason is that we can always adjoin insignificant 0’s to to the end of the dividend, bring them down, and so continue the division process. 

Example 116. Perform the division 12.4 ÷ 5. 

Solution. We set up the long division process as before, with a decimal point where the quotient will go, directly above the decimal point in the dividend. 

<!-- Start of picture text -->
.5 1 3 . 4<!-- End of picture text -->

After two steps, we arrive at 

Page 104 

<!-- Start of picture text -->
2 . 65 1 3 . 4− 1 03 4− 3 04<!-- End of picture text -->

Now, instead of stopping with a remainder of 4, we adjoin an insignificant 0 to the dividend, bring it down, and continue the process: 

<!-- Start of picture text -->
2 . 65 1 3 . 4 0− 1 03 4− 3 04 0<!-- End of picture text -->

5 goes into 40 exactly 8 times: 

<!-- Start of picture text -->
2 . 6 85 1 3 . 4 0− 1 03 4− 3 04 0− 4 00<!-- End of picture text -->

The 0 remainder signals the end of the process. Thus 13.4 ÷ 5 = 2.68. 

Since we can adjoin as many insignificant 0’s as we need, it might seem that we can always continue until we get a 0 remainder. But this doesn’t always happen. Sometimes, we never get a 0 remainder, but instead, we get a sequence of non-zero remainders that repeats, forever. In this case, we get what is know as a repeating decimal. 

Example 117. Perform the division 3.2 ÷ 11. 

Solution. We set up the long division process as usual. 

Page 105 

. 11 3 . 2 

11 goes into 32 twice with a remainder of 10: 

<!-- Start of picture text -->
. 211 3 . 2− 2 21 0<!-- End of picture text -->

Adjoin an insignificant 0 to the dividend, bring it down, and perform another step: 11 goes into 100 9 times with a remainder of 1. 

<!-- Start of picture text -->
. 2 911 3 . 2 0− 2 21 0 0− 9 91<!-- End of picture text -->

Now if we adjoin another insignificant 0 to the dividend, and bring it down, we see that 11 goes into 10 0 times. We record that with a 0 digit in the quotient, adjoin another insignificant 0 to the dividend, and bring it down. Now we see that (as above) 11 goes into 100 9 times with a remainder of 1. 

Page 106 

<!-- Start of picture text -->
. 2 9 0 911 3 . 2 0− 2 21 0 0− 9 91 0 0− 9 91<!-- End of picture text -->

It is evident that these last two steps will now repeat again and again, forever. The decimal will never terminate, since a 0 remainder will never occur. Still, it is easy to describe the quotient: it will consist of 29 after the decimal point, followed by an endless string of 09’s. To indicate this, we put a bar over the repeated string: 

<!-- Start of picture text -->
0.2909090909090909 · · · = 0.2909.<!-- End of picture text -->

Thus, 3.2 ÷ 11 = 0.2909. 

We emphasize that it may take a while for the digits to start repeating, and the bar is only placed over the repeating part. For example, the repeating decimal 

<!-- Start of picture text -->
0.796812341234123412341234 ...<!-- End of picture text -->

is written, using the bar notation, as 

0.79681234. 

The repeated string can be quite long, or just a single digit. Here are some examples, which you should verify by carrying out the division process: 

<!-- Start of picture text -->
3 ÷ 7 = 0.4285712 ÷ 11 = 0.095 ÷ 3 = 1.6<!-- End of picture text -->

Sometimes, we don’t care whether a decimal terminates or repeats. For example, if we know in advance that we can round off our answer to a given decimal place, we carry out the division only as far as the right neighboring place and stop (this gives us all we need to know to round off). Example 118. Suppose you bought 900 buttons for $421. To the nearest cent, how much did you spend for each button? 

Solution. We need to perform the division 421 ÷ 900. Since we are rounding to the nearest hundredth (cent), we need only carry out the division as far as the thousandths place. Since the thousandths place is the the third place to the right of the decimal point, we adjoin three insignificant 0’s to the dividend, setting up the division as 421.000 ÷ 900. We omit the details, but you can verify that the quotient, carried out to three decimal places, is 0.467, which, rounded to the nearest hundredth, is 0.47. Therefore, the buttons cost approximately 47 cents each. 

If you carried out the division process a little further, you noticed that the quotient is actually a repeating decimal: 

421 ÷ 900 = 0.46777777 · · · = 0.467. 

Page 107 

#### 3.8.1 Exercises 

Perform the indicated divisions. Use the bar notation for repeating decimals. If you round off, indicate to what place. 

1. 91 ÷ 20 2. 14.68 ÷ 5 3. 23 ÷ 90 4. 86 ÷ 71 5. 6.02 ÷ 9 6. 4.19 ÷ 13 7. 804.09 ÷ 215 8. 353 ÷ 37 9. 17 ÷ 19 

10. 38.8 ÷ 40 

### 3.9 Division of a decimal by a decimal 

What do we do when the divisor is a decimal? For example, how do we perform the division 8.61 ÷ 2.5? The answer is simple. Just multiply both the dividend and divisor by a power of 10 sufficiently large to make the divisor into a whole number, and then proceed as before. In this example, if we multiply both numbers by 10<sup>1</sup> , the divisor 2.5 turns into the whole number 25 and the dividend turns into 86.1. Recall that two fractions are equivalent, that is, represent the same number, if one is obtained from the other by multiplying both numerator and denominator by the same nonzero number. In this case, the convenient choice of nonzero multiplier is 10<sup>1</sup> = 10, because it turns the denominator (divisor) into a whole number. Thus, 

<!-- Start of picture text -->
8.612.5 = 8.61 2.5 ×  ×  10  10 = 86.1 25 .<!-- End of picture text -->

In other words, the division problem 8.61 ÷ 2.5 has the same quotient as the division problem 86.1 ÷ 25. We do the latter problem exactly as in the previous section. 

<!-- Start of picture text -->
3 . 4 4 42 5 8 6 . 1 0 0− 7 51 1 1− 1 0 01 1 0− 1 0 01 0 0− 1 0 00<!-- End of picture text -->

Page 108 

Since the remainder is 0, the quotient is a terminating decimal. 8.61 ÷ 2.5 = 3.444. (Question: why didn’t we write 3.4?) 

Example 119. Perform the division 32.067 ÷ 6.41 and round off the quotient to the nearest hundredth. Solution. There are two decimal places in the divisor, 6.41, so multiplying it by 10<sup>2</sup> = 100 will give us a whole number: 6.41 × 10<sup>2</sup> = 641. Doing the same to the dividend yields the equivalent division problem, 

<!-- Start of picture text -->
3206.7 ÷ 641.<!-- End of picture text -->

Since we are rounding off to the nearest hundredth, we will need to carry out the division to the thousandths place. We therefore add two insignificant 0’s to the dividend, and perform the division as follows: 

<!-- Start of picture text -->
5 . 0 0 26 4 1 3 2 0 6 . 7 0 0− 3 2 0 51 7 0 0− 1 2 8 24 1 8<!-- End of picture text -->

Since the digit in the thousandths place of the quotient is less than 5, we preserve the digit in the hundredths place. The quotient is ≈ 5.00 (to the nearest hundredth). 

#### 3.9.1 Exercises 

Write each division as an equivalent division with a whole number divisor. 

1. 680.4 ÷ 1.01 

2. 0.48 ÷ 11.4 

3. 804.09 ÷ 9.18 

4. 9.8 ÷ 0.0215 

Perform the divisions. 

<!-- Start of picture text -->
5. 4.19 ÷ 0.56. 4.09 ÷ 0.217. 353 ÷ 2.5<!-- End of picture text -->

8. 0.004 ÷ 0.002 

9. 29.997 ÷ 0.01 

Page 109 

### 3.10 Percents, Conversions 

A percent is a fraction in which the denominator is 100. The word “percent” comes from the Latin phrase per centum meaning “out of 100,” and is symbolized by %. For example, 

<!-- Start of picture text -->
9797% means or 0.97.100<!-- End of picture text -->

Percents need not be whole numbers, and they need not represent proper fractions. For example, 

<!-- Start of picture text -->
150% = 150100 = 1.50.5% = 0.5100 = 0.005<!-- End of picture text -->

Fractions, decimals, and percents represent the same quantities in different ways, and we need to know how to convert one to another. 

A decimal can be converted to a percent by moving the decimal point two places to the right and adjoining the % symbol. This is the same as multiplying the decimal fraction by 100, which exactly cancels the denominator, leaving just the numerator (the percent). Thus 

<!-- Start of picture text -->
0.68 = 68%2.05 = 205%0.708 = 70.8%1.4 = 140%0.0067 = 0.67%<!-- End of picture text -->

To convert a percent back into a decimal, we simply divide by 100, which, as we know, is equivalent to moving the decimal point two places to the left. Thus 

<!-- Start of picture text -->
92% = 0.920.2% = 0.002138% = 1.3871.02% = 0.7102<!-- End of picture text -->

To convert a percent to a fraction (or mixed number), first convert the percent to a decimal, as above, then express the decimal as a fraction (with a visible denominator), and finally, reduce the fraction to lowest terms, if needed. 

Example 120. Convert 10.8% into a fraction in lowest terms. 

Solution. We first write 10.8% as a decimal. 

<!-- Start of picture text -->
10.8% = 0.108.<!-- End of picture text -->

Then, we write the decimal as a fraction with a visible denominator. In this case, because there are 3 decimal places, the denominator is 1000. 

<!-- Start of picture text -->
0.108 = 1081000 .<!-- End of picture text -->

Page 110 

Finally, the GCF of the numerator and denominator is 4, so we cancel 4 from both of these numbers, obtaining a fraction in lowest terms: 

<!-- Start of picture text -->
: 27108 108 = 271000 = : 250 250 .1000<!-- End of picture text -->

Here are some common percents with their decimal and fractional equivalents (in lowest terms): 

<!-- Start of picture text -->
10% = 0.1 = 1 20% = 0.2 = 1 25% = 0.25 = 1 50% = 0.5 = 110 , 5 , 4 , 2 .<!-- End of picture text -->

To convert a fraction to a decimal, we just perform long division. 

Example 121. Convert<sup>1</sup> 4<sup>toadecimal.</sup> 

Solution. Performing the division 1 ÷ 4, we obtain 

<!-- Start of picture text -->
0 . 2 54 1 . 0 0− 82 0− 2 00<!-- End of picture text -->

Thus 4<sup>1= 0.25.</sup> 

To convert a fraction to a percent, first convert it to a decimal, and then convert the decimal to a percent. Example 122. Convert 401<sup>toapercent.</sup> 

Solution. Performing the division 1 ÷ 40, we obtain 0.025 (verify this – it is quite similar to the last example). Then, we convert 0.025 to a percent by multiplying by 100 (equivalently, by moving the decimal point two places to the right). We obtain 

<!-- Start of picture text -->
140 = 2.5%.<!-- End of picture text -->

#### 3.10.1 Exercises 

Convert the following percents to decimals. 

1. 43% 

2. 608% 

Page 111 

3. 56.04% 

4. 4.09% 

Convert the following decimals to percents. 

5. 14.09 

6. 0.00679 

7. 1.384 

8. 0.384 

Convert the following decimals or percents to fractions (or mixed numbers) in lowest terms. 

9. 44% 

10. 2% 

11. 0.15 

12. 0.25 

13. 40% 

14. 5% 15. 98% 

16. 7.2% 

17. 18% 

Convert the following fractions, first to decimals, then to percents. Round percents to the nearest tenth of a percent. 

18. 1 8 

19. 1 6 

20. 2 5 

21. 3 8 

22. 3 4 

23. 1 13 

24. 1 12 

25. 5 12 

Page 112 

### 3.11 Fractional parts of numbers 

We now have several ways of indicating a fractional part of a number. For example, the phrases 

<!-- Start of picture text -->
1of 9040.25 of 9025% of 90<!-- End of picture text -->

are all different ways of describing the number<sup>1</sup> 4<sup>× 90 =22.5.Theword“of”indicatesmultiplication.</sup> In the case of percent, the multiplication is done after first converting the percent to a fraction or a decimal. 

The fractional part taken need not be a proper fractional part. That is, we could end up with more than we started with. 

Example 123. Find 125% of 500. 

Solution. Converting the percent to the decimal 1.25, and then multiplying by 500, we get 

<!-- Start of picture text -->
1.25 × 500 = 625.<!-- End of picture text -->

Example 124. Sales tax in New York State is 8 4<sup>1%.Whatisthesalestaxonashirtpricedat$25?</sup> Solution. 8<sup>1</sup> 4<sup>= 8.25,and8.25%,asadecimal,is.0825.Sothesalestaxona$25shirtis</sup> 

.0825 × 25 = 2.0625 ≈ $2.06. 

Note that we rounded off to the nearest cent. 

Example 125. Josh spends<sup>2</sup> 5<sup>ofhisincomeonrent.Ifheearns$1250permonth,howmuchdoeshe</sup> have left over, after paying his rent? 

Solution. The left over part is<sup>3</sup> 5<sup>,since1 −2</sup> 5<sup>=5</sup> 5<sup>−</sup> 5<sup>2=3</sup> 5<sup>.Sohehas</sup> 

<!-- Start of picture text -->
: 2503 1250× = $7505 × 1250 = 3 * 1 1�5 �<!-- End of picture text -->

left over after paying rent. 

#### 3.11.1 Exercises 

1. Find 16% of 75 

2. Find 8<sup>3of60</sup> 

3. Find .05 of 280 

4. Find 150% of 105 

5. Find<sup>1</sup> 2<sup>%of248</sup> 

Page 113 

6. A $500 television is being sold at a 15% discount. What is the sale price? 

7. Angela gets a 5% raise. Her original salary was $36, 000 per year. What is her new salary? 

8. A car loses<sup>2</sup> 5<sup>of its value overa period of years.If the caroriginally sold for$12, 500,what it would</sup> it sell for now? 

9. On a test, Jose answers<sup>7</sup> 8<sup>oftheproblemscorrectly.Iftherewere24problemsonthetest,how</sup> many did he get wrong? 

10. Medical expenses can be deducted from a person’s income tax if they exceed 2% of total income. If Maribel’s medical expenses were $550, and her total income was $28, 000, can she deduct her medical expenses? 

Page 114 

## Chapter 4 - Ratio and Proportion 

In this chapter we develop another interpretation of fractions, as comparisons between two quantities. 

### 4.1 Ratio 

If a team wins ten games and loses five, we say that the ratio of wins to losses is 2 : 1, or “2 to 1.” Where did the numbers 2 : 1 come from? We simply made a fraction whose numerator is the number of games the team won, and whose denominator is the number of games they lost, and reduced it to lowest terms: wins losses<sup>=10</sup> 5<sup>=2</sup> 1<sup>.</sup> 

We can do the same for any two quantities, a and b, as long as b̸ = 0. 

<!-- Start of picture text -->
The ratio of a to b (b̸ = 0) is the fraction ab , reducedto lowest terms.<!-- End of picture text -->

Example 126. Find (a) the ratio of 9 to 18, (b) the ratio of 21 to 12, (c) the ratio of 64 to 4. 

Solution. (a) The ratio of 9 to 18 is 

<!-- Start of picture text -->
(b) The ratio of 21 to 12 is(c) The ratio of 64 to 4 is<!-- End of picture text -->

<!-- Start of picture text -->
9or 1 : 2.18 = 2 121or 7 : 4.12 = 4 764or 16 : 1.4 = 16 1<!-- End of picture text -->

Notice that in (c) we left the denominator 1 (rather than just writing 16) to maintain the idea of a comparison between two numbers. 

We can form ratios of non-whole numbers. When the ratio is expressed in lowest terms, however, it is always the ratio of two whole numbers, as small as possible. This is the main point of a ratio comparison: if the given two numbers were small whole numbers, how would they compare? Example 127. What is the ratio of 3 4<sup>3to11</sup> 2<sup>?</sup> 

115 

Solution. Converting the mixed numbers to improper fractions, and rewriting the division as multiplication by the reciprocal, we obtain 

<!-- Start of picture text -->
> 5 > 13 3 15 × 2 = 54 ÷ 11 2 = 15 4 × 3 2 = > 2 > 1 2 .4 3<!-- End of picture text -->

The ratio is 5 : 2. 

Example 128. What is the ratio of 22.5 to 15? 

Solution. We could perform the decimal division 22.5 ÷ 15, but it is easier to simplify the equivalent fraction 

<!-- Start of picture text -->
225150 = 2 3 .<!-- End of picture text -->

The ratio is 3 : 2. 

When finding the ratio of two measurable quantities, we must be sure the quantities are expressed in the same units. Otherwise the ratio will be a skewed or false comparison. Example 129. Find the ratio of 15 dollars to 30 cents. 

Solution. If we form the ratio<sup>15</sup> 30<sup>=</sup> 2<sup>1,weimplythatapersonwalkingaroundwith$15inhispocket</sup> has half as much money as a person walking around with only 30 cents! The proper comparison is obtained by converting both numbers to the same units. In this case, we convert dollars to cents. The correct ratio is 

<!-- Start of picture text -->
1500 cents = 5030 cents 1 .<!-- End of picture text -->

Example 130. Manuel gets a five minute break for every hour he works. What is the ratio of work time to break time? 

Solution. Since 1 hour = 60 minutes, the ratio of work time to break time is 

<!-- Start of picture text -->
55 minutes5 minutes = 11 1 .<!-- End of picture text -->

Recall that percent (%) means “per hundred.” So a percent can be viewed as a ratio whose second term (denominator) is 100. 

Example 131. At a certain community college, 55% of the students are female. Find (a) the ratio of female students to the total number of students, and (b) the ratio of female students to male students. 

Solution. 55% indicates the fraction 

<!-- Start of picture text -->
10055 = 11 20 ,<!-- End of picture text -->

so the ratio of female students to the total number of students is 11 : 20. For (b), we first deduce that 45% of the students are male (since 45% = 100% − 55% ). So the ratio of female students to male students is 

<!-- Start of picture text -->
55or 11 : 9.45 = 11 9<!-- End of picture text -->

Page 116 

Example 132. A printed page 8<sup>1</sup> 2<sup>inchesinwidthhasamargin5</sup> 8<sup>incheswideoneitherside.Textis</sup> printed between the margins. What is the ratio of the width of the printed text to the total margin width? 

Solution. The total margin width is<sup>5</sup> 8<sup>+5</sup> 8<sup>=</sup> 4<sup>5=1</sup> 4<sup>1inches(takingintoaccountbothleftandright</sup> margins.) The width of the printed text is the difference 

<!-- Start of picture text -->
total page width − total margin width = 8 1 2 − 11 4 = 71 4 inches.<!-- End of picture text -->

The ratio of the width of the printed text to total margin width is 

<!-- Start of picture text -->
7 1 4 ÷ 11 4 = 29 4 ÷ 4 5 = 29 4 · 5 4 = 29 5 ,<!-- End of picture text -->

or 29 : 5. 

#### 4.1.1 Exercises 

Find the ratios. 

1. 14 to 4 

2. 30 to 32 

3. 56 to 21 

4. 1<sup>5</sup> 8<sup>to31</sup> 4 

5. 2 12<sup>1to11</sup> 4 

6. 14.4 to 5.4 

7. 1.69 to 2.6 

8. 3 hours to 40 minutes 

9. 8 inches to 5 2<sup>1feet</sup> 

10. In the late afternoon, a 35 foot tree casts an 84 foot shadow. What is the ratio of the tree’s height to the shadow’s length? 

### 4.2 Proportions 

A proportion is a statement that two ratios are equal. Thus 

<!-- Start of picture text -->
2040 = 10 5<!-- End of picture text -->

is a proportion, because both ratios are equivalent to the ratio 2 : 1 (= the fraction<sup>2</sup> 1<sup>).</sup> 

Page 117 

<!-- Start of picture text -->
A proportion is a statement of the formba = d cwhere b, d̸ = 0.<!-- End of picture text -->

#### 4.2.1 The cross-product property 

There is a very useful fact about proportions: If the proportion b<sup>a=</sup> d<sup>cis true, then the “cross-products,”</sup> ad and bc, are equal, and, conversely, if the cross-products are equal, then the proportion must be true. Example 133. Verify that the cross-products are equal in the (true) proportion 

<!-- Start of picture text -->
2040 = 10 5 .<!-- End of picture text -->

Solution. 40 × 5 = 10 × 20 = 200. 

The general cross-product property is stated below for reference: 

<!-- Start of picture text -->
aif and only if ad = bc.b = d c<!-- End of picture text -->

To prove the cross-product property, we need to say a little bit about equations. An equation is a mathematical statement of the form X = Y . If the equation X = Y is true, and N is any nonzero number, then the following equations are also true, and have exactly the same solution(s): 

<!-- Start of picture text -->
XN × X = N × Y andN = Y N .<!-- End of picture text -->

Now go back to the proportion b<sup>a=</sup> d<sup>c,andmultiplybothsidesbythenonzeronumberbd.Weget</sup> 

<!-- Start of picture text -->
bd b a = bd c d .<!-- End of picture text -->

Cancelling b on the left and d on the right yields the cross-product property, ad = bc. Conversely, if we have four numbers a, b, c, d, (b, d̸ = 0), and we know that ad = bc, then, dividing both sides by the nonzero number bd gives us the proportion b<sup>a=</sup> d<sup>c.</sup> 

Example 134. Decide if the given proportions are true or false, using the cross-product property. (a) 113<sup>=2</sup> 7<sup>;</sup> (b) 10<sup>4=</sup> 15<sup>6.</sup> 

Solution. (a) The cross-products are 3 · 7 = 21 and 2 · 11 = 22. They are not equal, so the proportion is false. (b) The cross-products are 4 · 15 and 10 · 6, both equal to 60. So the proportion is true. 

Page 118 

#### 4.2.2 Solving a proportion 

If one of the four terms of a proportion is missing or unknown, it can be found using the cross-product property. This procedure is called solving the proportion. In the proportion below, x represents an unknown term (any other letter would do). 

<!-- Start of picture text -->
x3 = 34 51 .<!-- End of picture text -->

There is a unique x which makes the proportion true, namely, the one which makes the cross-products, 51x and 34(3), equal. The equation 

<!-- Start of picture text -->
51x = 34(3) = 102<!-- End of picture text -->

can be divided by 51 (the number which multiplies x) on both sides, giving 

<!-- Start of picture text -->
5151x = 102 51 .<!-- End of picture text -->

Cancellation yields 

<!-- Start of picture text -->
51>x 1 = �� 102*�= 2. 2> 1 > 151 51<!-- End of picture text -->

It follows that 

<!-- Start of picture text -->
x = 2<!-- End of picture text -->

which is the solution of the proportion. 

It doesn’t matter which of the four terms is missing; the proportion can always be solved by a similar procedure. 

Example 135. Solve the proportion 

<!-- Start of picture text -->
1009 = 36 y<!-- End of picture text -->

for the unknown term y . 

Solution. The cross-products must be equal, so 

<!-- Start of picture text -->
9y = 3600.<!-- End of picture text -->

Dividing both sides of the equation by 9 (the number which multiplies y ), and cancelling, yields 

<!-- Start of picture text -->
> 1 : 4009 y = 3600> 1 > 19 9y = 400.<!-- End of picture text -->

The unknown term is 400. We check our solution by verifying that the cross-products 

<!-- Start of picture text -->
9(400) = 36(100) = 3600<!-- End of picture text -->

are equal. 

Neither the terms nor the solution of a proportion are necessarily whole numbers. 

Page 119 

Example 136. Solve the proportion 

<!-- Start of picture text -->
10B = 15 4<!-- End of picture text -->

for B and check the solution. 

Solution. Setting the cross products equal, 

<!-- Start of picture text -->
40 = 15B.<!-- End of picture text -->

Dividing both sides of the equation by 15 (the number multiplying B), and simplifying, yields 

<!-- Start of picture text -->
> 840 = 15B> 3 151583 = B.<!-- End of picture text -->

The unknown term is<sup>8</sup> 3<sup>or22</sup> 3<sup>.</sup> Substituting 2<sup>2</sup> 3<sup>forBintheoriginalproportion,wecheckthatthecross-productsareequal.</sup> 

<!-- Start of picture text -->
10(4) = ? 2 2 (15)� 3 �> 540 = ? 8 15> 1 1340 = 40.<!-- End of picture text -->

Example 137. Solve the proportion 

<!-- Start of picture text -->
� 32 � = x5 15 .<!-- End of picture text -->

Solution. Set the cross-products equal, and solve for x: 

<!-- Start of picture text -->
23 · 15 = 5x2 > 5· 15 = 5x> 1310 = 5x2 = x.<!-- End of picture text -->

Example 138. Solve the proportion 

<!-- Start of picture text -->
7042 = 1.5 x .<!-- End of picture text -->

Page 120 

Solution. We could immediately set the cross-products equal, but it is simpler to first reduce the fraction 4270<sup>toitslowestterms,using–bytheway–aproportion:42</sup> 70<sup>=3</sup> 5<sup>.Stringingtwoproportionstogether</sup> 

<!-- Start of picture text -->
53 = 42 70 = 1.5 x<!-- End of picture text -->

lets us skip over the middle fraction. It is evident that the solution to our original proportion is the solution to the simpler proportion 

<!-- Start of picture text -->
35 = 1.5 x .<!-- End of picture text -->

Setting the cross-products equal 

<!-- Start of picture text -->
4.5 = 5x,we obtain the solution x = 4.55 = 0.9.<!-- End of picture text -->

We summarize the procedure for solving a proportion. 

To solve a proportion, 

   1. Reduce the numerical ratio (not containing the unknown) to lowest terms, if necessary; 

   2. Set the cross-products equal; 

   3. Divide both sides of the resulting equation by the number multiplying the unknown term. 

- To check the solution, 

   1. In the original proportion, replace the unknown term with the solution you obtained; 

   2. Verify that the cross-products are equal. 

Equivalence of fractions, and hence, most of fraction arithmetic, is based on proportion. To add 

<!-- Start of picture text -->
12 + 1 3proportions1 1and2 = x 6 3 = y 6<!-- End of picture text -->

for example, we first solve the two proportions 

(a task we have performed up to now without much comment) so that the fractions can be written with the LCD (6). Then 

<!-- Start of picture text -->
1.2 + 1 3 = x + 6  y<!-- End of picture text -->

Practice: solve the two proportions for x and y . 

Page 121 

#### 4.2.3 Exercises 

Solve the following proportions. 

1.<sup>1</sup> 5<sup>=</sup> x<sup>3</sup> 2.<sup>15</sup> y<sup>=</sup> 3<sup>2</sup> 3.<sup>100</sup> =<sup>20</sup> 5 y 4.<sup>A</sup> 9<sup>=</sup> 3<sup>5</sup> 5.<sup>11</sup> B<sup>=</sup> 2<sup>1</sup> 6.<sup>5</sup> 3<sup>=c</sup> 6 7. 3<sup>s=</sup> 13<sup>4</sup> 8.<sup>1.2</sup> A 7<sup>=</sup> 0.84 P 9. 100<sup>=</sup> 125<sup>75</sup> 5 10.<sup>31</sup> x<sup>=</sup> 2<sup>41</sup> 2 

### 4.3 Percent problems 

Any problem involving percent can be stated (or restated) in the form 

<!-- Start of picture text -->
“A is P percent of B”<!-- End of picture text -->

where one of the numbers A, B or P is unknown. We can make this into a mathematical equation by making the following “translations:” 

<!-- Start of picture text -->
“is” ←→ =P“P percent” ←→100“of” ←→ ×<!-- End of picture text -->

This gives us the equation 

<!-- Start of picture text -->
A = P100 × B.<!-- End of picture text -->

If we divide both sides of the equation by B, we obtain the proportion in the box below. 

Page 122 

<!-- Start of picture text -->
The statement “A is P percent of B” is equivalent to the proportionBA = 100 P .<!-- End of picture text -->

The letter B is used to suggest “base amount” – that is, B is the amount from which (or of which) a percentage is taken. Notice that B follows “of” in the verbal statement. It could be that A (the percentage taken) is greater than B, but only if the percentage P is greater than 100. 

In the following examples, the phrase involving “what,” as in “what number?” or “what percent?” helps determine which of A, B of P is the unknown. 

Example 139. 6 is what percent of 300? 

Solution. The percent is unknown, and the base amount B is 300 (since it follows the word “of”). We can restate the question as: “6 is P percent of 300.” The corresponding proportion is 

<!-- Start of picture text -->
3006 = 100 P<!-- End of picture text -->

and the solution (verify it!) is P = 2. Therefore, 6 is 2% of 300. 

Example 140. What number is 8% of 150? 

Solution. The base amount B is 150, since it follows the word “of,” the percentage is P = 8, and therefore A is the unknown amount. The question can be restated as: “A is 8% of 150.” The corresponding proportion is 

<!-- Start of picture text -->
A 8150 = 100<!-- End of picture text -->

and the solution is A = 12 (verify!). It follows that 12 is 8% of 150. 

(Note that this result could have been obtained without using a proportion, since 8% of 150 simply means .08 × 150 = 12.) 

Example 141. 58% of what number is 290? 

Solution. The base amount B is unknown, and A is 290. The question can be restated as “58% of B is 290.” The corresponding proportion is 

<!-- Start of picture text -->
290 = 58B 100<!-- End of picture text -->

<!-- Start of picture text -->
and the solution is 29000 = 500. So 58% of 500 is 290.58<!-- End of picture text -->

Everyday questions involving percent are not always as straightforward as in the previous examples. But with a little thought, they can be converted into such statements. 

Example 142. Approximately 55% of the students enrolled at BCC are female. If there are 2970 female students, what is the total enrollment at BCC? 

Page 123 

Solution. According to the given information, 2970 is 55% of the total enrollment, which is the base amount, B. The question can be restated as “2970 is 55% of B” and the corresponding proportion is therefore 

<!-- Start of picture text -->
2970 = 55B 100 .<!-- End of picture text -->

Using lowest terms of the fraction 10055<sup>=11</sup> 20<sup>,wesolve</sup> 

<!-- Start of picture text -->
2970 = 11B 2059400 = 11BB = 59400 = 5400.11<!-- End of picture text -->

The total enrollment is 5400 students. To check, verify that 55% of 5400 is 2970. 

Example 143. Full-time tuition at a university increased from $2, 850 to $3, 000. What was the percent increase in the tuition? (Round to the nearest tenth of a percent.) 

Solution. The tuition increased by $3000 − 2850 = $150. The percent increase is the ratio 

<!-- Start of picture text -->
amount of increase = 150original tuition 2850 ,<!-- End of picture text -->

expressed as a percent. Equivalently, we want to answer the question “$150 is what percent of $2850?” We solve the proportion 

<!-- Start of picture text -->
150(4.1)2850 = 100 P573 = 100 P57P = 300P ≈ 5.26<!-- End of picture text -->

Rounded to the nearest tenth of a percent, the tuition increase was approximately 5.3%. 

#### 4.3.1 Exercises 

1. 12 is 20% of what number? 

2. 12 is 30% of what number? 

3. 12 is 40% of what number? 

4. 90 is what percent of 225? 

5. 90 is what percent of 300? 

6. 90 is what percent of 375? 

7. What is 125% of 600? 

8. What is 175% of 600? 

Page 124 

9. 250 is what percent of 325? (Round to the nearest tenth of a percent.) 

10. 108 is 80% of what number? 

11. A baseball team won 93 games, or 62% of the games it played. How many games did the team play? 

12. New York State sales tax is 8.25%. If the sales tax on a DVD player is $16.50, what is the (before-tax) price of the player? 

13. Marina’s annual salary last year was $56, 000. This year she received a raise of $4, 480. By what percent did her salary increase? 

14. A town’s population decreased from 13, 000 to 12, 220. By what percent did the population decrease? 

### 4.4 Rates 

There are lots of real-world quantities which compare in a fixed ratio. For example, for any given car, the ratio of miles driven to gallons of gas used, 

<!-- Start of picture text -->
milesor “miles per gallon”gallon<!-- End of picture text -->

is essentially unchanging, or fixed. If we know, say, that 5 gallons of gas was needed to drive 150 miles, we can predict the amount that will be needed to drive any other distance, by solving a simple proportion. 

Example 144. Maya used 5 gallons of gas to drive 150 miles. How many gallons will she need to drive 225 miles? 

Solution. We solve the proportion 

<!-- Start of picture text -->
1505 gallonmiles = 225 x gallons  miles ,<!-- End of picture text -->

where x represents the number of gallons she will need. Before setting the cross-products equal, reduce the fraction on the left side to<sup>30</sup> 1<sup>.Then</sup> 

<!-- Start of picture text -->
30x = 225 (4.2)x = 22530 = 71 2 .<!-- End of picture text -->

She will need 7 2<sup>1gallonsofgastodrive225miles.</sup> 

Miles per gallon is an example of a rate, or comparison of unlike quantities by means of a ratio. In the example above, the miles per gallon rate for Maya’s car was 

<!-- Start of picture text -->
150 miles = 30 or 30 miles per gallon.5 gallons = 150 5 1<!-- End of picture text -->

Other examples of rates are: dollars per hour (pay rate for an hourly worker), dollars per item (price of an item for sale), calories per minute (energy use by an athlete). You can undoubtedly think of many others. 

Page 125 

Example 145. A runner burns 375 calories running 3.5 miles. (a) How many calories will she burn in running a marathon (approximately 26 miles)? (b) What is her rate of energy use (calories per mile)? Round off to the nearest whole unit. 

Solution. (a) The ratio 

<!-- Start of picture text -->
caloriesmiles<!-- End of picture text -->

is assumed fixed and, from the given information, is equal to 

<!-- Start of picture text -->
3753.5  .<!-- End of picture text -->

Let x denote the number of calories the runner burns in running a marathon. Then 

<!-- Start of picture text -->
375(setting cross-products equal)3.5 = x 26 calories miles<!-- End of picture text -->

<!-- Start of picture text -->
(375)(26) = 3.5xx = (375)(26) ≈ 2786.3.5<!-- End of picture text -->

She will burn approximately 2786 calories running the marathon. (b) Her rate of energy use is 

<!-- Start of picture text -->
375 calories≈ 107 calories per mile.3.5 miles<!-- End of picture text -->

Example 146. A painting crew can paint three apartments in a week. If a building contains 40 equal size apartments, how long will it take the crew to paint all the apartments? 

Solution. The ratio 

<!-- Start of picture text -->
apartments paintedtime in weeks<!-- End of picture text -->

is given as<sup>3</sup> 1<sup>.Ifyisthenumberofweeksneededtopaint40apartments,then</sup> 

<!-- Start of picture text -->
13 = 40 y ,<!-- End of picture text -->

and y =<sup>40</sup> 3<sup>= 13</sup> 3<sup>1weeks.</sup> 

#### 4.4.1 Exercises 

Use proportions to solve the following problems. 

1. On a map, 4<sup>3inchrepresents14miles.Iftwocitiesare42milesapart,howfarapartaretheyon</sup> the map? 

2. A truck burns 2<sup>1</sup> 2<sup>quartsofoilonan1800miletrip.Howmanyquartswillbeburnedonacross-</sup> country trip of 3240 miles? 

3. An investment of $2, 000 earns $48 in interest over a year. How much would need to be invested to earn $200 in interest? (Round to the nearest dollar.) 

Page 126 

4. In a sample of 600 bottles, 11 were found to be leaking. Approximately how many bottles would you expect to be leaking in a sample of 20, 000 bottles? 

5. The ratio of the weight of lead to the weight of an equal volume of aluminum is 21 : 5. If a bar of aluminum weighs 15 pounds, how much would a bar of lead of the same size weigh? 

### 4.5 Similar triangles 

Two triangles which have the same shape but possibly different sizes are called similar. Having the same shape means that the three angles of one triangle are equal to the three corresponding angles in the other. 

The triangles below are similar, because the angle at A in the small triangle is equal to the angle at D in the big triangle (50<sup>◦</sup> ); the angle at B in the small triangle is equal to the angle at E in the big triangle (95<sup>◦</sup> ); and similarly the angle at C in the small triangle is equal to the angle at F in the large triangle (35<sup>◦</sup> ). 

<!-- Start of picture text -->
E95 ◦B95 ◦50 ◦ 35 ◦ 50 ◦ 35 ◦A C D F<!-- End of picture text -->

Given any triangle, we can obtain a similar one by enlarging (or reducing) all the side lengths in a fixed ratio. In the example above, the bigger triangle was obtained from the smaller using the enlargement ratio 2 : 1. If AB stands for the length of the side AB, etc., then 

<!-- Start of picture text -->
DE = 2 × AB, EF = 2 × BC , and DF = 2 × AC .<!-- End of picture text -->

Equivalently, 

<!-- Start of picture text -->
DE EF DF= = = 2AB BC AC 1 .<!-- End of picture text -->

In words: sides which are opposite equal angles (called corresponding sides) have length ratio equal to the ratio 2 : 1. We must be careful to compare side lengths in the proper order. In this case, we used the order larger : smaller, since that is the order in the ratio 2 : 1. We could have used the reverse order, smaller : larger, but only if we also used the reversed ratio 1 : 2. 

If we know, say, that BC is 12 feet, we can solve the proportion 

<!-- Start of picture text -->
2 EF1 = 12<!-- End of picture text -->

and determine that EF is 24 feet. 

This is the key fact about similar triangles. 

Page 127 

<!-- Start of picture text -->
Corresponding sides of similar triangles are proportional:If: ∠A = ∠D, ∠B = ∠E , and ∠C = ∠F ,EBA CD FBC AC ABThen: = =EF DF DE .<!-- End of picture text -->

Example 147. The triangles below are similar, with ∠D = ∠A, ∠E = ∠B and ∠F = ∠C . AB = 15 feet, BC = 12 feet, and DE = 22.5 feet. Find EF . 

<!-- Start of picture text -->
DA15 ft. C22.5 ft.F12 ft.Bx ft.ESolution. The ratios of the corresponding sides opposite ∠F = ∠C ( DEAB ) and the corresponding sidesopposite ∠D = ∠A ( BCEF ) are equal:<!-- End of picture text -->

<!-- Start of picture text -->
DE EF=AB BC .<!-- End of picture text -->

<!-- Start of picture text -->
Filling in the given information, and using x to represent the unknown side length EF , we have22.515 = 12 x(22.5)(12) = 15x270 = 15xx = 27015 = 18.<!-- End of picture text -->

EF = 18 feet. 

We now describe two ways of obtaining a pair of similar triangles. Both involve the notion of parallel line segments. Two line segments are parallel if they do not cross, even if extended infinitely in either direction (think of straight train tracks). 

Page 128 

1. If two sides of a triangle are joined by a line segment parallel to the third side, the resulting (smaller) triangle is similar to the original triangle. 

<!-- Start of picture text -->
B BEA C A CD<!-- End of picture text -->

Starting with triangle ABC on the left, we drew the segment DE , parallel to AB, creating (smaller) triangle DEC , similar to ABC . Both triangles are visible on the right (the smaller overlapping the larger), so there was really no need to draw the first picture. By similarity, the corresponding sides are proportional: smaller triangle DE CD CE = larger triangle AB CA<sup>=</sup> CB<sup>.</sup> 

2. If a pair of parallel line segments is “cross-connected” as shown, the two triangles formed are similar. 

<!-- Start of picture text -->
C D C DEA B A B<!-- End of picture text -->

Starting with the parallel segments AB and CD, we connected D to A and C to B by means of straight lines (called transversals) which cross at point E . The upper and lower angles at E are equal. In addition, ∠D = ∠A and ∠C = ∠B. (These facts are visually plausible; they would be proved in a geometry class.) It follows that triangles ABE and CDE are similar and hence 

upper triangle CD EC ED = = lower triangle AB EB EA<sup>.</sup> 

Page 129 

In the examples and exercises, it will be convenient to use the following symbolism: 

<!-- Start of picture text -->
∥ ←→ “is parallel to”∼ ←→ “is similar to”△ ←→ “triangle”<!-- End of picture text -->

Example 148. In the picture below, AB ∥ CD. Some of the side lengths are given in inches. Find the length of the side AE . 

<!-- Start of picture text -->
AC1E.751.5B D<!-- End of picture text -->

Solution. Because AB ∥ CD, △ABE ∼△CDE . Corresponding sides are proportional, hence 

<!-- Start of picture text -->
smaller triangle CD EC ED= =bigger triangle AB EB EA .<!-- End of picture text -->

In particular, using EC = 1, EB = 1.5, and ED = .75, and x for the length of AE , 

<!-- Start of picture text -->
11.5 = .75 x<!-- End of picture text -->

or x = (1.5)(.75) = 1.125. The length of AE is 1.125 inches. 

Example 149. In the following figure, DE ∥ BC . Find the length of BC . 

<!-- Start of picture text -->
A2 ft.D E2 ft. 6 in.2 ft. 4 in.B C<!-- End of picture text -->

Page 130 

Solution. △ABC ∼△ADE because DE ∥ BC . Corresponding sides are proportional, hence 

<!-- Start of picture text -->
AC BC BC= 2 ft. + 2 ft. 4 in. = =AE 2 ft. DE 2 ft. 6 in. .<!-- End of picture text -->

Converting all measurements to inches, and letting x represent the length of BC in inches, 

<!-- Start of picture text -->
5224 = 30 x<!-- End of picture text -->

which gives x = 65 inches, or 5 ft. 5 in. 

#### 4.5.1 Exercises 

In the first two exercises, the triangles are similar, and similarly marked angles are equal. Find the length x in each case. 

<!-- Start of picture text -->
4.51.1.6 1 3x1.5<!-- End of picture text -->

<!-- Start of picture text -->
A 3E D2.1.5 1xB C1.4F<!-- End of picture text -->

Page 131 

3. In the figure below, AC ∥ DE . Find the side length x. 

<!-- Start of picture text -->
B1 1.5D E1.43 4.5A x C<!-- End of picture text -->

4. In the figure below, AB ∥ DE . Find the side length x. 

<!-- Start of picture text -->
B2 ft. 4 in.6 ft.D1 ft. 2 in.xA 2 ft. 8 in. E 1 ft. 4 in. C<!-- End of picture text -->

5. In the figure below, AB ∥ CD. Find the side length x. 

<!-- Start of picture text -->
DC1 1 44Ex8BA<!-- End of picture text -->

Page 132 

6. In the figure, DE ∥ BC . D cuts AB exactly in half. If BC is 12 centimeters long, how long is DE ? 

<!-- Start of picture text -->
AD EB C<!-- End of picture text -->

7. In the figure below, AB ∥ DE , and length measures are given in meters. How long is AB if DE has a length of 2 5<sup>2meters?</sup> 

<!-- Start of picture text -->
A5 metersD3 metersB CE<!-- End of picture text -->

Page 133 

8. In the figure below, AB ∥ CD. Find the side length x. 

<!-- Start of picture text -->
D.64 in.B 1.75 in. E.50 in.Cx in.A<!-- End of picture text -->

9. A 6 foot man casts an 8 foot shadow on the ground. How long is the shadow of a nearby 32 foot tree? Draw a figure involving similar triangles which illustrates the situation. 

Page 134 

## Chapter 5 - Signed Numbers 

In this chapter we expand the set of numbers available for doing arithmetic. We now include negative numbers, which lie to the left of 0 on the number line, forming a kind of “mirror image” of the positive numbers. On the expanded number line, each number (except 0) has a sign. The negative numbers have sign −, and the positive numbers have sign +. The + sign for positive numbers is understood and usually omitted. 0 has no sign. 

<!-- Start of picture text -->
| | | | | | | | | | |−5 −4 −3 −2 −1 0 1 2 3 4 5The rule of thumb “left is less” continues to hold on the expanded number line. Thus, for example,−3 < −1, since −3 lies to the left of −1 on the number line.<!-- End of picture text -->

The set of negative numbers (like the set of positive numbers), includes not just negative integers, but also negative fractions such as −<sup>13</sup> 3<sup>= −41</sup> 3<sup>, and negative irrational numbers, such as −</sup> √2 ≈−1.41 and −π ≈−3.14. 

<!-- Start of picture text -->
- 13 3 -π -√2 √2 π 133| | | | | | | | | | |−5 −4 −3 −2 −1 0 1 2 3 4 5<!-- End of picture text -->

The absolute value of a number is its distance from 0 on the number line. The symbol for absolute value is a pair of vertical lines, | |. Thus | 0 |= 0 and 

<!-- Start of picture text -->
| −1 |=| 1 |= 1, | −√2 |=| √2 |= √2, | −π |=| π |= π, etc.<!-- End of picture text -->

The absolute value of a number cannot be negative, even if the number itself is negative. This is because, intuitively, distance is a nonnegative quantity. 

### 5.1 Adding signed numbers 

To do arithmetic with signed numbers, we extend the ordinary operations of addition, subtraction, multiplication and division so that they remain consistent with the familiar operations with nonnegative numbers. We define the extended addition operation in terms of motion along the number line, as follows: 

<!-- Start of picture text -->
To add a positive number, move to the right;To add a negative number, move to the left.<!-- End of picture text -->

135 

Thus, to add 3 to 2, we imagine starting at 2 on the number line and moving 3 “steps” to the right, arriving at 5. 

<!-- Start of picture text -->
+3| | | | | | | | |−5 −4 −3 −2 −1 0 1 2 3 4 52 + 3 = 5<!-- End of picture text -->

Example 150. Perform the signed number addition 2 + (−3). 

Solution. We start at 2 as before, but now we move 3 steps left, taking the sign of −3 into account. 

<!-- Start of picture text -->
+(−3)| | | | | | | | |−5 −4 −3 −2 −1 0 1 2 3 4 52 + (−3) = −1<!-- End of picture text -->

As the picture shows, we end up at −1. We conclude that 2 + (−3) = −1. 

When two signed numbers are added, the order of addition does not affect the sum. 

Example 151. Perform the signed number addition (−3) + 2. 

Solution. This is just the previous example, with the addition in the reverse order. Now we start at −3, and move 2 steps right, taking into account the (positive) sign of 2. We arrive at the same result, −1: 

<!-- Start of picture text -->
+2| | | | | | | | |−5 −4 −3 −2 −1 0 1 2 3 4 5(−3) + 2 = −1<!-- End of picture text -->

More generally, for any two signed numbers, 

a + b = b + a. 

Addition, extended to signed numbers, remains commutative. 

Example 152. Perform the signed number addition −1<sup>1</sup> 2<sup>+ (−3)inbothpossibleorders.</sup> 

Page 136 

Solution. Both numbers are negative, so we move consistently left on the number line. We either start at −1<sup>1</sup> 2<sup>andmove3stepsleft,arrivingat</sup> 

<!-- Start of picture text -->
−1 1 + (−3) = − 1 1 = − = − 9� 2 � � 2 + 3 � � 23 + 6 2 � 2 = −41 2<!-- End of picture text -->

(upper arrow in the picture below); or we start at −3 and move 1<sup>1</sup> 2<sup>steps left (lowerarrow).Eitherway,</sup> we arrive at −4<sup>1</sup> 2<sup>.</sup> 

<!-- Start of picture text -->
+(−3)+(−1 1 2 )| | | | | | | | | | |−5 −4 −3 −2 −1 0 1 2 3 4 5−4 1 −1 12 2<!-- End of picture text -->

Example 153. Perform the signed number addition −2.50 + 3.75. 

Solution. Starting at −2.50, we move a distance of 3.75 to the right, ending at 1.25, as shown. 

+3.75 

<!-- Start of picture text -->
| | | | | | | | | | |−5 −4 −3 −2 −1 0 1 2 3 4 5−2.50 1.25<!-- End of picture text -->

In the last example, the absolute value of the sum was the difference obtained by subtracting the smaller absolute value from the larger (3.75 − 2.50 = 1.25), while the sign of the sum (+) was the same as the sign of the number with the larger absolute value. This is no accident, but illustrates a general rule about adding numbers with opposite signs. 

Page 137 

When two signed numbers are added 

- if the numbers have opposite signs, 

   1. the sign of the sum is the sign of the number with the larger absolute value; 

   2. the absolute value of the sum is the difference bewteen the two individual absolute values (larger − smaller). 

- if the two numbers have the same sign, 

   1. the sign of the sum is the common sign of the summands; 

   2. the absolute value of the sum is the sum of the individual absolute values. 

Example 154. Add 15 + (−18). 

Solution. The numbers have opposite signs, so the sign of the sum is the same as the sign of the number with the larger absolute value (−18), i.e., −. The absolute value of the sum is the difference | −18 | −| 15 |= 18 − 15 = 3. Thus the sum is −3. This reasoning is summarized as 

<!-- Start of picture text -->
15 + (−18) = −(18 − 15) = −3.<!-- End of picture text -->

Example 155. Add −7 + (−9). 

Solution. The numbers have the same sign, −, so that is also the sign of the sum. The absolute value of the sum is the sum of the individual absolute values, | −7 | + | −9 |= 7 + 9 = 16. Thus the sum is −16. The reasoning is summarized as 

<!-- Start of picture text -->
−7 + (−9) = −(7 + 9) = −16.<!-- End of picture text -->

Example 156. Add −3.6 + 4.9. 

Solution. The numbers have opposite signs, and the number with the larger absolute value (4.9) determines the sign of the sum (+). The absolute value of the sum is the difference | 4.9 | −| −3.6 |= 4.9 − 3.6. Thus 

<!-- Start of picture text -->
−3.6 + 4.9 = +(4.9 − 3.6) = +1.3 = 1.3.<!-- End of picture text -->

<!-- Start of picture text -->
Example 157. Add 4 3 −7 1 .5 + � 3 �<!-- End of picture text -->

Page 138 

Solution. The numbers have opposite signs, and the number with the larger absolute value is negative, so the sum will be negative. The absolute value of the sum is the difference in the individual absolute values, 

<!-- Start of picture text -->
= 7 1 3 − 43 5= 7 5 (using the LCD = 15)15 − 4 15 9= 6 20 15 − 4 15 9 (borrowing 1 = 15 15 from 7)= 2 1115 .<!-- End of picture text -->

Finally, recalling that the sign of the sum is negative, we have 

<!-- Start of picture text -->
4 3 −7 1 = −2 115 + � 3 � 15 .<!-- End of picture text -->

#### 5.1.1 Exercises 

Add. 

<!-- Start of picture text -->
1. −6 + 192. 12 + (−4)3. −34 + (−28)4. 266 + (−265)5. 5 3 −4 15 + � 2 �6. −13.38 + (−9.03)<!-- End of picture text -->

<!-- Start of picture text -->
7. −1001.36 + 909<!-- End of picture text -->

<!-- Start of picture text -->
8. − 3 + 2� 4 �9. − 5 + (−5)� 6 �10. 3 1 + 2 5� 5 � � 8 �<!-- End of picture text -->

Use an appropriate signed number addition for the following. 

11. Find the temperature at noon in Anchorage if the temperature at dawn was −11<sup>◦</sup> F and the temperature subsequently rose by 36<sup>◦</sup> F. 

12. Find the height (in feet above ground level) of an elevator which started 30 feet below ground level and subsequently rose 70 feet. 

Page 139 

#### 5.1.2 Opposites, Identity 

There are exactly two numbers at any given non-zero distance from 0, one negative and the other positive. Pairs of numbers such as {−<sup>13</sup> √2, √2}, {−π, π}, which are unequal but equidistant 3<sup>, 13</sup> 3<sup>}, {−</sup> from 0, and hence have the same absolute value, are called opposites. (0 is the only number which is its own opposite, having absolute value 0.) To find the opposite of a nonzero number, we simply change its sign. 

Example 158. (a) The opposite of 11 is −11. (b) The opposite of −1.7 is 1.7. 

Since there are only two possible signs, the opposite of the opposite of a number is the number we started with. 

The opposite of the opposite of N is N: −(−N) = N. 

Example 159. (a) The opposite of the opposite of<sup>5</sup> −<sup>5</sup> =<sup>5</sup> 8<sup>is −</sup> � 8 � 8<sup>.(b) the opposite of the opposite</sup> of −5 is −(−(−5)) = −5. 

Suppose a nonzero number is added to its opposite, for example, 3 + (−3). The rule for adding signed numbers with opposite signs doesn’t seem to work here: it is not clear what the sign of the sum should be. But in fact it doesn’t matter since the absolute value of the sum is 0, which has no sign. Accordingly, −3 + 3 = 0. (Intuitively: if we start at 3 and move 3 steps left, we arrive at 0.) In general, 

<!-- Start of picture text -->
The sum of a number and its opposite is 0:N + (−N) = 0.<!-- End of picture text -->

<!-- Start of picture text -->
− 1Example 160. (a) 1 = 0. (b) −23.04 + 23.04 = 0.7 + � 7 �<!-- End of picture text -->

Recall that 0 is the additive identity for ordinary addition because, when 0 is added to a number, the result is the identical number, i.e, the number does not change. This remains true for signed numbers. 

Example 161. −4 + 0 = −4. 

#### 5.1.3 Exercises 

Find the following: 

1. The opposite of 0.062 

<!-- Start of picture text -->
2. The opposite of −2 57<!-- End of picture text -->

Page 140 

<!-- Start of picture text -->
3. − − − 2� � 7 ��<!-- End of picture text -->

4. The sum of 99 and its opposite. 

5. The sum of −π and its opposite. 

6. The opposite of the opposite of −0.25. 

7. The sum of −5 and the opposite of 5. 

8. −258 + (−(−258)) 

9. −9.1 + (−9.1) 

<!-- Start of picture text -->
10. − 38 + 011. 0 + 5.512. 4 + �2 2 3 + �−2 2 3 ��<!-- End of picture text -->

#### 5.1.4 Associativity 

Another important property of addition, associativity, extends to signed number addition. Associativity of addition means that when three or more numbers are added, it doesn’t matter how you associate them into groups for addition: x + y + z = (x + y ) + z = x + (y + z). Recall that this property allowed us to add long columns of nonnegative numbers. 

We can make use of column addition with signed numbers, too, by associating and adding all the positive numbers, and, separately, associating and adding the absolute values of all the negative numbers. Then we add the two subtotals, treating the subtotal associated with the negative numbers as negative. This way, we apply the signed number rule just once, at the end. 

Example 162. Add: 43.6 + (−5.8) + (−135) + 69.5 + (−134) + 158.7 + (−162.3) 

Solution. We add all the positive numbers, 

<!-- Start of picture text -->
4 3 . 66 9 . 5+ 1 5 8 . 72 7 1 . 8<!-- End of picture text -->

and the absolute values of all the negative numbers, 

<!-- Start of picture text -->
5 . 81 3 5 .1 3 4 .+ 1 6 2 . 34 3 7 . 1<!-- End of picture text -->

Page 141 

Treating the subtotal associated with the negative numbers as negative, we add 271.8 + (−437.1). By the rule for adding signed numbers with opposite signs, 

<!-- Start of picture text -->
271.8 + (−437.1) = −(437.1 − 271.8) = −165.3.<!-- End of picture text -->

If we think of positive numbers as “profits,” and negative numbers as “losses,” then signed number addition is like “balancing the books.” There is a net gain if the total profits are larger than the total losses (in absolute value); otherwise there is a net loss. 

Example 163. Last week, a business received checks from clients in the amounts of $350.65, $461.00 and $900.78, and paid bills in the amounts of $261.50, $551.00 and $78.70. What was the net profit or loss for the week? 

Solution. Bills paid are losses, so we treat them as negative numbers; checks received are profits, counted as positive numbers. The total profits are 

and the total losses are 

<!-- Start of picture text -->
3 5 0 . 6 54 6 1 . 0 0+ 9 0 0 . 7 81, 7 1 2 . 4 32 6 1 . 5 05 5 1 . 0 0+ 7 8 . 7 08 9 1 . 2 0<!-- End of picture text -->

Affixing a negative sign to the total losses, we calculate the net profit (or loss) as the sum 1712.43 + (−891.20) = +(1712.43 − 891.20) = 821.23. 

There was a net profit of $821.23 for the week. 

#### 5.1.5 Exercises 

Perform the additions. 

<!-- Start of picture text -->
1. 1 + (−1) + 1 + (−1) + 1 + (−1)2. −8.2 + (−198.5) + 8.23. 44 + (−5.5) + 28.8 + 36 + (−19.1) + (−8)4. 1 − 1 + 62 + � 3 � 75. −6 3 + 4 3 − 2 1 + 7� 8 � 4 + � 2 � 8<!-- End of picture text -->

Page 142 

<!-- Start of picture text -->
6. −1 2 + −2 5 + −8 1� 3 � � 6 � � 3 �7. 18.50 + (−21.25) + (−69.95) + 13.50 + 79.99 + (−86.50)8. 5 + −3 1 + 4 1 − 2 1 + (−4) + − 1 + 7� 2 � 2 + � 2 � � 2 �<!-- End of picture text -->

9. Find the average noon temperature for the first week of January in Barrow, Alaska if the noon temperatures were: Monday: −8<sup>◦</sup> F, Tuesday: 2<sup>◦</sup> F, Wednesday: −3<sup>◦</sup> F, Thursday: −5<sup>◦</sup> F, Friday: 1<sup>◦</sup> F, Saturday: 4<sup>◦</sup> F, Sunday: 9<sup>◦</sup> F. 

10. Find the net profit (or loss) of a business that received checks in the amounts of $453.05, $865.50 and $300.25, and paid bills in the amounts of $561.50, $449.25, $798.75 and $75.25. 

### 5.2 Subtracting signed numbers 

The phrase “subtract A from B” indicates the operation B − A. We extend subtraction to signed numbers by defining it in terms of addition. 

To subtract a signed number A from a signed number B, add B to the opposite of A: 

<!-- Start of picture text -->
B − A = B + (−A).<!-- End of picture text -->

With this definition, there is no longer any real need for a separate operation called subtraction. For example, instead of subtracting 17 − 9, we could simply add 17 + (−9) (verify that the results are the same). Despite this, it is convenient to retain the operation of subtraction. 

Example 164. (a) Subtract 15 from 9. (b) Subtract 8 from −2. 

Solution. (a) 9 − 15 = 9 + (−15). Applying the rule for adding signed numbers with opposite signs, 

<!-- Start of picture text -->
9 + (−15) = −(15 − 9) = −6.<!-- End of picture text -->

(b) −2 − 8 = −2 + (−8). Applying the rule for adding signed numbers with the same sign, 

<!-- Start of picture text -->
−2 + (−8) = −(2 + 8) = −10.<!-- End of picture text -->

Example 165. Subtract −17 from 12. 

Solution. 12 − (−17) = 12 + (−(−17)). Remembering that −(−17) = 17 (opposite of the opposite), we have 

<!-- Start of picture text -->
12 − (−17) = 12 + 17 = 29.<!-- End of picture text -->

Example 166. Subtract (−15) from −32. 

Page 143 

Solution. −32 − (−15) = −32 + (−(−15)) = −32 + 15. Applying the rule for adding signed numbers with opposite signs, 

<!-- Start of picture text -->
−32 − (−15) = −32 + 15 = −(32 − 15) = −17.<!-- End of picture text -->

Example 167. Subtract 2 8<sup>7from15</sup> 6<sup>.</sup> 

Solution. Adding the opposite of 2 8<sup>7to15</sup> 6<sup>,weget</sup> 

<!-- Start of picture text -->
1 5 −2 7 = − 2 76 + � 8 � � 8 − 15 6 �= − 2 21 (LCD = 24)� 24 − 120 24 �= −1 124 .<!-- End of picture text -->

Example 168. Perform the subtraction 3.359 − 10.08. 

Solution. 3.359−10.08 = 3.359+(−10.08) = −(10.08−3.359). We perform the subtraction of absolute values vertically. 

<!-- Start of picture text -->
1 0 . 0 8 0− 3 . 3 5 9<!-- End of picture text -->

<!-- Start of picture text -->
6 . 7 2 1<!-- End of picture text -->

Remembering that the sign was negative, 3.359 − 10.08 = −6.721. 

Formerly “impossible” subtractions, such as 

<!-- Start of picture text -->
7 − 12<!-- End of picture text -->

can now be easily performed. 

<!-- Start of picture text -->
7 − 12 = 7 + (−12) = −(12 − 7) = −5.<!-- End of picture text -->

Examples like this show that subtraction is not commutative: changing the order of subtraction changes the result to its opposite. In general, for any two signed numbers, 

<!-- Start of picture text -->
B − A = −(A − B).<!-- End of picture text -->

Example 169. 22 − 100 = −78 = −(100 − 22). 

We often need to find the difference of two unequal quantities. By convention, difference is given as a positive quantity. If the two quantities are A and B, their difference is either A − B or B − A (whichever is positive). Intuitively, 

<!-- Start of picture text -->
difference = larger − smaller.<!-- End of picture text -->

Formally, the difference of A and B is defined to be the absolute value of A − B. 

Page 144 

Example 170. Find the difference in temperature between −2<sup>◦</sup> F and 50<sup>◦</sup> F. 

Solution. Intuitively, 

higher temperature − lower temperature = 50 − (−2) = 52, 

so the temperature difference is 52<sup>◦</sup> F. Formally, 

<!-- Start of picture text -->
| −2 − 50 |=| −52 |= 52.<!-- End of picture text -->

Example 171. The summit of Mount Whitney in California is 14505 feet above sea level. Not far away, in Death Valley, the lowest point is 282 feet below sea level. What is the altitude difference between Mount Whitney’s summit and the lowest point in Death Valley? 

Solution. Assigning a negative altitude to a point below sea level, the difference is 

<!-- Start of picture text -->
14505 − (−282) = 14505 + 282 = 14787 feet.<!-- End of picture text -->

#### 5.2.1 Exercises 

Perform the subtractions. 

1. Subtract 31 from 7 2. 98 − 100 3. .65 − (−6.4) 4. Subtract 5.5 from 2.4 5. Subtract −53 from 68.6 6. −8.88 − (−1.11) 7. Subtract 2.2 from<sup>1</sup> 5 8. −87 − 23 9. −87 − (−23) 10. 5<sup>3</sup> 8<sup>−11</sup> 11. 5<sup>3</sup> 8<sup>−(−11)</sup> 12. Subtract<sup>3</sup> 5<sup>from0.1andexpressthedifferenceasafraction.</sup> 13. −2.5 − 1<sup>4</sup> 5 

Page 145 

<!-- Start of picture text -->
14. − 1 − − 2� 2 � � 3 �<!-- End of picture text -->

15. A snowball at −5<sup>◦</sup> C is heated until it melts and then boils. If water boils at 100<sup>◦</sup> C , by how much did the temperature of the snowball rise? 

16. A sunken car is salvaged from the bottom of a lake. The elevation of the lake bottom is −66.2 feet. The car is lifted by a crane to a height 79.5 feet above lake level. Through what vertical distance was the car lifted? 

### 5.3 Multiplying Signed Numbers 

Multiplication of positive numbers was defined in terms of repeated addition. For example, 

<!-- Start of picture text -->
3 × 4 = 4 + 4 + 4 = 12.<!-- End of picture text -->

There is no problem extending this definition to the product of a negative number by a positive number. 

<!-- Start of picture text -->
3 × (−4) = (−4) + (−4) + (−4) = −12.<!-- End of picture text -->

Products such as 

<!-- Start of picture text -->
(−2) × 5<!-- End of picture text -->

pose no problem if, for consistency, we define signed number multiplication to be commutative (we do): 

(−2) × 5 = 5 × (−2) = (−2) + (−2) + (−2) + (−2) + (−2) = −10. 

The general rule is: 

The product of two numbers with opposite signs is the negative of the product of their absolute values. 

Example 172. Find the products (a) 7 × (−11) and (b) (−12) × 5. 

Solution. We take the negative of the product of the absolute values in each case. (a) 7 × (−11) = −(7 × 11) = −77. (b) (−12) × 5 = −(12 × 5) = −60. 

When it comes to the product of two negative numbers, our intuition fails. It makes no sense to “repeatedly” add a number to itself when the number of repeats is negative! How should we define (−2) × (−3)? 

It is best to give up on intuition and let consistency rule. Look at the pattern below: 

<!-- Start of picture text -->
4 × (−3) = −12 = the opposite of 4 × 33 × (−3) = −9 = the opposite of 3 × 32 × (−3) = −6 = the opposite of 2 × 31 × (−3) = −3 = the opposite of 1 × 30 × (−3) = 0 = the opposite of 0 × 3(−1) × (−3) = = ?(−2) × (−3) = = ??<!-- End of picture text -->

Page 146 

It looks like the pattern “ought” to continue as follows: 

(−1) × (−3) = 3 the opposite of (−1) × 3 (−2) × (−3) = 6 the opposite of (−2) × 3 

We make the following general definition: 

The product of two negative numbers is the (positive!) product of their absolute values. 

Example 173. Find the product (−8) × (−12). 

Solution. (−8) × (−12) = 8 × 12 = 96. 

Note that the product of two positive numbers could also be defined as the (positive) product of their absolute values. So our definition is consistent with what we already know about positive numbers, and applies whenever numbers with the same sign are multiplied. 

[OPTIONAL: If you find it hard to accept that the product of two negative numbers is positive, the following discussion might help. An important axiom (fact) of arithmetic states that multiplication “distributes” over addition. That is, for any three numbers, A, B and C , 

<!-- Start of picture text -->
A(B + C ) = AB + AC .<!-- End of picture text -->

If signed number arithmetic is to be consistent with the arithmetic of nonnegative numbers, this axiom must continue to hold. In particular, if A and B are positive, 

<!-- Start of picture text -->
(−A)(B + (−B)) = (−A)(B) + (−A)(−B).<!-- End of picture text -->

Since the left hand side equals 0 (why?) so does the right hand side. It follows that (−A)(−B) must be the opposite of (−A)(B) = −(−AB) = AB. In other words, it must be true that (−A)(−B) = AB.] Here is a summary of the rules for multiplying signed numbers. 

When two signed numbers are multiplied 

• if the numbers have the same sign, the product is positive. • if the numbers have opposite signs, the product is negative. In both cases, the absolute value of the product is the product of the individual absolute values. 

In the examples and exercises below, we freely use all three ways of symbolizing multiplication: ·, ×, and juxtaposition. It is easiest to determine the sign of the product first, and then compute with the absolute values. 

Example 174. Multiply (−16) × 5. 

Solution. (−16) × 5 = −80 (negative since the numbers have opposite signs). 

Example 175. Find the product (−11) · (−12). 

Page 147 

Solution. (−11) · (−12) = 132 (positive since the numbers have the same signs). 

Example 176. Find the product (−6.30)(−2.05). 

Solution. The product is positive since the numbers have the same sign. Temporarily ignoring the decimal points, 

<!-- Start of picture text -->
6 3 0× 2 0 53 1 5 01 2 6 01 2 9 1 5 0<!-- End of picture text -->

Inserting four decimal places counting from the right, and remembering that the product is positive, we conclude that 

<!-- Start of picture text -->
(−6.30)(−2.05) = 12.915.<!-- End of picture text -->

Example 177. Find the product<sup>3</sup> −<sup>6</sup> . 4<sup>·</sup> � 5 � 

Solution. The numbers have opposite signs, so the product is negative. 

<!-- Start of picture text -->
> 36− · = − 9 (pre-cancelling 2).� 43> 2 5 � 10<!-- End of picture text -->

<!-- Start of picture text -->
Example 178. Find the product − 2 1 −3 1 .� 2 �� 4 �<!-- End of picture text -->

Solution. The numbers have the same sign so the product is positive, and we compute with the absolute values. Converting the mixed numbers to improper fractions for multiplication, 

<!-- Start of picture text -->
25 · 13 4 = 65 8 = 81 8 .<!-- End of picture text -->

Recall the zero property, which states that 

<!-- Start of picture text -->
0 · x = 0 and x · 0 = 0, for any number x .<!-- End of picture text -->

This remains true for signed numbers. Example 179. (−17.1) · 0 = 0. 

Also, 1 continues to be the multiplicative identity , that is, 

<!-- Start of picture text -->
1 · x = x and x · 1 = x, for any number x.<!-- End of picture text -->

<!-- Start of picture text -->
Example 180. − 15 · 1 = − 15� 31 � 31 .<!-- End of picture text -->

Page 148 

Multiplication, like addition, continues to be associative when extended to signed numbers. Thus we can multiply several signed numbers without worrying how we group them for multiplication. One consequence is that the sign of a product of several signed numbers can be quickly determined in advance by simply determining whether the number of negative factors is even or odd. 

The sign of a product of several factors is 

- positive if the number of negative factors is even, 

- negative if the number of negative factors is odd. 

This is true because every pair of negative factors has a positive product. If there is an even number of negative factors, they can be “paired off” (in any convenient order), producing a product of positive numbers which is, of course, positive. But if the number of negative factors is odd, there is always one “unpaired” negative factor, which makes the total product negative. 

Example 181. 

(−1)(2)(−3)(−4) = −24 (an odd number (three) of negative factors makes a negative product), (−1)(−2)(−3)(−4) = 24 (an even number (four) of negative factors makes a positive product). 

#### 5.3.1 Exercises 

Find the products. 

1. 8 × (−6) 2. −9 × 7 3. (−6) × (−9) 4. (−1) × 5 5. (91.4)(−1) 6. (0)(−88.8) 7. (−1) × (−1) 8. (−1) × (−1) × (−1) 9. 6.5 × (−31) 10. (−5.03) × (−0.6) 11. × 0 � 79 � 12. −<sup>7</sup> � 67 �� 6 � 

Page 149 

<!-- Start of picture text -->
13. −1 6 −1 1� 7 �� 2 �14. (−1.62)(1000)15. 1(−1)16. (−3)(−50)(−2)17. (−3)(0.5)(−0.7)(1)18. (3)(−10)(2)(−5)19. (−6)(−5)(−4)(−3)(0)20. − 1 − 2 − 3� 2 �� 3 �� 8 �� 54 �<!-- End of picture text -->

### 5.4 Dividing Signed Numbers 

Recall that two numbers are reciprocal if their product is 1. We extend this definition unchanged to signed numbers. For example, since 

<!-- Start of picture text -->
− 1(−2) × = 1,� 2 �−2 and − 2 1 are reciprocal. Similarly, − 3 8 and − 3 8 are reciprocal, since− 3 − 8 = 1.� 8 �� 3 �<!-- End of picture text -->

Division by a signed number N̸ = 0 can then be defined (as with positive numbers) as multiplication by the reciprocal of N, i.e., 

<!-- Start of picture text -->
M ÷ N = M · 1N<!-- End of picture text -->

for any number M. Since a number and its reciprocal must have the same sign (why?), it follows that the rules for dividing signed numbers are exactly analogous to the rules for multiplying them. 

#### When two signed numbers are divided (and the divisor is nonzero) 

- if the dividend and divisor have the same sign, the quotient is positive 

- if the dividend and the divisor have opposite signs, the quotient is negative. 

In both cases, the absolute value of the quotient is the quotient of the individual absolute values. 

Page 150 

Recall that a fraction bar indicates division, that is,<sup>x</sup> y<sup>=x÷ y.Bytherulefordivisionofsigned</sup> numbers, if either x or y (but not both) is negative, the fraction represents a negative number. For example, suppose a, b and c are positive. Then 

<!-- Start of picture text -->
−ba = − a b = − b a .<!-- End of picture text -->

All three fractions are equivalent, but it is customary to avoid the form in the middle (with a negative number in the denominator). In the examples and exercises, we indicate division by the ÷ symbol or the fraction bar interchangeably. It is easiest to determine the sign first, and then compute with the absolute values. For divisions of whole numbers, explicit conversion to reciprocal multiplication is not necessary. 

Example 182. Divide 24 by −6. 

Solution. The quotient 24÷ (−6) is negative since the numbers have opposite signs. The absolute value is 24 ÷ 6 = 4. Thus 

<!-- Start of picture text -->
24 ÷ (−6) = −4.<!-- End of picture text -->

<!-- Start of picture text -->
Example 183. Express the fraction −33 as a mixed number.5<!-- End of picture text -->

Solution. The fraction represents division of numbers with opposite signs, so the result is negative. For the division 33 ÷ 5, the quotient is 6 and the remainder is 3, so 

<!-- Start of picture text -->
−33 = −6 35 5 .<!-- End of picture text -->

<!-- Start of picture text -->
Example 184. Find −2 5 ÷ − 1 .� 9 � � 6 �<!-- End of picture text -->

Solution. Because the numbers have the same sign, the quotient is positive. We convert the mixed number to an improper fraction and multiply by the reciprocal of the divisor. 

<!-- Start of picture text -->
−2 5 ÷ − 1 = ·� 9 � � 6 � � −923 � � −16 �26� �= � 233� · � 1 �9� �= 463= 15 13 .<!-- End of picture text -->

Example 185. Divide 3.738 ÷ (−100). 

Page 151 

Solution. The quotient is negative because the numbers have opposite signs. Thus 

<!-- Start of picture text -->
3.738 ÷ (−100) = −0.03738.<!-- End of picture text -->

(Recall that dividing a decimal by a power of 10 (10<sup>2</sup> in this case) simply results in a leftward shift of the decimal point by a number of places equal to the exponent on 10.) 

Example 186. Divide 16 ÷ (−0.25). 

Solution. The quotient is negative because the signs are opposite. We can either perform the long division 

<!-- Start of picture text -->
0.25)16 equivalent to 25)1600,<!-- End of picture text -->

or convert 0.25 to the fraction<sup>1</sup> 4<sup>andmultiplybyitsreciprocal.Thelatterseemseasier:</sup> 

<!-- Start of picture text -->
16 ÷ (−0.25) = − 16 ÷ 1 = −(16 × 4) = −64.� 4 �<!-- End of picture text -->

#### 5.4.1 Division and 0 

Recall that 0 can be the numerator of a fraction, but it cannot be the denominator. This remains true for signed fractions. Fractions are divisions, and conversely, every division can be represented as a 0 fraction. A fraction like −3<sup>makessenseandisequalto0,so</sup> 

<!-- Start of picture text -->
0 ÷ (−3) = − 0 3 = − 3 0 = −0 = 0.<!-- End of picture text -->

But the fraction<sup>−3</sup> 0<sup>,andthereforethedivision(−3) ÷ 0,isundefined.(Youmaywishtoreviewthe</sup> discussion in Section 2.2.1, where all attempts to make sense of a fraction with denominator 0 led to failure or contradiction.) We summarize the properties of 0 with respect to division. 

<!-- Start of picture text -->
For a nonzero signed number N• 0 ÷ N = 0•N ÷ 0 is undefined.0 ÷ 0 is also undefined.<!-- End of picture text -->

0 Example 187. 0 ÷ (−23) and −71<sup>arebothequalto0.</sup> 1.62 ÷ 0 and<sup>−16</sup> are undefined. 0 

Page 152 

#### 5.4.2 Exercises 

Perform the divisions, or state that they are undefined. 

1. (−24) ÷ (−8) 

2. (−24) ÷ 8 

3. 66 ÷ 0 

4. 30 ÷ (−6) 

5. (−30) ÷ 6 

6.<sup>−26</sup> 13 

7.<sup>−19</sup> 0 

8.<sup>−72</sup> −18 9.5 

9. −1.9 

10. 601.03 ÷ (−1000) 

11. 0 ÷ (−1000) 

<!-- Start of picture text -->
12. ÷ − 25� 54 � � 32 �13. −4 1 ÷ −1 7� 2 � � 8 �<!-- End of picture text -->

<!-- Start of picture text -->
14. −10 34 ÷ 5<!-- End of picture text -->

<!-- Start of picture text -->
15. 100 ÷ 14<!-- End of picture text -->

<!-- Start of picture text -->
16. −110.98 ÷ 4<!-- End of picture text -->

17. .5 ÷ .4 

18. 50 ÷ (−.4) 

### 5.5 Powers of Signed Numbers 

Since exponents indicate repeated multiplication, there is no problem applying exponents to signed numbers. 

<!-- Start of picture text -->
(−4) 3 = (−4)(−4)(−4) = −64 and (−2) 4 = (−2)(−2)(−2)(−2) = 16.<!-- End of picture text -->

Page 153 

<!-- Start of picture text -->
Example 188. Evaluate − 3 .� 2 �3<!-- End of picture text -->

Solution. 

<!-- Start of picture text -->
− 3 = − 3 − 3 − 3� 2 �3 � 2 �� 2 �� 2 �= − 33 (the product of three negative factors is negative)2 3= − 27 8 = −33 8 .<!-- End of picture text -->

Example 189. Evaluate (−0.2)<sup>4</sup> . 

Solution. (−0.2)<sup>4</sup> = (−0.2)(−0.2)(−0.2)(−0.2) = 0.0016. (The product of four negative factors is positive.) 

The previous examples show that 

<!-- Start of picture text -->
A power of a negative number is• negative if the exponent is odd,• positive if the exponent is even.<!-- End of picture text -->

When applying exponents to signed numbers, it is essential to put parentheses around the number, including its sign. For example, the square of −3 is written 

<!-- Start of picture text -->
(−3) 2 = (−3)(−3) = 9.<!-- End of picture text -->

Without parentheses, as in 

<!-- Start of picture text -->
−3 2 ,<!-- End of picture text -->

the exponent applies only to 3, not to −3, and this is not a power of −3. Rather, −3<sup>2</sup> represents the opposite of 3<sup>2</sup> , so 

<!-- Start of picture text -->
−3 2 = −9.<!-- End of picture text -->

Example 190. Evaluate −<sup>3</sup> and − � 4 �2 � 43 �2 

Solution. The first expression is the square of a negative number, which is positive, 

<!-- Start of picture text -->
− 3 = − 3 − 3 = 9� 4 �2 � 4 �� 4 � 16 ,<!-- End of picture text -->

while the second is the opposite of the square of a positive number, which is negative: 

<!-- Start of picture text -->
− = − = − 9� 43 �2 �34 �� 43 � 16 .<!-- End of picture text -->

Page 154 

The behavior of 0 in an exponential expression, in particular, the interpretation of 0 as an exponent, extends unchanged to signed numbers. (You may wish to review Section 1.4 on powers of whole numbers in Chapter 1.) 

<!-- Start of picture text -->
For a nonzero signed number N,• N 0 = 1• 0 N = 0(0 0 is undefined.)<!-- End of picture text -->

Example 191. (−3.5)<sup>0</sup> = 1. −<sup>1</sup> = 1. 0<sup>4</sup> = 0. 0<sup>0</sup> is undefined. � 2 �0 

#### 5.5.1 Exercises 

Find the value of each expression. 

1. 8<sup>2</sup> 2. (−8)<sup>2</sup> 3. −8<sup>2</sup> 4. −6<sup>3</sup> 5. (−6)<sup>3</sup> 6. 0<sup>5</sup> 7. −<sup>2</sup> � 5 �3 8. −(−3<sup>3</sup> ) 9. −(−2)<sup>4</sup> 10. (.01)<sup>3</sup> 11. (10)<sup>0</sup> 12. (−9.08)<sup>1</sup> 13. (−23)<sup>0</sup> 14. −(−1.4)<sup>3</sup> 15. (−1)<sup>59</sup> 16. 0<sup>0</sup> 

Page 155 

<!-- Start of picture text -->
17. 2 1� 2 �218. − 1� 10 �4<!-- End of picture text -->

### 5.6 Square Roots and Signed Numbers 

If there is a number whose square is the number n, it is called a square root of n. For example, since 4<sup>2</sup> = 16, 4 is a square root of 16. It is also true that (−4)<sup>2</sup> = 16, so −4 is another square root of 16. 

Every positive number N has two square roots, which are opposites: 

<!-- Start of picture text -->
• The positive square root is denoted √N.• The negative square root is denoted −√N.<!-- End of picture text -->

As usual, 0 is a special case. It has only one square root, itself: 

<!-- Start of picture text -->
√0 = 0.<!-- End of picture text -->

Whole numbers whose square roots are also whole numbers are called perfect squares. Example 192. The first few perfect squares are 0, 1, 4, 9, 16 and 25, because 

<!-- Start of picture text -->
√0 = 0, √1 = 1, √4 = 2, √9 = 3, √16 = 4, and √25 = 5.<!-- End of picture text -->

The square root of a whole number which is not a perfect square has a decimal expansion which neither terminates nor repeats. (Such numbers are called irrational.) A calculator will inform you that 

<!-- Start of picture text -->
√2 ≈ 1.41 and √3 ≈ 1.73 (rounded to the nearest hundredth).<!-- End of picture text -->

<!-- Start of picture text -->
Example 193. Between what two whole numbers do −√2 and −√3 lie? Which number is larger?<!-- End of picture text -->

Solution. On the number line, −√2 ≈−1.41 and −√3 ≈−1.73 both lie between −1 and −2. 

<!-- Start of picture text -->
-√3 -√2 √2 √3| | | | |−2 −1 0 1 2<!-- End of picture text -->

Recalling that “left is less” on the number line, 

<!-- Start of picture text -->
−√3 < −√2,<!-- End of picture text -->

in other words, −√2 is larger. 

Example 194. Between what two integers does −√19 lie? 

Page 156 

Solution. We first locate the largest perfect square less than 19, and the smallest perfect square greater than 19. We find that 19 is between 4<sup>2</sup> and 5<sup>2</sup> . That is, 16 < 19 < 25. It follows (by a geometric argument we gave in Section 1.4.3) that 

<!-- Start of picture text -->
4 < √19 < 5.<!-- End of picture text -->

This relationship has a “mirror image” on the negative half of the number line, as indicated below. 

<!-- Start of picture text -->
−√19 √19| | | | | | | | | | |−5 −4 −3 −2 −1 0 1 2 3 4 5<!-- End of picture text -->

We see that −√19 lies between −5 and −4. More precisely, −√19 is greater than −5 and less than −4, 

<!-- Start of picture text -->
−5 < −√19 < −4.<!-- End of picture text -->

<!-- Start of picture text -->
The square root of a positive fraction is not usually a quotient of whole numbers. The exceptionsoccur when the numerator and denominator of the fraction are both perfect squares. For example,� 49 = 2 3 because � 23 �2 = 9 4 . But � 25 cannot be evaluated in this way. We can, however, write2 √2 (since 2 = 2� 5 = √5 � √√5 �2 5 ).<!-- End of picture text -->

2 This expresses � 5<sup>asaquotient,butnotaquotientofwholenumbers.</sup> We come now to a troubling fact. 

Square roots of negative numbers cannot be defined within the system of signed numbers. 

Suppose, for example, there were a number which, when squared, yields −4. That number must have absolute value 2, so the only possibilities are 2 and −2. But 

<!-- Start of picture text -->
2 2 = (−2) 2 = 4 (not −4).<!-- End of picture text -->

A similar argument applies to any negative number. It is possible to expand the set of signed numbers so as to remedy this defect. This involves adjoining some “imaginary” (as opposed to “real”) numbers. We leave that for a more advanced course. For now, when we encounter the square root of a negative number, we simply say that it is not a real number. 

Example 195.<sup>√</sup> −5 is not a real number. 

Page 157 

#### 5.6.1 Exercises 

Find the square roots, or state that they are not real numbers. 

1. √9 2. −√25 3.<sup>√</sup> −25 4. −√49 81 5. � 4 121 6. − �144 7. √100 8. √0 25 9. − �36 −64 10. � −49 1 11. − � 16 

Between what two integers do the following square roots lie? 

11. √7 12. −√7 13. −√30 Insert the appropriate inequality (< or >) between the following pairs of numbers. 14. −√10 −√8 15. √12 √15 

### 5.7 Evaluating Expressions 

A mathematical expression is any meaningful combination of numbers, letters, operation symbols (such as +, −, ×, ÷,<sup>√</sup> ), and grouping symbols (such as parentheses, brackets, fraction bars and the extended square root symbol like<sup>√</sup> ). For example, the expression 

<!-- Start of picture text -->
x + yx − y<!-- End of picture text -->

Page 158 

indicates a fraction whose numerator is the sum of two unspecified numbers, x and y , and whose denominator is their difference. Letters in a mathematical expression are called variables because they represent unspecified numbers that can take various different values. Expressions can be evaluated (assigned a numerical value) if numerical values are assigned to all the variables appearing in the expression. 

Example 196. Evaluate the expression<sup>x+ y</sup> x − y<sup>ifx= 2andy= −6.</sup> 

Solution. We replace each letter by its assigned numerical value, enclosed in parentheses, 

<!-- Start of picture text -->
xx −+ yy = (2) + ( (2) − ( − − 6) 6) ,<!-- End of picture text -->

and simplify the resulting expression 

<!-- Start of picture text -->
(2) + (−6)(2) − (−6) = − 8 4 = − 1 2 .<!-- End of picture text -->

Assigning different values to the letters in an expression usually changes the value of the expression. Example 197. Evaluate the expression<sup>x+ y</sup> x − y<sup>ifx= −3andy= 3.</sup> 

Solution. Replacing x and y by their assigned values, 

<!-- Start of picture text -->
x + yx − y = ( ( − −3) 3) + (3)  − (3) = − 0 6 = 0.<!-- End of picture text -->

The reason for replacing letters with their assigned values in parentheses is to avoid pitfalls such as the ones highlighted in the next two examples. 

Example 198. Evaluate x<sup>2</sup> if x = −4. 

Solution. Forgetting parentheses, we would write x<sup>2</sup> = −4<sup>2</sup> = −16, which is wrong, since the square of any nonzero number is positive. The correct evaluation is 

<!-- Start of picture text -->
x 2 = (−4) 2 = 16.<!-- End of picture text -->

Example 199. Evaluate ab if a = 3 and b = −4. 

Solution. Without parentheses, we might think ab = 3 − 4 = −1, mistakenly turning multiplication into subtraction. The correct evaluation is 

<!-- Start of picture text -->
ab = (3)(−4) = −12.<!-- End of picture text -->

To evaluate complicated expressions consistently, we must follow the order of operations, which is restated below for convenience. 

Page 159 

1. operations within grouping symbols first; 

2. exponents and roots next; 

3. multiplications and divisions (in order of appearance) next; 

4. additions and subtractions (in order of appearance) last. 

Recall that “in order of appearance” means in order from left to right, and that grouping symbols include parentheses, brackets, braces (curly brackets), the square root symbol, and the fraction bar. 

Example 200. Evaluate the expression x − 3y if x = 4 and y = −<sup>1</sup> 2<sup>.</sup> 

Solution. Substituting the assigned values, and multiplying first according to the order of operations, 

<!-- Start of picture text -->
− 1x − 3y = (4) − 3� 2 �= 4 + 3211= 8 2 + 2 3 = 2 = 5 1 2 .<!-- End of picture text -->

Example 201. Evaluate a − b − c and a − (b − c) if a = 2, b = −11 and c = 10. 

Solution. The first expression is evaluated as follows: 

<!-- Start of picture text -->
a − b − c = (2) − (−11) − (10)= 13 − 10 (left subtraction before right subtraction)= 3.<!-- End of picture text -->

For the second expression, 

<!-- Start of picture text -->
a − (b − c) = (2) − (−11) − (10)� �= 2 − (−21) (subtraction within grouping symbols first)= 23.<!-- End of picture text -->

Example 202. Evaluate 3 − (p − r ÷ t) if p =<sup>3</sup> 4<sup>,r= −1</sup> 8<sup>andt=</sup> 12<sup>5.</sup> 

Page 160 

Solution. Within grouping symbols, division comes first. 

<!-- Start of picture text -->
3 − (p − r ÷ t) = 3 − − 1 ÷ (changing parentheses to brackets for clarity)� 34 − � 8 � � 125 ��> 3= 3 − − 1 · 12 (division as multiplication by the reciprocal)� 34 − � 8> 2 � � 5 ��= 3 − − 3� 43 − � 10 ��= 3 − (subtraction within grouping symbols first)� 43 + 10 3 �= 3 − (using the LCD = 20)� 2015 + 20 6 �60 39= 3 − = = = 1 19� 2021 � 20 − 20 21 20 20 .<!-- End of picture text -->

<!-- Start of picture text -->
Example 203. Evaluate 3x 3 − 5x 2 + 13x − 4 if x = 0.x 2 + 2Solution. 3(0)3 − 5(0)2 + 13(0) − 4 = −40 2 + 2 2 = −2.<!-- End of picture text -->

Example 204. Evaluate the expressions √a<sup>2</sup> + b<sup>2</sup> and a + b if a = −0.6, and b = 0.8. Solution. For the first expression, 

<!-- Start of picture text -->
�a 2 + b 2 = (−0.6) 2 + (0.8) 2�= √.36 + .64 = √1 = 1.<!-- End of picture text -->

For the second expression, 

<!-- Start of picture text -->
a + b = −0.6 + 0.8= 0.2.<!-- End of picture text -->

This example shows that, in general, 

<!-- Start of picture text -->
�a 2 + b 2̸ = a + b.<!-- End of picture text -->

#### 5.7.1 Exercises 

Evaluate the expressions for the given values of the variables. Reduce fractions to lowest terms and express improper fractions as mixed numbers. 

<!-- Start of picture text -->
1. 2a − b if a = 11 and b = −52. 2rt if r = 5 and t = −6<!-- End of picture text -->

Page 161 

<!-- Start of picture text -->
3. −6x 2 if x = − 234. p 2 − q 2 if p = −2 and q = 35. a − ab − b if a = −0.6 and b = 0.86. −x 2 + 3y 2 − 8y + 5 if x = −2 and y = 07. (d − e)(d 2 + ed + e 2 ) if d = −1 and e = −48. 2x + y if x = 4 and y = −6x − 2y9. 2pq − q 2 if p = 1.2 and q = 2.310. 3 5 a a  −  + 2  b b if a = 1 1 2 and b = 1 411. �x 2 + y 2 if x = 23 and y = − 1 212. −b + √b 2 − 4ac if a = −2, b = 7 and c = −3<!-- End of picture text -->

### 5.8 Using Formulae 

A formula expresses one quantity in terms of others. For example, the formula for the area A of a rectangle of length l and width w is 

<!-- Start of picture text -->
A = lw .<!-- End of picture text -->

If we know the length and width of a rectangle, we can calculate its area, using the formula. For example, the area of a rectangle of width 17 feet and length 50 feet is 

<!-- Start of picture text -->
A = lw = (17)(50) = 850 square feet.<!-- End of picture text -->

Example 205. The formula for the distance s (in feet) that an object falls in a time t (in seconds) is 

<!-- Start of picture text -->
s = 16t 2 .<!-- End of picture text -->

Use the formula to determine the distance an object falls in (a) 2 seconds; (b) 4 seconds. 

Solution. We substitute t = 2 and t = 4 into the formula. In 2 seconds the object falls 

<!-- Start of picture text -->
s = 16(2) 2 = 64 feet,<!-- End of picture text -->

while, in 4 seconds it falls 

<!-- Start of picture text -->
s = 16(4) 2 = 256 feet.<!-- End of picture text -->

Example 206. The formula which converts temperature in degrees Celsius (<sup>◦</sup> C ) to temperature in degrees Fahrenheit (<sup>◦</sup> F ) is 

<!-- Start of picture text -->
F = 95 C + 32.<!-- End of picture text -->

Find the temperature in<sup>◦</sup> F if a thermometer reads −10<sup>◦</sup> C . 

Page 162 

Solution. Substituting (−10) for C in the formula, we find 

<!-- Start of picture text -->
F = 95 (−10) + 32> 2= − 9 · 10> 1 1 + 325= −18 + 32 = 14.<!-- End of picture text -->

The temperature is 14<sup>◦</sup> F. 

Example 207. The Pythagorean theorem gives a formula for the length c of the hypotenuse of a right triangle in terms of the lengths a, b of its legs. 

<!-- Start of picture text -->
c = �a 2 + b 2 .<!-- End of picture text -->

Find the length of the hypotenuse of a right triangle whose legs have lengths 5 and 12 feet. 

Solution. We put a = 5 and b = 12 in the Pythagorean formula. 

<!-- Start of picture text -->
c = �a 2 + b 2 = (5) 2 + (12) 2 = √25 + 144 = √169 = 13 feet.�<!-- End of picture text -->

Example 208. The semi-perimeter of a triangle with side lengths a, b and c is given by the formula 

<!-- Start of picture text -->
s = 12 (a + b + c).<!-- End of picture text -->

Find the semi-perimeter of a triangle with side lengths a = 6 ft 8 in, b = 9 ft 4 in, and c = 11 ft 10 in. Solution. We convert all measurements to inches, using the fact that 1 ft = 12 in. Thus 

<!-- Start of picture text -->
a = 80 in, b = 112 in, and c = 142 in.<!-- End of picture text -->

The semi-perimeter is 

<!-- Start of picture text -->
s = 1 2 (a + b + c) = 1 2 (80 + 112 + 142)= 167 in= 13 ft 11 in.<!-- End of picture text -->

Example 209. The child’s dosage for a medicine is given by the formula 

<!-- Start of picture text -->
tC = t + 12 · A,<!-- End of picture text -->

where C is the child’s dosage, A is the adult dosage, and t is the child’s age in years. Find the dosage for a four-year old child if the adult dosage is 48 mg (milligrams). 

Solution. Substituting t = 4 and A = 48, 

<!-- Start of picture text -->
4C =4 + 12 · 48 = 1 4 · 48 1 = 12.<!-- End of picture text -->

The child’s dosage is 12 mg. 

Page 163 

#### 5.8.1 Exercises 

1. Find the area of a rectangle whose length is 4.8 meters and whose width is 3.6 meters. Use the formula A = lw , where A is the area, l is the length, and w is the width. 

2. Find the perimeter of the rectangle in the preceding exercise, using the formula P = 2l + 2w , where P is the perimeter and l , w are the length and width, respectively. 

3. Find the length of the hypotenuse of a right triangle whose legs are 0.3 yards and 0.4 yards. Use the Pythagorean theorem. 

4. How far does an object fall in 3 seconds? Use the formula s = 16t<sup>2</sup> , where s is the distance fallen (in ft), and t is the time (in sec). 

5. If a thermometer reads 22<sup>◦</sup> C, find the temperature in<sup>◦</sup> F. Use the formula F =<sup>9</sup> 5<sup>C+ 32.</sup> 

6. Heron’s formula, A = �s(s − a)(s − b)(s − c), gives the area (A) of a triangle (not necessarily a right triangle) with side lengths a, b and c, and semi-perimeter s. Use Heron’s formula and the semi-perimeter formula s =<sup>1</sup> 2<sup>(a + b + c)tofindtheareaofatrianglewitha = b= c= 2ft.</sup> 

7. The formula A = P(1 + r )<sup>t</sup> gives the amount A of money in a bank account t years after an initial amount P is deposited, when the annual interest rate is r . Find A after 2 years if the interest rate is 5% (r = .05), and the initial deposit was P = $500. 

8. Find the child’s dosage for a 10-year old, if the adult dosage is 2.2 grams. Use the formula t 

C = t + 12<sup>· A,</sup> where C is the child’s dosage, t is the child’s age, and A is the adult dosage. 

### 5.9 Linear Equations in One Variable 

An equation is a statement that two mathematical expressions are equal. If the statement has just one variable, and if 

- the variable does not appear in the denominator of a fraction, 

- the variable does not appear under a<sup>√</sup> symbol, 

- the variable is not raised to a power other than 1, 

then we have a linear equation in one variable. Here are some examples of linear equations in one variable: 

<!-- Start of picture text -->
2x + 4 = 8 − 3y = 12 z − 9 = −1 2 − 2 3 t = 0.<!-- End of picture text -->

A solution to an equation in one variable is a number which, when substituted for the variable, makes a true statement. 

Example 210. Show that −4 is a solution to the equation −3y = 12 

Solution. When we substitute −4 for y in the equation, we get 

<!-- Start of picture text -->
−3(−4) = 1212 = 12, a true statement.<!-- End of picture text -->

Page 164 

Example 211. Show that 10 is not a solution to the equation z − 9 = −1. 

Solution. When we substitute 10 for z in the equation, we get 

<!-- Start of picture text -->
10 − 9 = −1−1 = 1, a false statement.<!-- End of picture text -->

Example 212. Show that 3 is a solution to the equation 2 −<sup>2</sup> 3<sup>t= 0,but4isnot.</sup> 

Solution. When we substitute 3 for t, we obtain 

<!-- Start of picture text -->
2 − 2 · ��31 = 0� 3�2 − 2 = 00 = 0, a true statement.<!-- End of picture text -->

When we substitute 4 for t, we obtain 

<!-- Start of picture text -->
2 − 23 · 1 4 = 02 − 83 = 0,− 2 3 = 0, a false statement.<!-- End of picture text -->

Here is the formal definition of the subject of this section. 

A linear equation in one variable x is an equation that can be written in the form 

<!-- Start of picture text -->
ax + b = cfor some numbers a, b and c, with a̸ = 0.<!-- End of picture text -->

Such an equation always has a unique (i.e., exactly one) solution. 

#### 5.9.1 Finding solutions 

We find solutions to equations using two common-sense principles: 

- Adding equals to equals produces equals, 

- Multiplying equals by equals produces equals. 

Page 165 

For example, 2 and 2 are equals, and so are 3 and 3. Adding equals to equals, 

<!-- Start of picture text -->
2 = 23 = 32 + 3 = 2 + 3<!-- End of picture text -->

produces equals: 5 = 5. 

##### Consider the linear equation 

<!-- Start of picture text -->
x − 3 = 6.<!-- End of picture text -->

Although we cannot say that x − 3 and 6 are “equals” (without knowing the value of x) we can say that if they are equal for some x, then adding equals to both sides, or multiplying both sides by equals, will produce a new pair of equals for the same x. In particular, if x − 3 = 6 is true for some x, so is the equation obtained by adding 3 to both sides: 

<!-- Start of picture text -->
x − 3 = 6+3 +3x = 9.<!-- End of picture text -->

The solution to the last equation is obvious (and obviously unique): x must be 9. It is slightly less obvious that 9 is a solution of the original equation. Could there be some other solution to the original equation, say, x = p? If so, then p − 3 = 6, and adding 3 to both sides yields p = 9. So p is no different from the solution we already found. We conclude that 9 is the unique solution of x − 3 = 6. 

Example 213. Find the solution of the equation 9 = −<sup>1</sup> 5<sup>zbymultiplyingbothsidesbyequals.Check</sup> that you have indeed obtained the unique solution. 

Solution. If we multiply both sides of the equation by −5, we get 

<!-- Start of picture text -->
−5(9) = −5 − 1 z� 5 �−45 = z.<!-- End of picture text -->

To check that −45 is the solution, substitute −45 for z in the original equation, and verify that a true statement results. 

<!-- Start of picture text -->
9 = − 15 z9 = ?  − 15 (−45)> 9459 = ?> 159 = 9 a true statement.<!-- End of picture text -->

Equations which have the same solution are called equivalent. As the previous examples show, a strategy for finding the solution of an equation is to systematically transform it into simpler equivalent equations, until we arrive at an equation like x = 8, or −45 = z, whose solution is obvious. 

Page 166 

To find the solution (solve) a linear equation in one variable, we can do one or both of the following: 

- add the same number to both sides of the equation; 

- multiply both sides of the equation by the same nonzero number. 

We can replace “add” by “subtract,” and “multiply” by “divide,” if convenient. (This is because subtracting a number is the same as adding the opposite number, and dividing by a nonzero number is the same as multiplying by the reciprocal number.) 

Example 214. Solve the equation 2x + 4 = −10 and check that the solution is correct. 

Solution. First subtract 4 from both sides: 

<!-- Start of picture text -->
2x + 4 = −10−4 −42x = −14.<!-- End of picture text -->

Then divide both sides by 2: 

<!-- Start of picture text -->
2x = −14* −72 · x = ��� −142 > 12x = −7.<!-- End of picture text -->

The solution is −7. To check, we substitute −7 for x in the original equation, and see if a true statement results. 

<!-- Start of picture text -->
2x + 4 = −102(−7) + 4 = ?  −10−14 + 4 = ?  −10−10 = −10 a true statement<!-- End of picture text -->

Example 215. Solve the equation 26 = 5 −<sup>7</sup> 8<sup>xandcheckthesolution.</sup> 

<!-- Start of picture text -->
Solution. At some point it will be necessary to multiply both sides by the reciprocal of − 78 . But it isbetter not to do that immediately. If we first subtract 5 from both sides, the computations are shorter.26 = 5 − 78 x− 5 − 521 = − 78 x<!-- End of picture text -->

Page 167 

−<sup>8</sup> Now we multiply both sides by � 7 � 

<!-- Start of picture text -->
− 8 − 8 − 77 · 21 = � 7 �� 8 x �− 8 · 21 => 3 − 8� − 7�7 � 7 � �� 8 � x �−24 = x<!-- End of picture text -->

A linear equation given in the standard form 

<!-- Start of picture text -->
ax + b = c (a̸ = 0)<!-- End of picture text -->

is solved in two steps: first, subtract b from both sides; second, divide both sides by a. Example 216. Solve the equation −x + 5 = 12. 

Solution. Note that −x means −1x. Following the two step procedure, we first subtract 5 from both sides, and then divide both sides by −1. 

<!-- Start of picture text -->
−x + 5 = 12−x = 7 (subtracting 5 from both sides)x = −7 (dividing or multiplying both sides by −1)<!-- End of picture text -->

Note that dividing by −1 is the same as multiplying by −1, since −1 is its own reciprocal! Example 217. Solve 3x +<sup>1</sup> 2<sup>=1</sup> 2<sup>.</sup> 

Solution. We first subtract<sup>1</sup> 2<sup>frombothsides.</sup> 

<!-- Start of picture text -->
3x + 1 2 = 1 23x = 1 2 − 1 23x = 0x = 0.<!-- End of picture text -->

At the last step, we divided both sides by 3. Recall that<sup>0</sup> 3<sup>= 0.</sup> 

Example 218. Four times a number is −5.6. What is the number? 

Solution. Let x represent the unknown number. The sentence “Four times a number is −5.6” is a verbal form of the equation 

<!-- Start of picture text -->
4x = −5.6.<!-- End of picture text -->

Dividing both sides by 4 yields 

<!-- Start of picture text -->
x = −5.6 = −1.4.4<!-- End of picture text -->

The number is −1.4. It is straightforward to check that four times −1.4 is indeed −5.6. 

Page 168 

#### 5.9.2 Exercises 

Determine if the given value of the variable is a solution of the equation. 

1. y + 1.6 = 14.4, y = 2 2. 2x + 3 = 19, x = 8 

Solve the equations and check the solutions. 

3. x − 5 = 19 4. 6 + y = −2 5. 9x = 45 2 6. 5<sup>t= 24</sup> 7. −y − 14 = 5 x 8. 8<sup>= −4</sup> 9. 19t − 5 = −5 10. 4x − 5 = 7 11. 2y − 1.6 = 13.2 2 12. 3<sup>−x</sup> 5<sup>=−</sup> 15<sup>14</sup> 13. Twelve times a number is 108. What is the number? 

14. Five more than a number is −9<sup>1</sup> 2<sup>.Whatisthenumber?</sup> 

Page 169 

#### **ARITHMETIC: A Textbook for Math 01 3rd edition (2012)** 

**Answers to odd numbered exercises for Chapters 1, 2 by Natalia Novak** 

###### **Section 1.1.3 Exercises** 

1. _{_ 1 _}_ 2 6 + 5 5 8 1 3. _{_ 1 _} {_ 1 _}_ 3 2 4 5 + 6 4 1 4 1 5. _{_ 2 _} {_ 1 _} {_ 2 _}_ 9 0 9 7 7 7 + 6 9 6 4 8, 6 5 0 7. _{_ 2 _} {_ 1 _} {_ 2 _}_ 9 9 9 9 9 0 2 + 9 5 0 2 1 1, 4 1 2 9. _{_ 1 _} {_ 2 _}_ 3 2 0 0 0 9 8 4 4 9 0 2 + 4 5 0 3 4 7, 2 4 9 

###### **Section 1.2.5 Exercises** 

<!-- Start of picture text -->
1.{ 8 } { 14 }9 4− 3 75 73.{ 2 } { 14 } { 10 }3 5 0− 7 62 7 4<!-- End of picture text -->

1 

5. _{_ 5 _} {_ 9 _} {_ 10 _}_ 6 0 0 _−_ 1 9 9 4 0 1 7. 5 6 7 8 _−_ 4 5 6 7 1, 1 1 1 9. _{_ 7 _} {_ 10 _}_ 8 0 1 _−_ 7 9 0 1 1 11. _{_ 4 _} {_ 9 _} {_ 9 _} {_ 9 _} {_ 10 _}_ 5 0 0 0 0 0 _−_ 4 3 2 1 0 4 5 6, 7 9 0 

**Section 1.3.3 Exercises** 

<!-- Start of picture text -->
1.1 2 2× 44 8 83.{ 2 }1 0 4× 77 2 85.2 1 2× 4 36 3 6+ 8 4 89, 1 1 67.1 3 6× 2 79 5 2+ 2 7 23, 6 7 29.2 1 0 3× 4 48 4 1 2+ 8 4 1 29 2, 5 3 2<!-- End of picture text -->

2 

**Section 1.4.2 Exercises** 

1. 8 _×_ 8 _×_ 8 _×_ 8 = 8<sup>4</sup> 

3. 2<sup>5</sup> = 2 _×_ 2 _×_ 2 _×_ 2 _×_ 2 = 32 

5. 0<sup>7</sup> = 0 _×_ 0 _×_ 0 _×_ 0 _×_ 0 _×_ 0 _×_ 0 = 0 

7. 10<sup>2</sup> = 10 _×_ 10 = 100 9. 0<sup>3</sup> = 0, 1<sup>3</sup> = 1, 2<sup>3</sup> = 8, 3<sup>3</sup> = 27, 5<sup>3</sup> = 125, . . . , 9<sup>3</sup> = 729, 10<sup>3</sup> = 1000, 100<sup>3</sup> = 1000000. 

###### **Section 1.4.4 Exercises** 

1. _~~√~~_ 49 = 7 3. _~~√~~_ 169 = 13 5. _~~√~~_ 64 = 8 7. _~~√~~_ 75 is between _~~√~~_ 64 = 8 and _~~√~~_ 81 = 9 9. _~~√~~_ 32 is between _~~√~~_ 25 = 5 and _~~√~~_ 36 = 6 

**Section 1.5.3 Exercises** 

1. 4 _×_ 22 = 88 3. 3 _×_ 17 = 51 5. 8 _×_ 12 = 96 7. 712 _÷_ 101 = 7 _R_ 5 9. 3333 _÷_ 111 = 10 _R_ 3 11. 457 _÷_ 41 = 11 _R_ 6 13. 317 _÷_ 21 = 15 _R_ 2 15 21 )317 _−_ <u>21</u> 107 _−_ <u>105</u> 2 15. 712 _÷_ 21 = 33 _R_ 19 33 21 )712 _−_ <u>63</u> 82 _−_ <u>63</u> 19 

**Section 1.6.1 Exercises** 

1. 6 + 16 _÷_ 4 = 6 + 4 = 10 

3 

3. 15 _−_ 9 _−_ 4 = 6 _−_ 4 = 2 

5. 4 _×_ 3 _×_ 2 _÷_ 8 _−_ 3 = 12 _×_ 2 _÷_ 8 _−_ 3 = 24 _÷_ 8 _−_ 3 = 3 _−_ 3 = 0 

7.<sup>_~~√~~_</sup> 21 _−_ 30 _÷_ 6 =<sup>_~~√~~_</sup> 21 _−_ 5 = _~~√~~_ 16 = 4 

9. 2 + 2 _×_ 8 _−_ (4 + 4 _×_ 3) = 2 + 2 _×_ 8 _−_ (4 + 12) = 2 + 2 _×_ 8 _−_ (16) = 2 + 16 _−_ 16 = 18 _−_ 16 = 2 

###### **Section 1.7.1 Exercises** 

<!-- Start of picture text -->
1. 1 + 2 + 3 + 4 + 5 + 6 + 7 = 287 7 = 43. 206 + 196 + 204 = 606 = 2023 3<!-- End of picture text -->

<!-- Start of picture text -->
5. Note that there were 9 seasons: 2002-2009 and 2010 years.5 + 6 + 2 + 10 + 9 + 4 + 6 + 5 + 7 = 549 9 = 6<!-- End of picture text -->

**Answer** : on average, 6 games were canceled for the 2002-2010 seasons. 

###### **Section 1.8.1 Exercises** 

1. Two of these triangles make up a rectangle of 5” wide and 12” long. So, the area of the triangle is half the area of the rectangle. _A_ =<sup>1</sup> 2<sup>_×_5</sup><sup>_×_12 =1</sup> 2<sup>_×_60 = 30in2.</sup> 

3. _A_ = _W × L_ = 7 _×_ 8 = 56 ft<sup>2</sup> 

5. The diagonal is a hypothenuse of a right triangle with legs 2 cm and 2 cm. Therefore, by the Pythagorean Theorem, _c_<sup>2</sup> = 2<sup>2</sup> + 2<sup>2</sup> , i.e. _c_<sup>2</sup> = 8, i.e. _c_ = _~~√~~_ 8. _~~√~~_ 4 _<_ _~~√~~_ 8 _<_ _~~√~~_ 9, i.e. 2 _<_ _~~√~~_ 8 _<_ 3. **Answer** : the length of the diagonal is _~~√~~_ 8 cm, and it is a value between 2 and 3. 

###### **Section 2.2.2 Exercises** 

1. The picture has two whole circles and<sup>5</sup> 6<sup>ofacircle.Wecanthinkofeachwholecircleas6sixths,</sup> 

so altogether the picture represents 6 + 6 + 5 = 17 sixths, i.e.<sup>17</sup> 6<sup>.</sup> 

3. Divide a circle into 4 equal parts and shade in three of the parts. 

5. With circles, we would have a whole circle (6 sixths) and 5 sixths of a circle. So we need the same picture as question 1, but with one whole circle removed. 

<!-- Start of picture text -->
7. We can represent 6 2 as 3 whole squares, since each square is 2 2 : ■ + ■ + ■9. Examples of five fractions that equal 0 are: 1 0 , 0 2 , 0 3 , 10 0 , 21070<!-- End of picture text -->

###### **Section 2.3.2 Exercises** 

<!-- Start of picture text -->
1. 19 (because 19  ÷  3 = 6 R 1)3 = 61 33. 135 = 27 (because 135  ÷  5 = 27)55. 77 (because 77  ÷  5 = 15 R 2)5 = 152 57. average= 11 + 14 + 9 + 12 = 464 4 = 112 4 = 111 2<!-- End of picture text -->

4 

###### **Section 2.3.4 Exercises** 

<!-- Start of picture text -->
1. 1 1 2 = 1  ·  2 + 1 2 = 3 23. 15 3 8 = 15  ·  8 + 3 8 = 123 85. 11 5 6 = 11  ·  6 + 5 6 = 71 67. 11 = 11 1 = 22 2 = 44 4<!-- End of picture text -->

###### **Section 2.4.1 Exercises** 

<!-- Start of picture text -->
1. 13 · 5 7 = 21 53. Two thirds of one third = 2 3 · 1 3 = 2 95. 3  · 8 5 = 1 3 · 8 5 = 15 87. 1 2 · 7 8 ·  3 = 2 1 · 7 8 · 1 3 = 21 16Section 2.5.2 Exercises1. 4 1 = 2 8 = 12 3 = 40 10 = 44 113. 5 1 = 10 50 = 10 2 = 15 3 = 40 85. 8 1 = 11 88 = 16 2 = 24 3 = 10 807. 12 8 = 12 8  ÷  ÷  4  4 = 2 3 = 11 29. 45 20 = 20 45  ÷  ÷  5  5 = 9 45411.108 = 108 54  ÷  ÷  54  54 = 1 2<!-- End of picture text -->

###### **Section 2.5.2 Exercises** 

###### **Section 2.6.1 Exercises** 

1. 60 = 2 _·_ 30 = 2 _·_ 15 _·_ 2 = 2 _·_ 3 _·_ 5 _·_ 2 = 2<sup>2</sup> _·_ 3 _·_ 5, therefore 60 = 2<sup>2</sup> _·_ 3 _·_ 5 

3. 81 = 9 _·_ 9 = 3<sup>4</sup> , so 81 = 3<sup>4</sup> 

5. 85 = 5 _·_ 17 

7. The only numbers divisible by 3 in the list 60, 48, 81, 360, 85 and 154 are: 60, 48 and 360 

###### **Section 2.6.3 Exercises** 

1. GCF(72,48) = 24 

3. GCF(72,36) = 36 

5. GCF(36,15) = 3 

7. GCF(15,14) = 1 

5 

###### **Section 2.6.5 Exercises** 

<!-- Start of picture text -->
1. 3672 = 36 72  ÷  ÷  36  36 = 2 13. 1448 = 14 48  ÷  ÷  2  2 = 24 75. 14 15 = 14 15487.180 = 180 48  ÷  ÷  12  12 = 15 49. 105 147 = 105 147  ÷  ÷  21  21 = 5 7Section 2.7.1 Exercises71. 4 ÷ 4 · = 15 12 ÷ 4 5 · 7 3 = 15 72 13. 12  · 5 8 · 2 5 = 12 1 · 5 ÷ 8 5 · 5 ÷ 5 = 12 1 ÷ 4 · 8 ÷ 4 · 2 1 = 3 1 · 2 1 · 2 1 = 35. 3 2 of 24 = 2 3 · 24 1 = 16 1 = 1677. 2 2 3 ·  13 4 = 8 ÷ 3 4 · 4 ÷ 4 = 14 3 = 42 39. If the tank is only three-fifths full ( 35 of the aquariums capacity), then we need to add 5 2 of 121 2gallons of water. So, we get 5 2 ·  121 2 = 2 5 · 25 2 = 5 gallons.<!-- End of picture text -->

###### **Section 2.7.1 Exercises** 

**Section 2.8.1 Exercises** 

<!-- Start of picture text -->
1. 1 5 + 3 5 = 4 53. 15 11 + 13 15 + 15 8 = 32 15 = 2 15 255.13 − 13 4 = 13 17. 109 − 117 7 = 98 7 = 149. 10 7 + 6 7 − 11 7 = 10 + 6 7  − 11 = 16  − 7 11 = 7 5<!-- End of picture text -->

###### **Section 2.8.4 Exercises** 

1. LCM is 50 

3. LCM is 150 

5. LCM is 36 

7. LCM is 102 

9. LCM is 72 

11. LCM is 28 

6 

13. LCM is 3<sup>4</sup> _·_ 5<sup>2</sup> _·_ 7<sup>2</sup> _·_ 11 

###### **Section 2.8.6 Exercises** 

1. 5<sup>1+3</sup> 6<sup>=1</sup> 5<sup>_×_</sup> _×_<sup>6</sup> 6 + 6<sup>3</sup> _×_<sup>_×_</sup> 5<sup>5</sup> =<sup>6 + 15</sup> 30 =<sup>21</sup> 30<sup>=</sup> 10<sup>7</sup> LCD = 30 3.<sup>15</sup> 1 _×_<sup>_×_</sup> 3<sup>3</sup> +<sup>2</sup> 3<sup>=47</sup> 3<sup>= 152</sup> 3 LCD = 3 5. 3<sup>2</sup> _×_<sup>_×_</sup> 20<sup>20</sup> +<sup>3</sup> 4<sup>_×_</sup> _×_<sup>15</sup> 15 +<sup>4</sup> 5<sup>_×_</sup> _×_<sup>12</sup> 12 =<sup>133</sup> 60<sup>= 213</sup> 60 LCD = 60 7. 51<sup>17</sup><sup>_−_</sup> 50<sup>3=17</sup> 51<sup>_÷_</sup> _÷_<sup>17</sup> 17 _−_ 50<sup>3=1</sup> 3<sup>_−_</sup> 50<sup>3=1</sup> 3<sup>_×_</sup> _×_<sup>50</sup> 50 _−_ 50<sup>3</sup><sup>_×_</sup> _×_<sup>3</sup> 3 = 150<sup>59</sup> LCD = 150 9.<sup>11</sup> 5 _×_<sup>_×_</sup> 5<sup>5</sup> _−_ 25<sup>2=55</sup> 25<sup>_−_2</sup> = 25<sup>53= 2</sup> 25<sup>3</sup> LCD = 25 11.<sup>3</sup> 2<sup>_×_</sup> _×_<sup>6</sup> 6 _−_ 12<sup>1=18</sup> 12<sup>_−_1</sup> =<sup>17</sup> 12<sup>= 1</sup> 12<sup>5</sup> LCD = 12 13.<sup>11</sup><sup>_×_5</sup> _−_<sup>2</sup><sup>_×_4</sup> =<sup>55</sup><sup>_−_8</sup> =<sup>47</sup> 20 _×_ 5 25 _×_ 4 100 100 LCD = 2<sup>2</sup> _·_ 5<sup>2</sup> = 100 **Section 2.9.1 Exercises** 1. Use LCD = 72. Decreasing order:<sup>4</sup> 9<sup>_,_3</sup> 8<sup>_,_1</sup> 3 5 3. 12<sup>islessthan</sup> 16<sup>7.TheLCDis48.</sup> 5. The price went up. 

**Section 2.9.1 Exercises** 

###### **Section 2.10.2 Exercises** 

1. 2<sup>1</sup> 3 5 3. 14 5. 1<sup>1</sup> 5 

###### **Section 2.10.4 Exercises** 

2 1. 15 7 3. 10 5.<sup>1</sup> 6 

7 

<!-- Start of picture text -->
7. 3 1339. We need 36  ÷  1 1 2 = 36  ÷ 3 2 = 36 1 · 2 3 = 24Answer : 24 of these pieces can be cut.<!-- End of picture text -->

###### **Section 2.11.2 Exercises** 

<!-- Start of picture text -->
1. 1 3 1 + 1 2 = 15 61+0 = 113 + 1 2 = 2 + 3 6 = 5 63. 1 1 5 + 10 = 111 55. 12 1115 − 213 20 = 10 12 112 - 2 = 1011 = 515 − 13 20 = 44  − 60 39 60 = 12 17. 1 2 3 − 1 13 4 = 14 391-1 = 032 − 13 4 = 26  − 39 12 = 14 399. 1 1 7 − 3 7 = 7 8 − 3 7 = 7 511. 3 6 7 − 11 12 = 279 843 - 0 = 3 ; borrow 1 from 3, getting 21 7 6 − 11 12 = 13 7 − 11 12 = 156 84  − 77 = 79 84<!-- End of picture text -->

###### **Section 2.11.4 Exercises** 

1. 9 ft 4 in - 6 ft 7 in = 8 ft 16 in - 6 ft 7 in = 2 ft 9 in 

   - **Answer** : The length of the leftover pieces is 2 ft 9 in. 

3. (a) The total length is 2 hrs 30 min + 2 hrs 15 min + 1 hr 45 min = 5 hrs 90 min = 6 hrs 30 min (6) The average is the total divided by 3. **Answer** : 2 hrs 10 min. 

###### **Section 2.12.1 Exercises** 

<!-- Start of picture text -->
1. 4 3 + 2 3 ÷ 4 9 = 4 3 + 2 3 ÷ ÷ 2 3 × 9 4 ÷ ÷ 3 2 = 3 4 + 2 3 = 3 4 + 6 4 = 9 4 = 21 43. − 2 = 4 1� 43 + 31 2 � 4 − 2 = 21 40 + 3 = 343 + 1 2 = 3 4 + 2 4 = 5 4 = 11 45. 7 1 2 ÷ 3 5 + 17 8 ·  22 5 = 15 2 · 5 3 + 15 8 · 12 5 = 25 2 + 9 2 = 34 2 = 177. The perimeter of a rectangle P = 2 W + 2 L  = 2  ·  1 3 4 + 2  ·  21 2 = 7 2 + 5 = 81 2 ft.<!-- End of picture text -->

8 

#### **ARITHMETIC: A Textbook for Math 01 3rd edition (2012)** 

**Answers to odd numbered exercises for Chapters 3, 4, 5 by Natalia Novak** 

**Section 3.1.1 Exercises** 

1. 19.01 stands for ”nineteen and one hundredth” 

3. 98.6 stands for ”ninety eight and six tenths” 

5. (a) 2<sup>23</sup> 100<sup>= 2</sup><sup>_._23</sup> 237 (b) 1000<sup>= 0</sup><sup>_._237 =</sup><sup>_._237</sup> (c) 19<sup>7</sup> 10<sup>= 19</sup><sup>_._7</sup> 12 (d) 10000<sup>= 0</sup><sup>_._0012</sup> 

###### **Section 3.3.1 Exercises** 

1. 210304 _._ 0900 = 210304 _._ 09 3. 210 _._ 00 = 210 5. 0 _._ 2 _,_ 0 _._ 121 _,_ 0 _._ 009 7. 0 _._ 61 _,_ 0 _._ 5 _,_ 0 _._ 106 

###### **Section 3.4.1 Exercises** 

1. (a) 304.1 (b) 304.09 3. (a) 115.5 (b) 115.5 5. (a) 7 (b) 7.01 

###### **Section 3.5.1 Exercises** 

1. `1 1 680.48 + 56.09 -------736.57` 3. `58.09 - 32.1 --------` 

```
25.99
```

5. `14.093 - 6.39 --------7.703` 

7. `830 - 16.61 -------813.39` 

1 

9. 3.) `1 25.99 + 32.1 -------58.09` 5.) `11 7.703 + 6.39 -------14.093` 7.) `11 1 813.39 + 16.61 -------830.00` 11. 4.6 + 0.07 = 4.67, then 20 - 4.67 = 15.33 **Answer:** 15.33 

###### **Section 3.6.1 Exercises** 

1. 60,804.8 3. 1.9 5. 8.0409 7. 0.0000908 9. 2,608,040,900 11. 0.0483 

###### **Section 3.7.1 Exercises** 

1. `64.8 1 decimal place, x 23 0 decimal places, so the answer should have 1 + 0 = 1 decimal place -----1944 result of multiplying 648 by 23 +1296 result of multiplying 648 by 2 -----14904 then we need to "create" one decimal place, i.e. 1490.4 Answer` 3. `26.09 2 decimal places, x 0.0004 4 decimal places, so the answer has 2+4=6 decimal places --------10436` 

2 

`0000 0000 0000 0000 --------00010436 0.010436 Answer` 5. 100 _×_ 9 _._ 9 = 990 (move decimal point two places to the right) 7. `64.9 1 decimal place, x 0.345 3 decimal places, so the answer has 1+3=4 decimal places --------3245 2596 +1947 --------223905 22.3905 Answer` 

9. 1000 _×_ 0 _._ 053 = 53 

(move decimal point 3 places to the right, remove insignificant zeros) 

###### **Section 3.8.1 Exercises** 

1. 91 _÷_ 20 = 4 _._ 55 Here is the solution: 4 _._ 5 5 20 � 9 1 _−_ 8 0 1 1 0 _−_ 1 0 0 1 0 0 _−_ 1 0 0 0 

3. 23 _÷_ 90 = 0 _._ 25 Here is the solution: 

0 _._ 2 5 5 90 � 2 3 _._ 0 _−_ 1 8 0 5 0 0 _−_ 4 5 0 5 0 0 _−_ 4 5 0 5 0 

5. 6 _._ 02 _÷_ 9 = 0 _._ 668 7. 804 _._ 09 _÷_ 215 = 3 _._ 74, correct to two decimal places 9. 17 _÷_ 19 _≈_ 0 _._ 895, correct to three decimal places 

3 

###### **Section 3.9.1 Exercises** 

1. 680 _._ 4 _÷_ 1 _._ 01 =<sup>680</sup><sup>_._4</sup> = 68040 _÷_ 101 1 _._ 01<sup>=68040</sup> 101 

3. 804 _._ 09 _÷_ 9 _._ 18 = 80409 _÷_ 918 5. 4 _._ 19 _÷_ 0 _._ 5 = 41 _._ 9 _÷_ 5 = 8 _._ 38 Here is the solution: 

<!-- Start of picture text -->
8 . 3 85 � 4 1 . 9− 4 01 9− 1 54 0− 4 00<!-- End of picture text -->

7. 353 _÷_ 2 _._ 5 = 3530 _÷_ 25 = 141 _._ 2 Here is the solution: 

<!-- Start of picture text -->
1 4 1 . 225 � 3 5 3 0− 2 51 0 3− 1 0 03 0− 2 55 0− 5 00<!-- End of picture text -->

###### 9. 29 _._ 997 _÷_ 0 _._ 01 = 2999 _._ 7 _÷_ 1 = 2999 _._ 7 

###### **Section 3.10.1 Exercises** 

1. 43% = 0 _._ 43 (decimal point is moved two places to the left, since 43% =<sup>43</sup> 100<sup>= 0</sup><sup>_._43)</sup> 

3. 56 _._ 04% = 0 _._ 5604 

5. 14 _._ 09 = 1409% (the decimal point is moved two decimal places to the right) 

<!-- Start of picture text -->
7. 1 . 384 = 138 . 4%9. 44% = 100 44 = 11 2511. 0 . 15 = 100 15 = 20 313. 40% = 100 40 = 10 4 = 2 515. 98% = 100 98 = 49 5017. 18% = 100 18 = 50 9<!-- End of picture text -->

4 

19.<sup>1</sup> 6<sup>_≈_0</sup><sup>_._167 = 16</sup><sup>_._7%</sup> 21.<sup>3</sup> 8<sup>= 0</sup><sup>_._375 = 37</sup><sup>_._5%</sup> 1 23. 13<sup>_≈_0</sup><sup>_._077 = 7</sup><sup>_._7%</sup> 5 25. 12<sup>_≈_0</sup><sup>_._417 = 41</sup><sup>_._7%</sup> 

###### **Section 3.11.1 Exercises** 

1. 16% of 75 = 0 _._ 16 _×_ 75 = 12 

3. _._ 05 of 280 = 0 _._ 05 _×_ 280 = 0 _._ 5 _×_ 28 = 14 

<!-- Start of picture text -->
5. 12 % of 248 = 0 . 5% of 248 = 0 . 005  ×  248 = 1.24or1 11 2 2 1 1×  248 = × = 1242 % of 248 = 100 ×  248 = 100 2 ÷ 2 100 × 248 1 ÷ 2 100 = 1 . 241<!-- End of picture text -->

7. Let’s find how much is 5% of her original salary: 0 _._ 05 _×_ 36000 = 5 _×_ 360 = 1800, hence her new salary is $36000 + $1800 = $37800. 

9. If Jose did<sup>7</sup> 8<sup>of the problems correctly,then he got1</sup> 8<sup>of the problems wrong,i.e.he got1</sup> 8<sup>_×_24 = 3</sup> problems wrong. 

###### **Section 4.1.1 Exercises** 

<!-- Start of picture text -->
1. 14 to 4 = 14 4 = 7 23. 56 to 21 = 21 56 = 8 3<!-- End of picture text -->

<!-- Start of picture text -->
255. 2 1 12 = 2512 to 11 4 = 25 12 to 5 4 = 5 12 × 4 5 = 5 347. 1.69 to 2.6 = 1 2 . . 69 6 = 169 260 = 13 26  ×  ×  13  10 = 2  × 13 10 = 20 139. 8 inches to 5 1 2 feet = 8 inches to 11 2 ×  12 inches = 66 8 = 33 4<!-- End of picture text -->

###### **Section 4.2.3 Exercises** 

<!-- Start of picture text -->
1. x  = 5  ·  3 = 1513. y = 5 100  ·  20 = 100 100 = 15. B = 2  ·  11 = 2217. s  = 3 13  ·  4 = 12 13<!-- End of picture text -->

5 

<!-- Start of picture text -->
9. P = 75  ·  100 = 15  ·  100 = 15  ·  4 = 60125 25 1Section 4.3.1 Exercises<!-- End of picture text -->

1. A= 12, P = 20, B = ? 12 = 12 _·_ 5 = 60 **Answer:** 60 _B_<sup>=</sup> 100<sup>20,so</sup><sup>_B_=12</sup><sup>_·_</sup> 20<sup>100</sup> 3. A= 12, P = 40, B = ? 12 = 3 _·_ 10 = 30 **Answer:** 30 _B_<sup>=</sup> 100<sup>40,so</sup><sup>_B_=12</sup><sup>_·_</sup> 40<sup>100</sup> 5. A = 90, B = 300, P = ? 90 =<sup>1</sup><sup>_·_90</sup> = 30 **Answer:** 30% 300<sup>=</sup> 100<sup>_P_,so</sup><sup>_P_=100</sup> 300<sup>_·_90</sup> 3 7. A = ?, B = 600, P = 125 _A_ = 6 _·_ 125 = 750 **Answer:** 750 600<sup>=125</sup> 100<sup>,so</sup><sup>_A_=600</sup> 100<sup>_·_125</sup> 9. A = 250, B = 325, P = ? 250 =<sup>1000</sup> = 75<sup>12</sup> **Answer:** 76 _._ 9% 325<sup>=</sup> 100<sup>_P_,so</sup><sup>_P_=250</sup> 325<sup>_÷_25</sup> _÷_<sup>_·_</sup> 25<sup>100</sup> 13 13<sup>_≈_76</sup><sup>_._9</sup> 11. A= 93, P = 62, B = ? 93 = 150 **Answer:** The team played 150 games _B_<sup>=</sup> 100<sup>62,so</sup><sup>_B_=93</sup><sup>_·_</sup> 62<sup>100</sup> 13. A = 4, 480, B = 56, 000, P = ? 4480 =<sup>448</sup><sup>_·_1</sup> = 8 **Answer:** Her salary increased by 8% 56000<sup>=</sup> 100<sup>_P_,so</sup><sup>_P_=4480</sup> 56000<sup>_·_100</sup> 56 **Section 4.4.1 Exercises** 1. Let’s set up a proportion: 3 4<sup>in.represents14miles.</sup> _x_ in. represent 42 miles. 3 <u>4</u><sup>`in`</sup> One way to set up a proportion (as ratios): _x_ `in`<sup>=</sup> 42<sup>14</sup> `mi`<sup>`mi`,</sup> 3 <u>4</u><sup>`in`</sup> another way (as rates): 14 `mi`<sup>=</sup> 42<sup>_x_</sup><sup>`in`</sup> `mi` Using any of the proportions and cross-produce property, we will get:<sup>3</sup> 4<sup>_·_42 = 14</sup><sup>_x_,</sup> 3 3 3 by dividing both part by 14 we will get: <u>4</u><sup>_·_42</sup> = _x_ , or _x_ = <u>4</u><sup>_·_42</sup> = <u>4</u><sup>_·_42</sup> <u>1</u> =<sup>3</sup><sup>_·_42</sup><sup>_÷_7</sup> _·_ 1 = 14 14 14 4 14 _÷_ 7 1 34 _· ·_ 6 2<sup>=3</sup> 4<sup>_·_</sup> _·_<sup>3</sup> 1<sup>=</sup> 4<sup>9= 21</sup> 4<sup>in</sup> 

**Answer** : The two cities are 2<sup>1</sup> 4<sup>inapartonthemap.</sup> 

6 

3. summary: $2000 earns $48, $ _x_ earns $200. 2000 =<sup>48</sup> or 2000 =<sup>12</sup> or 2000 =<sup>6</sup> so 2000 _·_ 25 = 6 _x_ , and _x_ =<sup>2000</sup><sup>_·_25</sup> , _x_ 200<sup>,</sup> _x_ 50<sup>,</sup> _x_ 25<sup>,</sup> 6 or _x_ =<sup>1000</sup><sup>_·_25</sup> =<sup>25000</sup> _≈_ 8333($) 3 3 **Answer** : Approximately $8333 would need to be invested. 5. summary: 21 `weight of lead` 5<sup>=</sup> `weight of aluminum`<sup>,andabarofaluminum(15lb)</sup> 21 so 21 _·_ 15 = 5 _x_ or _x_ =<sup>21</sup><sup>_·_15</sup> = 63 (lb) 5<sup>=</sup> 15<sup>_x_,</sup> 5 **Answer** : A bar of lead of the same size weighs 63 pounds. 

###### **Section 4.5.1 Exercises** 

<!-- Start of picture text -->
1. Let’s use 1 . 6 or x  = 4 . 8x = 3 1 , so 1 . 6  ·  3 =  x3. Let’s use 1 . 4 so 1 . 4  ·  4 =  x or x  = 5 . 6x = 4 1 ,x5. Let’s use x = 8 or x = 2 or 1 = 2 or x or 4 x4 5 1 5 1 1 · 4 5 = 1 2 5 = 1 2 , so 4 x  = 5  ·  21 14 4 4or x  = 10 4 = 5 2 = 2 . 5x x 5 x7. Let’s use = 8 or = 8 or so 15 x = 12  ·  8 or x = 12  ·  8 =2 2 3 12 3 12 = 8 3 , 155 54  ·  8 = 325 5 = 62 5 = 6 . 4 m.9. summary:6 foot tall man casts 8 foot shadow,32 foot tree casts x foot shadowSo let’s use 6 or 3 so 3 x = 4  ·  32 or x = 4  ·  32 = 128 = 42 28 = 32 x 4 = 32 x , 3 3 3 ft.Answer: The shadow of the tree is 42 2 3 ft long.<!-- End of picture text -->

###### **Section 5.1.1 Exercises** 

<!-- Start of picture text -->
1. (-6) + 19 = 13 (different signs; subtract, choose sign)3. (-34)+(-28) = -62 (same signs; add, keep the sign)5. 5 3 − 4 1 = 1 15 + � 2 � 105-4 = 153 − 1 2 = 10 6 − 10 5 = 10 17. (-1001.36) + 909 = -92.36 (different signs; subtract, choose sign)<!-- End of picture text -->

7 

<!-- Start of picture text -->
9. − 5 + ( − 5) =  − 5 5� 6 � 6<!-- End of picture text -->

11. ( _−_ 11) + 36 = 25. **Answer:** The temperature at noon in Anchorage was 25<sup>_◦_</sup> F 

###### **Section 5.1.3 Exercises** 

<!-- Start of picture text -->
1. − 0 . 0623. − − − 2 =  − 2� � 7 �� 7<!-- End of picture text -->

5. _−π_ + _π_ = 0 

7. ( _−_ 5) + ( _−_ 5) = _−_ 10 9. _−_ 9 _._ 1 + ( _−_ 9 _._ 1) = _−_ 18 _._ 2 

11. 0 + 5 _._ 5 = 5 _._ 5 

###### **Section 5.1.5 Exercises** 

1. 1 + ( _−_ 1) + 1 + ( _−_ 1) + 1 + ( _−_ 1) = 3 + ( _−_ 3) = 0 

<!-- Start of picture text -->
3. 44 + ( − 5 . 5) + 28 . 8 + 36 + ( − 19 . 1) + ( − 8) = 108 . 8 + ( − 32 . 6) = 76 . 25. − 6 3 + 4 3 − 2 1 + 7 6 3 = 5 5� 8 � 4 + � 2 � 8 = 43 4 + 7 8 − � 8 + 21 2 � 8 − 87 8 =  − 32 8 =  − 31 47. 18 . 50 + ( − 21 . 25) + ( − 69 . 95) + 13 . 50 + 79 . 99 + ( − 86 . 50) = 111 . 99 + ( − 177 . 70) =  − 65 . 71<!-- End of picture text -->

9. ( _−_ 8) + 2 + ( _−_ 3) + ( _−_ 5) + 1 + 4 + 9 = 15 + ( _−_ 16) = _−_ 1 _◦_ Therefore, the average temperature for the first week is _−_<sup>1</sup> F. 7 

###### **Section 5.2.1 Exercises** 

1. 7 _−_ 31 = _−_ 24 3. _._ 65 _−_ ( _−_ 6 _._ 4) = 0 _._ 65 + 6 _._ 4 = 7 _._ 05 

5. 68 _._ 6 _−_ ( _−_ 53) = 68 _._ 6 + 53 = 121 _._ 6 7.<sup>1</sup> 5<sup>_−_2</sup><sup>_._2 = 0</sup><sup>_._2</sup><sup>_−_2</sup><sup>_._2 =</sup><sup>_−_2</sup> 

<!-- Start of picture text -->
9. − 87  − ( − 23) =  − 87 + 23 =  − 6411. 5 8 3 − ( − 11) = 163 813. − 2 . 5  − 1 5 4 =  − 2 10 5 − 14 5 =  − 2 10 5 − 1 10 8 =  − 313 10 =  − 4 10 3<!-- End of picture text -->

15. 100<sup>_◦_</sup> C _−_ ( _−_ 5<sup>_◦_</sup> ) C = 105<sup>_◦_</sup> C 

###### **Section 5.3.1 Exercises** 

1. 8 _×_ ( _−_ 6) = _−_ 48 

3. ( _−_ 6) _×_ ( _−_ 9) = 54 

5. 91 _._ 4 _×_ ( _−_ 1) = _−_ 91 _._ 4 

7. ( _−_ 1) _×_ ( _−_ 1) = 1 

8 

9. 6 _._ 5 _×_ ( _−_ 31) = _−_ 201 _._ 5 11. _×_ 0 = 0 � 97 <u>�</u> 13. _−_ 1<sup>6</sup> _−_ 1<sup>1</sup> =<sup>13</sup> � 7 �� 2 � 7<sup>_×_</sup> 2<sup>3=39</sup> 14<sup>= 211</sup> 14 15. 1( _−_ 1) = _−_ 1 17. ( _−_ 3)(0 _._ 5)( _−_ 0 _._ 7)(1) = 3 _×_ 0 _._ 35 = 1 _._ 05 19. ( _−_ 6)( _−_ 5)( _−_ 4)( _−_ 3)(0) = 0 

###### **Section 5.4.2 Exercises** 

1. ( _−_ 24) _÷_ ( _−_ 8) = 3 3. 66 _÷_ 0 = _undefined_ 5. ( _−_ 30) _÷_ 6 = _−_ 5 7.<sup>_−_19</sup> = _undefined_ 0 9 _._ 5 9. _−_ 1 _._ 9<sup>=</sup><sup>_−_5</sup> 11. 0 _÷_ ( _−_ 1000) = 0 13. _−_ 4<sup>1</sup> _÷ −_ 1<sup>7</sup> =<sup>9</sup> _×_<sup>8</sup><sup>_÷_2</sup> =<sup>12</sup> � 2 <u>� �</u> 8 <u>�</u> 2<sup>_÷_15</sup> 8<sup>=</sup> 2<sup>9</sup><sup>_×_</sup> 15<sup>8=9</sup> 2<sup>_÷_</sup> _÷_<sup>3</sup> 2 15 _÷_ 3 5<sup>= 22</sup> 5 15. 100 _÷_ 4<sup>1=100</sup> 1 _×_<sup>4</sup> 1<sup>= 400</sup> 17. _._ 5 _÷ ._ 4 = 0 _._ 5 _÷_ 0 _._ 4 = 5 _÷_ 4 = 1 _._ 25 

**Section 5.5.1 Exercises** 

<!-- Start of picture text -->
1. 8 2 = 8  ·  8 = 643. − 8 2 =  − (8  ·  8) =  − 645. ( − 6) 3 = ( − 6)  ·  ( − 6)  ·  ( − 6) =  − 2167. − 2 = − 2 · − 2 · − 2 =  − 8� 5 �3 � 5 � � 5 � � 5 � 1259. − ( − 2) 4 =  − (( − 2)  ·  ( − 2)  ·  ( − 2)  ·  ( − 2)) =  − 1611. (10) 0 = 1, by definition13. ( − 23) 0 = 1, by definition15. ( − 1) 59 =  − 1 (odd power preserves the sign)17. 2 1 = 5� 2 �2 2 · 2 5 = 25 4 = 61 4<!-- End of picture text -->

**Section 5.6.1 Exercises** 

1. _~~√~~_ 9 = 3, because 3<sup>2</sup> = 9 

9 

3.<sup>_~~√~~_</sup> _−_ 25 = _undefined_ (what should we square to get _−_ 25?) 

<!-- Start of picture text -->
81 √ 815. � 4 = √ 4 = 9 2 = 41 27. √ 100 = 1025 √ 259. − � 36 =  − √ 36 =  − 6 51 √ 111. −� 16 =  − √ 16 =  − 4 1<!-- End of picture text -->

11. The closest numbers to 7 (from the left and from the right) that are ‘extractable’ are 4 and 9, therefore _~~√~~_ 4 _<_ _~~√~~_ 7 _<_ _~~√~~_ 9, or 2 _<_ _~~√~~_ 7 _<_ 3. 

**Answer:** between 2 and 3 

13. _−_ _~~√~~_ 36 _< −_ _~~√~~_ 30 _<_ _~~√~~_ 25, or _−_ 6 _< −_ _~~√~~_ 30 _< −_ 5 

**Answer:** between _−_ 6 and _−_ 5 

15. _~~√~~_ 12 _<_ _~~√~~_ 15 

###### **Section 5.7.1 Exercises** 

<!-- Start of picture text -->
1. 2 a − b  = 2  ·  11  − ( − 5) = 22 + 5 = 273. − 6 x 2 =  − 6  · � − 3 2 �2 =  − 6  · 4 9 =  − 1 6 · 4 9 =  − 6 ÷ 1 3 · 9 ÷ 4 3 =  − 8 3 =  − 22 3<!-- End of picture text -->

5. _a − ab − b_ = ( _−_ 0 _._ 6) _−_ ( _−_ 0 _._ 6) _·_ 0 _._ 8 _−_ 0 _._ 8 = _−_ 0 _._ 6 + 0 _._ 48 _−_ 0 _._ 8 = _−_ 1 _._ 4 + 0 _._ 48 = _−_ 0 _._ 92 

7. ( _d − e_ )( _d_<sup>2</sup> + _ed_ + _e_<sup>2</sup> ) = (( _−_ 1) _−_ ( _−_ 4))(( _−_ 1)<sup>2</sup> +( _−_ 1)( _−_ 4)+( _−_ 4)<sup>2</sup> ) = ( _−_ 1+4)(1+4+16) = 3 _·_ 21 = 63 

9. 2 _pq − q_<sup>2</sup> = 2 _·_ 1 _._ 2 _·_ 2 _._ 3 _−_ 2 _._ 3<sup>2</sup> = 5 _._ 52 _−_ 5 _._ 29 = 0 _._ 23 

<!-- Start of picture text -->
11. � x 2 +  y 2 = + − 1 = 4 16 + 9 = 25 √ 25� � 32 �2 � 2 �2 � 9 + 1 4 = � 36 � 36 = √ 36 = 6 5<!-- End of picture text -->

###### **Section 5.8.1 Exercises** 

1. Area is 4 _._ 8 _×_ 3 _._ 6 = 17 _._ 28 square meters. 

<!-- Start of picture text -->
3. Length of the hypotenuse is � (0 . 3) 2 + (0 . 4) 2 = √ 0 . 09 + 0 . 16 = √ 0 . 25 = 0 . 5 yards.1 √ 1Why is √ 0 . 25 = 0 . 5? Probably easiest to see with fractions: √ 0 . 25 =� 4 = √ 4 = 2 1 = 0 . 5. Ofcourse we can check that (0 . 5) 2 = 0 . 25 too.<!-- End of picture text -->

5. _F_ =<sup>9</sup> 5<sup>_·_22</sup> 1<sup>+ 32 =198</sup> 5 + 32 = 39<sup>3</sup> 5<sup>+ 32 = 713</sup> 5<sup>= 71</sup><sup>_._6.</sup> **Answer:** 22<sup>_◦_</sup> C is 71 _._ 6<sup>_◦_</sup> F. 

7. _A_ = 500(1 + 0 _._ 05)<sup>2</sup> = 500(1 _._ 05)<sup>2</sup> = 500 _·_ 110 _._ 25 = 551 _._ 25. **Answer:** The amount if money in the bank after 2 years is $551.25 

###### **Section 5.9.2 Exercises** 

1. _y_ = 2 is not a solution because 2 + 1 _._ 6 is not equal to 14 _._ 4 

3. _x_ = 19 + 5 = 24 

5. _x_ = 45 _÷_ 9 = 5 

10 

7. _y_ = _−_ 19 

9. _t_ = 0 

11. _y_ = 7 _._ 4 

13. If the number we want is _x_ then we need to solve 12 _x_ = 108. Divide both sides by 12 to get _x_ = 9. **Answer:** The number is 9 

11
