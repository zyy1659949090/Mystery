# Mystery

Mystery

Description

The Egyptian archeologists have found an old mysterious document that shows the secret key that should be used to open the main room of the largest pyramid. When the linguists translated the old documen t they found that they still have a problem to open the door, because the document itself is a puzzle whose solution will be the secret key. The old puzzle says that the key is consisted of some known integers and it shows the number of each integer in the key. It also mentions that there must be some pairs of letters in the key and the lexical order of the key must be as small as possible. A pair (x, y) of integers is considered to be in a key if there is a y coming after an x in the key. Your task is to help the archeologists to find the proper key.

Input

The input consists of several test cases. In the first line of each test case there are two integers m < 100 and d <= 1000, number of different integers in the key and number of given pairs, then in the next line there are m integers. The U+1th integer is the number of U's in the key . In the next d lines, in each line there is two integers x and y indicating that the pair ( x,y) is in the key. The test case with d=0 indicates the end o f file. If there is no solution for an input case you must report "Impossible!" as the output for this case.

Output

In the output, for each test case except the one with d=0 write the key in a separate line. Each two consecutive integers should be separated by exactly a single space.

Sample Input

3 2
1 0 2
2 0
2 2
0 0
Sample Output

2 0 2
