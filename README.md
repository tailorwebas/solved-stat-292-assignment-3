Download Link: https://assignmentchef.com/product/solved-stat-292-assignment-3
<br>
<h1><span style="font-size: 16px;">There are five questions, worth a total of 100 marks. Question 1 starts on page 2.</span></h1>

<strong>Assignment Guidelines (one more time)</strong>

You are encouraged to discuss assignments with other students, but your submitted work must be your own.

The following Assignment Guidelines are helpful for all the assignments in Parts 2 and 3 of the course.

When you carry out a statistical test of hypothesis, you should state the following, <strong>when relevant</strong>:

<ul>

 <li>Model equation.</li>

 <li>Assumptions about the data, and comments about whether diagnostic graphs support those assumptions.</li>

 <li>Null and alternative hypotheses.</li>

 <li>ANOVA Table (if relevant), <em>p</em>-value.</li>

 <li>Statistical conclusions. For example, “We reject H<sub>0 </sub>and conclude H<em><sub>A</sub></em>, that <em>µ</em><sub>1 </sub>and <em>µ</em><sub>2 </sub>differ at the 5% significance level”.</li>

 <li>Interpretation of the statistical conclusions back to the original problem, using the original meaning of the response variable and any factors or covariates. For example, if comparing heights of two groups, “Female and male adults have different mean heights, with males being taller on average”.</li>

</ul>

<em>Assignment Guidelines</em>

<h1>1. Skink Temperatures</h1>

Skinks are tested for their preferred daytime temperature. Each one is placed in a long tank which is warmer at one end, cooler at the other. The temperature at the position where it settles is recorded. There are four different species of skink, and we wish to test (at the 5% level of significance) whether the species differ in their preferred temperature.

The following table gives the data.

<table width="486">

 <tbody>

  <tr>

   <td width="65">Species</td>

   <td width="40"> </td>

   <td colspan="7" width="252">Preferred temperatures (<em><sup>o</sup></em>C)</td>

   <td width="24"> </td>

   <td width="52">Total</td>

   <td width="54">Mean</td>

  </tr>

  <tr>

   <td width="65">A</td>

   <td width="40">18</td>

   <td width="63">21     22</td>

   <td width="32">18</td>

   <td width="32">20</td>

   <td width="32">19</td>

   <td width="32">19</td>

   <td width="32">23</td>

   <td width="32">17</td>

   <td width="24">22</td>

   <td width="52">199</td>

   <td width="54">19.9</td>

  </tr>

  <tr>

   <td width="65">B</td>

   <td width="40">24</td>

   <td width="63">18     19</td>

   <td width="32">21</td>

   <td width="32">20</td>

   <td width="32">17</td>

   <td width="32">23</td>

   <td width="32">22</td>

   <td width="32">22</td>

   <td width="24">19</td>

   <td width="52">205</td>

   <td width="54">20.5</td>

  </tr>

  <tr>

   <td width="65">C</td>

   <td width="40">22</td>

   <td width="63">21     24</td>

   <td width="32">19</td>

   <td width="32">25</td>

   <td width="32">18</td>

   <td width="32">23</td>

   <td width="32">21</td>

   <td width="32">24</td>

   <td width="24">22</td>

   <td width="52">219</td>

   <td width="54">21.9</td>

  </tr>

  <tr>

   <td width="65">D</td>

   <td width="40">21</td>

   <td width="63">19     26</td>

   <td width="32">24</td>

   <td width="32">25</td>

   <td width="32">21</td>

   <td width="32">20</td>

   <td width="32">20</td>

   <td width="32">27</td>

   <td width="24">25</td>

   <td width="52">228</td>

   <td width="54">22.8</td>

  </tr>

 </tbody>

</table>

SAS output is given on pages 3 and 4.

