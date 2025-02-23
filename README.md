# Movie Recommendation System

This is a **Movie Recommendation System** built using **Streamlit** and **Pickle**, which recommends movies based on a given movie title using a similarity model.

## Features
- Enter a movie title, and the system will recommend **five similar movies**.
- Displays **movie posters** for better visualization.
- Uses **The Movie Database (TMDb) API** to fetch movie posters.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-recommender.git
   cd movie-recommender
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Ensure you have the required model files:
   - `movie_list.pkl`
   - `similarity.pkl`
   
   These files should be placed inside a `model` folder.

## Running the Application

Run the Streamlit app using:
```bash
streamlit run app.py
```

## Dependencies
- `streamlit`
- `pickle`
- `requests`
- `pandas`

Install dependencies using:
```bash
pip install -r requirements.txt
```

## Usage
1. Select or type a movie title from the dropdown list.
2. Click on **'Show Recommendation'**.
3. The system will display **five recommended movies** with their **posters**.

## API Usage
This project uses **TMDb API** to fetch movie posters. Ensure the API key is correctly set within the script.

## Notes
- The system uses a **precomputed similarity matrix** to recommend movies.
- Make sure that the **movie_list.pkl** and **similarity.pkl** files are updated.

