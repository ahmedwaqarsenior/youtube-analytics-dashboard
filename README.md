# YouTube Analytics Dashboard

A mid-level project that uses the YouTube Data API v3 to analyze video and channel performance. This tool provides insights such as view trends, most engaged content, subscriber growth, and more.

## Features
- Fetch public video/channel stats via YouTube API
- Visualize views, likes, comments, and publish trends
- Filter videos by keyword, date range, or performance
- Export data to CSV for further analysis

## Tech Stack
- Python 3
- Pandas
- Matplotlib / Seaborn
- YouTube Data API v3

## Setup Instructions
1. Clone the repo: `git clone https://github.com/yourusername/youtube-analytics-dashboard.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Create a `config.py` with your API key:
    ```python
    YOUTUBE_API_KEY = 'YOUR_API_KEY_HERE'
    ```
4. Run the app: `python main.py`

## License
This project is licensed under the MIT License.
