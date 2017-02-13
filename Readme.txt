Stream Keyword Extraction Code

The code for scenario 1 is in keyword_extraction_nx.py
STEPS
1) Split the dataset in train and development set
2) Specify the data path folder which is called basepath on line 45
3) Run keyword_extraction_nx which produces the results for scenario 1

For scenario 2 the summaries need to be extracted.

We include the extracted summaries in this zip. If you wish to re-extract them you can export the variables in lines 521-528
in a file.

We then use the ROUGE implementation from (http://kavita-ganesan.com/content/rouge-2.0-documentation) to extract the scores.
In order to calculate WMD we used the JAVA wrapper from https://github.com/dkoslicki/EMDeBruijn for earth movers distance.
We include the wrapper in the zip.

