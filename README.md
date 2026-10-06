This repo contains data files that have a list of values of x and y that form a palindrome prime of the below form, with x upto 10000. 
Form : N(x,y)=10^x + 10^(x-y) + 12345678987654321*10^(x/2-8) + 10^y + 1 where x is an even number and 1 <= y <= x/2-9.
Example :  For x=40 and y = 3,  N(40,3)= 10^40 + 10^(37) + 12345678987654321*10^(12) + 10^3 + 1 = 10010000000012345678987654321000000001001, a palindrome prime.
