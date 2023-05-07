Download Link: https://assignmentchef.com/product/solved-fin5330-exam-1
<br>
<ul>

 <li>Replicate the pairs trading results in the paper <em>Illuminating the Profitability of Pairs Trading: A Test of the Relative Pricing Efficiency of Markets for Water Utility Stocks.</em></li>

 <li>Use the historical data in the accompanying file <em>csv</em>.</li>

 <li>Use the BIC criteria for the number of lags to use in all ADF tests. Consider a max number of lags equal to 10.</li>

 <li>Submit your work as either a Jupyter Notebook with Python code or an R Markdown notebook with R code.</li>

</ul>

<strong>Update: </strong>March 22, 2019

<ul>

 <li>I decided that you could take another month trying to get the exact replication of the paper’s trading strategy implementation. I don’t want you to spin your wheels on a lost cause. So here is what I want you to do instead.</li>

 <li>Estimate equation (6) in the paper for each of your pairs. Then form the residuals as outlined (see equations (7) and (8) in the paper).</li>

 <li>Esimate <em>σ </em>from the estimated residuals.</li>

 <li>Calculate the upper and lower bounds for the trading rules as:</li>

</ul>

UpperBound = +1<em>.</em>0 <em>∗ δ<sub>i</sub>σ</em>ˆ

LowerBound = <em>−</em>1<em>.</em>0 <em>∗ δ<sub>i</sub>σ</em>ˆ

<ul>

 <li>for <em>i </em>= <em>{</em>1<em>,</em>2<em>,</em>3<em>} </em>and <em>δ </em>= <em>{</em>0<em>.</em>25<em>,</em>0<em>.</em>5<em>,</em>0<em>.</em>75<em>} </em>as in the paper.</li>

 <li>Make three time series graphs with the residuals plotted against the upper and lower bounds for each <em>δ<sub>i</sub></em>.</li>

 <li>Fill in the following table with the number of buy and sell signals for each trading rule:</li>

</ul>

<em>δ<sub>i                 </sub></em>Buy Signals        Sell Signals

<ul>

 <li>Explain what a <em>buy signal </em>and a <em>sell signal </em>means in the context of pairs trading.</li>

 <li>For example, identify the first buy and the first sell signals for the <em>δ</em><sub>1 </sub>= 0<em>.</em>25 trading rule and interpret them both qualitatively and quantitatively. How many days is each position held for? What the return on the trade?</li>

</ul>

1