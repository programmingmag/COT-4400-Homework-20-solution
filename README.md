# COT-4400-Homework-20-solution

Download Here: [COT 4400 Homework 20 solution](https://jarviscodinghub.com/assignment/cot-4400-homework-20-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Consider the following algorithm, which correctly solves the Bandersnatch
(BS) problem using a solution to the JubJub (JJ) problem:
Input: data: array of positive integers
Input: n: size of data
Output: Bandersnatch(data)
1 Algorithm: BandersnatchReduction
2 Sort data
3 for i = 1 to n do
4 if JubJub(data) then
5 data[i] = data[n − i] − data[i]
6 else
7 data[i] = data[i] · data[n − i]
8 end
9 Sort data
10 end
11 return data
1. Suppose that BS is NP-Hard and JJ ∈ P. Prove that P = NP or explain
why BandersnatchReduction does not prove P = NP.
2. Suppose that BS ∈ P and JJ is NP-Hard. Prove that P = NP or explain
why BandersnatchReduction does not prove P = NP.

