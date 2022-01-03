GNU Octave, version 6.4.0
Copyright (C) 2021 The Octave Project Developers.
This is free software; see the source code for copying conditions.
There is ABSOLUTELY NO WARRANTY; not even for MERCHANTABILITY or
FITNESS FOR A PARTICULAR PURPOSE.  For details, type 'warranty'.

Octave was configured for "x86_64-w64-mingw32".

Additional information about Octave is available at https://www.octave.org.

Please contribute if you find this software useful.
For more information, visit https://www.octave.org/get-involved.html

Read https://www.octave.org/bugs.html to learn how to submit bug reports.
For information about changes from previous versions, type 'news'.

>> 3-2.5*8
ans = -17
>> 1=2
error: parse error:

  invalid constant left hand side of assignment

>>> 1=2
     ^
>> 1==2
ans = 0
>> 1==1
ans = 1
>> 1~=2
ans = 1
>> 1~=2 #not equal
ans = 1
>> 1 && 0
ans = 0
>> 1 && 0 #AND operation
ans = 0
>> 1 || 0
ans = 1
>> 1 || 0 #OR operation
ans = 1
>> xor(1,0) #XOR operation
ans = 1
>> xor(1,0) #XOR operation

ans = 1
>> PS('>>')
error: 'PS' undefined near line 1, column 1
>> PS('>> ')
error: 'PS' undefined near line 1, column 1
>> PS1('> ')
> a=3
a = 3
> a=3; #semicolon suprresses print statement
> b = 'hi'
b = hi
> c = (3<=1)
c = 0
>
> c
c = 0
> a #print statement
a = 3
> disp(b)
hi
> disp(c) #display statement
0
> disp(sprintf('2 decimals: %0.2f', a))
2 decimals: 3.00
> disp(sprintf('2 decimals: %0.2f', a)) #sprintf generates string as per defined criteria wi
thin it
2 decimals: 3.00
> disp(sprintf('2 decimals: %0.2f', a)) #%0.2f defines a to be a 2 decimal places value
2 decimals: 3.00
> disp(sprintf('2 decimals: %0.3f', a))
2 decimals: 3.000
> disp(sprintf('2 decimals: %0.2f', a)) #%0.3f defines a to be a 3 decimal places value
2 decimals: 3.00
> a
a = 3
> format long #sets datatype to long
> a
a = 3
> format long a
error: format: unrecognized format state 'a'
> format long
> a
a = 3
> format int
error: format: unrecognized format state 'int'
> format integer
error: format: unrecognized format state 'integer'
> format short
> a
a = 3
> a = 3.149
a = 3.1490
> format long
> a
a = 3.149000000000000
>
>
> #vectors and matrices
> MAT A = (1,2),(3,4),(5,6)
error: parse error:

  syntax error

>>> MAT A = (1,2),(3,4),(5,6)
                    ^
> MAT A = [1 2; 3 4; 5 6]
error: parse error:

  syntax error

>>> MAT A = [1 2; 3 4; 5 6]
                    ^
> MAT A = [1 2;3 4;5 6]
error: parse error:

  syntax error

>>> MAT A = [1 2;3 4;5 6]
                   ^
> A = [1 2;3 4;5 6]
A =

   1   2
   3   4
   5   6

> A = [1 2;
3
4 5]
error: vertical dimensions mismatch (1x2 vs 1x1)
> A = [1 2;
3 4;
5 6}
error: parse error:

  syntax error

>>> 5 6}
        ^
> A = [1 2;
3 4;
5 6]
A =

   1   2
   3   4
   5   6

> #vector example
> v = 1,2,3
v = 1
ans = 2
ans = 3
> v = [1,2,3]
v =

   1   2   3

> v = [1;2;3]
v =

   1
   2
   3

> v = [1:0.1:2]
v =

 Columns 1 through 4:

   1.000000000000000   1.100000000000000   1.200000000000000   1.300000000000000

 Columns 5 through 8:

   1.400000000000000   1.500000000000000   1.600000000000000   1.700000000000000

 Columns 9 through 11:

   1.800000000000000   1.900000000000000   2.000000000000000

>
>
>