<ul>

 <li>When running the experiment, other possible factors such as time of day, light,amount of food recently eaten, are kept as near constant as possible. Why?</li>

 <li>The skinks are not put in the tank together. Why?</li>

 <li>Give values of <em>n </em>and <em>p </em>(the number of treatments) for this experiment. How many degrees of freedom are in the Treatments row, the Error row and the Total row of the ANOVA table? (Give the algebraic expressions and the actual values for this experiment.)</li>

 <li>Use the output to write up the ANOVA in the style suggested in the AssignmentGuidelines on page 1. You should include a statement of the (complete) model equation, and also comments on whether the assumptions are satisfied. Use a 5% significance level for the ANOVA test.</li>

</ul>

<h2><em>One-Way Analysis of Variance  </em></h2>

<strong><em>Dependent Variable: Temperature    </em></strong>




<em>Source                  DF Sum of Squares Mean Square F Value Pr &gt; F </em>

Model                  3       52.0750000 17.3583333       3.06 0.0402

Error                  36     203.9000000    5.6638889

Corrected Total 39     255.9750000




<strong><em>One-Way Analysis of Variance  </em></strong>




<em>Levene’s Test for Homogeneity of Temperature Variance ANOVA of Squared Deviations from Group Means </em>

<em>Source DF Sum of Squares Mean Square F Value Pr &gt; F </em>

Species 3              86.1428        28.7143      1.36 0.2691

Error      36                <u>757.4        21.0391                        </u>










<strong><em>Means and Descriptive Statistics  </em></strong>




<em>Mean of                   Std. Dev. of                   Minimum of                   Maximum of </em>

<em>Species </em>

<em>Temperature                  Temperature                  Temperature                  Temperature </em>

21.275              2.5619253577                                17                                 27

<ul>

 <li>9 2.0248456731 17        23</li>

 <li>5 2.2730302828 17        24</li>

 <li>9 2.2335820757 18        25</li>

 <li><u>8 </u>2.8982753492<u> 19        </u>27</li>

</ul>
















<h1>2. Nasal Sprays</h1>

Improvement in breathing airflow is measured for twenty-five people suffering from nasal congestion. They were treated with either a saline spray (A) or one of four nasal sprays (B, C, D, E) available over the counter in pharmacies.

<table width="320">

 <tbody>

  <tr>

   <td width="55">Spray</td>

   <td colspan="4" width="159">Airflow improvement</td>

   <td width="52">Total</td>

   <td width="54">Mean</td>

  </tr>

  <tr>

   <td width="55">A</td>

   <td width="71">15      10</td>

   <td width="32">16</td>

   <td width="33">14</td>

   <td width="24">8</td>

   <td width="52">63</td>

   <td width="54">12.6</td>

  </tr>

  <tr>

   <td width="55">B</td>

   <td width="71">25      41</td>

   <td width="32">37</td>

   <td width="33">44</td>

   <td width="24">26</td>

   <td width="52">173</td>

   <td width="54">34.6</td>

  </tr>

  <tr>

   <td width="55">C</td>

   <td width="71">21         6</td>

   <td width="32">9</td>

   <td width="33">15</td>

   <td width="24">14</td>

   <td width="52">65</td>

   <td width="54">13.0</td>

  </tr>

  <tr>

   <td width="55">D</td>

   <td width="71">16         7</td>

   <td width="32">24</td>

   <td width="33">22</td>

   <td width="24">15</td>

   <td width="52">84</td>

   <td width="54">16.8</td>

  </tr>

  <tr>

   <td width="55">E</td>

   <td width="71">24      15</td>

   <td width="32">39</td>

   <td width="33">34</td>

   <td width="24">30</td>

   <td width="52">142</td>

   <td width="54">28.4</td>

  </tr>

  <tr>

   <td width="55"> </td>

   <td colspan="4" width="159"> </td>

   <td width="52">527</td>

   <td width="54">21.08</td>

  </tr>

 </tbody>

</table>

Relevant SAS output follows, on pages 5 to 7.

