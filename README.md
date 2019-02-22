# AGBT-2019-Poster-Analysis
Identifying the “Success Factors” That Predict Liquid Biopsy Winners Using Logistic Regression

Background:
 
Liquid biopsies can be used for multiple applications including early detection, therapy selection, and longitudinal assessment during and post-treatment. To date, $4B+ have been invested in companies that develop or offer liquid biopsy products, including distributed kits and send-out services. While 100+ companies currently compete in this space, we anticipate the industry may only support a dozen players in the future.
 
Objective:
 
The first objective of this study was to gather data on the market activities of 80+ liquid biopsy test manufacturers. The secondary objective of this study was to identify ‘success factors’ that enable a liquid biopsy company to capture >2% market share.
 
Approach:
 
We developed a dynamic tool to track ~100 liquid biopsy companies, including both public and private entities. We characterized and ranked companies on five key metrics: 1) research (e.g., publications), 2) funding, 3) products (e.g., current and pipeline products, technology [i.e., ctDNA, CTCs, exosomes, others]), 4) HR activity (e.g., number of hires by department), and 5) engagement (e.g., press releases, number of partnerships). We supplemented our secondary research with 15 primary interviews conducted with technical experts and investors familiar with the liquid biopsy space.

We developed a market model to estimate the share of each liquid biopsy manufacturer, and defined a market share of >2% as “success” (i.e., outcome variable = 1). We used python version 2.0, pandas and a range of python packages in Jupyter software to conduct exploratory data analysis and identify which success factors may be correlated with success (i.e., market share >2%). We developed a logistic regression model to identify which factors may be more relevant in predicting company success.
