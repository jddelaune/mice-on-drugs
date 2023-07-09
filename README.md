# mice-on-drugs

**Introduction**
This project uses simulated data to examine a trial of drugs that might be effective for the treatment of squamous cell carcinoma, a common form of skin cancer. We use python, pandas, and matplotlib to import and analyze the data, generate summary statistics and data visualizations, and draw some conclusions about the effectiveness of our company's drug, Capomulin, in comparison to the other nine drugs in the study.

**Files**
The originally provided data is included in the Mouse_metadata.csv and Study_results.csv files in the /data folder. Code and visualizations are in the pymaceuticals.ipynb Jupyter notebook. Observations are summarized below in the *Analysis* section.

**Analysis**

Our study measured the results of the treatment of mice with ten different drugs. There were 249 mice in the study; one had to be excluded due to duplicate data which was clearly erroneously recorded, leaving 248 mice.

Mice were observed at multiple time points throughout their treatment. The minimum number of total observations per drug was 148 and the most promising two drugs, Capomulin and Ramicane, had over 200 observations each. (see Figure: Drug Regimen, cell 12)

The two most effective drugs in the study by far were Capomulin and Ramicane. They saw extremely similar performance, with a mean tumor volume at the end of the treatment period of 40.68 and 49.22 respectively. (See summary statistics in cell 9 and boxplot in cell 20) The performance of both drugs was far better than any of the other drugs included in the study.

The graph shown in cell 23 illustrates the reduction in tumor volume over the entire Capomulin treatment regimen for a single example mouse. Interestingly, the reduction is not continuous, which suggests that a trial with more frequent administrations of the drug may produce results of interest.

The graph in cell 51 shows that for mice treated with Capomulin, the average tumor volume is strongly correlated with the mouse's weight. Unfortunately, someone would probably notice if we tried to re-run the study and give the skinny mice Capomulin and give the fat mice Ramicane.

**Acknowledgements**
Many thanks to Kourt Bailey, whose assistance with learning the Python, Pandas, and Matplotlib techniques demonstrated here was invaluable.
