# Proportion of ischemia in PN (I)

Study title: Configuration of a prototype variable corresponding to the proportion of ischemia for the comparison between robotic and open partial nephrectomy. A meta-analysis accompanied by sensitivity analysis.

Computational procedure: I variable formulation, meta-analysis (MA), subgroup analysis (SGA) & meta-regression analysis (MRA), sensitivity analysis (SA) at four levels.

Included items: Individual study data, sensitivity analysis data, derived data & R code.

Outcome: Expected value (EV) & 95% confidence interval (CI95%) of the mean difference (MD) of I when comparing robotic (RPN / RAPN) vs. open partial nephrectomy (OPN). RPN / RAPN is considered the experimental arm, while OPN the control arm.

Meta-analysis: R code is included for the implementation of a random effects model with Hartung & Knapp modification; subgroups: studies published before & after 2018, studies with & without patient matching, single- / multicenter studies, stratification of studies according to ROBINS-I tool class (Low - Moderate - Serious).

Meta-regression analysis: R code is included for the implementation of a random effects model, using the restricted maximum likelihood (REML) estimation; subgroups: studies published before & after 2018, studies with & without patient matching, single- / multicenter studies, stratification according to ROBINS-I tool, moderators: year of publication, number of quality stars assigned according to the Newcastle - Ottawa Scale (NOS).

Sensitivity analysis: Level 1: Re-analysis in a subset of studies with relatively increased accuracy of reported results. Level 2: Re-analysis in the subset of "ROBINS: Low" studies with patient matching. Level 3: Re-analysis in a subset of studies with total population above the average. 4: Observation of the change in the MD of I between robotic and open partial nephrectomy for the various values obtained by the correlation coefficient (r) between the original variables (IT & OT).

Instructions for the replication of results: Create a desktop folder named "Data" and save the “.csv” files provided. Make sure you provide the appropriate absolute / relative paths for your system. The code creates various desktop folders with appropriate names to save the derived data and plots.
