# EODP_Project2: Who Else Likes This Book?

## Overview
This project involves analyzing datasets containing information about books, users, and their reviews from an online bookstore. The goal is to extract actionable insights that can help the bookstore managers make decisions about future book acquisitions and recommendations.

## Datasets
1. **Main Datasets:**
   - `BX-Books.csv`: Details of 18,185 books, including ISBN, title, author, year of publication, and publisher.
   - `BX-Users.csv`: Information about 48,299 users (ID, city, state, country, age).
   - `BX-Ratings.csv`: User ratings of books (user ID, ISBN, rating).

2. **Recommendation Datasets**:
   - `BX-NewBooks.csv`: Information on 8,924 new books.
   - `BX-NewBooks-Users.csv`: Information on 8,520 users with existing rating histories.
   - `BX-NewBooks-Ratings.csv`: Actual ratings for new books.

## Key Tasks
1. **Data Preprocessing:** Apply at least three preprocessing techniques, such as data imputation, scaling, encoding, or text processing.
2. **Machine Learning Implementation:** Use at least two supervised/unsupervised models to answer your research question. Alternatively, implement a recommendation system.
3. **Insights and Evaluation:** Interpret and analyze results to derive meaningful insights and evaluate the models’ performance.

## Code Instructions
1. Clone the repository or download the files.
2. Ensure all required libraries are installed.
3. Open EODP_A2_CODE and press RUN ALL.

DEBUGGING:
- Please ensure all dependencies are met
- Code may not run properly on ed due to lack of memory
- There may be a problem with nan in the cities fuzzy matching but could not recreate error

NOTE:
- Some parts of the code can take up to 90 seconds to run, entire code should take around 5 minutes

## Tools used  
- Python
- pandas, numpy, re, matplotlib, sklearn, seaborn, nltk

## Methods used 
- Data Cleaning
- Fuzzy Matching
- KNN Imputation
- Encoding
- Feature Selection using Mutual Information
- Cross Validation
- Supervised Data Modeling (Decision Trees, K Nearest Neighbours)

## Contributors
- Kerui Huang
- Peter Lu
- Dylan Tran
- University of Melbourne COMP20008 Teaching Team (Project Specifications and dataset Provider)

## License
This project is for academic purposes under the University of Melbourne's COMP20008 course.
