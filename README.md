# wier_proj2_structured_data_extraction
The goal of this project is to explore different approaches for structured data extraction from similar webpages.
We implemented regular expression based approach, xpath based approach and automatic approach for data extraction.


# Instructions to run the project
* Clone the project
* extraction can be run in 3 modes:
    * A: extraction with regular expressions
    * B: extraction with XPath
    * C: Automatic extraction
* make `implementation-extraction` your working directory
* from there run `run-extraction.py mode` where mode is either A, B or C
    * Example: `run-extraction.py A`
* When the script is run extraction results will be outputed to standard output and written to the appropriate mode foldier in the `results` foldier. For modes A and B we generate a .json object of extracted data fields. For mode C we generate a .txt file with aligned data items from two similar pages


Required libraries to run:
* python 3.6
* re
* os
* sys
* json
* numpy
* lxml