Write a report that compares the five treatments using the guidelines on page 1. Ensure that you comment on all the included SAS output. Use a 5% significance level for all statistical tests. Make a recommendation for either a single best nasal spray, or a group of best choices which are similar in their effects; refer to the Tukey test to justify your decision.

<strong><em>One-Way Analysis of Variance  </em></strong>

<strong><em>Results: Nasal Spray Example </em></strong>

<strong><em>The ANOVA Procedure </em></strong>




<em>Class Level Information Class Levels Values </em><u>Spray 5 A B C D E </u>




Number of Observations Read 25 <u>Number of Observations Used 25 </u>







<strong><em>Dependent Variable: Improvement    </em></strong>




<em>Source                      DF Sum of Squares Mean Square F Value      Pr &gt; F </em>

Model                 4     1959.440000 489.860000       9.73 0.0002

Error                  20    1006.400000    50.320000

<h2>                                             <u>Corrected Total 24     2965.840000                                             </u></h2>



















<strong><em>The ANOVA Procedure </em></strong>

<strong><em>Nasal Spray Example </em></strong>




<em>Levene’s Test for Homogeneity of Improvement Variance </em>

<em>ANOVA of Squared Deviations from Group Means </em>

<em>Source DF Sum of Squares Mean Square F Value      Pr &gt; F </em>

Type       4             11893.9           2973.5       1.59 0.2156

<h1>                                               <u>Error    20             37393.0           1869.6                            </u></h1>










<em>Level of                 Improvement </em>

<em>Type      N             Mean         Std Dev </em>

<ul>

 <li>5 12.6000000 3.43511281</li>

 <li>5 34.6000000 8.67755726</li>

 <li>5 13.0000000 5.78791845</li>

 <li>5 16.8000000 6.68580586</li>

 <li><u>5 28.4000000 9.28977933 </u></li>

</ul>










<strong><em>Tukey’s Studentized Range (HSD) Test for Improvement </em></strong>




Note: This test controls the Type I experimentwise error rate, but it generally has a higher     Type II error rate than REGWQ.




Alpha                                                        0.05

Error Degrees of Freedom                           20

Error Mean Square                                 50.32

Critical Value of Studentized Range 4.23186

<u>Minimum Significant Difference         13.425 </u>




<em>Means with the same letter are not significantly different. </em>

<em>Tukey Grouping         Mean N Type </em>

<ul>

 <li>600 5 B</li>

</ul>

A

<ul>

 <li>A 400 5 E</li>

</ul>

B

<ul>

 <li>C 800 5 D</li>

</ul>

C

<ul>

 <li>000 5 C</li>

</ul>

C

C               12.600 5 A




























<h2><em>Nonparametric One-Way ANOVA  </em></h2>

<strong><em>The NPAR1WAY Procedure: Nasal Spray Example </em></strong>




<em>Wilcoxon Scores (Rank Sums) for Variable Improvement</em>

<em>Classified by Variable Type </em>

<em>Sum of      Expected            Std Dev    Mean </em>

<em>Type N      Scores      Under H0         Under H0    Score </em>

<ul>

 <li>5 50   65.0     14.682756       7.30</li>

 <li>5 00 65.0     14.682756       21.60</li>

 <li>5 00   65.0     14.682756       7.00</li>

 <li>5 50   65.0     14.682756       11.10</li>

 <li>5 00   65.0     14.682756       18.00</li>

</ul>

<em>Average scores were used for ties. </em>

<em>Kruskal-Wallis Test </em>

Chi-Square        15.8695

DF                               4

<u>Pr &gt; Chi-Square 0.0032</u>
















<h2>3. Forensic dental X-rays</h2>

The extent to which X-rays can penetrate tooth enamel has been suggested as a suitable mechanism for differentiating between females and males in forensic medicine (e.g., think about shows like ‘CSI’ and parts of ‘NCIS’). The table below gives <em>spectropenetration gradients </em>for one tooth from each of eight females and eight males.

