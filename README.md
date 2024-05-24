# Movie_Recommender
# Overview

This project is a Movie Recommender System that suggests movies based on content similarity. The system uses natural language processing and machine learning techniques to analyze movie metadata, such as genres, keywords, cast, and crew, to provide personalized recommendations.

# Features

Data Merging and Cleaning: Combined movie and credits datasets, processed essential columns.
Text Preprocessing: Applied stemming and vectorization to normalize and convert text data into vectors.
Similarity Calculation: Used cosine similarity to find and recommend movies with similar metadata.
Interactive Web Application: Built with Streamlit to allow users to input a movie title and receive recommendations along with movie posters.
# Technologies Used

Python
Pandas, NumPy
Scikit-learn
NLTK
Streamlit
Requests
# Setup Instructions

Clone the repository:

git clone https://github.com/yourusername/movierecommender.git
cd movierecommender
# Install dependencies:

pip install -r requirements.txt
Place the dataset files (tmdb_5000_movies.csv and tmdb_5000_credits.csv) in the project directory.
# Run the script to preprocess data and build the model:

python build_model.py
# Run the Streamlit app:

streamlit run app.py
# Usage

Open the Streamlit app in your browser.
Enter the name of a movie in the input box.
Click the "Recommend" button to get a list of recommended movies along with their posters.
# Project Structure


├── app.py              # Streamlit application
├── build_model.py      # Script to preprocess data and build the recommendation model
├── requirements.txt    # List of dependencies
├── tmdb_5000_movies.csv # Movies dataset
├── tmdb_5000_credits.csv # Credits dataset
└── README.md           # Project documentation
# Screenshots


![Screenshot (343)](https://github.com/Amisha-Raj/Movie_Recommender/assets/108174322/47d0c7aa-3a3c-47d6-9bbf-a6f8b224736b)

![Screenshot (345)](https://github.com/Amisha-Raj/Movie_Recommender/assets/108174322/423c7161-e93e-4a5a-9862-ff65ea72b52e)
![Screenshot (346)](https://github.com/Amisha-Raj/Movie_Recommender/assets/108174322/73808d12-ad3b-4d67-a322-4d1b11cc41f0)

# Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

#Acknowledgments

The Movie Database (TMDB) for the datasets.
Streamlit for providing an excellent framework for building web applications.

# Contact

For any questions or suggestions, feel free to contact me at amisharaj268@gmail.com
 
