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

**Methods:** This paper analyzes data from the NBA drafts occurring between 2000 and 2013, inclusive. The sample comprises all (NCAA) collegiate players entering those drafts (n = 1,189). Survival analysis of time to first event is conducted using Kaplan-Meier estimation and accelerated failure-time Weibull regression. I make several cuts at the data and extend the analysis to a larger sample that includes all amateur players entering the drafts between 2000 and 2013 (n = 1,436), thereby accounting for those entrants, subsequently drafted or undrafted, without NCAA experience.

**Results:** Among the sample of 1,189 collegiate players, comparison of the univariate Kaplan-Meier survivor functions suggests that professional career length is decreasing in collegiate experience, and the Peto-Peto-Prentice test indicates that NBA career duration across the collegiate strata is significantly different. In multivariate analyses the estimates from the Weibull regression models provide no support for collegiate playing experience as a factor of NBA career duration; however, the Weibull coefficients suggest that the draft round, draft number, position, height, and select performance statistics of a player are determinants of career length in the league. In extending the analysis to the larger sample of 1,436 draft entrants, the findings remain unchanged. 

**Conclusion:** Contrary to the alternative hypothesis, there is no evidence to suggest that NBA career length is affected by collegiate career length. The implications of this analysis are important for both amateur players and general managers, particularly with continuing debate about changing the age limit for the draft and the alternatives to NCAA basketball for preparing for the NBA. For players and front offices alike, investing in more college experience may not be optimal.


***

### METHODS  

**Data Analysis**  

**Time to event.** For every report, time to event was recorded in person-years (PYs). In cases where total PYs were not provided, aggregate PYs were approximated by cumulative disease duration or time between biopsies, which were estimated by the product of the sample size and the sample mean of the duration of infection or interval separating paired biopsies. 

**Fibrosis progression.** We estimated the progression of fibrosis using two methods: i) the stage-constant method, wherein the rate of progression is assumed to be linear, and therefore constant, across person-time, and ii) the stage-specific method, in which fibrosis progression is presumed to be nonlinear and thus advances unevenly over person-time. All fibrosis staging data were standardized by converting the original fibrosis scores graded by the Ishak, Knodell, or Scheuer system to METAVIR units (F0-F4) (Thein, Yi, Dore, & Krahn, 2008). 

_**Linear estimation:**_ An annual stage-constant FPR, which refers to a uniform rate of progression from METAVIR stage F0→F1, was estimated for any report that did not directly report it but provided relevant data for its computation. The FPR was approximated using one of three methods depending on the amount of data included in the report. In general, a modified version of the indirect or direct method for estimating a stage-constant FPR, appropriate for single-biopsy or serial-biopsy data (Yi, Wang, & Krahn, 2004; Thein et al. 2008), respectively, was applied when the report provided the distribution of fibrosis stages. 

1. *Standard direct method:* The FPR was the average of each participant’s progression rate, which was calculated by dividing the difference in a participant’s METAVIR scores between two biopsies by the time interval separating the biopsies. 

2. *Modified direct method:* The estimated FPR was the quotient of the difference in cumulative METAVIR units between paired biopsies divided by the time elapsed between the biopsies. 

3. *Modified indirect method:* The FPR was derived from the ratio of cumulative METAVIR units to total disease duration of the participants biopsied. 

_**Nonlinear estimation:**_ We also estimated annual stage-specific FPRs, which describe fibrosis progression as a function of METAVIR staging&mdash;that is, the rate at which an individual transitions from one given METAVIR stage to the next. For each report that provided the fibrosis staging distribution and person-time of the sample, four METAVIR stage-specific transition rates were estimated: F0→F1, F1 →F2, F2→F3, and F3→F4. The stage-specific FPRs were generated using the Markov maximum likelihood (MML) estimation method (Yi et al., 2004; Sweeting, De Angelis, Neal, Ramsay, Irving, Wright, Brant, Harris, Trent HCV Study Group, & HCV National Register Steering Group, 2006; Thein et al., 2008; Bochud, Cai, Overbeck, Bochud, Dufour, Müllhaupt, Borovicka, Heim, Moradpour, Cerny, Malinverni, Francioli, & Negro, 2009).

**Incidence of hepatic sequelae.** Separate incidence rates of CC, DC, and HCC were estimated as the ratio of the event count for an outcome to the cumulative PYs of the subgroup under examination. When necessary, total PYs were estimated as described in the preceding section. All estimates of incidence were expressed as events per 1,000 PYs.

**Meta-analysis**
Pooled estimates were generated from both fixed-effect and random-effects metaanalysis models. Heterogeneity was assessed using both Cochran’s *Q* and *I*<sup>2</sup> (Higgins, Thompson, Deeks, & Altman, 2003) measures. Random-effects meta-regression of fibrosis progression and incidence of CC were performed. Statistical analysis was conducted using Stata 13.1 (StataCorp, 2013) and SAS 9.3 (SAS Institute Inc., 2012). . . .

<br/>

### RESULTS

**Pooled estimates**   
In the supporting tables (1–5), both fixed-effect and random-effects meta-analysis results are presented. We discuss below only the random-effects estimates. 

**Fibrosis progression rate.** A total of 2,607 participants representing 41,119 PYs and 3,775 cumulative METAVIR units contributed to the study of FPR in 10 reports. Among 2,361 PWID in 9 of the remaining 10 reports, the estimated mean duration of infection was 15.2 years (median 14.6; range 5.6, 26.0) and the estimated mean age of infection was 20.7 years (median 21.0; range 15.8, 23.0).

