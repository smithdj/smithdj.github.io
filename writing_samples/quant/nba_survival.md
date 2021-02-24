## Writing Sample

<br/>

### Survival of the youngest? An analysis of collegiate experience and NBA career duration.

Daniel J. Smith 

<br/>

<details>
  <summary>Note</summary>  
  <br/>
  
  This writing sample includes excerpts from the methods, results, discussion, and conclusion sections of an unpublished manuscript that was presented at the New England Symposium on Statistics in Sports in 2015.
  
</details>

***

### ABSTRACT

**Background:** The National Basketball Association’s (NBA) annual draft underscores a salient issue for both amateur players and team front offices: the value of collegiate playing experience. One decision problem for a U.S. collegiate player is deciding on the number of years to commit to National Collegiate Athletic Association (NCAA) basketball that maximizes his time in the NBA to pursue various goals, such as winning championships or accumulating wealth. This study examines the effect of collegiate playing experience on career length in the league. I hypothesize that professional career length in the NBA is increasing in collegiate career length.

**Methods:** This paper analyzes data from the NBA drafts occurring between 2000 and 2013, inclusive. The sample comprises all (NCAA) collegiate players entering those drafts (*n* = 1,189). Survival analysis of time to first event is conducted using Kaplan-Meier estimation and accelerated failure-time Weibull regression. I make several cuts at the data and extend the analysis to a larger sample that includes all amateur players entering the drafts between 2000 and 2013 (n = 1,436), thereby accounting for those entrants, subsequently drafted or undrafted, without NCAA experience.

**Results:** Among the sample of 1,189 collegiate players, comparison of the univariate Kaplan-Meier survivor functions suggests that professional career length is decreasing in collegiate experience, and the Peto-Peto-Prentice test indicates that NBA career duration across the collegiate strata is significantly different. In multivariate analyses the estimates from the Weibull regression models provide no support for collegiate playing experience as a factor of NBA career duration; however, the Weibull coefficients suggest that the draft round, draft number, position, height, and select performance statistics of a player are determinants of career length in the league. In extending the analysis to the larger sample of 1,436 draft entrants, the findings remain unchanged. 

**Conclusion:** Contrary to the alternative hypothesis, there is no evidence to suggest that NBA career length is affected by collegiate career length. The implications of this analysis are important for both amateur players and general managers, particularly with continuing debate about changing the age limit for the draft and the alternatives to NCAA basketball for preparing for the NBA. For players and front offices alike, investing in more college experience may not be optimal.


***

### METHODS  

**Data analysis**

To assess the empirical evidence for a systematic relationship between collegiate experience and career length (i.e., duration), I analyze single-event failure data from all amateur players who declared for (and remained in) any of the NBA drafts occurring between 2000 and 2013, inclusive. From this population I derive the primary study sample, which comprises all collegiate players entering the aforementioned drafts (*n* = 1,189). I later expand the sample to include all NBA draft entrants (i.e., those with or without collegiate experience) from those years (*n* = 1,436). To analyze both data sets, multiple cuts are made using nonparametric and parametric analyses. Kaplan-Meier curves are presented to illustrate the differences in the probability of survival across subgroups, and the Peto-Peto-Prentice test is utilized to assess the equality of survivor functions. A Weibull survival model with accelerated failure-time parameterization is used to analyze the effect on career duration of factors related to player characteristics and performance. The data is from RealGM and Basketball-Reference. All analyses were conducted in Stata (StataCorp 2013). . . .

<br/>

### RESULTS

In the primary study group of *n* = 1,189 collegiate draft entrants, 958 players (81%) experienced a failed event across 2,649 years of observation. 

**Nonparametric**  
As a first cut at the data, a univariate Kaplan-Meier analysis of collegiate experience was conducted on the primary study group, for which there is complete survival data for all 1,189 players. Figure 1 presents a comparison of the survivor functions of the four subgroups. Contrary to the expected effect as stated in H<sub>1</sub>, figure 1 suggests the inverse influence of college career length on NBA career duration. Indeed, the probability of survival is greatest for amateur players with one year of college, and the function is decreasing in collegiate experience, as demonstrated by the curve for four-year collegiate players, who have the lowest survival rate. 

A comparison of the median survival times (detailed data not presented) supports this conclusion; although there is no median survival time for one-year collegiate players, the medians for two-, three-, and four-year players are 4.49, 3.27, and 0.24 years, respectively. As a more robust assessment of the equality of survivor functions, an unstratified Peto-Peto-Prentice test was utilized. The univariate results (*x*<sup>2</sup> = 281.01, *p* < 0.001) indicate that collegiate experience affects career duration in the league. However, because the nonparametric analysis does not account for other factors, I conduct a multivariate analysis using a parametric survival model. 

**Parametric**  
As a second cut at the data from the primary study group, I employed a Weibull survival model using an accelerated failure-time (AFT) metric to fit the data. This AFT Weibull approach was selected because the assumptions of the model are consistent with the collegiate experience hypothesis proposed earlier; I posit that the hazard for a NBA player increases over time and that changes in the hazard across players of different collegiate experience are not proportional across time. Estimates from the Weibull regressions for two models are presented in table 1. Complete data on all covariates was available for only *n* = 646 (54%) players; this proportion is primarily a function of the number of players who were waived before the start of a given regular season and thus do not have data for player performance variables. For ease of interpretation, the survival time ratios (TR) are presented rather than the coefficients, which require exponentiation. 

