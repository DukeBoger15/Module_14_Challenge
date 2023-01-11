<h1>Module_14_Challenge</h1>
<li>This repo contains the code for my FinTech Bootcamp Module 14 Challenge</li>
<h2>Background</h2>
<li>We are assuming the role of a financial advisor at one of the top five financial advisory firms in the world. Our firm constantly competes with the other major firms to manage and automatically trade assets in a highly dynamic environment. In recent years, the firm has heavily profited by using computer algorithms that can buy and sell faster than human traders. The speed at which these transactions occur give our firm a competitive advantage early on. But people still need to specifically program these systems, which creates limits in their ability to adapt to new data. Thus we are planning to improve the existing algorithmic trading systems and maintain the firm's competitive advantage in the market. To accomplish this, we will enhance the existing trading signals with machine learning algorithms that can adapt to new data.</li>
<h3>What We Are Creating</h3>
<li>We are combining our new algorithmic trading skills with our existing skills in financial Python programming and machine learning to create an algorithmic trading bot that learns and adapts to new data and evolving markets. In our Jupyter notebook, we will do the following:</li>
<li>1). Implement an algorithmic trading strategy that uses machine learning to automate the trade decisions.</li>
<li>2). Adjust the input parameters to optimize the trading algorithm.</li>
<li>3). Train a new machine learning model and compare its performance to that of a baseline model.</li>
<h4>Libraries and Programs Used</h4>
<li>Pandas, numpy, hvplot, matplotlib, scikit-learn, StandardScaler, DateOffset, & classification_report</li>
<h2>Usage</h2>
<li>To use this application, please clone the repository and open JupyterLab. In JupyterLab, use the run tab and select run all cells</li>
<img width="410" alt="image" src="https://user-images.githubusercontent.com/113187706/211690402-036cca61-d056-40ab-8e42-ed9e19bff30a.png">
<h3>Conclusions About Baseline Trading Algorithm Performance</h3>
<li>Looking at the Cumulative Return Plot below of actual returns vs Strategy returns, the actual returns and strategy returns follow a similar path. At the beginning of the time period, there is a decrease in returns and the lines are stacked ontop of each other in the plot, therefore you cannot tell a difference in them. As the time period gets closer to 2019, we start to see the two returns separate with the strategy returns outperforming the actual returns. IN the year 2020, we see an extreme decrease in both the actual and strategy returns, presumably due to the Covid-19 Pandemic. Then moving towards 2021, both actual and strategy returns begin to increase with the strategy retuns out performing the actual returns.</li>
<img width="460" alt="image" src="https://user-images.githubusercontent.com/113187706/211691357-6b4c8f8d-2f86-471c-acc0-ae0bcc201dce.png">
