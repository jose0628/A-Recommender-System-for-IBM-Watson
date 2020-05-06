# A-Recommender-System-for-IBM-Watson

Based on interactions that users have with articles on the IBM Watson Studio platform, I designed a recommended system, which makes recommendations of articles to users. The type of recommended systems selected are:

* Rank Based Recommendations
* User-User Based Collaborative Filtering

## Project Requirements

* Jupiter Notebook with Python3 and [Anaconda Distribution](https://www.anaconda.com/products/individual) (recommended)

## Project Structure

    .
    ├── app     
    │   ├── run.py                           # Flask file that runs app
    │   └── templates   
    │       ├── go.html                      # Classification result page of web app
    │       └── master.html                  # Main page of web app    
    ├── data                   
    │   ├── disaster_categories.csv          # Dataset including all the categories  
    │   ├── disaster_messages.csv            # Dataset including all the messages
    │   └── process_data.py                  # Data cleaning
    ├── models
    │   └── train_classifier.py              # Train ML model    
    ├── pipeline_design     
        │   ├── ETL Pipeline Preparation.ipynb   # Design of the ETL Pipeline
        │   └── ML Pipeline Preparation.ipynb    # Design of the ML Pipeline       
    └── README.md



### Instructions:
1. 
