# Interpreting Financial Statements

## Short Selling

Shorting. Short sale. Going short. Short selling.

1. Borrow stocks
2. Sell the stocks
3. Wait for the price to go down
4. Buy the stocks at a lower price 
5. Give the stocks back to the owner 
6. Profit

There are two types of short selling: naked and covered.  
Naked short selling means to sell the stock without borrowing (need permissions).  
It also naturally happens due to discrepancies between electronic and paper trading.  
It exacerbates short squeezes by allowing for additional shorting that would otherwise not exist.

The mutual fund (MF) lending is done via a repurchase agreement (called "repo").  
So MF A sells its shares to MF B and asks it to resell it back to him after 1 week with interest.  
Meanwhile, since MF B actually bought the shares, it is the owner of the shares, and can do anything with it.

## NASDAQ (National Association of Security Dealers Automated Quotations)

NASD = National Association of Securities *Dealers*  
FINRA = Financial Industry Regulatory Authority  
NASD has become FINRA.  
SEC = Securities and Exchange Commission

NASDAQ started in 1971 as a subsidiary of the NASD, now known as the FINRA, because the SEC urged them to automate  
the market for securities not listed on an exchange.  
In 2008, NASDAQ merged with the scandinavian exchange group OMX. Today more than 5_000 stocks are listed on NASDAQ,
including those listed in NYSE.

## Derivatives

Derivative is a financial contract whose value depends on some underlying security, asset or a benchmark.  
This contract can be traded on an exchange or OTC (Over The Counter).

Some derivative instruments include:
- options
- futures
- swaps
- Collateralized Debt Obligations (CDOs)

Every derivative contract has a "strike price" and an expiration date. This value of the underlying asset will change
in the time period, but the strike price won't. You can exercise the derivative at any time before the expiration date.

### Options

Ok, so first, there are two types of options: a call option and a put option.
- Call: the holder has a right, but not an obligation, to buy the security at the strike price.
- Put: the holder has a right, but not an obligation, to sell the security at the strike price.

Now you can either be an option buyer or an option seller (also called an option writer).  
So when do you do what?

Firstly, you go into options only because of easy leverage.

- If you're feeling bullish. 
  - Buy a call option.
    - You can buy the security at $50 within 1 week.
    - The price goes to $70.
    - The option is in-the-money (ITM).
    - You buy the security at $50 from the option seller, and sell it on the market for $70.
  - Or, sell a put option.
    - You pocket the premium.
    - The buyer gets to sell the security to you at $50 within 1 week.
    - The price never rises, and the buyer never exercises its put option.
    - The option remains out-of-the-money (OTM).

- If you're feeling bearish.
  - Buy a put option.
    - You can sell the security at $50 within 1 week.
    - The price goes to $30.
    - The option is in-the-money (ITM).
    - You buy the security at $30 from the market, and sell it to the option seller for $50.
  - Or, sell a call option.
    - You pocket the premium.
    - The buyer gets to buy your stock at $50 within 1 week.
    - The price never rises, and the buyer never exercises its call option.
    - The option remains out-of-the-money (OTM).

That's that.

If the broker fails to return the borrowed stocks, his name will go into the SEC's Failure-To-Deliver (FTD) list.  
Sometimes brokers go into the FTDs even when they can arrange the stock to profit from a Bear market.  
How?
- They have to give you back the stock.
- The price is falling.
- So, why give you the stock I hold right now?
- I sell the stocks I own, call into the FTD, and wait for the price to drop.
- When I'm satisfied with the price, I buy the stocks back and give it to you.
- I pocket the profit.

Then what happens when a broker goes into FTD list?  
Well, what happened during the 2008 financial crisis?

### Futures

A derivative contract to buy or sell security at the future specified date, at the specified price.  
Unlike options, this is an obligation.  

### Swaps

