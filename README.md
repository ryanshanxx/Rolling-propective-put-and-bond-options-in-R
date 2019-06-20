# Rolling-propective-put-and-bond-options-in-R
Via Monte-Carlo Simulation

1.	Portfolio Strategies – Rolling Protective Put
    Simulate the returns to the strategy over an investment horizon of one year.
    a. Simulation parameters are as follows:  
       Discretize using the log-normal approximation using a monthly grid over one year. Simulate for two different levels of drift            (8% and 12%) and for two different levels of volatility (20% and 30%).

    b. Option parameters are as follows:
      The strategy uses 3-month options rolled over every month, i.e. you will buy a three-month option and sell it at the end of one           month when the option has two-months remaining for expiration. The strike price is always a constant proportion of stock price.           Simulate for two different levels of the strike: 5% in-the-money and 5% out-of-the-money. Use the Black-Scholes model to                 calculate the value of the options. Assume that the risk free rate is 2%.

    c. In calculating returns, assume that the initial investment is equal to the initial value of the stock. The purchase of puts will          be financed by borrowing at the risk-free rate.  Any excess cash received from puts will also be invested at the risk free rate.

2.	Given the following term structure:
    Maturity		Yield
    1 year			1.0%
    2 year			2.0%
    3 year			2.5%
    4 year			3.0%
    5 year			3.25%
Determine the value of a 5-year bond with a face value of 100 and a coupon rate of 6% per year. Calculate the price of a 1-year option to call the bond at face value.  Calculate using simulations under the Ho-Lee and Vasicek framework.

