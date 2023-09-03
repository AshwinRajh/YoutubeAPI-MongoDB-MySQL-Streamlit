# YoutubeAPI-MongoDB-MySQL-Streamlit

Project that combines the YouTube API, MongoDB, MySQL, and Streamlit to analyze and visualize YouTube data.
A brief overview about steps that were done for the project:

	Step 1: Imports necessary libraries, including Streamlit, pymongo, googleapiclient, pandas, and mysql.connector.
	
	Step 2: Defines functions to retrieve channel statistics, playlist IDs, video IDs, video statistics, and video comments from YouTube channels using the YouTube Data API.
	
	Step 3: Sets up a Streamlit user interface with options to collect data from YouTube and store it in a MongoDB Database and migrate that data to a MySQL database.
	
	Step 4: Allows the user to choose from a set of data analysis options, such as listing video names and their corresponding channels, identifying channels with the most videos, finding 		  the most viewed videos, and more. The analysis is performed using SQL queries on the MySQL database.
	
	Step 5: Executes the selected data analysis option and displays the results in a DataFrame using Streamlit.

