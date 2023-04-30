Download Link: https://assignmentchef.com/product/solved-mfe409-homework-5-var-for-option-on-two-underlying
<br>
<h2>1         VaR for option on two underlying</h2>

<ol>

 <li>We are interested in managing the risk of an option on two stocks withprices <em>S</em><sub>1<em>,t </em></sub>and <em>S</em><sub>2<em>,t</em></sub>. Assume a short rate <em>r </em>and:</li>

</ol>

where all the parameters are in daily units. Call <em>M</em>(<em>S</em><sub>1<em>,t</em></sub><em>,S</em><sub>2<em>,t</em></sub>) the price of the option. <em>Derive a formula for the 99%-VaR for the option using the delta approach.</em>

<ol start="2">

 <li><em>Derive a formula for the 99%-VaR for the option using the delta-gamma approach.</em></li>

 <li>Consider the case of a European option on the minimum of the two stockprice, with maturity <em>T </em>and final payoff:</li>

</ol>

<em>M<sub>T </sub></em>= max(min(<em>S</em><sub>1<em>,T</em></sub><em>,S</em><sub>2<em>.T</em></sub>) − <em>K,</em>0)

From Stulz (1982) (attached paper), the price of the option when the time to maturity is <em>τ </em>is:

1

where

and N<sub>2 </sub>(<em>α,β,θ</em>) is the bivariate cumulative standard normal distribution with upper limits <em>α </em>and <em>β </em>and correlation <em>θ</em>. That is, if <em>X</em><sub>1 </sub>and <em>X</em><sub>2</sub>are standard normal with correlation <em>θ</em>:

N<sub>2 </sub>(<em>α,β,θ</em>) = <em>P </em>(<em>X</em><sub>1 </sub>≤ <em>α,X</em><sub>2 </sub>≤ <em>β</em>)

Assume: <em>r </em>= 0<em>.</em>005%<em>,σ</em><sub>1 </sub>= <em>σ</em><sub>2 </sub>= 2%<em>,ρ </em>= 0<em>.</em>4<em>,µ</em><sub>1 </sub>= <em>µ</em><sub>2 </sub>= 0<em>.</em>03%. Further assume that at date 0, we have <em>T </em>= 6months, and that <em>S</em><sub>1<em>,</em>0 </sub>= 99, <em>S</em><sub>2<em>,</em>0 </sub>= 101 and <em>K </em>= 100. <em>Compute the price of the option at date </em>0<em>.</em>

<ol start="4">

 <li><em>Compute the VaR for the option using the two formulas you have derived before. Compare the results and explain the intuition behind this result.</em></li>

 <li><em>Compute the VaR for the option using simulations. Compare to the results of the previous question and explain the intuition behind this result.</em></li>

 <li><em>Now assume you are a trader in the real world and you do not know for sure that the model for the underlying is correct. What other types of risks would you worry about? If you had to worry about just one more risk, what would it be? Explain (quantitatively) how you get to this conclusion.</em></li>

</ol>

<h2>2       Interview questions</h2>

<ol>

 <li>A ball is right in the corner of a room. What is the distance between thecenter of the ball and the corner on the floor? (Assume you know the radius of the ball).</li>

 <li>A stock has been going up 10% each year for the past three years. Whatis the three-month forward price of this stock today?</li>

 <li>There are 57 coins, one side black, the other white. You cannot distinguishby touch. You start blindfolded and 10 coins are on the white side and 47 on the black side. You can split them in any way you want and flip them as much as you want. The goal is to get 2 groups with equal number of white side up in it.</li>

</ol>