Two models are presented because of the high correlation between *draft round* and *draft pick*. Therefore, model (1) includes draft round but excludes draft pick, while the model (2) is the inverse. In neither model do the Weibull estimates provide support for H<sub>1</sub>, and therefore I fail to reject the null hypothesis that *collegiate experience* has no effect on career duration. *Age* is also not supported by the empirical evidence. However, most of the remaining covariates maintain significance across both models. In particular, referring to *round* in model (1), draftees have longer careers than their undrafted cohorts. Compared to undrafted players, career duration is 64% longer for draftees selected in the second round and 94% for those selected in the first round. The results also suggest that survival time in the league is increasing by 25% and 11% for those players that tend to assist and score, respectively. Model (1) further provides evidence that taller players experience career duration that is longer than shorter players by 40%.

In Model (2), all variables sustain their significance except for *PER*. The time ratio associated with *draft pick* indicates that players selected later in the draft have careers extended by 0.01 percent in relation to draftees chosen earlier. *Assists* and *points*, which increase survival by 23% and 14%, respectively, for every unit increase, remain highly significant. One difference in the models concerns the scale parameter denoted ln(*p*); the implication is that the hazard function is increasing at a decreasing rate in model (1), but the hazard is increasing at an increasing rate in model (2).

**Secondary study group**  
I extend the analysis of the effect of collegiate experience to all draft entrants over 2000-2013. Of the *n* = 1436 players in this secondary study group, comprising those with or without collegiate playing experience (i.e., foreign players and high-school graduates), 1157 failures occurred over 3,377 years of analysis time. A plot of the Kaplan-Meier curves illustrates that probability of survival for those without collegiate playing experience is greater than that of four-year collegiate players but less than that of players with three years or fewer of collegiate experience.

Results from the Peto-Peto-Prentice test (*x*<sup>2</sup> = 348.49, *p* < 0.001) suggest the inequality of survivor functions. AFT Weibull survival models are performed using the same set of covariates as in models (1) and (2). Complete data on all covariates was available for only *n* = 770 (54%) players. Consistent with the previous results, the data in models (3) and (4) in table 2 do not support H<sub>1</sub>; *draft age* is also not supported by the empirical evidence. Nevertheless, *round*, *assists*, and *points* are highly significant covariates. The effect of *round* on survival time in model (3) is consistent with the findings from model (1). In considering the inclusion of foreign players and high-school graduates as draft entrants, the careers of first- and second-round selections are 86% and 59% longer, respectively, compared to undrafted players.

Hazard curves based on model (3) are generated to graphically assess the difference in hazard functions across *collegiate experience*. Figure 3 demonstrates the similarity in the hazard function for each strata of the variable. This further supports the conclusion that the effect of collegiate playing experience is not as strong as hypothesized.

<br/>

### DISCUSSION  
Multiple cuts of the data suggest that collegiate playing experience has no effect on NBA career length. In considering the univariate Kaplan-Meier curves, the survivor functions presented a result that is the opposite of what is predicted by the alternative hypothesis H<sub>1</sub>. Accounting for other covariates, the Weibull estimates suggest that collegiate career length is not a factor that determines career duration in the NBA; instead, the models demonstrate, in particular, the 50 to100% increase in survival time that is associated with being selected in the draft, regardless of round, as compared to undrafted players. The models also, not surprisingly, highlight height as a factor of career duration. Given this, those who play the traditional power forward and center positions, as well as those who rebound, extend their survival time. Players with an emphasis on scoring or passing also experience longer careers.

Despite the strength of these estimates, there are limitations to this analysis. Most important, since these data represent the single-event-failure method, the results provide only a partial view into survival in the league. More complete insight would account for multiple failure events. Another limitation is the selected model. While the data was fitted to a Weibull distribution, additional data may suggest an improper fit, and thus an alternative model would be necessary. Third, and related to the previous two limitations, these data correspond only to the last 14 NBA draft years. On the one hand, the sample used in this study is representative of the current period of the NBA. On the other hand, extending the sample population to all NBA draft entrants since 1971 would provide a more complete understanding of the effect of collegiate playing experience on survival in the league.

<br/>

### CONCLUSION

The findings suggest that NBA careers are not longer for players who remain in college through their senior year. The implications of this analysis are important for both players and general managers, particularly with continuing debate about changing the age limit for the draft. For players and front offices seeking to widen their championship windows, investing in more college experience may not be optimal. Indeed, this study suggests that collegiate playing experience is not a factor that determines career duration. Despite debate about the non-basketball-related effects of a shorter tenure in college, the trend of one-and-done does not seem to negatively affect player survival in the NBA.

---

<details>
 <summary>TABLES & FIGURES</summary>
 <br/>
  
 [PDF version](nba_survival-tables_and_figures.pdf)
 *For optimal viewing, open the link in a new tab and download the PDF file.
</details>

<details>
 <summary>REFERENCES</summary>
 <br/>
  
Fynn, Kwame and Morgan Sonnenchein. 2011. An analysis of the career length of professional basketball players. <i>Macaleter Review</i> 2(2): 1-11.

Groothius, Peter and J. Richard Hill. 2004. Exit discrimination in the NBA: A duration analysis of career length. <i>Economic Inquiry</i> 42(2): 341-9.

Rodenberg, Ryan and Jun Woo Kim. 2012. Testing the On-Court Efficacy of the NBA's Age Eligibility Rule. <i>Journal of Quantitative Analysis in Sports</i>:1-21.

StataCorp. 2013. Stata Statistical Software: Release 13. College Station, TX: StataCorp LP.

</details>
