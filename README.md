# YouTube Scraping Project Overview
## Overview

The YouTube Scraping project utilizes the Google API Client to interact with the YouTube Data API. The script establishes a connection to the API using an API key, allowing for the extraction of channel and video details. The project provides a comprehensive solution for extracting and storing valuable information from YouTube.

## Getting Started

  1. Clone the Repository: Begin by cloning the project repository to your local machine using the following command:

       git clone https://github.com/MKGourab/youtube_scrapping
  2. Update Credentials: Open the credentials.py file and update the API Key, MongoDB database username, and password with your own credentials.
  3. Install Dependencies: Install the required Python packages by running:

       pip install -r requirements.txt

  4. Run the Application: Execute the application.py script to start the YouTube scraping application.

  5. Access the Application: Open a web browser and navigate to the provided URL to access the application. Explore channel and video details as well as perform YouTube video scraping.

  6. Deployment: If you want to deploy the application, it can be deployed using AWS Elastic Beanstalk. Refer to the AWS Elastic Beanstalk documentation for deployment instructions.

  7. Data Usage: Please note that the extracted data is used solely for educational purposes and is not intended for commercial use. Any data retrieved is temporary and will be removed from the deployed server.



## Project Structure
<pre>
<code>
project_root/
│
├── .ebextensions/
│   └── python.config       # Configuration for AWS Elastic Beanstalk deployment
│
├── .elasticbeanstalk/
│   └── config.yml          # Elastic Beanstalk configuration settings
│
├── application.py          # Application entry point (main script)
├── build.py                # creates a connection to the YouTube Data API using an API key, facilitating interactions with the API                                   for retrieving channel and video details.
├── credentials.py          # Module for managing credentials (e.g., API keys)
├── mongo_op.py             # Module for uploading the retrieved data to MongoDB (Mongo operations)
├── requirements.txt        # List of Python dependencies
└── utility.py              # Module containing general utility functions

</code>
</pre>


## Output as shown below.

### Homepage:

<img width="959" alt="Homepage" src="https://github.com/MKGourab/youtube_scrapping/assets/104300031/caa68913-7a5d-4fec-8e0a-7e8a02244de7">

### Video Details:

<img width="950" alt="video details" src="https://github.com/MKGourab/youtube_scrapping/assets/104300031/5707084c-c5a2-4487-8f87-bcb01f88fa04">

### Mongo DB:

<img width="957" alt="Mongodb" src="https://github.com/MKGourab/youtube_scrapping/assets/104300031/41752d1f-f77e-463e-80c2-fe5ede449bb4">

### AWS Beanstalk Deployment:

<img width="950" alt="AWS beanstalk Deployment" src="https://github.com/MKGourab/youtube_scrapping/assets/104300031/0e97404f-e938-4f7a-bb38-a075de8ab1ab">
