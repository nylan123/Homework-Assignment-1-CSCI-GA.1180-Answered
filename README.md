# Homework-Assignment-1-CSCI-GA.1180-Answered
email: jarviscodinghub@gmail.com

https://jarviscodinghub.com/product/homework-assignment-1-csci-ga-1180-answered/

Exercise 1.1. In each part, give a specific numerical example of a 2 × 2 matrix such that every one of its
elements is a nonzero integer, and such that the matrix satisfies the given conditions. Explain how you found
each answer.
(a) A2 = −I, where I is the identity matrix;
(b) B2 = 0, where 0 is the zero matrix;
(c) CD = −DC, with CD 6= 0.
Exercise 1.2. If A and B are nonsingular, prove that their product AB is nonsingular. (Do not use
determinants.)
Exercise 1.3. Let
A =


1 8 7
2 10 8
3 12 9

 .
Confirm that the three columns of A (a1, a2, and a3) are linearly dependent by expressing a3 as a linear
combination of a1 and a2, i.e.,
a3 = λ1a1 + λ2a2, so that a3 − λ1a1 − λ2a2 = 0,
where λ1 and λ2 are scalars. Give the numerical values of λ1 and λ2 and explain how you found them.
Exercise 1.4. Let A be an n × n real matrix. Prove that there is a unique n-vector x satisfying Ax = b for
any nonzero n-vector b if and only if the only solution of Ay = 0 is y = 0. (Prove both the “if” and “only
if” results.)
Exercise 1.5.
(a) If A has linearly independent columns and Ax = Ay for vectors x and y, show that x = y. (This result
implies that we can “cancel” a matrix with linearly independent columns appearing on the left of both
sides of an equation.)
2
(b) Give a specific numerical example where A has linearly independent rows and Ax = Ay, but x 6= y.
(The contrast between parts (a) and (b) emphasizes the differing roles of rows and columns in matrix
multiplication.)
Exercise 1.6. If A is m × n and has rank m, what does this imply about the relative sizes of m and n?
Explain.
Exercise 1.7. Fredholm’s alternative1
is a famous result that can be expressed in the form of a theorem of
the alternative as follows: given any matrix A and vector b of appropriate dimensions, precisely one of the
following two relations is true:
(1) there exists a vector x such that Ax = b, or
(2) there exists a vector y such that AT y = 0 and y
T
b 6= 0.
Show that condition (1) and condition (2) are contradictory, i.e., they cannot both be true.
Exercise 1.8. For a given nonzero m × n matrix A and nonzero m-vector x, assume that x may be written
as x = xR + xN , where xR is a linear combination of the columns of A, i.e., x lies in the range of A, and
AT xN = 0, i.e., xN is in the null space of AT
. (The vector xR is called the range-space portion of x [with
respect to A], and xN is called the null-space portion of x.)
(a) Show that x
T
RxN = 0.
(b) Show that xR and xN are unique.
(c) If xR and xN are both nonzero, show that they are linearly independent.
Exercise 1.9.
(a) Let C be a given m × n matrix with full column rank, and let d be a given m-vector. If there is a
solution x to the linear system Cx = d (i.e., if the system is compatible), show that x is unique.
(b) Use part (a) and the uniqueness of the decomposition of b into its range- and null-space portions to
show that if A is an m×n matrix with rank m, then the system Ax = b is compatible for every b ∈ ℜm.
(Which means that every b ∈ ℜm lies in the range of A.)
(c) Construct a 2 × 4 matrix A and a 2 × 1 right-hand side vector b to show that the result of part (b)
may not be true if the columns of A are linearly dependent.
Exercise 1.10.
(a) Give a 2 × 5 matrix A such that (i) rank(A) = 2 and (ii) the 2 × 2 submatrix consisting of the first 2
columns of A has rank 1. Explain how you constructed A, and confirm numerically that properties (i)
and (ii) hold.
(b) Give a nonzero 2-vector b such that b lies in the range of A (i.e., b can be written as a linear combination
of the columns of A), and explain how you constructed b.
(c) Is it possible to find a 2-vector b that does not lie in the range of A? Explain your answer.
(d) Find a vector c that does not lie in the range of AT
. Explain how you chose c.
1Erik Ivar Fredholm, 1866–1927, from Sweden.