_**Linear estimation:**_ In the 10 reports, the pooled stage-constant estimate of fibrosis progression (F0→F4), described in table 1, was 0.117 units per year (range 0.070, 0.232). Using this estimate, time to CC was 34 years for an individual with chronic HCV. 

_**Nonlinear estimation:**_ MML estimation was performed for 6 of the 10 reports containing sufficient data on the fibrosis staging distribution and person-time of the sample. Table 3 presents the pooled stage-specific transition rates among this subset; the FPRs were the following: F0→F1, 0.128 (CI 0.080, 0.176); F1→F2, 0.059 (CI 0.035, 0.082); F2→F3, 0.078 (CI 0.056, 0.100); and F3→F4, 0.116 (CI 0.070, 0.161). Based on this progression sequence, time to CC was 46 years. 

**Cirrhosis.** In aggregate, 4,340 participants contributing 63,662 PYs were examined in the 15 reports characterizing CC. Among these participants the estimated mean disease duration was 15.4 years (median 14.6; range 7.8, 26.0); from 12 reports examining 3,022 PWID, the estimated mean age of infection was 20.5 years (median 21.0; range 15.8, 22.0). The pooled incidence rate was 6.6 events per 1,000 PYs (CI 4.8, 8.4). 

**Decompensated cirrhosis.** Within the four reports investigating DC, there were 2,003 participants who provided 15,880 PYs of observation. The estimated mean duration of infection was 14.9 years (median 13.0; range 7.6, 26.0; 4 reports), and the estimated mean age of infection was 21.4 years (median 21.7; range 15.8, 26.4; 4 reports). The pooled incidence was 1.8 events per 1,000 PYs (range 0.3, 3.3). 

**Hepatocellular carcinoma.** HCC was examined in five reports representing 80,096 PYs and 4,506 participants. In these reports, the estimated mean disease duration was 16.9 years (median 18.0; range 12.0, 19.0); from the four reports that assessed 4,432 PWID, the estimated mean age of infection was 20.4 years (median 20.3; range 19.0, 22.0). Most of these reports presented data from cohorts prior to 2001. The pooled incidence rate was 0.3 events per 1,000 PYs (range −0.1, 0.6). . . .

**Heterogeneity**  
Tests for heterogeneity, detailed in tables 1–3, revealed significant variability across the reports contributing to each outcome. Among the meta-analysis estimates affected by heterogeneity, the *Q*-statistic was associated with a *p*-value less than 0.05, and the *I*<sup>2</sup> values suggested moderate to high inconsistency. However, there was no evidence to suggest the influence of heterogeneity in the estimation of three outcomes: the stage-specific progression from F2→F3 and F3→F4, and the incidence of HCC. The *p*-values for all *Q*-statistics were greater than 0.10, and *I*<sup>2</sup> values were below 23%.

**Meta-regression**  
We performed a random-effects meta-regression to examine the influence of report and participant characteristics on fibrosis progression and incidence of CC. Both stage-constant and stage-specific rates were used as dependent variables. In a univariate regression, quality rating (coeff. −0.029; 95% CI −0.055, −0.004; *p* = 0.026) was associated with a slower stage-constant FPR. However, there was no evidence of an effect of quality rating on stage-specific fibrosis progression or incidence of CC. (Results are not shown.) The results of a multivariate analysis are presented in table 5. Across all three outcome variables, there was no evidence to suggest the influence of age at infection, duration of infection, male sex, or recruitment from clinical settings.

<br/>

### DISCUSSION  
This systematic review synthesized the available data on the progression of fibrosis and the incidence of severe hepatic sequelae in PWID with chronic HCV infection. Random-effects estimation generated a stage-constant FPR of 0.117 and stage-specific FPRs of 0.128 (F0→F1), 0.059 (F1→F2), 0.078 (F2→F3), and 0.116 (F3→F4). The stage-constant rate (0.117) is within the range (and near the midpoint) of other stage-constant estimates from samples of HIV-negative patients with HCV infection due to other exposures (range 0.07, 0.151). . . .

Likewise, based on a progression rate of 0.117, the estimated time to cirrhosis of 34 years is near the midpoint of the time-to-event range (22, 57) in the other patient groups. Although there is wide variance in the estimates of fibrosis progression and the associated times to event, the stage-constant rate of the present meta-analysis lies near the centers of the distributions. 

Similarly, the stage-specific rates we derived--0.128 (F0→F1), 0.059 (F1→F2), 0.078 (F2→F3), and 0.116 (F3→F4)&mdash;are consistent with the rates of Thein et al. (2008), who also examined fibrosis progression among PWID: 0.116 (F0→F1), 0.085 (F1→F2), 0.085 (F2→F3), and 0.130 (F3→F4). With the exception of the transition from F1→F2, our estimates deviate slightly from Thein et al.; this is demonstrated in the comparison of between-stage duration and overall time to CC. We estimate the occurrence of compensated cirrhosis at 46 years post-infection, and Thein et al. provide an estimate of 40 years. One explanation for the difference in rates is the moderation effect of HIV co-infection, which was prevalent in higher proportions in the PWID samples of Thein et al. . . .

---

<details>
 <summary>TABLES & FIGURES</summary>
 <br/>
  
</details>

<details>
 <summary>REFERENCES</summary>
 <br/>
  
</details>
