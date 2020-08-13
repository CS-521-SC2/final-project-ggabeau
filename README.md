Name: Gigi Gabeau

Collaborators: None

Sources:
    
    1) https://scikit-learn.org/stable/
    
    2) https://matplotlib.org/
    
    3) https://www.crummy.com/software/BeautifulSoup/bs4/doc/
    
    4) stack overflow 


Current Late Days: 0

Total Late Days: 3


**Program Summary**

*Bolded Sections produce desired results (whether an article is REAL or FAKE)*

Section 1: Set Up 
    
    Imports matplotlib, numpy, pandas, and sklearn 
    
    Creates data frame with 6335 news articles 
    
    splits creates number of random groups to train and test to create original model testing how accurate the program can be given large dataset
    

Section 2: Proof of Text Model Concept
    
    Prints graphs proving Accuracy Rates when training and testing article text
    
    Includes classification report (needs to be uncommented to be printed) 


Section 3: Proof of Title Model Concept
    
    Does same as Section 2 but for article titles
    
    Proves that using full text yeilds more accurate results than just the title
    

Section 4: Creating Models 
    
    Uses all of data from data set for training model


Section 5: Web Scraping and Formatting
    
    Helper function using BeautifulSoup to scrape through url to find title and text


**Section 6: Test Article by Text** 
    
    Asks User for article url or article information if site can't be scraped
    
    Uses User input for tests against the trained dataset
    
    Prints results (Yes, article is REAL or No, article is FAKE)
    

**Section 7: Test Article by Title**
    
    Performs same task as Section 6 but uses article title instead of text
    
    Can be used to compare results
    