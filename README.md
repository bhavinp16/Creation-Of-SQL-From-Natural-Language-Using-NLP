# RDBMS-IA-1911100-NL-TO-SQL

Name: Bhavin Patel

Roll No: 1911100

Batch: B3

Class: SY/Course: Computer Engineering
<br />
<br />
<br />

Mentors: Pradnya Bhangale, Vaibhav Vasani

College: K J Somaiya College Of Engineering
<br /><br />

Topic : Formation of SQL from Natural Language Query using NLP

Scope:
  This project is focused towards queries generation related to railway database
  The model provides two types of queries:
    Getting train information by source and destinaton as input, 
    User asks about the fare of specific train as per the class of bogey.
<br /><br /><br />
Required dependencies:

  Pandas, nltk, os, re, string
  
  Some nltk functions may require to install seperately:
  PorterStemmer, WordNetLemmatizer, word_tokenize
  <br />
  NLTK's POS (Part Of Speech Tagger) is used
<br /><br />
To install the dependencies use
  pip3 install [dependency name]
  <br /><br /><br />
Instructions:
  Inside the input folder test.csv file under the text column
  the data enteries act as the Natural Language input to the NLP model.
  <br />
  The .ipynb file after installing the required dependencies in your environment
  you can simply run the queries and view the resultant SQL query formed at the 
  end of the last block.