<table width="489">

 <tbody>

  <tr>

   <td width="65">Gender</td>

   <td width="287"><em>Y </em>= spectropenetration gradient</td>

   <td width="59">Mean</td>

   <td width="77">Std. dev.</td>

  </tr>

  <tr>

   <td width="65">Female</td>

   <td width="287">4.8    5.3    3.7    4.1    5.6    4.0    3.6 5.0</td>

   <td width="59">4.5125</td>

   <td width="77">0.7605</td>

  </tr>

  <tr>

   <td width="65">Male</td>

   <td width="287">4.9    5.4    5.0    5.5    5.4    6.6    6.3 4.3</td>

   <td width="59">5.4250</td>

   <td width="77">0.7440</td>

  </tr>

 </tbody>

</table>

Note that a high reading reflects a fast drop-off in X-ray penetration, with less penetration by X-rays.

<ul>

 <li>Explain why the teeth have been sampled from eight different people of eachsex, and not eight teeth from one female and eight from one male.</li>

 <li>Given that the researcher could afford to test <em>n </em>= 16 subjects, explain the advantages of choosing eight from each group.</li>

 <li>SAS output from an ANOVA is on pages 9 and 10. Write a report, followingthe guidelines on page 1.</li>

 <li>Explain why there is no point doing a Tukey test with this data.</li>

</ul>




<h3><strong><em>One-Way Analysis of Variance  </em></strong></h3>

<strong><em>Results: X-ray Penetration Gradient </em></strong>

<strong><em>The ANOVA Procedure </em></strong>




<em>Class Level Information Class Levels Values </em>

<h3>                                                                            Gender          2 Female Male</h3>




Number of Observations Read 16

<h3>Number of Observations Used 16</h3>













<strong><em>Dependent Variable: Xray_grad    </em></strong>




<em>Source                  DF Sum of Squares Mean Square F Value      Pr &gt; F </em>

Model                  1        3.33062500 3.33062500        5.88 0.0294

Error                  14        7.92375000 0.56598214

<u>Corrected Total 15      11.25437500                                               </u>




<em>R-Square Coeff Var Root MSE Xray_grad Mean </em>

<u>0.295940 15.14099 0.752318            4.968750 </u>




<em>Source DF        Anova SS Mean Square F Value     Pr &gt; F </em>

<h3>                                                  Gender      1 3.33062500 3.33062500        5.88 0.0294</h3>




























<strong><em>The ANOVA Procedure </em></strong>

<h4>X-ray Penetration Gradient</h4>




<em>Levene’s Test for Homogeneity of Xray_grad Variance </em>

<em>ANOVA of Squared Deviations from Group Means </em>

<em>Source DF Sum of Squares Mean Square F Value       Pr &gt; F </em>

Gender    1            0.00189         0.00189      0.01 0.9305

<h3>                                               Error     14               3.3504           0.2393</h3>

<em>Level of                  Xray_grad </em>

<em>Gender N             Mean         Std Dev </em>

Female 8 4.51250000 0.76052144

<h3>                                                                     Male      8 5.42500000 0.74402381</h3>






















<h2>4. Personality types</h2>

In psychology, there are tests to classify people into one of many personality types. An experiment is run to find the extent of the influence of personality type on the subject’s score in a certain test. A random sample of four personality types is taken, and within each type a random sample of ten subjects is taken. Each subject is given the test, and the score <em>Y </em>is recorded, with data as follows:

