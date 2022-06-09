# Module-2-Challenge
## Project Overview
The goal of this project was to analyze the success of a small number of green energy stocks in order to help better inform my friend Steve's clients as to what their best investment choice might be. These clients already own DQ, so note that this is especially a stock of interest. The data is only from two years. The anaylsis only calculates performence for the year being analyzed, and does not compare performance between years, though we can compare the outputs of the years. Performance indicators include totalt daily volume throughout the year as well as the the return of the stock. The return of the stock is defined in this anaylsis as the percentage price increase or decrease of the stock at the end of the year as compared to what it was at the beginning.
## Results
### Comparing Stock Performance Between 2017 and 2018
![2017 Data](https://github.com/bpiffard/Module-2-Challenge/blob/main/Resources/2017%20Output.png)
![2018 Data](https://github.com/bpiffard/Module-2-Challenge/blob/main/Resources/2018%20Output.png)

While two of the stocks continued to show a strong, positive return in 2018, the majority of them showed losses in 2018. The stocks that continued to rise were ENPH and RUN. One stock, TERP, showed a loss on invenstment in 2017 and 2018. Unfortunately for the clients, the DQ stock showed a loss of 62.6% in 2018, when it had gained 199.4% in 2017. Overall, it's likely that the stock was still a relative gain for the clients. It would be best if we did an analysis on the return for the beginning of 2-17 and the end of 2018 to know if, overall, what the return for this investment is. It is unclear is 2018 was bad for the stock market in general, or just green energy stocks.
### Comparing Code Efficiency
Here is the time it took the original data to run:

![2017 Analysis, time spent, original code](https://github.com/bpiffard/Module-2-Challenge/blob/main/Resources/2017%20og%20time%20analysis.png)

![2018 Analysis, time spent, original code](https://github.com/bpiffard/Module-2-Challenge/blob/main/Resources/2018%20og%20time%20analysis.png)

Here is the time it took the refactored data to run:

![2017 Analysis, time spent, refactored code](https://github.com/bpiffard/Module-2-Challenge/blob/main/Resources/2017%20Analysis.png)

![2018 Analysis, time spent, refactored code](https://github.com/bpiffard/Module-2-Challenge/blob/main/Resources/2018%20Anaylsis.png)

The refactored code worked 0.4453125 seconds faster than the original for the 2017 analysis. That is a 80.28% reduction in runtime. This is significant in relative terms for sure, but with this data set, is not much of a practical difference.

The refactored code worked 0.546875 seconds faster than the original for the 2018 analysis. That is a 81.40% reduction in runtime I would interpret this change the same as for the above.

## Summary
### Advantages and Disadvantages of Refactoring
The potential drawbacks of refactoring code is the risk of adding new errors or bugs. It also involves a time investment, that in a business setting, costs moeny in the form of workers' wages. The potential benefits, however are many. The code could be made to run faster. It could be made clearer so that new developers need less time to understand it. By going through the code again, you may identify new bugs. By making your code leaner, and more efficient, it will take less time to make new changes when new needs to be met. Overall, refactoring is generally a good idea, unless the program is not used often and the time it would take is high.
### Refactoring Code and this Project
While refactoring the code did reduce the runtim by quite a lot, percentage wise, the reduction was a fraction of a second. That miniscule amount of time is probably not worth the time it took to refactor. However, if the client, Steve, wanted to use this macro to analyze a more robust dataset, then we might be grateful for having done the work to refactor the code already. Larger datasets take a longer time to go through, so the time saved may end up being significant. Additionally, if something about the data is set up changes, it might be easier to adapt the refactored code rather than the original code.
