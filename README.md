java c
STA 4001
Stochastic Processes
Fall 2024
Homework 2
Due Oct 8-th Midnight
1.  A total of m white and m blackballs are distributed among two urns, with each urn containing m balls. At each stage, a ball is randomly selected from each urn and the two selected balls are interchanged.  Let Xn denote the number of blackballs in urn 1 after thenth interchange.
(a)  Give the transition probabilities of the Markov chain Xn , n ≥ 0.
(b)  Find the limiting probabilities and show that the stationary chain is time reversible.
2.  Consider a Markov chain {Xn , n ≥ 0} on the state space E = {1, 2, 3} with transition probability matrix given by

Assume that the (initial) distribution of X0 is the uniform. distribution on E. (a)  Calculate P(X3  = 2, X1  = 3).
(b)  Calculate P(X4  = 1, X3  ≠  1, X2  ≠  1|X1  = 1).
(c)  Determine whether a limiting distribution exists for this MC, justifying your answer.  If so, find the limiting distribution.3.  Four people sit at a round table for dinner. As appetizer, they play a game where a ball is passed from one to another as follows. At each round of the game, the person holding the ball will choose at random one of his two neighbors and then pass him the ball. The four people are numbered 1, 2, 3 and 4 in a clockwise order.
(a)  Explain briefly why the successive positions of the ball in the game form. a Markov chain. (b)  Give the transition matrix of the Markov chain.
(c)  Find the communication classes of the chain. (d)  Find the periods of the states of the chain.
(e)  Does the chain have limiting probabilities?
(f)  Mr. Kwok, the person with the number 4, is now holding the ball. Find the expected number of rounds to be played until the ball goes back to him.
4.  A coin is successively flipped and its probability of showing up heads isp  ∈ (0, 1). Let Y1 , Y2 , . . . be the sequence of outcomes. For n ≥ 0, let
Xn  = (Yn+1, Yn+2, Yn+3),
that is thenth triple of consecut代 写STA 4001 Stochastic Processes Fall 2024 Homework 2Python
代做程序编程语言ive outcomes from the flips. The sequence Xn is a Markov chain on the state space
E = {TTT,TTH,THT,HTT,THH,HTH,HHT,HHH}  :=  {1, 2, 3, 4, 5, 6, 7, 8},
where T and H denotes tail and head shown in the flips while the 8 possible states are also numbered from 1 to 8 in the order given above.
In all the calculations, we denote q = 1 − p to simplify the formulas.
(a)  Suppose we just see THH as the last three outcomes.  Determine the probability to observe, after two more flips, the triples THH and HTT.
(b)  Determine the transition matrix of the chain.
(c)  Determine the communication classes of the chain.
(d)  Determine the periods of the states.
(e)  Show that the long run proportions of the eight states in E exist for the chain and determine these proportions.
(f)  The triples appearing in the chain are overlapping for near times: for example by definition the last two flip outcomes {Yn+2, Yn+3} in Xn  are identical to the first two ones in Xn+1 .  We now consider the non-overlapping triples in the sequence as follows:
Y1 Y2 Y3 , Y4 Y5 Y6 , Y7 Y8 Y9 , . . . .
Clearly, the outcomes from these non-overlapping triples are still the eight ones in E.
Show that the long run proportions of the eight states in E from these non-overlapping triples still exist and they coincide with those found in (e).
5.  I have 4 umbrellas, some at home, some in the office.  I keep moving between home and office.  I take an umbrella with me only if it rains.  If it does not rain I leave the umbrella behind (at home or in the office). It may happen that all umbrellas are in one place, I am at the other, it starts raining and must leave, so I get wet.
(a)  If the probability of rain isp, what is the probability that I get wet?
(b)  Current estimates show that p = 0.6 in Edinburgh.  How many umbrellas should I have so that, if I follow the strategy above, the probability I get wet is less than 0.1?

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
