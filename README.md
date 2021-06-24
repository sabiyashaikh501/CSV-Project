#String Matching

  Fuzzy string matching like a boss.The problem of approximate string matching is typically divided into two sub-problems: finding approximate substring matches inside a   given string and finding dictionary strings that match the pattern approximately.
  
#Installation
 Using PIP via PyPI
  ->ip install fuzzywuzzy
  
#Requirements
  ->Python 2.7 or higher
  
#Usage
  -> from fuzzywuzzy import process
  
#Process
  results=process.extract(query,choices,limit=limit)---You can also pass additional parameters to extract method to make it use a specific choices. A typical use case is   to match file paths.
  
#For testing
  ->pytest









  
  

  
