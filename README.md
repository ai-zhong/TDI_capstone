# The Data Incubator Capstone Project

The project used the Patent assignment data from USPTO (https://www.uspto.gov/) to analyze what is happening in different sectors. The assignment activity is the activity happens between company to company or person to company. This might be a merger/acquisition or an employee assigns its patents to the current employer etc. 

The first stage capstone mainly looks into the data numerically, e.g. how many patents are being assigned each year; what are the major companies in the sector that are dominating the assignment activities etc.

This second stage of capstone extracts the titles of those assigned patents for key words extraction and trying to find what is the research trend inside the sector (I set a cut-off time at 2010 to reduce the file size). After cleaning the text data, Latent Dirichlet allocation (LDA) is used for topic modeling to find the main topics in each sector. For visualizations, pyLDAvis package is used for an interactive interface.

The interactive plots need to be downloaded as html to view on local computer.

Inside the interactive plots folder, there are 10 files each represent a model ran for that sector. It shows the top hot words appeared in that sector.
