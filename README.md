# Submission for the DLL COVID-19 Hackathon Event
Our team's submission for the DLL COVID-19 Hackathon event (https://dllglobal.com/), taken directly from the Amazon SageMaker instance we were using.

Considering it was a hackathon, the code in this repository is quite messy.

There are 6 folders:

* Datasets: the public datasets we were using (John Hopkins, OxCGRT, World Bank, ...)
* Arian, Leon, Lovro, Robert, Stole: notebooks from each member of the team

We tried several different methods:

* ARIMA
* CNN model
* XGBoost:
* Curve fitting

In the end, curve fitting was most efficient. 

The code and visualizations for curve fitting can be seen in Lovro's folder.

Final results (predictions of confirmed cases and deaths for the next two weeks) are in  `final.csv`

Team members:

* Arian Skoki
* Leon Luttenberger
* Lovro Vrček
* Robert Injac
* Dominik Stanojević

