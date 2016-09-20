# GBSE
This Project is developed using Java 8 and Junit 4.x version.
.zip file contains whole workspace to fetch in eclipse used as an IDE.
JPMCGbse.jar is an executable jar file .
Command to run jar

Java -jar JPMCGbse

Assumptions made while solving this assignment:
1.  Buying of stock has considered as 1 and selling of a stock is considered as 0 while calculating Weighted Volume Stock price and Geometric Mean.
2.  Buying quantity and corresponding price are being added and selling quantity and corresponding amount are being deducted for Weighted Volume stock price.
3.  Assumption has been taken that user can only sell those stocks which are bought.
4.  for fast calculation, I have taken key of trading map as Nano seconds so that every trade can be recorded and Weighted Volume stock price can be calculated for any length of time.
5.  For calculating Geometric mean, I have used Log base 10.
6.  For PE Ration, I have assumed dividend=dividend Yield in formula as in assignment, only dividend was mentioned.
    And for stocks which do not have any dividend, will get PE Ratio as 0.00.
7.  For Dividend Yield, I have taken care only one dividend either Fixed or Last in the formula.

Test cases covers only services which are actually taking care of business logic. In Further enhancement, we can expose these as REST services as well.




