# spotify-notebook

A Jupyter notebook for visualizing user top artist / track data in Spotify.

Data time range can be configured by setting the `t_range` variable. Acceptable values include:

- `short_term`
- `medium_term`
- `long_term`

Track Attributes:

- Danceability
- Energy
- Loudness
- Speechiness
- Acousticness
- Instrumentalness
- Liveness
- Valence
- Tempo

Data can be sorted by individual columns by setting the `sort_attribute` variable.

## Getting Started

1. Set up a [Spotfiy Developer account](https://developer.spotify.com/).
2. Create a custom Spotfy app via the App Dashboard, adding `http://localhost:8080` as a valid redirect URI.
3. Rename `setup.env` to `.env`.
4. Populate the missng `.env` values from the custom Spotify app.
5. [OPTIONAL] Enable virtual environment.
6. Install requirements (`pip install -r requirements.txt`).
7. Run the notebook: `jupyter notebook`