<table width="367">

 <tbody>

  <tr>

   <td width="51">Type</td>

   <td width="40"> </td>

   <td width="32"> </td>

   <td width="32"> </td>

   <td colspan="3" width="126">Test Score, <em>Y</em></td>

   <td width="32"> </td>

   <td width="32"> </td>

   <td width="24"> </td>

  </tr>

  <tr>

   <td width="51">T1</td>

   <td width="40">50</td>

   <td width="32">52</td>

   <td width="32">44</td>

   <td width="63">49     60</td>

   <td width="32">51</td>

   <td width="32">40</td>

   <td width="32">41</td>

   <td width="32">54</td>

   <td width="24">39</td>

  </tr>

  <tr>

   <td width="51">T2</td>

   <td width="40">63</td>

   <td width="32">45</td>

   <td width="32">48</td>

   <td width="63">49     65</td>

   <td width="32">55</td>

   <td width="32">47</td>

   <td width="32">58</td>

   <td width="32">57</td>

   <td width="24">56</td>

  </tr>

  <tr>

   <td width="51">T3</td>

   <td width="40">50</td>

   <td width="32">52</td>

   <td width="32">47</td>

   <td width="63">48     44</td>

   <td width="32">56</td>

   <td width="32">55</td>

   <td width="32">39</td>

   <td width="32">51</td>

   <td width="24">53</td>

  </tr>

  <tr>

   <td width="51">T4</td>

   <td width="40">39</td>

   <td width="32">38</td>

   <td width="32">51</td>

   <td width="63">50     53</td>

   <td width="32">53</td>

   <td width="32">59</td>

   <td width="32">41</td>

   <td width="32">45</td>

   <td width="24">48</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Explain why this is a random effects design, rather than a fixed effects design.</li>

 <li>Some SAS output is given on pages 12 and 13. Note that the boxplots do notinclude estimates of group means, since any differences in population means are not the focus of this investigation.</li>

</ul>

Present a report and your conclusions. Include in your report comments on whether the relevant assumptions seem satisfied. Give your estimated components of variance, plus the percentage of the total variance of <em>Y </em>that is due to personality, along with the percentage unexplained,

Do you think personality type is important in determining the score on this particular test?

<h1>                                       SAS Output for Personality Type Example</h1>

<strong> </strong>

<strong>Box Plot  </strong>







<strong> </strong>

<strong> </strong>

<table width="598">

 <tbody>

  <tr>

   <td width="598"><strong>One-Way Analysis of Variance  </strong></td>

  </tr>

  <tr>

   <td width="598"><strong>Results  </strong></td>

  </tr>

 </tbody>

</table>

<strong>The ANOVA Procedure </strong>




<table width="184">

 <tbody>

  <tr>

   <td colspan="3" width="184"><strong>Class Level Information </strong></td>

  </tr>

  <tr>

   <td width="63"><strong>Class </strong></td>

   <td width="45"><strong>Levels</strong></td>

   <td width="77"><strong> Values </strong></td>

  </tr>

  <tr>

   <td width="63"><strong>PersType</strong></td>

   <td width="45"><strong>          </strong>4</td>

   <td width="77"> T1 T2 T3 T4</td>

  </tr>

 </tbody>

</table>




<table width="213">

 <tbody>

  <tr>

   <td width="195"><strong>Number of Observations Read</strong></td>

   <td width="18"><strong> </strong>40</td>

  </tr>

  <tr>

   <td width="195"><strong>Number of Observations Used</strong></td>

   <td width="18"><strong> </strong>40</td>

  </tr>

 </tbody>

</table>




<strong>Dependent Variable: Score    </strong>




<table width="409">

 <tbody>

  <tr>

   <td width="101"><strong>Source </strong></td>

   <td width="21"><strong>DF</strong></td>

   <td width="105"><strong> Sum of Squares</strong></td>

   <td width="86"><strong> Mean Square</strong></td>

   <td width="51"><strong> F Value</strong></td>

   <td width="44"><strong> Pr &gt; F</strong></td>

  </tr>

  <tr>

   <td width="101"><strong>Model </strong></td>

   <td width="21">3</td>

   <td width="105">          279.675000</td>

   <td width="86">       93.225000</td>

   <td width="51">      2.23</td>

   <td width="44"> 0.1017</td>

  </tr>

  <tr>

   <td width="101"><strong>Error </strong></td>

   <td width="21">36</td>

   <td width="105">        1506.700000</td>

   <td width="86">       41.852778</td>

   <td width="51"> </td>

   <td width="44"> </td>

  </tr>

  <tr>

   <td width="101"><strong>Corrected Total</strong></td>

   <td width="21"><strong> </strong>39</td>

   <td width="105">        1786.375000</td>

   <td width="86"> </td>

   <td width="51"> </td>

   <td width="44"> </td>

  </tr>

 </tbody>

