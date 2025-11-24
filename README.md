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

Create .env file and save the Client ID, Client Secret to the .env file.

# Dependencies
Upload Spotify JSON data to Azure using the Azure Storage Blob SDK

pip install azure-storage-blob

# Spotify Client Credentials Flow
<img width="783" height="677" alt="image" src="https://github.com/user-attachments/assets/a3e9ec5a-d0c6-4dc4-9e01-f2c82f5275dd" />

# Scopes 
Scopes grant authorization and information to third-party apps.
Link to the documentation: https://developer.spotify.com/documentation/web-api/concepts/scopes
