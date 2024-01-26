# Application of Piotroski F-score in American Depositary Receipt (ADR)
## Project Description
This research aims to explore the applicability of the Piotroski F-Score in American Depositary Receipts or ADR (i.e., non-US stocks with home exchange outside the U.S. but are being traded on U.S. exchanges).
## Contents
1. **Code: ADR-piotroski-F-score.ipynb** contains the Python script.
2. **Folder: \adr-universe** contains the list of ADRs from adr.com.
3. **Folder: \output-files** contains the results from major steps in the code for historical reference.
## Logic (Pseudo-code)
1. Identify the list of foreign ADRs and extract it.
2. Retrieve financial data using YahooQuery.
3. Transform data and compute Piotroski F-Scores.
   - Transform data to prepare for F-score calculation.
   - Calculate F-scores.
5. Measure the performance of High-Fscore ADR stocks VS Index VS Low-F-score stock returns.
   - Set up an ADR stock index by region and compute for the stock returns.
   - Compare the performances against the Index and Low-F-score stock returns.