</table>




<table width="269">

 <tbody>

  <tr>

   <td width="62"><strong>R-Square</strong></td>

   <td width="63"><strong> Coeff Var</strong></td>

   <td width="66"><strong> Root MSE</strong></td>

   <td width="78"><strong> Score Mean</strong></td>

  </tr>

  <tr>

   <td width="62">0.156560</td>

   <td width="63"> 12.97117</td>

   <td width="66"> 6.469372</td>

   <td width="78">      49.87500</td>

  </tr>

 </tbody>

</table>




<table width="346">

 <tbody>

  <tr>

   <td width="63"><strong>Source </strong></td>

   <td width="21"><strong>DF</strong></td>

   <td width="81"><strong>     Anova SS</strong></td>

   <td width="86"><strong> Mean Square</strong></td>

   <td width="51"><strong> F Value</strong></td>

   <td width="44"><strong> Pr &gt; F</strong></td>

  </tr>

  <tr>

   <td width="63"><strong>PersType</strong></td>

   <td width="21"><strong> </strong>3</td>

   <td width="81"> 279.6750000</td>

   <td width="86">     93.2250000</td>

   <td width="51">      2.23</td>

   <td width="44"> 0.1017</td>

  </tr>

 </tbody>

</table>










<h2>                                       SAS Output for Personality Type Example</h2>










<table width="352">

 <tbody>

  <tr>

   <td colspan="6" width="352"><strong>Levene’s Test for Homogeneity of Score Variance ANOVA of Squared Deviations from Group Means </strong></td>

  </tr>

  <tr>

   <td width="60"><strong>Source </strong></td>

   <td width="20"><strong>DF</strong></td>

   <td width="100"><strong> Sum of Squares</strong></td>

   <td width="82"><strong> Mean Square</strong></td>

   <td width="48"><strong> F Value</strong></td>

   <td width="42"><strong> Pr &gt; F</strong></td>

  </tr>

  <tr>

   <td width="60"><strong>PersType</strong></td>

   <td width="20"><strong> </strong>3</td>

   <td width="100">               2400.7</td>

   <td width="82">            800.2</td>

   <td width="48">      0.49</td>

   <td width="42"> 0.6926</td>

  </tr>

  <tr>

   <td width="60"><strong>Error </strong></td>

   <td width="20">36</td>

   <td width="100">             59004.7</td>

   <td width="82">          1639.0</td>

   <td width="48"> </td>

   <td width="42"> </td>

  </tr>

 </tbody>

</table>






















<strong> </strong>

<h3>5. <strong>Phytoremediation</strong></h3>

Phytoremediation (New Scientist, 20 Dec 1997, p.26) is a process by which plants are used to remove toxic metals from the soil. For example, sunflowers were used around Chernobyl, where there was radioactive contamination from a nuclear power station accident.

Certain plants take up toxic metals (e.g. zinc, cadmium, uranium) and accumulate them in their vacuoles as protection against chewing insects and infection.

Suppose that four species of plant were tested, at lower and higher soil pH, for their uptake of zinc, <em>Y </em>, measured in parts per million (ppm) of dry plant weight at the end of the trial.

<strong>Uptake of zinc, </strong><em>Y</em><strong>, (ppm):</strong>

