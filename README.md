# Movie Recommendation System

A machine learning-based movie recommendation system that suggests personalized movie recommendations based on user preferences and movie characteristics.

## Project Overview

This project implements a content-based and collaborative filtering recommendation system using the MovieLens dataset. The system analyzes movie features, user ratings, and credits to provide personalized movie recommendations.

## Dataset

The project uses the following datasets:
- `movies.csv`: Contains movie metadata including titles, genres, and release dates
- `ratings.csv`: Contains user ratings for movies
- `credits.csv`: Contains cast and crew information for movies
- `movies_small.csv`: A smaller subset of the movies dataset for testing

## Features

- Content-based filtering using movie features
- Collaborative filtering using user ratings
- Movie similarity analysis
- Personalized recommendations based on user preferences
- Support for both movie-to-movie and user-to-movie recommendations

## Getting Started

### Prerequisites

- Python 3.x
- Required Python packages (install using `pip install -r requirements.txt`):
  - pandas
  - numpy
  - scikit-learn
  - jupyter

### Installation

1. Clone the repository:
```bash
git clone https://github.com/AhmadTawil1/movie-recomendation-system.git
cd movie-recomendation-system
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Run the Jupyter notebooks:
```bash
jupyter notebook
```

## Usage

The project consists of three main notebooks:
1. `Notebook 1.ipynb`: Data preprocessing and exploration
2. `Notebook 2.ipynb`: Content-based filtering implementation
3. `Notebook 3.ipynb`: Collaborative filtering implementation

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Ahmad Tawil 