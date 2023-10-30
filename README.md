# documentAI

# Steps to be followed:
You have been given a few pages in PDF’s where you have to load texts in Python efficiently (ignore the pages that are irrelevant in the below context).
You need to work on below two assignments:
Paragraph items: text extraction and parsing
Tabular items extractions and transformation


# Assignment 1
For paragraphs, text parses the data on the paragraph level and has to store the parsed items in data frame object in a way that for every new paragraph, there should be a new line entry in the row. 
For all the paragraphs where you find numerical information, like counts or currencies, you have to create a flag against them as “num_flag”. Please refer to the attached Excel format for the expected results. 
You need to return the list of all numerical values for the given paragraphs in num_list column.
You need to extract a list of “keywords” for each paragraph, which will be all the important KPIs, eg. “Annual YoY growth” and financial ratios  You need to return the financial keywords In “keywords” columns.


# Assignment 2
For tabular items, you have to return them to the data frame object. All the tabular items then have to be transformed into two generic column names called “dimension” and “measures”.
All the non-numerical columns have to be concatenated into dimension columns, and all the numerical fields should be parsed into measure columns (in the case of multiple numerical columns, you need to transform the columns into rows). Please refer to the attached Excel format for more details. 
