java c
Financial Risk Management
(FINA865-2024V2)
Group Project
Due at 23:59 PM, Wednesday, 02 October 2024
Your assigned index will be emailed to you in due course.
TASKS: Submit Excel Sheet to Canvas.
Preparation steps: [2 marks]
For the assigned index (via emails from the instructor), do the following:
(a) Download the index prices (data type: PI) for the period of 01/01/2024 – 30/06/2024.
(b) Calculate daily index returns using ln(PIt/PIt-1 ). [0.5 mark]
(c) Based on the daily index returns between 01/01/2024 and 30/05/2024, calculate the index’s daily return volatility using an excel function of STDEV.S(). Then, annualize this daily volatility by multiplying it by the  square root of 252. [0.5 mark]
(d) Based on the index price on 01/06/2024 find the index’s options that will expire on 18 September 2024. Choose the following options:
(i) A call and a put with the exercise price (denoted as K2) closest to the current index price (S0).
(ii) A call and a put with the exercise price (K1) of at least 5 points lower than K2.
(iii) A call and a put with the exercise price (K3) of at least 5 points higher than K2.
Download these options’ daily prices (data type: MP) for the entire month of June 2024. [0.5 mark]
(f) Download the U.S. 3-month T-bill’s (RIC: TRFRTBS3M) interest rate (data type: IR) on a daily basis for the June of 2024. This interest rate is already an annualized rate and assumed it is continuously compounded. [0.5 mark]
(g) Each index’s dividend yield will be sent via emails.
(h) Recommended to have the preparation finished before the semester break.
Show all your working and formulas in excel.
Question 1: [7 marks]
Assume that you were on 01/06/2024, use the index price on that date, exercise price K2, time to maturity, interest rate, and the prices of call and put options with K2, do the following:
(1.1.) Check the lower and upper bounds of these options. Note to check if they are European or American options (static data type: OEXT (option expiry type)). [0.5 mark]
(1.2) Check if the P-C parity/relationship of these options hold. If not, explain clearly how to exploit this opportunity. How much profit could you earn at time 0 (i.e., 01/06/2024)? [2 marks](1.3) Use the annualized return volatility calculated before in (c), S0, K2, T, and r estim代 写FINA865-2024V2 Financial Risk ManagementC/C++
代做程序编程语言ate the call and put prices assuming that they are European options. What are the likely reasons that explain the differences between these prices and the market prices you have downloaded? [2 marks]
(1.4) Use the annualized return volatility, S0, K2, T, and r to estimate these options’ prices using a one-step binomial option pricing model. Clearly identify a, u, d, and p. What is the hedge ratio and how do you use it to establish a hedged portfolio on 01/06/2024? [2.5 marks]
Note that although you can use the textbook’s DerivaGem software to check your solution, but you must show your own calculations.
Question 2: [6 marks]
Using the options and their prices downloaded in (d), establish the following strategies on 01/06/2024 and clearly show the payoff and P/L table for each strategy at expiration:
(2.1) A long position in bull spread using put options with K2 and K3. [1.5 marks]
(2.2) A long position in bear spread using call options with K1 and K2. [1.5 marks]
(2.3) A short position in butterfly spread using put options with K1, K2, and K3. [1.5 marks]
(2.4) A short position in straddle with K2. [1.5 marks]
For this question, just assume that these options are European options.
Question 3: [5 marks]
Assume that you were option traders in January 2020 when the early news around a deadly infectious virus spread out. Assume also that you had a perfect foresight about what would happen to the US stock market from February 2020.
(3.1) What option trading strategy would you have employed to exploit the US market situation during February and April 2020? Clearly state the strategy and explain your reasons. [2.5 marks].
(3.2) Would you use the same option strategy for the Chinese stock market during that period? [1.5 marks]
(3.3) With your understanding in (3.1), do you think using a futures or swap contract would provide a similar outcome? Clearly explain your reasons. Note you do not need to do any calculation. [1 mark]
You can go to Yahoo Finance and look at the charts for volatility index VIX (ticker: ^VIX), SP 500 stock index (^GSPC), and Shanghai Stock Market Index (000001.SS) for useful information. Using your projections about the direction and magnitude of market movements to select an appropriate strategy.







         
加QQ：99515681  WX：codinghelp
