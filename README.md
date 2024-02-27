# Application of Piotroski F-score in American Depositary Receipts (ADR)
## Project Description
This research aims to test the efficacy of the Piotroski F-Score classifier in predicting 'winner' and 'loser' stocks. The stock universe used is a basket of American Depositary Receipts or ADR (i.e., non-US stocks with home exchange outside the U.S. but are being traded on U.S. exchanges).
## Contents
1. **Code: adr-piotroski-f-score-script.ipynb** contains the Python script.
2. **Folder: \adr-universe** contains the list of ADRs from adr.com.
3. **Folder: \output-files** contains the results from major steps in the code for historical reference.
4. **Folder: \output-files\01-18-2024** contains the results from using January 18, 2024 data for historical reference and reproducibility.
5. **Folder: \solution-design** houses the Solution Design Document for this project.
## Logic (Pseudo-code)
1. Identify the list of foreign ADRs and extract it.
2. Retrieve financial data using YahooQuery.
3. Transform data and compute Piotroski F-Scores.
   - Transform data to prepare for F-score calculation.
   - Calculate F-scores.
4. Measure the performance of the Piotroski F-score classifier in predicting 'winner' and 'loser' stocks.
   - Benchmark: Set up an ADR stock index by market group (i.e., benchmark).
   - Return-based metrics: Compare the return rates of High-F-score ADR stocks against the Benchmark and Low-F-score stocks.
   - Precision metrics: Compute the precision of the F-score in predicting 'winner' stocks; compute the precision of the F-score in predicting 'loser' stocks.
