# 🎬 Netflix Movie Streaming Analysis
This project is a Netflix movie streaming dataset analysis completed using Python.
It focuses on exploring the data, cleaning it, and visualizing key insights related to genres, vote averages, popularity, and movie release years.

## 📂 Project Structure
• Data Loading
• Exploratory Data Analysis (EDA)
• Data Cleaning
• Feature Engineering
• Visualization
• Insights and Conclusion

## 🛠️ Technologies Used
• Python 🐍
• Pandas 📊
• NumPy ➗
• Matplotlib 📈
• Seaborn 🎨

## 📄 Dataset Information
The dataset (mymoviedb.csv) includes information like:

• Movie Title
• Overview
• Popularity
• Vote Count
• Vote Average
• Original Language
• Genre
• Poster URL
• Release Date

## 📊 Analysis Performed
• Null Value Handling: No missing values found.
• Duplicate Handling: No duplicate records found.
• Dropped Columns: Overview, Original_Language, Poster_Url were dropped.
• Date Processing: Converted Release_Date to year.
• Genre Processing: Exploded genre into multiple rows.
• Vote Categorization: Vote_Average was categorized into Not Popular, Below Average, Average, and Popular.

## 📈 Key Visualizations
🎥 Most frequent movie genres
⭐ Popularity distribution based on vote averages
🏆 Highest and lowest popularity movies
📅 Number of movies produced per year

## 🔍 Key Insights
✅ Most Frequent Genre:
Drama is the most common genre in the dataset.
✅ Highest Votes Genre:
Drama leads with the highest number of popular votes.
✅ Most Popular Movie:
Spider-Man: No Way Home (Genres: Action, Adventure, Science Fiction)
✅ Least Popular Movies:
The United States vs. Billie Holiday and Threads.
✅ Most Productive Year:
2020 had the highest number of movies produced.
