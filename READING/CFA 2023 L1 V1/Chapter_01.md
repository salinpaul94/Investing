# Chapter 1

## THE TIME VALUE OF MONEY

### LEARNING OUTCOMES

**The reader should be able to:-**

- Interpret interest rates as required rates of return, discount rates, or opportunity costs.
- Explain an interest rate as the sum of a real risk-free rate and premiums that compensate investors for bearing distinct types of risk.
- Calculate and interpret the future value **(FV)** and present value **(PV)** of a single sum of money, an ordinary annuity, an annuity due, a perpetuity (PV only), and a series of unequal cash flows.
- Demonstrate the use of a time line in modeling and solving time value of money problems.
- Calculate the solution for time value of money problems with different frequencies of compounding.
- Calculate and interpret the effective annual rate, given the stated annual interest rate and the frequency of compounding.

### INTRODUCTION

- As individuals, we often face decisions that involve saving money for a future use, or borrowing money for current consumption.
- We then need to determine the amount we need to invest, if we are saving, or the cost of borrowing.
- As investment analysts, much of work also involves evaluating transactions with present and future cash flows.
- When we place a value on any security, for example, we are attempting to determine the worth of stream of future cash flows.
- **To carry out all the above tasks accurately, we must understand the mathematics of time value of money problems.**
- _Money has time value in that individuals value a given amount of money more highly the earlier it is received._
- > [!IMPORTANT]
  > Therefor, a smaller amount of money now may be equivalent in value to a large amount received at a future date.
- > [!NOTE]
  > The **time value of money** as a topic in investment mathematics deals with equivalence relationships between cash flows with different dates.
- **Mastery of time value of money concepts and techniques is essential for investment analysis.**

### INTEREST RATES

- [ ] Interpret interest rates as required rates of return, discount rates, or opportunity costs
- [ ] Explain an interest rate as the sum of a real risk-free rate and premiums that compensate investors for bearing distinct types of risk

In this section a brief explanation of the meaning and interpretation of interest rates is covered.

- Time value of money concerns equivalence relationships between cash flows occurring on different dates.
- The idea of equivalence relationships is relatively simple.

  - Consider the following exchange:
  - You pay \$10,000 today and in return receive \$9,500 today.
    - Would accept this arrangement? **Not Likely**.
  - But what if you received the \$9,500 today and paid the \$10,000 one year from now?
  - Can these amounts be considered equivalent?
  - Possibly, because a payment of \$10,000 a year from now would probably be worth less to you than a payment of \$10,000 today.
  - **It would be fair, therefore, to discount the \$10,000 received in one year; that is, to cut its value based on how much time passes before the money is paid.**
  - An **Interest rate**, denoted **r**, is a rate of return that reflects the relationship between differently dated cash flows.
  - > [!IMPORTANT]
    > If \$9,500 today and \$10,000 in one year are equivalent in value, then \$10,000 - \$9,500 = \$500 is the required compensation for receiving \$10,000 in one year rather than now.
  - > [!NOTE]
    > The interest rate - the required compensation stated as a rate of return - is \$500 / \$9,500 = 0.0526 or 5.26 percent.

- Interest rates can be thought of in three ways.
  - [ ] First, they can be considered required rates of return - that is, the minimum rate of return an investor must receive in order to accept the investment.
  - [ ] Second, interest rates can be considered discount rates.
    - 5.26 percent is that rate at which we discounted the \$10,000 future amount to find its value today.
    - Thus we use the terms **"interest rate"** and **"discount rate"** almost interchangeably.
  - [ ] Third, interest rates can be considered opportunity costs.
  - > [!NOTE]
    > An **opportunity cost** is the value that investors forgo by choosing a particular course of action. In the example, if the party who supplied \$9,500 had instead decided to spend it today, he would have forgone earning 5.26 percent on the money. So we can view 5.26 percent as the opportunity cost of current consumption.
- Economics tells us that interest rates are set in the marketplace by the forces of supply and demand, where investors are suppliers of funds and borrowers are demanders of funds.
- **Taking the perspective of investors in analyzing market-determined interest rates, we can view an interest rate "r" as being composed of a real risk-free interest rate plus a set of four premiums that are required returns or compensation for bearing distinct types of risk:-**

> r = Real risk-free interest rate + Inflation premium + Default risk premium + Liquidity premium + Maturity Premium

- [ ] The **real risk-free interest rate** is the single-period interest rate for a completely risk-free security if no inflation were expected.
  - In economic theory, the real risk-free rate reflects the time preferences of individuals for current versus future real consumption.
