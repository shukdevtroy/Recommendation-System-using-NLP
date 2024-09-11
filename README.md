# Netflix Data Analysis and Recommendation System

This repository contains a comprehensive analysis and recommendation system for Netflix movies and TV shows using a dataset of Netflix titles. The project involves data cleaning, visualization, and building a content-based recommendation system using similarity metrics.

## Project Overview

The project consists of the following main components:

1. **Data Cleaning and Preparation**: Cleaning the Netflix dataset by handling missing values and preparing it for analysis.
2. **Exploratory Data Analysis (EDA)**: Visualizing the dataset to gain insights into the distribution of movies and TV shows, their categories, countries of origin, and runtime.
3. **Recommendation System**: Building a content-based recommendation system using cosine similarity based on the combined features of movies and TV shows.
4. **User Interface**: Implementing a GUI using Tkinter for users to interact with the recommendation system.

## Installation and Setup

To get started, clone the repository and install the necessary dependencies. 

### Clone the Repository

```bash
git clone https://github.com/shukdevtroy/Recommendation-System-using-NLP.git
cd Recommendation-System-using-NLP
```

### Install Dependencies

Ensure you have Python installed. Install the required packages using pip:

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn 
```

## Data

The dataset used in this project is `netflix_titles.csv`, which should be placed in the root directory of the project. 

## Scripts and Usage

### 1. Data Cleaning and Preparation

The script loads the dataset, cleans it by removing rows with missing values, and separates it into movies and TV shows. 

### 2. Exploratory Data Analysis

Visualizations are created to understand the distribution of movies and TV shows by country, category, and runtime. Key visualizations include pie charts, bar plots, and scatter plots.

### 3. Recommendation System

The content-based recommendation system is implemented using cosine similarity. The system uses features like `director`, `cast`, `country`, `description`, and `listed_in` to compute similarities between titles.

### 4. User Interface

A simple Tkinter-based GUI allows users to input a movie or TV show title and receive recommendations for similar content.

## Notes

- Ensure that `netflix_titles.csv` is in the same directory as the script files.
- The GUI code uses Tkinter, which is included in the standard Python library.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests. If you find any bugs or have suggestions for improvements, please let us know.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- Data source: Uploaded above 
- Libraries: pandas, numpy, matplotlib, seaborn, plotly, scikit-learn, tkinter

---

Feel free to adjust the paths, project names, and other specific details to fit your project structure and personal preferences.