A derivative contract through which two parties can exchange cash flows or liabilities from two different financial
instruments.
I have a use case.
- Suppose you open a new Company.
- The credit rating of your new Company is low.
- You need a loan, and you're getting it at a variable interest rate.
- You don't want this speculation.
- You find a Company that got a fixed-rate loan, and you swap the interest rates.
- Now why would that Company swap?
- Because that Company is expecting that the interest rates will fall off in the future.

### The London Interbank Offered Rate (LIBOR)

It was the benchmark interest rate for short-term loans between major global banks in the world from 1986 to 2023.  
This in turn affected every other interest rate in the countries.

The rate was calculated and published each day by "The Intercontinental Exchange" (ICE).  
ICE is the parent company of the "New York Stock Exchange" (NYSE) and a couple of dozen other exchanges and markets
around the world.  
"The ICE Benchmark Administration" (IBA) is a unit of ICE and is the actual administrator of LIBOR.

ICE took over the administration of LIBOR from "The British Bankers Association" (BBA) in early 2014.  
The entire LIBOR system ceased to be used at the end of June 2023 and was replaced with other benchmarks such as the
"The Sterling Overnight Index Average" (SONIA).

### The Sterling Overnight Index Average (SONIA)

It is the benchmark interest rate used in the United Kingdom, administered by "The Bank Of England" (BOE).  
It is used to fund trades that occur overnight during the off-hours.  
Thus, it represents the depth of overnight business in the marketplace.

## Capitalizing Fixed Charges

If I can afford to pay $100,000 of fixed charges annually, and the prevailing interest rate is 4%, then I can raise
($100,000 / 4% = $25,00,000) of debt or some other instrument.

## Promissory Notes

Written promises by one party to pay another party a fixed amount, either on demand or at a future date.
It's negotiable as it does not have the name of the promisee, only the signature of the promisor.

The Indian Law System has a hard cap on the amount and validity of a promissory note.
Three years.  
I have downloaded a book on Negotiable Instruments Act.

There is another convention that governs the international trade regarding promissory notes, called 
"The 1930 Geneva Convention of Uniform Law on Bills Of Exchange and Promissory Notes."  
I have also downloaded some data on it.

The appeal of promissory notes is that they're simple, inexpensive and easy, but also legally enforceable. 
Universities make students sign a 10-year-long recurrent promissory note for student loans.

## Broker-dealer

If you want to buy stocks, you must open your brokerage account with a broker.
When you want to buy the stock, you tell your broker to go and buy it.
Similarly, when you want to sell, you tell your broker to sell it for you.
The broker is acting on your behalf, so he is your "agent" (broker is also called agent).
The broker will charge you a commission per trade.

Brokers are of two types:
- full-service brokers, for one-on-one personal service, and 
- discount brokers, those who provide trade execution like online brokers (Groww).

While brokers work for clients, the dealers work for themselves.  
Dealers are also called "Market Makers," because they simultaneously declare the buy (bid price) and sell price 
(offer price) of securities. They do this in what's called a "dealer market." They increase liquidity in the market.

Imagine a person holding a home and willing to sell it for $5 million. Another person wants to buy the home, 
but at $4 million. It's not possible. But then comes a third party (dealer) who declares that he'll buy the house for 
$4.5 million and sell it for $4.7 million in the dealer market profiting on the $0.2 million (called the bid-ask spread, 
which is similar to scalping, which means profiting from small price changes).

The homeowner may sell the house for $4.7 million thinking it's good enough. Hence, the price moved down where it 
originally would not have. The seller will never agree to $4 million, considering it too low. The seller and the buyer
would think that these are third-party people, and would probably value the security at its right price.

This also happens with stocks in the primary market, but there are other securities out there that don't sell on the 
stock market.

NASDAQ is a dealer market.

Take another example, suppose you have a security that you want to exit, but is not finding a buyer.
It could happen that you find the dealers in the dealer market.
They are willing to buy the security at the price lower than what you want, but not too low.
So you sell to the dealer, and now it's a dealer's headache to find a buyer.
