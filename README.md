# Master-Project---Data-Analysis

Results (Pilot Study)


1. BartlettsTestrevealsthatthethreeratingsystemsdonothaveequal variances. Therefore the three rating systems are inherently different.
2. Thethreeratingsystemsaredifferent;However,Thedistributionofratingsis similar between the emoji rating system and the 5-point slider.
3. The5-starratingsystemhasinflatedratings.Theratingsarenotspreadout evenly even for the same products. It doesn’t work well when we want to differentiate products. Overall for varied ratings and to determine factors which influence rating 5-point slider and Emoji work better.
4. PowerAnalysisindicatesthatweneedatleast175participantstoparticipate in the survey to prove or disprove the dependency between ratings and gender (assuming a power of 0.8 is sufficient). Degrees of freedom = 4 = (5-1)*(2-1)
5. PowerAnalysisindicatesthatweneedatleast235or300participantsto participate in the survey to prove the dependency between ratings and city size, IT skill level, education, and age (assuming a power of 0.8 is sufficient). Degrees of freedom = 6 or 8 = (5-1)*(3-1) or (4-1)*(3-1). DOF = 6 or 8 depending on how evenly spread the ratings are for each rating system.
6. Currently,wehave100participantswhoratetwodifferentproductsfromtwo categories. Each participant is randomly assigned a rating system so each rating system has about 33 participants who rate 2 products each. For the final study, this needs to be at least 300 to attain a power of 80%
The following dependencies can be observed based on the current data and using p- values and Cramer’s V. Each Rating system has different results, and the dependencies on each factor change for each system.
Emoji
Age – Yes (Medium Effect)
City Size – Yes (Low Effect) Gender – Yes (Low Effect) Education – Yes (Low Effect)
IT skill level – Yes (Medium Effect)
5-star
Age – Yes (Low Effect)
City Size – Yes (Low Effect) Gender –Yes (Low Effect) Education – Yes (Low Effect) IT skill level – Yes (Low Effect)
5-point Slider
Age – Yes (Medium Effect)
City Size – Yes (Low Effect) Gender – Yes (Low Effect) Education –Yes (Low Effect)
IT skill level – Yes (Medium Effect)
     
************************************************************************************************
Notes: Cramer’s V is a measure of the strength of association between two nominal variables. It ranges from 0 to 1 where 0 indicates no association between the two variables and 1 indicates a perfect association between the two variables.
A score between 0.22 and 0.25 indicates a high/large association between two variables depending on the number of degrees of freedom. A score between 0.12 and 0.15 indicates medium dependency or association.
The Bartlett's Test is a method used in statistics to evaluate whether variances are similar or equal in the available samples. Bartlett's Test statistics tests for equality of variances across populations.
Alpha = 0.05 or 5 % So if p-value > 0.05: The null hypothesis is true we say that the factors influence the ratings and that the corresponding factor and ratings are independent. If p < 0.05, the alternate hypothesis is true and the corresponding factor influences the ratings. But we have no way to quantify this using just a Chi-square test or t-test. In that case, we use Cramer’s V to measure how much the factor influences the ratings which is the effect size.
If you don’t know what Cramers’ V is read this
https://www.real-sta/s/cs.com/chi-square-and-f-distribu/ons/effect-size-chi-square/




The data analysis of the final version is uploaded as a Jupyter Notebook
