<div class="banner">
  <img src="/images/analytics_banner.jpg" alt="Data Analysis Banner">
</div>

<style>
  .banner {
    width: 100%;
    margin-bottom: 20px;
    overflow: hidden;
    max-height: 250px;
  }
  .banner img {
    width: 100%;
    object-fit: cover;
  }
</style>

# Hello, I'm ***Vy Dang***

<div class="contact-info">
  <a href="mailto:vykdang@gmail.com">Email</a>
  <span class="separator">•</span>
  <a href="https://www.linkedin.com/in/khanh-vy-dang/">LinkedIn</a>
  <span class="separator">•</span>
  <a href="https://github.com/vydang02">GitHub</a>
  <span class="separator">•</span>
  <a href="https://public.tableau.com/app/profile/vy.dang4934/vizzes">My Tableau Public</a>
  <span class="separator">•</span>
  <span> Tel: (734)-276-5348</span>
</div>

<style>
  .contact-info {
    margin: 10px 0;
  }
  .separator {
    margin: 0 10px;
    color: #ccc;
  }
</style>

## About Me

Hello! I'm Vy, a data-driven analyst at the intersection of business strategy and statistical methods. With a dual background in Business Administration and Statistics from the University of Michigan, I transform complex datasets into actionable business insights across economic research, consulting, and financial analysis domains.

My core strengths include:

* Developing statistical models that illuminate market dynamics and economic trends
* Translating complex quantitative findings into clear, accessible recommendations
* Designing data workflows that enhance accuracy and streamline decision-making processes
* Applying analytical rigor to business challenges through SQL, Python, R, and Stata implementations

I excel at bridging quantitative analysis with strategic thinking, consistently delivering data-driven solutions that enhance business performance and provide competitive intelligence across diverse industry contexts.

## Work Experience

<div class="experience-section">
  <div class="company-card">
    <a href="https://www.pwc.com/" target="_blank" class="company-link">
      <img src="/images/pwc_logo.png" alt="PwC" class="company-logo">
      <h3>PwC</h3>
    </a>
    <p>Delivered data-driven insights for Fortune 500 clients, specializing in financial analytics and risk modeling.</p>
  </div>
  
  <div class="company-card">
    <a href="https://www.bcg.com/" target="_blank" class="company-link">
      <img src="/images/BCG-Logo.png" alt="Boston Consulting Group" class="company-logo">
      <h3>Boston Consulting Group</h3>
    </a>
    <p>Led quantitative analysis projects, developing statistical models to drive strategic business decisions.</p>
  </div>
  
  <div class="company-card isr-card">
    <a href="https://isr.umich.edu/" target="_blank" class="company-link">
      <img src="/images/ISR_logo.png" alt="University of Michigan Institute for Social Research" class="company-logo">
      <h3>UMich Institute for Social Research</h3>
    </a>
    <div class="sub-organization">
      <a href="https://hrs.isr.umich.edu/" target="_blank" class="company-link">
        <img src="/images/hrs_logo.jpeg" alt="Health and Retirement Study" class="sub-logo">
        <h4>Health and Retirement Study (HRS)</h4>
      </a>
    </div>
    <p>Conducted advanced statistical research analyzing longitudinal data on America's aging population to study retirement trends and inform public policy decisions.</p>
  </div>
</div>

