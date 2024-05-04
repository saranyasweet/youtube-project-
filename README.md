# YOUTUBE DATA HARVESTING AND WAREHOUSING
INTRODUCTION:

YouTube Data Harvesting and Warehousing is a project aimed at developing a user-friendly Streamlit application that leverages the power of the Google API to extract valuable information from YouTube channels. The extracted data is then stored in a MongoDB database, subsequently migrated to a SQL data warehouse, and made accessible for analysis and exploration within the Streamlit app.

TABLE OF CONTENT:

Key Technologies and Skills
Installation
Usage
Features
Retrieving data from the YouTube API
Storing data in MongoDB
Migrating data to a SQL data warehouse

SKILLS TAKEAWAY:

Python scripting
Data Collection
API integration
Streamlit
Plotly
Data Management using MongoDB (Atlas) and SQL

FEATURES:

Retrieve data from the YouTube API, including channel information, playlists, videos, and comments.
Store the retrieved data in a MongoDB database.
Migrate the data to a SQL data warehouse.
Analyze and visualize data using Streamlit and Plotly.
Perform queries on the SQL data warehouse.

RETRIEVING DATA FROM YOUTUBE API

The project utilizes the Google API to retrieve comprehensive data from YouTube channels. The data includes information on channels, playlists, videos, and comments. By interacting with the Google API, we collect the data and merge it into a JSON file.

STORING DATA IN MongoDB

The retrieved data is stored in a MongoDB database based on user authorization. If the data already exists in the database, it can be overwritten with user consent. This storage process ensures efficient data management and preservation, allowing for seamless handling of the collected data.

MIGRATE DATA TO SQL

The application allows users to migrate data from MongoDB to a SQL data warehouse. Users can choose which channel's data to migrate. To ensure compatibility with a structured format, the data is cleansed using the powerful pandas library. Following data cleaning, the information is segregated into separate tables, including channels, playlists, videos, and comments, utilizing SQL queries.


CONCLUSION

Contributions to this project are welcome! If you encounter any issues or have suggestions for improvements, please feel free to submit a pull request.

Contact

📧 Email: saranyasweety770@gmail.com

🌐 LinkedIn:https://www.linkedin.com/in/saranya-s-71b6b6270

For any further questions or inquiries, feel free to reach out. We are happy to assist you with any queries.
