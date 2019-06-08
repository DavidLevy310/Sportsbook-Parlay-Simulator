# Sportsbook-Parlay-Simulator

### Python script which simulates hypothetical parlay bets and generates a pnl/probability distribution

### Background

#### * This script was written to solve a practice problem I was presented with.

#### * Assume that a sportsbook is taking Parlay bets from customers and a Parlay submission consists of 2 or more choices.

### * There are 5 questions the customer can answer either Yes or No to, or choose not to answer.

#### The Hypothetical Probability of each question/answer occurring is below:

* 1Yes = 50% 1No = 50%

* 2Yes = 20% 2No = 80% 

* 3Yes = 30% 3No = 70%

* 4Yes = 10% 4No = 90%

* 5Yes = 50% 5No = 50%

### Challenge: Build a probability distribution for the sportsbook, with PNL on the x-axis and Probability on the y-axis

#### 1) This script creates a list of all possible parlay submissions and the associated probability of occurring.
#### 2) It then allows you to randomly choose x amount of submissions from the list
#### 3) Based on the submissions chosen and the bet size per parlay, the script will generate a probability distribution for the sportsbook
#### 4) The x-axis is PNL and the y-axis is probability of occurrence

#### Note that if a parlay hits for a customer, they are paid out PROFIT as follows:

#### (1/(Probability parlay wins))*(bet size) - bet size