<style>
  .experience-section {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
    margin: 40px 0;
  }
  
  .company-card {
    text-align: center;
    padding: 30px 20px;
    border-radius: 10px;
    background: #f8f9fa;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }
  
  .company-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  }
  
  .company-link {
    text-decoration: none;
    color: inherit;
    display: block;
  }
  
  .company-link:hover {
    text-decoration: none;
  }
  
  .company-logo {
    height: 60px;
    width: auto;
    margin-bottom: 15px;
    transition: transform 0.3s ease;
  }
  
  .company-link:hover .company-logo {
    transform: scale(1.05);
  }
  
  .company-card h3 {
    margin: 10px 0;
    color: #333;
    transition: color 0.3s ease;
  }
  
  .company-link:hover h3 {
    color: #0066cc;
  }
  
  .company-card p {
    color: #666;
    font-size: 0.95em;
    line-height: 1.5;
  }
  
  .sub-organization {
    margin: 15px 0;
    padding: 10px;
    background: #fff;
    border-radius: 5px;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  
  .sub-logo {
    height: 40px;
    width: auto;
    margin-bottom: 8px;
    transition: transform 0.3s ease;
  }
  
  .company-link:hover .sub-logo {
    transform: scale(1.05);
  }
  
  .sub-organization h4 {
    margin: 5px 0;
    color: #555;
    font-size: 0.9em;
    transition: color 0.3s ease;
  }
  
  .company-link:hover h4 {
    color: #0066cc;
  }
  
  @media (max-width: 768px) {
    .experience-section {
      grid-template-columns: 1fr;
    }
  }
</style>

## Projects

### Credit Card Fraud Analytics
*Python (PyTorch, Pandas, NumPy, scikit-learn, transformers, SMOTE, NLP Model Fine-tuning)* | [View Project](https://github.com/vydang02/STATS-507-Credit-Card-Fraud-Detection-NLP-Model) | [View Report](https://github.com/vydang02/STATS-507-Credit-Card-Fraud-Detection-NLP-Model/blob/main/Project%20Report.pdf)

![](/images/credit_card_fraud.jpg)


An end-to-end machine learning project focused on detecting fraudulent credit card transactions. Using a dataset of over 1 million transactions, I built a cost-sensitive fraud detection model that improved accuracy by 15% and reduced false positives by 20%.

**Key techniques:** Anomaly detection, logistic regression, cost-sensitive learning, class imbalance handling

- **Machine Learning:** Class imbalance handling (SMOTE, class weights), cost-sensitive learning, hyperparameter tuning
  
- **Deep Learning:** Transfer learning, BERT fine-tuning, custom dataset classes, gradient clipping, learning rate scheduling

- **Feature Engineering:** Text transformation from tabular data, automated pipeline construction, column transformers
  
- **Statistical Analysis:** Bootstrap confidence intervals, McNemar's test, ROC/PR curve analysis, distribution visualization
  
- **Model Evaluation:** Precision-recall optimization, threshold tuning, confusion matrix analysis, KDE plots

![](/images/Dashboard_1.png)

### Tennessee STAR Education Analysis
*R (ggplot2, dplyr, tidyr, AER, stats)* | [View Project](https://github.com/vydang02/Tennessee-STAR-EDA-Project)

![](/images/class-project.jpg)

Exploratory data analysis of Tennessee's Student-Teacher Achievement Ratio (STAR) experiment, examining how class sizes impact student performance across different demographics. This project involved cleaning and analyzing 11,000+ student records across a 4-year longitudinal study.

**Key techniques:** Hypothesis testing, multiple regression analysis, data visualization, causal inference

- **Statistical Analysis:** Marginal and joint distribution analysis, conditional distributions, numerical summaries using dplyr (group_by/summarize/mutate), centered measure calculations, mean/median comparisons across cohorts
  
- **Data Visualization:** Advanced ggplot2 (faceted plots with facet_grid, coord_flip transformations, stat_summary for statistical aggregations, geom_bin_2d heatmaps), multivariate visualization across school types and demographics
  
- **Programming & Automation:** Custom R functions (group_by_column for flexible grouping, is_integer predicate function), tidy evaluation with {{}} syntax, pipeline operations with magrittr pipes
  
- **Data Manipulation:** Complex dplyr workflows (filter/select operations, group_by with multiple variables, across() for column-wise operations), na.omit and na.rm handling for 5,800+ missing values
  
- **Advanced R Operations:** Custom theme development for publication-quality plots, factor manipulation for categorical variables, table operations for complex educational metric aggregations

### Applied Regression Analysis Portfolio
*R, Statistical Modeling (car, sandwich, lmtest, leaps, glmnet, MASS)* | [View Project](https://github.com/vydang02/STATS-413)

![](/images/linear_regression.jpg)

A comprehensive portfolio demonstrating advanced statistical modeling techniques through real-world applications. This project showcases my expertise in multiple regression, model diagnostics, polynomial fitting, and regularization methods to solve complex analytical problems.

**Key techniques:** Multiple regression, interaction analysis, robust standard errors, ridge regression, model selection, cross-validation

- **Regression Diagnostics:** Comprehensive diagnostic analysis (linearity, homoscedasticity, normality checks), VIF calculation for multicollinearity detection, leverage and influence point identification, heteroscedasticity-consistent standard errors (HC1, HC2)
  
- **Advanced Modeling:** Multiple regression with interaction terms, polynomial regression of varying degrees, ridge regression for multicollinearity handling, best subset selection with AIC/BIC criteria
  
- **Simulation Studies:** Monte Carlo simulations (10,000 iterations) for inference robustness, coverage probability assessment under assumption violations, comparison of standard vs. robust standard errors, impact of non-normality and heteroscedasticity on confidence intervals
  
- **Model Selection:** Forward stepwise and backward elimination procedures, cross-validation for model comparison, out-of-sample R² evaluation, optimal model complexity determination
  
- **Statistical Inference:** Bootstrap confidence intervals with pairs resampling, hypothesis testing with multiple comparison corrections, variance-covariance matrix manipulation, t-distribution based inference procedures


### ERP System Analysis for Pharmaceutical Distribution
*Business Analysis, Strategic Planning, ERP Implementation* | [View Report](https://drive.google.com/file/d/102njUfGM1eByIjsdTUnLQOhyON6rcgrC/view?usp=sharing)

![](/images/erp_logo.jpg)

A comprehensive enterprise resource planning (ERP) strategy for a $4B pharmaceutical distributor facing legacy system end-of-life. As part of a consulting team, I evaluated SAP S/4HANA, Oracle, and Batchmaster against industry requirements, developing a strategic implementation roadmap with detailed cost-benefit analysis.

**Key techniques:** Systems evaluation, requirements analysis, implementation planning, cost-benefit analysis, risk mitigation

- **Industry Analysis:** Pharmaceutical distribution market assessment, regulatory compliance mapping, competitive positioning analysis, industry-specific ERP requirements identification
  
- **Systems Evaluation:** Comparative analysis of Tier 1 ERP systems (SAP, Oracle) against specialized solutions, feature mapping against pharma-specific requirements, scalability and integration assessment
  
- **Strategic Planning:** Five-phase implementation roadmap development, phased transition strategy, hybrid implementation model combining internal expertise with external consultants
  
- **Financial Analysis:** Comprehensive cost modeling ($245K-$2.55M range), ROI calculation, TCO analysis, licensing and implementation cost breakdown
  
- **Risk Management:** Identification of implementation risks (data migration, user adoption, timeline delays), development of mitigation strategies, contingency planning for business continuity

### Warrnambool Acquisition Valuation Analysis
*Financial Modeling, Valuation, M&A Analysis* | [View Valuation Report](https://drive.google.com/file/d/1QBHQ-y64M9kXIWDTcGAcM0M1WPvpP1IG/view?usp=sharing)

![](/images/M&A_logo.jpg)

A comprehensive valuation analysis of Saputo Inc.'s acquisition of Warrnambool Cheese & Butter Factory (WCB), Australia's oldest dairy manufacturer. Using discounted cash flow and multiple valuation methodologies, I worked in a group to develop a fair price assessment that accounted for cross-border considerations, exchange rate forecasting, and industry-specific factors.

**Key techniques:** DCF modeling, comparable company analysis, weighted valuation, cross-border considerations, sensitivity analysis

- **Financial Modeling:** Built complex DCF model with 10-year projection period, terminal value calculation, exchange rate forecasting, and iterative debt-to-enterprise value optimization using goal seek functionality
  
- **Cost of Capital Analysis:** Calculated WACC using regression-based beta estimation, risk premium adjustments, credit rating analysis, and cross-border cost of debt determination
  
- **Multiple Valuation:** Performed EV/EBITDA and P/E multiple analysis with industry-specific comparables, geographic market adjustments, and currency conversion between AUD and USD
  
- **Long-Term Growth Projection:** Developed custom long-term growth projection based on reinvestment rate analysis, return on invested capital calculations, and comparison against global dairy industry growth rates
  
- **Sensitivity Analysis:** Created weighted valuation framework (80% DCF, 20% multiples) accounting for business model uniqueness, exchange rate volatility, and management strategy considerations
  
### [Your Other Project]
*[Technologies Used]* | [View Project](#)

[Brief compelling description of another project you've worked on]

**Key techniques:** [List relevant techniques/methods]

## Technical Skills

- **Languages:** SQL (MySQL, Microsoft SQL Server, PostgreSQL), Python (scikit-learn, pandas, numpy, scipy, matplotlib, seaborn, etc.), R (dplyr, tidyr, plotly, ggplot2, shiny, stats, forecast, etc.), LaTeX
- **Data Science:** Statistical modeling, regression analysis, AI/ML (supervised, unsupervised, deep learning, feature engineering), data visualization, Probability and statistics, Linear algebra, Game theory, Time series analysis, A/B testing and hypothesis testing, Equity research (DCF modeling, ratio analysis, valuation)
- **Tools:** Tableau (dashboards, LOD, trend analysis), STATA (regression, statistical modeling), Excel (VBA, pivot tables, pivot charts), Google Analytics, Bloomberg (financial research), FactSet, GitHub
- **Interpersonal Skills:** Stakeholder Engagement, Requirement Gathering, Usability Testing, Cross-functional Collaboration, Data Storytelling, Problem Solving, Attention to Detail

---

*Want to connect? Reach out via [LinkedIn](https://www.linkedin.com/in/khanh-vy-dang/) or [email](mailto:vykdang@gmail.com)!*
