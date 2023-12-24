YouTube Data Harvesting and Warehousing
Introduction
YouTube Data Harvesting and Warehousing is a project aimed at developing a user-friendly Streamlit application that leverages the power of the Google API to extract valuable information from YouTube channels. The extracted data is then stored in a MongoDB database, subsequently migrated to a SQL data warehouse, and made accessible for analysis and exploration within the Streamlit app.

Table of Contents
Key Technologies and Skills
Installation
Usage
Features
Retrieving Data from the YouTube API
Storing Data in MongoDB
Migrating Data to a SQL Data Warehouse
Data Analysis
Contributing
License
Contact
Key Technologies and Skills
Python scripting
Data Collection
API integration
Streamlit
Data Management using MongoDB (Atlas) and SQL
Installation
To run this project, you need to install the following packages:

bash
Copy code
pip install google-api-python-client
pip install pymongo
pip install pandas
pip install psycopg2
pip install streamlit
Usage
To use this project, follow these steps:

Clone the repository: git clone https://github.com/scholarisravi/YouTube-Data-Harvesting-and-Warehousing.git
Install the required packages: pip install -r requirements.txt
Run the Streamlit app: streamlit run app.py
Access the app in your browser at http://localhost:8501
Features
Retrieve data from the YouTube API, including channel information, playlists, videos, and comments.
Store the retrieved data in a MongoDB database.
Migrate the data to a SQL data warehouse.
Analyze and visualize data using Streamlit.
Perform queries on the SQL data warehouse.
Gain insights into channel performance, video metrics, and more.
Retrieving Data from the YouTube API
The project utilizes the Google API to retrieve comprehensive data from YouTube channels. The data includes information on channels, playlists, videos, and comments. By interacting with the Google API, we collect the data and merge it into a JSON file.

Storing Data in MongoDB
The retrieved data is stored in a MongoDB database based on user authorization. If the data already exists in the database, it can be overwritten with user consent. This storage process ensures efficient data management and preservation, allowing for seamless handling of the collected data.

Migrating Data to a SQL Data Warehouse
The application allows users to migrate data from MongoDB to a SQL data warehouse. Users can choose which channel's data to migrate. To ensure compatibility with a structured format, the data is cleansed using the powerful pandas library. Following data cleaning, the information is segregated into separate tables, including channels, playlists, videos, and comments, utilizing SQL queries.

Data Analysis
The project provides comprehensive data analysis capabilities using Streamlit. The Streamlit app offers an intuitive interface to interact with the data, allowing users to customize visualizations, filter data, and explore insights. Although Plotly was initially mentioned, it is not used in the current version of the project.

Contributing
Contributions to this project are welcome! If you encounter any issues or have suggestions for improvements, please feel free to submit a pull request.

License
This project is licensed under the MIT License. Please review the LICENSE file for more details.

Contact
📧 Email: scholarisravi@gmail.com

For any further questions or inquiries, feel free to reach out. We are happy to assist you with any queries.

