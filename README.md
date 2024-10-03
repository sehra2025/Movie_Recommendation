# Movie Recommendation System

## Project Overview
This project builds a **Movie Recommendation System** that suggests movies to users based on their preferences. The system uses machine learning techniques like **collaborative filtering** and **content-based filtering** to make personalized movie recommendations.

## How It Works
1. **Collaborative Filtering**: Recommends movies based on what similar users have liked.
2. **Content-Based Filtering**: Recommends movies similar to ones the user has rated highly in the past.

## Requirements
To run this project, install the following Python libraries:
- pandas
- numpy
- scikit-learn

You can install them using:
```bash
pip install -r requirements.txt
```

## How to Run
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/movie-recommendation.git
   cd movie-recommendation
   ```

2. **Run the Jupyter Notebook**:
   Start Jupyter and open the notebook:
   ```bash
   jupyter notebook movie_recommendation.ipynb
   ```

3. **Follow the instructions in the notebook** to preprocess the data, train the models, and generate movie recommendations.

## Data
The notebook uses a dataset of movie ratings, which includes:
- **User Ratings**: Ratings provided by users for various movies.
- **Movie Information**: Details about the movies such as titles, genres, etc.

You can replace this with your own dataset by modifying the data loading section.

## Results
The system provides movie recommendations and evaluates the performance using metrics like **accuracy** and **RMSE**.

## License
This project is open-source and free to use under the MIT License.
