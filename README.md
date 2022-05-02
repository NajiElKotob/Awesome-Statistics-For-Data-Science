# Awesome Statistics for Data Science

{Awesome Works in Progress}

## Let's Talk Data
* What is data?
  * [What is Data](https://online.stat.psu.edu/stat508/lesson/1b/1b.1) - Data represent facts or something that has actually taken place, observed and measured. 
    * Data > (beats) Opinion
* Data literacy
  * [How to build data literacy in your company](https://mitsloan.mit.edu/ideas-made-to-matter/how-to-build-data-literacy-your-company) - mit.edu
  * [Boost Your Team’s Data Literacy](https://hbr.org/2020/02/boost-your-teams-data-literacy) - hbr.org
  * [Data Analytics vs Data Analysis](https://www.bmc.com/blogs/data-analytics-vs-data-analysis/) - bmc.com
  * [Data literacy training](https://www.statcan.gc.ca/en/wtc/data-literacy) - statcan.gc.ca
* Data Culture
* Data Types
  * Qualitative
    * Nominal, Ordinal, Binary
  * Quantitative
    * Discrete, Continous
  * _Learn more_
    * [Types of Data & Measurement Scales: Nominal, Ordinal, Interval and Ratio](https://www.mymarketresearchmethods.com/types-of-data-nominal-ordinal-interval-ratio/) - mymarketresearchmethods.com
    * [Types of Variable](https://statistics.laerd.com/statistical-guides/types-of-variable.php) - Laerd.com
    * Interval scale Vs Ratio scale: Interval scales hold no true zero and can represent values below zero e.g., you can measure temperature below 0 degrees Celsius, such as -10 degrees.; Ratio variables never fall below zero. Height and weight measure from 0 and above, but never fall below it.
    * [When a Variable’s Level of Measurement Isn’t Obvious](https://www.theanalysisfactor.com/level-of-measurement-not-obvious/) - theanalysisfactor.com
    * Foot Size vs Shoe Size
    * Is Age Discrete or Continuous? 
-----

## Data Bias
* Selection bias
* [Berkson’s Bias](https://www.statology.org/berksons-bias/) - statology.org
* Historical Bias
* Outlier Bias
* Visualization Bias 

## Numbers and Statistics
### Statistical Analysis
#### Samples and Populations
* [Samples & Populations](https://online.stat.psu.edu/stat800/lesson/3/3.1) - stat.psu.edu
* Types of Sampling
* Sample Size
  * [Sample Size Calculator](https://www.calculator.net/sample-size-calculator.html) - calculator.net
  * A general rule of thumb for the Large Enough Sample Condition is that n≥30, where n is your sample size. [Learn more](https://www.statisticshowto.com/large-enough-sample-condition/) - statisticshowto.com
  * Number of Samples (You can Afford) = Budget / Cost per Sample
  * Power Analysis
* [Law Of Large Numbers](https://www.investopedia.com/terms/l/lawoflargenumbers.asp) - investopedia.com | The law of large numbers, in probability and statistics, states that as a sample size grows, its mean gets closer to the average of the whole population. 
* [Central Limit Theorem (CLT)](https://www.investopedia.com/terms/c/central_limit_theorem.asp) - investopedia.com | In probability theory, the central limit theorem (CLT) states that the distribution of a sample variable approximates a normal distribution (i.e., a “bell curve”) as the sample size becomes larger, assuming that all samples are identical in size, and regardless of the population's actual distribution shape.
* Confidence Intervals
  * [Confidence intervals explained](https://www.scribbr.com/statistics/confidence-interval/) - scribbr.com
  * [Understanding Confidence Intervals :tv:](https://www.youtube.com/watch?v=tFWsuO9f74o) - Dr Nic's Maths and Stats


#### Descriptive Statistics
`Describe, show or summarize data in a meaningful way`
* Measures of Central Tendency - are single values that attempt to describe the central position of a set of data.
  * Mean - Most meaningful with normally distributed data
  * Median - Diminish the effect of outliers
  * Mode - bi-modal distribution; categorical data
  * [Numerical Summarization](https://online.stat.psu.edu/stat508/lesson/1b/1b.2) - stat.psu.edu
  * Sensitivity to skewness
* Measures of Variability (Dispersion)
  * Range
  * Interquartile Range (IQR)
  * Variance σ2
  * Standard Deviation σ
    * Standard deviation (S) = square root of the variance
  * [Standard Error](https://corporatefinanceinstitute.com/resources/knowledge/other/standard-error/) | A mathematical tool used in statistics to measure variability
* Shapes of Distribution
  * Normal Distribution
    * The [empirical rule](https://www.investopedia.com/terms/e/empirical-rule.asp), also referred to as the three-sigma rule or [68-95-99.7 rule](https://en.wikipedia.org/wiki/68%E2%80%9395%E2%80%9399.7_rule), is a statistical rule which states that for a normal (aka Gaussian or Gauss or Laplace–Gauss) distribution, almost all observed data will fall within three standard deviations (denoted by σ) of the mean or average (denoted by µ).
  * Non-normal Distribution (Flat, Bi-modal, Parabolic)
  * Skewness (-ve Skewness/Skewed Left, +ve Skewness/Skewed Right)
    - When data are skewed right, the mean is larger than the median. 
    - When data are skewed left, the mean is smaller than the median.
  * Kurtosis (Leptokurtic, Mesokurtic, Platykurtic)
* Percentiles and Quartiles
  * Percentiles
    * The 30th percentile is the value from the data set greater than 30% of observations, and therefore less than 70% of observations. 
    * Median = 50th percentile
    * 1st Quartile = 25th percentile
    * 3rd Quartile = 75th percentile
    * IQR = The difference between Q3 and Q1. IQR contains the middle 50% of data
  * [Quartiles](https://www.mathsisfun.com/data/quartiles.html) are the values that divide a list of numbers into quarters - mathsisfun.com
    * Interquartile range =  3rd quartile - 1st quartile
    * Quintile - "A quintile is one of five values that divide a range of data into five equal parts, each being 1/5th (20 percent) of the range." [Investopedia](https://www.investopedia.com/terms/q/quintile.asp)
    * Decile - Devide a range of data into ten equal parts, each being 1/10th (10 percent) of the range. 1st and 9th deciles equal to 10th and 90th percentiles.
  * Outliers
    * [Identifying outliers with the 1.5xIQR rule](https://www.khanacademy.org/math/statistics-probability/summarizing-quantitative-data/box-whisker-plots/a/identifying-outliers-iqr-rule) - khanacademy.org
* Percentage
  * [Percentage Difference, Percentage Error, Percentage Change](https://www.mathsisfun.com/data/percentage-difference-vs-error.html) - mathsisfun.com
  * [Percentage Change and Percent Difference](http://sumn.org/downloads/Percentage_Change.pdf) - sumn.org
* Binning
  * [Freedman–Diaconis rule](https://en.wikipedia.org/wiki/Freedman%E2%80%93Diaconis_rule)
  * Sturge’s rule
* Measures of Association
  * Correlation and Causation
    * [Correlation vs Causation: Understand the Difference for Your Product](https://blog.amplitude.com/causation-correlation) - amplitude.com
    * [Correlation](https://www.khanacademy.org/test-prep/praxis-math/praxis-math-lessons/gtp--praxis-math--lessons--statistics-and-probability/a/gtp--praxis-math--article--correlation-and-causation--lesson) means there is a relationship or pattern between the values of two variables. A scatterplot displays data about two variables as a set of points in the xyxyx, y-plane and is a useful tool for determining if there is a correlation between the variables.
    * [Causation](https://www.khanacademy.org/test-prep/praxis-math/praxis-math-lessons/gtp--praxis-math--lessons--statistics-and-probability/a/gtp--praxis-math--article--correlation-and-causation--lesson) means that one event causes another event to occur. Causation can only be determined from an appropriately designed experiment. In such experiments, similar groups receive different treatments, and the outcomes of each group are studied. We can only conclude that a treatment causes an effect if the groups have noticeably different outcomes.
  * Correlation Coefficients
    * [What Do Correlation Coefficients Positive, Negative, and Zero Mean?](https://www.investopedia.com/ask/answers/032515/what-does-it-mean-if-correlation-coefficient-positive-negative-or-zero.asp) - investopedia.com 
  * Covariance
    * [What Is Covariance?](https://www.investopedia.com/terms/c/covariance.asp) - investopedia.com
* [Normalization vs Standardization](https://towardsdatascience.com/normalization-vs-standardization-cb8fe15082eb)

-----

#### Inferential Statistic
##### Hypothesis
* Hypothesis tests attempt to provide an answer to questions such as "How likely is an observation just random change?"
* Null Hypothesis
  * The null hypothesis, H0 is the commonly accepted fact; it is the opposite of the alternate hypothesis. Researchers work to reject, nullify or disprove the null hypothesis. Researchers come up with an alternate hypothesis, one that they think explains a phenomenon, and then work to reject the null hypothesis. [learn more](https://www.statisticshowto.com/probability-and-statistics/null-hypothesis/)
  * The null statement must always contain some form of equality (=, ≤ or ≥) Always write the alternative hypothesis, typically denoted with Ha or H1, using less than, greater than, or not equals symbols, i.e., (≠, >, or <) [learn more](https://opentextbc.ca/introstatopenstax/chapter/null-and-alternative-hypotheses/)
* Confidence Intervals
* Confidence Level
* Alpha value (aka significance level)
* [Type I and Type II errors](https://www.scribbr.com/statistics/type-i-and-type-ii-errors/) - scribbr.com
  * Which is more dangerous for a smoke detector? A type I (false positive) or type II error (false negative)? 
* t-test
* z-test
  * Z-Scores
    * Simply put, a z-score (also called a standard score) gives you an idea of how far from the mean a data point is. But more technically it’s a measure of how many standard deviations below or above the population mean a raw score is. [learn more](https://www.statisticshowto.com/probability-and-statistics/z-score/)
    * [Z-Table](https://z-table.net/) - z-table.net
* Probability
  * [Probability Line](https://www.dcp.edu.gov.on.ca/en/curriculum/elementary-mathematics/grades/g6-math/strand-d/d2) - dcp.edu.gov.on.ca
  * [Intro to Probability for Data Science (Free e-book)](https://probability4datascience.com/TOC.html) - probability4datascience.com
  * Statistical significance ♟
    * Statistical significance refers to the claim that a result from data generated by testing or experimentation is not likely to occur randomly or by chance but is instead likely to be attributable to a specific cause [learn more](https://www.investopedia.com/terms/s/statistical-significance.asp) 
    * [A Refresher on Statistical Significance](https://hbr.org/2016/02/a-refresher-on-statistical-significance) - Amy Gallo (Harvard Business Review)
* P-value ⬆⬇
  * [Meet P. Value (aka p-value)](https://community.alteryx.com/t5/Data-Science/The-Data-Science-Celebrity-Q-amp-A-Meet-P-Value-aka-p-value/ba-p/743016) - Alteryx Community Team
    * [P-Values, clearly explained (Video)](https://www.youtube.com/watch?v=5Z9OIYA8He8) - StatQuest
    * In general, P values larger than 0.01 should be reported to two decimal places, those between 0.01 and 0.001 to three decimal places; P values smaller than 0.001 should be reported as P<0.001. [learn more](https://www.graphpad.com/support/faq/how-to-report-p-values-in-journals/)
    * A p-value less than 0.05 (typically ≤ 0.05) is statistically significant. It indicates strong evidence against the null hypothesis, as there is less than a 5% probability the null is correct (and the results are random). Therefore, we reject the null hypothesis, and accept the alternative hypothesis. [learn more](https://www.simplypsychology.org/p-value.html)
  * [Cheatsheet](https://github.com/wzchen/probability_cheatsheet)
* Univariate, bivariate, multivariate and multivariate multiple analysis (MMR)
  * [What’s the difference between univariate, bivariate and multivariate descriptive statistics?](https://www.scribbr.com/frequently-asked-questions/univariate-vs-bivariate-vs-multivariate/) - scribbr.com
  * [What is a multivariate relationship?](https://treehozz.com/what-is-a-multivariate-relationship)
* Upsampling and Downsampling  
##### Statisticsl Tests
* [Statistical tests: which one should you use?](https://www.scribbr.com/statistics/statistical-tests) - scribbr.com
* [Choosing the correct statistical test in SAS, Stata, SPSS and R](https://stats.idre.ucla.edu/other/mult-pkg/whatstat) - stats.idre.ucla.edu
* [How to choose the right statistical test?](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3116565/) - Barun Nayak and Avijit Hazra1
##### Error Estimatinos
##### Effect Size
* Cohen's d is designed for comparing two groups. It takes the difference between two means and expresses it in standard deviation units. It tells you how many standard deviations lie between the two means [learn more](https://www.scribbr.com/statistics/effect-size/)
* [Power Analysis, Clearly Explained! :tv:](https://www.youtube.com/watch?v=VX_M3tIyiYk) - StatQuest

-----
### Other Topics
* Equations and Functions
  * [The Distributive Property (Video)](https://www.youtube.com/watch?v=v-6MShC82ow) - Algebra Basics: The Distributive Property - Math Antics
* Aggregation
  * [The perils of calculating an Average of Averages](http://geekswithblogs.net/darrengosbell/archive/2014/07/28/the-perils-of-calculating-an-average-of-averages.aspx) - Darren Gosbell
  * [Calculating a Weighted Average (Average of Averages)](https://help.analyticsedge.com/howto/calculating-the-average-of-averages/)- Analytics Edge
* [Anscombe's Quartet](https://en.wikipedia.org/wiki/Anscombe%27s_quartet)
* [The Datasaurus Dozen](https://www.autodesk.com/research/publications/same-stats-different-graphs) - Same Stats, Different Graphs: Generating Datasets with Varied Appearance and Identical Statistics through Simulated Annealing.
* Derivatives and Optimizations
* Vectors and Matrices
* Wide and Long data
* [Pairwise vs. Listwise deletion](https://www.ibm.com/support/pages/pairwise-vs-listwise-deletion-what-are-they-and-when-should-i-use-them)
* APA
  * [Numbers & Statistics](https://owl.purdue.edu/owl/research_and_citation/apa_style/apa_formatting_and_style_guide/apa_numbers_statistics.html) - APA Formatting And Style Guide (7th Edition)
  * [Reporting a multiple linear regression in APA](https://www2.slideshare.net/plummer48/reporting-a-multiple-linear-regression-in-apa)
* Monte Carlo
  * [Monte Carlo Simulation](https://www.youtube.com/watch?v=OgO1gpXSUzU) - MIT OpenCourseWare
* A/B Testing
* Baye’s Theorem

-----
### Write-Up
* [Analytical Report – What Is It and How to Write It?](https://whatagraph.com/blog/articles/analytical-report) - whatagraph.com


-----
### Surveys
* [Survey testing](https://www.abs.gov.au/websitedbs/d3310114.nsf/home/Basic+Survey+Design+-+Survey+Testing) - abs.gov.au


-----

### Algorithms 
#### Regression
* [zedstatistics :tv:](https://www.youtube.com/watch?v=aq8VU5KLmkY&list=PLTNMv857s9WUI1Nz4SssXDKAELESXz-bi)
* [The OLS Assumptions](https://365datascience.com/tutorials/statistics-tutorials/ols-assumptions/) - 365datascience.com

-----

### Math
#### Calculus
#### Linear Algebra
* [Scalars, Vectors and Matrices](https://www.mathsisfun.com/algebra/scalar-vector-matrix.html)
  * A scalar is a number, like 3, -5, 0.368 | A vector is a list of numbers (can be in a row or column) | A matrix is an array of numbers (one or more rows, one or more columns).
* [Khan Academy - Linear algebra](https://www.khanacademy.org/math/linear-algebra)
* [Essential Math for Data Science: Introduction to Matrices and the Matrix Product](https://www.kdnuggets.com/2021/02/essential-math-data-science-matrices-matrix-product.html)

#### Optimization Methods

#### Extra Knowledge
* [Mathematics is the queen of Sciences (Video)](https://www.youtube.com/watch?v=8mve0UoSxTo)
* [What Is The Fibonacci Sequence?](https://elearningindustry.com/fibonacci-sequence-what-is-and-how-applies-agile-development) - The Fibonacci Sequence: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55… (Xn = Xn-1 + Xn-2)

#### Vidoes :tv:
* [How Imaginary Numbers Were Invented](https://www.youtube.com/watch?v=cUzklzVXJwo)

#### Textbooks
* [Mathspace](https://mathspace.co/textbooks/syllabuses/select) - mathspace.co | We bring all of your learning tools together in one place, from video lessons, textbooks, to adaptive practice. Encourage your students to become self-directed learners.

-----

#### Books
* [Pattern Recognition and Machine Learning (Free)](https://www.microsoft.com/en-us/research/publication/pattern-recognition-machine-learning/)
* [Mathematics for Machine Learning (Free)](https://mml-book.github.io/)
* [Analysis of Multiple Dependent Variables](https://www.amazon.com/Analysis-Multiple-Dependent-Variables-Research/dp/0199773599)
* [Introductory Statistics](https://saylordotorg.github.io/text_introductory-statistics/index.html) - saylordotorg.github.io
* [Introduction to Statistics](https://courses.lumenlearning.com/odessa-introstats1-1/) - courses.lumenlearning.com

#### YouTube :tv:
* [MIT 18.650 Statistics for Applications, Fall 2016](https://www.youtube.com/playlist?list=PLUl4u3cNGP60uVBMaoNERc6knT_MgPKS0) - MIT OpenCourseWare
* [Joshua Emmanuel](https://www.youtube.com/c/profjoshemman)
* [zedstatistics](https://www.youtube.com/channel/UC6AVa0vSrCpuskzGDDKz_EQ) :star:
* [Dr Nic's Maths and Stats](https://www.youtube.com/channel/UCG32MfGLit1pcqCRXyy9cAg)
* [Stephanie Glen](https://www.youtube.com/channel/UCs3IhN8VOA_5WxpAgbSmFkg) - statisticshowto.com
* [Khan Academy](https://www.youtube.com/watch?v=uhxtUt_-GyM&list=PL1328115D3D8A2566) - The average, Descriptive statistics, Probability and Statistics
* [statisticsfun](https://www.youtube.com/channel/UClD8c_piy1nrJySPJUgyivg)


#### Learning
* [Praxis Core Math](https://www.khanacademy.org/test-prep/praxis-math/praxis-math-lessons)
* [Data Science for Beginners (Microsoft)](https://github.com/microsoft/Data-Science-For-Beginners)

-----
### Tools
* [Statistics Kingdom](https://www.statskingdom.com/) - statskingdom.com
* [DrawMyData](http://robertgrantstats.co.uk/drawmydata.html) - a tool for teaching stats and data science by Robert Grant
* [Desmos - Graphing Calculator](https://www.desmos.com/calculator) - desmos.com
* [Standard Normal Distribution Table](https://www.mathsisfun.com/data/standard-normal-distribution-table.html) - mathsisfun.com
* [Probability Distribution Applets](https://homepage.divms.uiowa.edu/~mbognar/) - divms.uiowa.edu (Matt Bognar, Ph.D.)
* [Simulated Sampling Distributions](https://shiny.rit.albany.edu/stat/sampdist/) :star: - albany.edu
* [One Sample T-Test Calculator](https://www.statskingdom.com/130MeanT1.html) - statskingdom.com
* [Comparing Two Independent Samples (Sample Size)](https://www.stat.ubc.ca/~rollin/stats/ssize/n2.html) :star: - stat.ubc.ca
* [Poisson Distribution Calculator](https://www.statology.org/poisson-distribution-calculator/) - statology.org | The probability that the restaurant receives more than 100 (Normal avg). e.g., 130 => P(X = 130): 0.00058




-----
## Related Topics
* [KPIs](https://github.com/NajiElKotob/Awesome-KPIs) - Awesome KPIs
