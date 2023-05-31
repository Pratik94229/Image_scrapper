# Image Scraper Project

This project is a web application built using Flask that allows users to scrape images and store them in a local folder as well as in a MongoDB database.

## Features

- Users can enter a search term to scrape images from a specific source.
- The scraped images are saved in a local folder for later access.
- The scraped images are also stored in a MongoDB database for persistence.

## Prerequisites

Before running the application, ensure you have the following prerequisites installed:

- Python 3.7 or above
- Flask
- pymongo
- Requests

## Getting Started

1. Clone the repository:

git clone https://github.com/Pratik94229/Image_scrapper.git



2. Install the required dependencies:

pip install -r requirements.txt


3. Set up the MongoDB connection:

- Make sure you have MongoDB installed and running on your local machine or specify the remote MongoDB connection URL in the application code.

4. Start the Flask application:

python app.py



5. Access the web application in your browser at `http://localhost:8000`.

## Usage

1. Enter a search term in the provided input field and click the "Scrape Images" button.
2. The application will scrape images related to the entered search term.
3. The scraped images will be saved in the local `images` folder.
4. The scraped images will also be stored in the MongoDB database for later retrieval.

## Folder Structure

The project folder is structured as follows:

├── app.py # Flask application file
├── requirements.txt # Required Python dependencies
├── templates # HTML templates for the Flask application
│ └── index.html
├── static # Static assets (CSS, JS, images)
│ ├── css
│ │ └── style.css
│ └── images # Folder to store scraped images
└── README.md # Project documentation (you're reading it!)


## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

