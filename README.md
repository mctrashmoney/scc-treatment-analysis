# scc-treatment-analysis

## About the analysis & sources
1. I took a look at the dependencies that were put as a starter and put the ones that were necessary for the completion of the analysis. Namely scipy.stats to import linregress.
2. This piece of code was the one that I took from class especially copy-pasted to get the linear regression part at the bottom.
3. I saw Mark on Thursday because I was having trouble with the distribution of unique sex of the mice in the pie charts. He then told me what I was doing wrong and told me to drop duplicate mice through their ID with the following code: sex_of_mice = `clean_df.loc[:, ["Mouse ID", "Sex"]].drop_duplicates()`
4. I made note of the mice in the line and scatter plots but also commented how any ID can be entered.
5. We can make a Capomulin search before this to know which IDs are good to search from.
6. As has been the norm, the Learning Assistant has been a huge help. Explaining parameters of functions mostly. In retrospect, one thing I realize I can improve on is moving things such as `x_values` and `y_values` to make the code cleaner. 
