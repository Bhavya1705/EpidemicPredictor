Final Code: EpidemicPredictor2<br>
Please visit the site (experimental) at https://cocky-beaver-ae5834.netlify.app/) at https://cocky-beaver-ae5834.netlify.app/
# EpidemicPredictor
A Python based Epidemic Detector
## Inspiration
The Corona Epidemic of 2019-20 is the largest epidemic of the 21st Century. With loss of human and monetary interest, it becomes necessary to have a system capable of predicting possible epidemics.
## Team
## Infinitum Circa
- Bhavya Bhardwaj
- Syed Ishtiyaq Ahmed
- Jaiharie J
- Sorabh Dadhich
## Goal 
To have asystem that parses through news articles on the web and extracts necessary information regarding possible epidemics and suspected outbreaks and makes them acessible in a user friendly format
## Expected Input
Random URLs of sites from Google Search for particular Keywords.
![alt text](https://github.com/Bhavya1705/EpidemicPredictor/blob/master/Screenshot%20from%202020-08-29%2021-54-38-1.png)
## Tasks
- Web Parsing
- Data Extraction
- Tokenizing 
- Data Cleanup
- Named Entity Recognitiona(NER)
### Web Parsing
Done using Beautiful Soup and Requests library in Python. The HTML is extracted and cleaned.
### Data Extraction and  Tokenizing
The **UNIQUE** aspect of this programmme is its ability to **PARSE RANDOM WEBSITES** (Whose HTML format and tags are unknown), as such the cleaned text from parsing is passed through nlp models and summarizers
### Data Cleanup
The obtained information from **Data Extraction and  Tokenizing** is passed through a condition set to extract relevant information.
### Named Entity Recognition(NER)
Done using spaCy to extract figures and mathematically significant data.
## Expected Output
![alt text](https://github.com/Bhavya1705/EpidemicPredictor/blob/master/Screenshot%20from%202020-08-29%2021-54-53-1.png)
## Libraries Used
- **datetime** - For date
- **requests** - request URL
- **bs4** - Parsing and HTML extraction and Cleanup
- **geograpy** - Country Details and Name Identification
- **nltk** - Natural Language Toolkit
- **openpyxl** - For writing to excel
- **pycountry** - Country details
- **spaCy** - NER 
- **googlesearch** - Google Search Operation
- **geopandas** - World Map details and plotting
- **folium** - Interactive Map

   ![alt text](https://github.com/Bhavya1705/EpidemicPredictor/blob/master/Infinitum%20Circa.png)
