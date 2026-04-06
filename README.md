# Automated-News-Data-Scraper-Content-Archival-System

## About The Project


A Python-based automated web scraping system that collects and archives technology articles from The Guardian using their API. The project extracts article titles and full content, organizes them into structured text files, and stores them in timestamped directories for efficient data management and future analysis.


## Installation Steps

### Installation from GitHub

Follow these steps to install and set up the project directly from the GitHub repository:

1. **Clone the Repository**
   - Open your terminal or command prompt.
   - Navigate to the directory where you want to install the project.
   - Run the following command to clone the GitHub repository:
     ```
     git clone https://github.com/KalyanMurapaka45/Article-Web-Scraping.git
     ```

2. **Create a Virtual Environment** (Optional but recommended)
   - It's a good practice to create a virtual environment to manage project dependencies. Run the following command:
     ```
     conda create -p <Environment_Name> python==<python version> -y
     ```

3. **Activate the Virtual Environment** (Optional)
   - Activate the virtual environment based on your operating system:
       ```
       conda activate <Environment_Name>/
       ```

4. **Install Dependencies**
   - Navigate to the project directory:
     ```
     cd [project_directory]
     ```
   - Run the following command to install project dependencies:
     ```
     pip install -r requirements.txt
     ```

5. **Run the Project**
   - Start the project by running the appropriate command.
     ```
     python app.py
     ```

6. **Access the Project**
   - Open a web browser or the appropriate client to access the project.
   
  
## Usage and Configuration

### Guardian API Key

This project requires an API key from The Guardian to fetch article data. If you don't already have one, you can obtain an API key by following these steps:

1. Visit The Guardian Developer Portal: [The Guardian API Developer Portal](https://open-platform.theguardian.com/access/)

2. Sign up for an account or log in if you already have one.

3. Create a new application and obtain your API key.

### Configuration

Once you have obtained your API key, you need to configure the project to use it. Here's how to do it:

1. Open the Python script where you make the API request (the one with the URL to The Guardian's API).

2. Locate the `URL` variable that contains the API request URL.

3. In the URL, replace `YOUR_API_KEY` with the actual API key you obtained from The Guardian.



