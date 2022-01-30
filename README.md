# AI-IMDBReviewClassifier

(Machine Learning - Labelled Data)
This program is an introductory exerciser to Machine Learning. In short, the program scrapes IMDB for The Office Episode reviews, or any show/movie can be given. Then from this collected DataSet, its determined if it was a good or bad review by checking the rating the user gave (>= 8 stars is good), hence this is labelled data. The text/wording used in a review is organized into a category of good or bad based on classification of the review.

Now that certain words in both classes (good and bad review) have been collected from the labelled data, a Vocabulary (word frequency) then The classification Model (Compute the frequency and its conditional probability from the Vocabulary) can be build. Now a simple Machine Learning model has been trained with labelled data, new reviews are tested against the model to classify if they are good or bad reviews. The results of the model are outlined and detailed in the text files of the Repo.

## Notes:
This assignment was made using jupyter notebooks which can be installed using:
- pip install notebook
    
Note: This was coded with python 3.8.5, although any recent version of python (3.5+) should be sufficient.

To install this project's dependencies simply run:
- pip install numpy
- pip install matplotlib
- pip install beautifulsoup4

Then, in the project directory, run: jupyter notebook

List of libraries:
- numpy
- matplotlib
- math
- re
- csv
- bs4
- requests

## How to run the program:
1. If you are injecting your own data.csv file to follow the csv format you must add "Name,Season,Review Link,Year" as the first line of the file
2. Run the second cell (the one with the imports and global variables)
3. To test Part 1 of the assignment: Go to cell "Driver for Part 1"
    - Step 1: Run all the cells above
    - Step 2: If you no longer need to scrape (if you dont want to overwrite the data.csv), comment out the scraping() method
    - Step 3: Run this cell
4. To test Task 2.1 of the assignment: Go to cell "Driver Task 2.1 Infrequent Word Filtering"
    - Step 1: Run Driver for Part 1 once above if you have never yet
    - Step 2: Run this cell
5. To test Task 2.3 of the assignment: Go to cell "Driver Task 2.3 Word Length Filtering"
    - Step 1: Run Driver for Part 1 once above if you have never yet
    - Step 2: Run this cell