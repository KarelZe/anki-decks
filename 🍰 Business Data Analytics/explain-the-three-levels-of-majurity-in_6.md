## Note
nid: 1655655932040
model: Basic-02d89
tags: 03_gastvortrag_bda
markdown: false

### Front
Explain the <b>three levels of majurity</b> in MLOps regarding <b>Performance Measurements</b>.

### Back
<div>
  <ul>
    <li><u>Proof of Concept:</u> Ex post analysis of metrics;
    Metrics are chosen by Data Scientists and are highly
    specialized to the application.
    <li><u>Proof of Value:</u> Model performance is validated
    through A/B tests, but only monitored by a specialized
    audience; Metrics for model performance include business driven
    KPIs as well as operational KPIs (response times etc.).
    <li><u>Continuous Improvement:</u> New models are automatically
    validated in A/B tests against the current default
    (Champion-Challenger) wrt analytical, business and operational
    measurements; Validation performance in A/B tests is accessible
    to general audience
  </ul>
</div>
