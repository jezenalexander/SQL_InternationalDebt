# SQL_InternationalDebt
In this project, I did a short analysis regarding countries' debts using data from The World Bank.

#1
A snipshot of the data.
The first ten rows shows only the debt owed by Afghanistan in different debt indicators.
There are repetitions in the country names because a country is most likely to have debt in more than one debt indicator.
The column indicator_name tells what each indicator code means / the purpose of the debt (i.e. principal repayments, interest repayments, etc.).

#2
Finding the number of distinct countries.
There are 124 countries.

#3
Finding out the distinct debt indicators.
There are 25 indicators listed.
Knowing about these various debt indicators will understand the areas in which a country can possibly be indebted to.

#4
Finding out the country with the highest total debt (debts from all indicators combined).
Highest Total Debt: China with over USD 285 billion.

#5
Finding out the average amount of debt across indicators, listing the result in a descending order.
This gives us a better sense of the distribution of the amount of debt across different indicators.
Found out that Principal repayments on external debt tops the chart of average debt.
An interesting observation in this finding is that there is a huge difference in the amounts of the indicators after the second one. This indicates that the first two indicators might be the most severe categories in which the countries owe their debts.

#6
Finding out country with the highest amount of debt in the category of Principal repayments on external debt, which is the categpry from the top of the list from #6.
The answer is China.

#7
We saw that long-term debt is the topmost category when it comes to the average amount of debt. But is it the most common indicator in which the countries owe their debt?
There are a total of six debt indicators in which all the countries listed in our dataset have taken debt.

#8
Let's change tracks from debt_indicators now and focus on the amount of debt again. Let's find out the maximum amount of debt that each country has. With this, we will be in a position to identify the other plausible economic issues a country might be going through.