- [ ] The **inflation premium** compensates investors for expected inflation and reflects the average inflation rate expected over the maturity of the debt.
  - Inflation reduces the purchasing power of a unit of currency - the amount of goods ans services one can but with it.
  - The sum of the real risk-free interest rate and the inflation premium is the **normal risk-free interest rate**.
  - Many countries have governmental short-term debt whose interest rate can be considered to represent the nominal risk-free interest rate in that country.
  - **The interest rate of a 90-day US Treasury bill (T-bill), for example, represents the nominal risk-free interest rate over that time horizon.**
- [ ] The **default risk premium** compensates investors for the possibility that the borrower will fail to make a promised payment at the contracted time and in the contracted amount.
- [ ] The **liquidity premium** compensates investors for the risk of loss relative to an investment's fair value if the investment needs to be converted to cash quickly.
  - US T-bills, for example, do not bear a liquidity premium because large amounts can be bought and sold without affecting their market price.
  - Many bonds of small issuers, by contrast, trade infrequently after they are issued; the interest rate on such bonds includes a liquidity premium reflecting the relatively high costs (including the impact on price) of selling a position.
- [ ] The **maturity premium** compensates investors for the increased sensitivity of the market value of debt to a change in market interest rates as maturity is extended, in general (holding all else equal).
  - The difference between the interest rate on longer-maturity, liquid Treasury debt and that on short-term Treasury debt reflects a positive maturity premium for the longer-term debt (and possibly different inflation premiums as well).

### FUTURE VALUE OF A SINGLE CASH FLOW

> - Calculate and interpret the future value (FV) and present value (PV) of a single sum of money, ans ordinary annuity, an annuity due, a perpetuity (PV only), and a series of unequal cash flow.
> - Demonstrate the use of a time line in modeling and solving time value of money problems

- In this section an introduction to time value associated with a single cash flow or lump-sum investment.
- We describe the relationship between an initial investment or **present value (PV)**, which earns a rate of return (the interest rate per period) denoted as **"r"**, and its **future value(FV)**, which will be received _"N"_ years or periods from today.
  > For example you invest \$100 (PV = \$100) in an interest-bearing bank account paying 5 percent annually. At the end of the first year, you will have the \$100 plus the interest earned, 0.05 x \$100 = \$5, for a total of \$105. To formalize this one-period example, we define the following terms.

> - PV = present value of the investment
> - FV<sub>_N_</sub> = future value of the investment _N_ periods from today
> - _r_ = rate of interest per period
> - For _N_ = 1, the expression for the future value of amount PV is
>   FV<sub>1</sub> = PV(1 + _r_)
>   For this example, we calculate the future value one year from today as FV<sub>1</sub> = \$100(1 + 0.5) = \$105.

- If you invest for 2 year with 5% interest then in first year you will make \$5 as interest next year the interest to be paid will be calculated on \$105, which is \$5.25.
- At the end of second year you will have \$100 capital + \$5 + \$5 interest + \$0.25 compound interest.
- Although the interest earned on the initial investment is important, for a given interest rate it is fixed in size from period to period.
- \*\*The compound interest earned on reinvested interest is a far more powerful force because, for a given interest rate, it grows in size each period.
- For example \$100 invested today would be worth about \$13,150 after 100 years if compounded annually at 5 percent, but worth more than \$20 million if compounded annually over the same time period at a rate of 13 percent.
  > We need a general formula to handle compounding for any number of periods. The following general formula relates the present value of an initial investment to its future value after N periods:
  > FV<sub>N</sub> = PV(1 + _r_)<sup>N</sup>
  > where
  >
  > - _r_ = stated interest rate per period
  > - _N_ = number of compounding period
  >   In bank example FV<sub>2</sub> = \$100(1 + 0.05)<sup>2</sup> = \$110.25

> [!IMPORTANT]
> The stated interest rate, _r_, and the number of compounding periods, _N_, must be compatible i.e., both should be expressed in same time period. If _r_ is per year then _N_ should be also in Year

### NON-ANNUAL COMPOUNDING (FUTURE VALUE)

> - Calculate the solution for time value of money problems with different frequencies of compounding.

- Many banks offer a monthly interest rate that compounds 12 times a year.
- In such an arrangement, they pay interest on interest every month.
- Rather than quote the periodic monthly interest rate, financial institutions often quote an annual interest rate that we refer to as the **stated annual interest rate** or **quoted interest rate**.
- _r<sub>s</sub>_ is the stated annual interest.

- With more than one compounding period per year, the future value formula can be expressed as
  > FV<sub>N</sub> = PV(1 + (_r<sub>s</sub>_/_m_))<sup>_mN_
  >
  > - _r<sub>s</sub>_ = stated annual interest rate
  > - _m_ = number of compounding per year
  > - _N_ = number of years
  > - _r<sub>s</sub>/m_ = the stated annual interest rate divided by the number of compounding periods per year.
  >   [!Note]
  >   The periodic rate _r<sub>s</sub>/m_, and the number of compounding periods, _mN_, must be compatible.
