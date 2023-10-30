# YouTube-Data-Harvesting-and-Warehousing-using-SQL-MongoDB-and-Streamlit
Introduction

YouTube Data Harvesting and Warehousing is a project aimed at developing a user-friendly Streamlit application that leverages the power of the Google API to extract valuable information from YouTube channels. The extracted data is then stored in a MongoDB database, subsequently migrated to a SQL data warehouse, and made accessible for analysis and exploration within the Streamlit app.


Some of the key features include:

Retrieve channel statistics: Get detailed information about YouTube channels, including subscriber count, view count, video count, and other relevant metrics.

Fetch video details: Extract data such as video title, description, duration, view count, like count, dislike count, and publish date for individual videos.

Analyze comments: Retrieve comments made on YouTube videos and perform analysis, such as sentiment analysis or comment sentiment distribution.

Generate reports: Generate reports and visualizations based on the collected data, allowing users to gain insights into channel performance, video engagement, and audience interaction.

Data storage: Store the collected YouTube data in a database for easy retrieval and future reference.


Technologies Used
Python: The project is implemented using the Python programming language.

YouTube Data API: Utilizes the official YouTube Data API to interact with YouTube's platform and retrieve data.

Streamlit: The user interface and visualization are created using the Streamlit framework, providing a seamless and interactive experience.

MongoDB: The collected data can be stored in a MongoDB database for efficient data management and querying.

PostgreSQL: A powerful open-source relational database management system used to store and manage the retrieved data.

PyMongo: A Python library that enables interaction with MongoDB, a NoSQL database. It is used for storing and retrieving data from MongoDB in the YouTube Data Scraper.

Psycopg2: A PostgreSQL adapter for Python that allows seamless integration between Python and PostgreSQL. It enables the YouTube Data Scraper to connect to and interact with the PostgreSQL database.

Pandas: A powerful data manipulation and analysis library in Python. Pandas is used in the YouTube Data Scraper to handle and process data obtained from YouTube, providing functionalities such as data filtering, transformation, and aggregation.



Process Flow
Obtain YouTube API credentials: Visit the Google Cloud Console.

Create a new project or select an existing project.

Enable the YouTube Data API v3 for your project.

Create API credentials for youtube API v3.


ETL Process
Extracting Data from youtube API.

Transforming data into required format.

Loading Data into SQL

Input the Channel Id and click on Get Channel Statistics in order to retrive data from Youtube API.

Next click on Push to MongoDB to store data in MongoDB Lake.

Select a channel name from the dropdown Channel Details and click on Push to SQL to import data into PostgreSQL.

Once imported, you can select the Analysis and Reports Page from the drop down to get a detailed analysis of the collected data.