<table width="422">

 <tbody>

  <tr>

   <td width="139"> </td>

   <td colspan="2" width="283">Soil pH</td>

  </tr>

  <tr>

   <td width="139">Plant Name</td>

   <td width="141">5.5 (acid)</td>

   <td width="141">7 (neutral)</td>

  </tr>

  <tr>

   <td width="139">Lettuce</td>

   <td width="141">250       470     330</td>

   <td width="141">400       310     430</td>

  </tr>

  <tr>

   <td width="139">Martin red fescue</td>

   <td width="141">2850   2380  3130</td>

   <td width="141">1070     960  1300</td>

  </tr>

  <tr>

   <td width="139">Alpine pennycress</td>

   <td width="141">6340   4280  5170</td>

   <td width="141">2880   4330  3050</td>

  </tr>

  <tr>

   <td width="139">Bladder campion</td>

   <td width="141">3690   4750  5100</td>

   <td width="141">2360   1990  2140</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>What kind of design is this? Give the model equation, including an interactionterm.</li>

 <li>SAS analysis of the data using the model from part (a) was tried on both rawdata <em>Y </em>and transformed data log <em>Y </em>. Diagnostic graphs from both analyses are given on pages 15 and 16. Explain, with reasons, whether it is better to analyse <em>Y </em>or log <em>Y </em>.</li>

 <li>Further SAS output is given on pages 17 to 19. Present a report and yourconclusions, following the usual guidelines. Use a 5% significance level.</li>

</ul>

<h2>                                  SAS Output for Phytoremediation Example</h2>










<h2>                                  SAS Output for Phytoremediation Example</h2>

<strong> </strong>




<h1>                                  SAS Output for Phytoremediation Example</h1>




<strong>Linear Models  </strong>




<strong>The GLM Procedure </strong>




<table width="316">

 <tbody>

  <tr>

   <td colspan="3" width="316"><strong>Class Level Information </strong></td>

  </tr>

  <tr>

   <td width="36"><strong>Class</strong></td>

   <td width="42"><strong> Levels</strong></td>

   <td width="237"><strong>Values </strong></td>

  </tr>

  <tr>

   <td width="36">pH</td>

   <td width="42">2</td>

   <td width="237">acid neutral</td>

  </tr>

  <tr>

   <td width="36">Plant</td>

   <td width="42">4</td>

   <td width="237">AlpineP BladderC Lettuce MartinRF</td>

  </tr>

 </tbody>

</table>




<table width="212">

 <tbody>

  <tr>

   <td width="196">Number of Observations Read</td>

   <td width="17"> 24</td>

  </tr>

  <tr>

   <td width="196">Number of Observations Used</td>

   <td width="17">24</td>

  </tr>

 </tbody>

</table>










<table width="605">

 <tbody>

  <tr>

   <td colspan="2" width="192"><strong>Dependent Variable: logZinc   </strong></td>

   <td colspan="7" width="413"><strong> </strong></td>

  </tr>

  <tr>

   <td width="102"> </td>

   <td colspan="2" width="101"><strong>Source </strong></td>

   <td width="18"><strong>DF</strong></td>

   <td width="102"><strong> Sum of Squares</strong></td>

   <td width="84"><strong>Mean Square</strong></td>

   <td width="48"><strong> F Value</strong></td>

   <td width="46"><strong>Pr &gt; F</strong></td>

   <td width="103"> </td>

  </tr>

  <tr>

   <td width="102"> </td>

   <td colspan="2" width="101">Model</td>

   <td width="18">7</td>

   <td width="102">     24.03027190</td>

   <td width="84">3.43289599</td>

   <td width="48"> 92.71</td>

   <td width="46">&lt;.0001</td>

   <td width="103"> </td>

  </tr>

  <tr>

   <td width="102"> </td>

   <td colspan="2" width="101">Error</td>

   <td width="18">16</td>

   <td width="102">       0.59245521</td>

   <td width="84">0.03702845</td>

   <td width="48"> </td>

   <td width="46"> </td>

   <td width="103"> </td>

  </tr>

  <tr>

   <td width="102"> </td>

   <td colspan="2" width="101">Corrected Total</td>

   <td width="18">23</td>

   <td width="102">     24.62272711</td>

   <td width="84"> </td>

   <td width="48"> </td>

   <td width="46"> </td>

   <td width="103"> </td>

  </tr>

  <tr>

   <td width="102"></td>

   <td width="90"></td>

   <td width="12"></td>

   <td width="19"></td>

   <td width="102"></td>

   <td width="84"></td>

   <td width="48"></td>

   <td width="46"></td>

   <td width="102"></td>

  </tr>

 </tbody>

