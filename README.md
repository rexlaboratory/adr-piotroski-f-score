# Application of Piotroski F-score in American Depositary Receipt (ADR)
## Project Description
This research aims to explore the applicability of the Piotroski F-Score in American Depositary Receipts or ADR (i.e., non-US stocks with home exchange outside the U.S. but are being traded on U.S. exchanges).
## Contents
**ADR-piotroski-F-score.ipynb** contains the code.
## Logic (Pseudo-code)
1. Identify the list of foreign ADRs and extract it.
2. Retrieve financial data using YahooQuery.
3. Transform data and compute Piotroski F-Scores
  3.1 Transform data to prepare for F-score calculation
  3.2 Calculate F-scores
4. Measure the performance of High-Fscore ADR stocks VS Index VS Low-F-score stock returns
  4.1 Set up an ADR stock index by region and compute for the stock returns
  4.2 Compare the performances against the Index and Low-F-score stock returns
