# MongoDB--Movies

## Description
  The purpose of this code is to plot movie data and identify unusual movies that seem different from others. The task is to discover and address bad data in the data set, including outliers. To do this we will connect our Jupyter notebook to our MongoDB instance, write queries, and display results to identify the problematic data.

  ## Table of Contents
  * [Installation](#installation)
  * [Author](#author)
  * [Username](#username)
  * [License](#license)
  
  ## Installation
  1. Download the  ```imdb_superhero_2.csv``` and  ```metacritic_movies.csv``` files into a MongoDB database

  2. Obtain your mongodb connection string

  3. Clone the repositary to your local computer 

  4. Create a secrets file that is not part of your Jupyter notebook. For example, you might save it as "credentials.json". It should contain the following text: 
  ```
    {
        "mongodb": "mongodb+srv://... here is where I put my MongoDB connection string ..."
    }
  ```

  5. Open ```DetectingOutliers.ipynb``` and replace the following code from line 5 with your file path to your secret file (Credentials.json)
  ```
  with open(r'C:\Users\kater\anaconda3\MongoDB--Movies\Credentials.json') as f:
  ```

  6. Make sure to install the following libraries before running your code 

  ```pip install pymongo ```

  ```pip install certifi ```

  ```pip install pandas ```

  ```pip install regex```

  ```pip install matplotlib ```

  ```pip install seaborn ```

  ```pip install regex```

  7. Run your code to visualize charts of the same data (Budget and Runtime against the 2015 Release Date)

  8. Note... Code runs in Python version 3.12

  ## Author
  Kateryna Tekmenzhi
  
  ## Github Username
  KaterynaTekmenzhi
  
  ## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