</table>




<table width="275">

 <tbody>

  <tr>

   <td width="62"><strong>R-Square</strong></td>

   <td width="62"><strong> Coeff Var</strong></td>

   <td width="65"><strong> Root MSE</strong></td>

   <td width="87"><strong>logZinc Mean</strong></td>

  </tr>

  <tr>

   <td width="62">0.975939</td>

   <td width="62"> 2.589699</td>

   <td width="65"> 0.192428</td>

   <td width="87">7.430507</td>

  </tr>

 </tbody>

</table>




<table width="342">

 <tbody>

  <tr>

   <td width="61"><strong>Source </strong></td>

   <td width="18"><strong>DF</strong></td>

   <td width="85"><strong>      Type I SS</strong></td>

   <td width="84"><strong> Mean Square</strong></td>

   <td width="48"><strong> F Value</strong></td>

   <td width="46"><strong>Pr &gt; F</strong></td>

  </tr>

  <tr>

   <td width="61">pH</td>

   <td width="18">1</td>

   <td width="85"> 1.46932364</td>

   <td width="84"> 1.46932364</td>

   <td width="48"> 39.68</td>

   <td width="46">&lt;.0001</td>

  </tr>

  <tr>

   <td width="61">Plant</td>

   <td width="18">3</td>

   <td width="85"> 21.65807393</td>

   <td width="84"> 7.21935798</td>

   <td width="48"> 194.97</td>

   <td width="46">&lt;.0001</td>

  </tr>

  <tr>

   <td width="61">pH*Plant</td>

   <td width="18">3</td>

   <td width="85"> 0.90287433</td>

   <td width="84"> 0.30095811</td>

   <td width="48">     8.13</td>

   <td width="46">0.0016</td>

  </tr>

 </tbody>

</table>




<table width="342">

 <tbody>

  <tr>

   <td width="61"><strong>Source </strong></td>

   <td width="18"><strong>DF</strong></td>

   <td width="85"><strong>    Type III SS</strong></td>

   <td width="84"><strong> Mean Square</strong></td>

   <td width="48"><strong> F Value</strong></td>

   <td width="46"><strong>Pr &gt; F</strong></td>

  </tr>

  <tr>

   <td width="61">pH</td>

   <td width="18">1</td>

   <td width="85"> 1.46932364</td>

   <td width="84"> 1.46932364</td>

   <td width="48"> 39.68</td>

   <td width="46">&lt;.0001</td>

  </tr>

  <tr>

   <td width="61">Plant</td>

   <td width="18">3</td>

   <td width="85"> 21.65807393</td>

   <td width="84"> 7.21935798</td>

   <td width="48"> 194.97</td>

   <td width="46">&lt;.0001</td>

  </tr>

  <tr>

   <td width="61">pH*Plant</td>

   <td width="18">3</td>

   <td width="85"> 0.90287433</td>

   <td width="84"> 0.30095811</td>

   <td width="48">     8.13</td>

   <td width="46">0.0016</td>

  </tr>

 </tbody>

</table>




<h1>                                  SAS Output for Phytoremediation Example</h1>

<strong> </strong>













<h1>             Alternative interaction graph for phytoremediation example</h1>














