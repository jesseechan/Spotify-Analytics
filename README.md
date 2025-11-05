# Spotify API Analytics with Azure Databricks and Snowflake

This project analyzes Spotify streaming and generates insights like top artists by popularity, genre, and audio features. It is an end-to-end data pipeline that pulls real music data from the Spotify Web API, processes and enriches through Azure, Databricks, and loads it into Snowflake for analytics and visualization.

# Tech Stack
- Python ('spotipy', 'pandas')
- Azure
- Databricks
- Snowflake

# Quick Start/ Setup
Set up Spotify Developer account by creating App to gain access to:
- Client ID
- Client Secret

# Dependencies
-upload Spotify JSON data to Azure using the Azure Storage Blob SDK
pip install azure-storage-blob
