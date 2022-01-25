# Anomaly Detection Exercises
1. About Anomaly Detection
2. Continuous Probabilistic Methods
3. 
<br>
a. Lesson<br>
b. Exercises<br>
<br>
z. Miscellaneous
<br>

# Notes 
### Tue., Jan. 25, 2022
1. Individual Project Closeout
- Overcommunicate early. Some things feel like "nothing work" so keep stakeholders informed and yourself accountable by investing in planning (e.g. kanban). 
    - Weekly summaries
    - Daily updates

2. 01_about
- The best way to detect outliers is to know your domain.
- One person's noise is another person's signal. Context is important. 
- The decision rule for whether something is an inlier/outlier is usually decided by cost/benefit analysis (FP vs FN).
- Techniques for Detecting Anomalies:
    - Statistical methods
    - Machine learning
        - Support Vector Machine
        - Isolation Forest Anomal Detection
    - Cluster based anomaly detection
    - Density based anomlay detection
- Anomaly detection can be vulnerable to overfitting.

3. 02_continuous 
- Detecting anomalies in continuous data:
    - Visualize
    - Z score (normally distributed data)
    - IQR method
- "Black Swan" events[^1]
    - unexpected
    - severe consequences
    - has a major impact
    - often inappropriately rationalized after the fact with the benefit of *hindsight*
        - 9/11
        - 2008 Financial Crisis
- White Swan Event
    - all of the above, except it was predicted
        - COVID Pandemic
- Grey Swan Event
    - Somewhat surprising
    - Ambiguous impact (unclear what it will mean in terms of impact)
        - Brexit
        - Trump's election

# References
[^1] "Black Swan Theory", [Wikipedia](https://en.wikipedia.org/wiki/Black_swan_theory).