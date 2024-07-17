# Anime Recommendation System

Welcome to the Anime Recommendation System! This project is designed to help users find new anime to watch based on their current favorites. By entering the name of an anime, our model suggests several related animes that the user might enjoy.

## Features

- **Search-Based Recommendation:** Users can input the name of an anime and receive a list of recommended animes related to it.
- **Machine Learning Model:** The recommendations are generated using a trained machine learning model.
- **User-Friendly Interface:** The project includes a Google Colab notebook to run the model and provide recommendations, designed to look and feel like a responsive web app.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Mohini17/anime-recommendation-system.git
   cd anime-recommendation-system
2.Requirements:
- **Make sure you have the following installed:**

- Python 3.x
- Jupyter Notebook or Google Colab
- **Dependencies:**
**Install the necessary Python libraries:**
  ```bash
  pip install -r requirements.txt
## Usage
- **Open the Colab Notebook:**

Navigate to Anime_Recommendation_System.ipynb to open the notebook in Google Colab.
Run the Notebook:

- **Follow the instructions in the notebook to run each cell. This will load the model and display the user interface for entering an anime name and getting recommendations.**
Enter an Anime Name:

In the input cell provided in the notebook, enter the name of an anime.
The notebook will output a list of recommended animes based on the entered name.

## About CountVectorizer and Cosine Similarity
In this project, we use the CountVectorizer from the scikit-learn library for text processing and cosine_similarity for measuring the similarity between anime tags. These tools are essential for transforming textual data into a format suitable for our machine learning model and for finding similar animes based on tags.

## About Model Building
**CountVectorizer**
CountVectorizer converts a collection of text documents to a matrix of token counts, making it possible to analyze and learn from textual data.

**Steps:**

- **Tokenization:** Splits text data into individual terms (tokens).
- **Building the Vocabulary:** Constructs a vocabulary of unique tokens.
- **Encoding the Text:** Transforms text documents into vectors where each element represents the count of a token.

## Cosine Similarity
cosine_similarity is used to measure the similarity between vectors. In this project, it helps in finding how similar different animes are based on their tags.

- **Steps:**

- **Vector Representation:** Each anime's tags are represented as a vector.
- **Similarity Calculation:** Computes the cosine similarity between vectors, indicating how similar they are.

## Integration in the Anime Recommendation System
The combination of CountVectorizer and cosine_similarity enables the system to recommend animes based on tag similarity:

- **Text Processing:** The CountVectorizer processes anime tags, converting them into vectors.
- **Similarity Calculation:** cosine_similarity calculates the similarity between these vectors.
- **Recommendation Generation:** Based on the similarity scores, the system recommends animes that are similar to the user's input.
By leveraging these tools, our anime recommendation system can effectively analyze and recommend animes based on textual data, providing users with relevant suggestions.

## Contributing
I welcome contributions! If you have suggestions for improvements or have found a bug, please open an issue or submit a pull request.

## Acknowledgements
Thanks to  the **CampusX's** (you tube channel) Nitish sir **Best ML Tutor**. He made movie recommendation system on tmdb dataset from which i made this anime recommendation sysytem with some modifications in code and learn a lot while doing this project great experience
, Special thanks to the creators of the datasets and the tools used in this project.
