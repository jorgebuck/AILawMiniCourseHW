# AILawMiniCourseHW

Step 1 and 2: Data Collection & Preparation
Pulled all the data sets and lists of Supreme Court docs to be analysed later. Also created the colummn identifiers of what we would be collecting for easier sorting. Then began to ingest the docs themselves to break them down into the table

Step 3: Data Processing 
This is the main processing function, defining the parameters with which to search the documents and then actually doing it. The code is set up to remove certain words and then sort the rest. This allows us to only get the data we want and care about out of the set of Supreme Court documents. 

Step 4: Topic Modeling Method and Testing 
This step creates a topic model based on the previous step and then has the ability to test it on future data sets. The model looks at frequency of words used and comparing each document against the rest. 

Step 5: Topic Model Application to Data 
This final step is a visualisation of the data, allowing for analysis and results to be shared by non-engineers. Also creates a dictionary of what the machine found to look up topics.

