# RNN-Attention-COVID19
Project done by Anil Naidu and Elaine Sui for CSC413 Winter 2021 Term at UofT

This project examines the effects of attention mechanisms on various RNN type architectures. We examine COVID-19 time-series data in this project. We run tests to output attention visualization, and we check to see which input features are most relevant. The feature that we chose to plot for and test with is cumulative deaths, because this feature has an upwards trend, whereas weekly deaths is more stochastic. The pdf-file in the repository is the report which sums up all results and outputs from the code. It also contains the main research papers used to help with this project (in the references section). I would recommend just reading through the report and looking at the code but if you want to run the code, then by all means follow what is written below. 

How To Run the Code?

If you want to run the code, either open the .ipynb file in Google Colab and run it, or download the .py file and run it on your own machine. However, the problem with the .py file is that you will need to make sure that you have all relevant libraries, so I would honestly just use Colab since you can have access to a GPU, which isn't really necessary due to the minimal amount of data (COVID-19 is still relatively new).  The code requires access to the internet to run, since we get data from an external url. 
