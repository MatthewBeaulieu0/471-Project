# Project Summary
# Team 5: Price comparison
The project's objectives are to create a complete drug price comparison tool, recognise popular drug names, link them to their specific Manufactured Part Numbers (MPNs), and use machine learning algorithms to create connections between drug names and specifications and MPNs—particularly in situations where MPNs are hard to come by. This entails using Crawlab to crawl competitors websites take the picture of items, their description and store these for further comparison.

### Research Questions To Be Addressed
- How can we gather drug data using Crawlab and the script given?
- How can associations be made between MPNs and product details/names?
- How can price comparisons be done efficiently with such large amounts of data? 

## Phase 1: 
The project also entails converting the current script to use Crawlab and use a SQL database for improved scalability and data management.
### Tasks:
Adapt two web crawling scripts tailored to navigate and extract data from targeted websites.
Ensure the script can handle various website structures and data formats.
Integrate the scripts with a SQL database to store the fetched data, including photographs of the drugs, their descriptions, and MPNs. The design should account for data normalization to ensure that each drug's information is stored in an organized and accessible manner.

## Phase 2: Create a script for medline
### Tasks:
Collect and preprocess a dataset of drug names, specifications, and MPNs to train the machine learning model. This involves cleaning the data, handling missing values, and possibly augmenting data to improve model performance.
Choose and train a suitable machine learning model that can accurately predict or identify the MPN based on drug names and specifications. 
Integrate the machine learning model into the application, ensuring it can operate in real-time or batch mode to enrich the database with MPN information where it is missing.

Fetching items via crawling then being able to compare their prices in an accurate manner. Take photo of item , description put it in mysql db. Keep the MPN for each item  

### Class of models to be applied to dataset
- Natural Language Processing (NLP) Models
    - to link drug names to MPN
- Assocation Rule Mining
    - to link drug details and names to MPN
- Image Recognition Models (Might not be useful for our situation)

### Algorithms
- NLP : Reccurent Neural Networks (RNNs)
- Image Recognition Models : Convolutional Neural Networks (CNNs)


### Conclusion
Our team is dedicated to creating a reliable system for MPN identification and medication pricing comparison by incorporating these algorithms into our workflow. This approach will enhance the standardisation and dependability of medicine identification across various vendors in addition to making pricing comparisons more efficient. Our strategy is intended to satisfy the pharmaceutical industry's urgent need for precise, easily available, and thorough medication information.


