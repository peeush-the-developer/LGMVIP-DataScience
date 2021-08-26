# LetsGrowMore Virtual Internship program

We're given several tasks out of which we need to complete atleast 2 tasks by the end of the given month.

I've chosen to work with:

- Stock market prices prediction and forecasting using Stacked LSTM

## Prepare development environment

### Setup Git repo

1. Make a new directory
   ```shell
   $ mkdir LGMVIP-DataScience
   ```
2. Change directory
   ```shell
   $ cd LGMVIP-DataScience
   ```
3. Init git repo
   ```shell
   $ git init
   ```
4. Create README file

### Setup virtual environment

I'm using Anaconda's conda tool to manage packages required for the project.

1. Create new environment
   ```shell
   $ conda create -n lgmvip-env
   ```
2. Activate environment
   ```shell
   $ conda activate lgmvip-env
   ```
3. Install basic python (v3.8.6)
   ```shell
   $ conda install -y python==3.8.6
   ```
4. Install required packages for Machine learning tasks
   ```shell
   $ conda install pandas numpy matplotlib scikit-learn seaborn
   ```

## [Stock market prices prediction and forecasting using Stacked LSTM](Stock-Prices-Prediction-LSTM)

[Python notebook](Stock-Prices-Prediction-LSTM/stacked_lstm.ipynb)
