# Class4-PythonModule-Week2
## 1.
Write a programme to generate the lucky numbers from the range(n). These are generated starting with the sequence s=[1,2,...,n]. At the first pass, we remove every second element fromthe sequence, resulting in s2. At the second pass, we remove every third element from the sequence s2, resulting in s3, and we proceed in this way until no elements can be removed. The resulting sequence are the numbers lucky enough to have survived elimination. The following example describes the entire process for n=22: <br /><br />
Original sequence: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22]<br />
Remove 2nd elements: [1, 3, 5, 7, 9, 11, 13, 15, 17, 19, 21] <br />
Remove 3rd elements: [1, 3, 7, 9, 13, 15, 19, 21] <br />
Remove 4th elements: [1, 3, 7, 13, 15, 19] <br />
Remove 5th elements: [1, 3, 7, 13, 19] <br />
We cannot remove every other 6th element as there is no 6th element.<br /><br />
**Input>>>** 22 <br />
**Output>>>** Lucky numbers are [1, 3, 7, 13, 19] <br /><br />

## 2.
Write a program that takes two inputs; one of them is a list and the other is a number, and returns the list obtained by shifting the elements in the list n places to the right (left) when n is positive (negative). Use wrap-around: if an element is shifted beyond the end of the list, then continue to shift starting at the beginning of the list. <br /><br />
**Example <br />
Inputs>>>** [1, 2, 3, 4, 5], 2 <br />
**Output>>>** [4, 5, 1, 2, 3] <br />
**Inputs>>>** [1, 2, 3, 4, 5], -2 <br />
**Output>>>** [3, 4, 5, 1, 2] <br /><br />

## 3.
Write a code snippet that inputs a sentence from the user, then uses a dictionary to summarize the number of occurrences of each letter. Ignore case, ignore blanks and assume the user doesnot enter any punctuation. Display a two-column table of the letters and their counts with the letters in sorted order. <br /><br />
**Example <br />
Input >>>** "This is a sample text with several words This is more sample text with some differentwords" <br />
**Output >>>** [('a', 4), ('d', 3), ('e', 10), ('f', 2), ('h', 4), ('i', 7), ('l', 3), ('m', 4), ('n', 1), ('o', 4), ('p', 2), ('r', 5), ('s', 10), ('t', 9), ('v', 1), ('w', 4), ('x', 2)] <br /><br />

## 4.
Write a program that takes in two words as input and returns a list containing three elements, in the following order: <br />
- Shared letters between two words.
- Letters unique to word 1.
- Letters unique to word 2. <br />

Each element of the output should have unique letters, and should be alphabetically sorted. Useset operations. The strings will always be in lowercase and will not contain any punctuation. <br /> <br />
**Example <br />
Input1>>>** "sharp" <br />
**Input2>>>** "soap" <br />
**Output>>>** ['aps', 'hr', 'o']
