# YouTube API Scraper
This is a Python script that uses the YouTube API to scrape data from four different YouTube channels. The script gathers information about the videos uploaded to each channel, including the title, description, view count, like count, dislike count, and comment count.

Getting Started
To use this script, you'll need to have a Google account and create a project in the Google Developers Console. Follow these steps:

Go to the Google Developers Console.
Create a new project and enable the YouTube Data API v3.
Create a new API key and make sure to restrict it to the YouTube Data API.
Once you have your API key, clone this repository and create a new Python virtual environment:

git clone https://github.com/your-username/youtube-api-scraper.git
cd youtube-api-scraper
python3 -m venv env
source env/bin/activate

Next, install the required packages:


pip install -r requirements.txt

Finally, create a .env file in the root directory of the project with your API key:

API_KEY=your_api_key_here

Usage
To use the script, simply run the following command:

python scraper.py

This will scrape data from four different YouTube channels (change the channel IDs in channels.txt to scrape data from different channels). The script will output a CSV file with the following columns:

Channel Name
Video Title
Video Description
View Count
Like Count
Dislike Count
Comment Count
The CSV file will be saved to the output directory.

Contributing
Contributions are welcome! If you'd like to contribute to this project, please create a pull request.






