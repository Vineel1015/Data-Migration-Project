YouTube Channel Analytics Project
This project uses Python to fetch and analyze key statistics from YouTube channels, allowing users to gain insights into channel growth and audience engagement. The code connects to the YouTube Data API, retrieves data on channel metrics, and processes this information into a structured format for visualization and analysis.

Key Features:
Data Retrieval: Uses Google API client to connect to the YouTube Data API, fetching data such as subscriber count, total views, and video count.
Data Processing: Aggregates the fetched data into a DataFrame, enabling further manipulation and analysis with libraries like Pandas.
Visualization: Generates visual insights using Seaborn to help understand trends and comparisons across different channels.
How it Works:
Specify YouTube channel IDs.
Run get_channel_stats to pull statistics for each channel.
Process and display the data to understand and visualize audience engagement metrics.
