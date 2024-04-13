# YouTube-Data-Analysis-Project
Analyze YouTube channel stats &amp; video data using Python &amp; YouTube API. Gain insights on views, engagement, &amp; audience behavior. Optimize content strategy with data-driven decisions.
#### Introduction:
This project involves analyzing YouTube channel statistics and video data using the YouTube Data API. The goal is to gain insights into channel performance, video engagement, and audience behavior.

#### Technologies Used:
- Python
- Google API Client
- Pandas
- Seaborn
- Matplotlib
- NLTK
- WordCloud

#### Project Structure:
- **`youtube_data_analysis.ipynb`**: Jupyter Notebook containing the Python code for data collection, preprocessing, exploratory data analysis, and visualization.
- **`README.md`**: Documentation detailing project overview, technologies used, and instructions for running the notebook.
- **`requirements.txt`**: List of Python dependencies required to run the project.
- **`LICENSE`**: License information for the project.

#### Data Collection:
- Utilized the YouTube Data API to retrieve channel statistics and video details.
- Extracted information such as subscribers, views, video count, video titles, descriptions, tags, and publication dates.

#### Data Preprocessing:
- Handled missing values and converted data types.
- Extracted additional features like day of the week for video publication and converted video duration to seconds.

#### Exploratory Data Analysis (EDA):
- Analyzed video performance metrics such as views, likes, comments, and duration.
- Visualized data using bar plots, violin plots, scatter plots, and histograms.
- Generated a word cloud to visualize frequent words in video titles.

#### Project Outcome:
- Identified best and worst-performing videos based on views.
- Explored relationships between views, likes, comments, and video duration.
- Investigated the distribution of views across different days of the week.
- Visualized word frequencies in video titles using a word cloud.

#### Conclusion:
This project provides valuable insights into YouTube channel performance and audience engagement, which can inform content strategy and optimization efforts.

### How to Run:
1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Open and run the `youtube_data_analysis.ipynb` notebook in a Jupyter environment.

#### License:
This project is licensed under the [MIT License](LICENSE).
