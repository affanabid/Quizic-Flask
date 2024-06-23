# Spotify Music Quiz App
This is a Flask web application that allows users to play a music quiz based on songs from their favorite artists on Spotify. Users authenticate with their Spotify accounts, select an artist, and then guess the track names of randomly selected songs by the chosen artist.

## Deployment Guide
### Prerequisites
Before you begin, ensure you have the following installed on your local machine:

* Python 3.8 or higher
* pip (Python package installer)
* Spotify Developer account (to obtain client ID and client secret)


**1. Clone the Repository**:
Clone the GitHub repository to your local machine using the following command

*git clone https://github.com/your-username/spotify-music-quiz-app.git*

Replace your-username with your actual GitHub username.

**2. Navigate to the Project Directory:**

*cd spotify-music-quiz-app*

**3. Set Up a Virtual Environment**
Create a virtual environment to manage project dependencies

*python -m venv venv*

**4. Install Dependencies**:
Install the required packages using pip:

*pip install -r requirements.txt*

**5. Configure Spotify API Credentials**:
Create a file named .env in the project root directory and add your Spotify API credentials:


*SPOTIPY_CLIENT_ID='your_client_id'*

*SPOTIPY_CLIENT_SECRET='your_client_secret'*

*SPOTIPY_REDIRECT_URI='http://127.0.0.1:5000/callback'*

Replace your_client_id and your_client_secret with your actual Spotify API client ID and secret.

**6. Run the Application**
Start the Flask application:

*python app.py*

Open your web browser and navigate to http://127.0.0.1:5000 to access the application.

**7. Contributing**
If you'd like to contribute to this project, please fork the repository and use a feature branch. Pull requests are warmly welcome.
