# Online Gaming Behavior EDA

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Overview](#dataset-overview)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Distribution of Player Ages](#distribution-of-player-ages)
  - [Gender Distribution](#gender-distribution)
  - [Play Time by Gender](#play-time-by-gender)
  - [Play Time by Game Genre](#play-time-by-game-genre)
  - [Heatmap of Gender and Game Genre Correlation](#heatmap-of-gender-and-game-genre-correlation)
  - [Average Session Duration vs. Engagement Level](#average-session-duration-vs-engagement-level)
  - [Player Level Distribution by Gender](#player-level-distribution-by-gender)
  - [Sessions Per Week by Difficulty Level](#sessions-per-week-by-difficulty-level)
  - [Gender Distribution Within Each Game Genre](#gender-distribution-within-each-game-genre)
- [Conclusion and Business Insights](#conclusion-and-business-insights)

## Project Overview
The purpose of this analysis is to understand user behavior in online gaming. By analyzing the provided dataset, which includes various player demographics, in-game behavior, and engagement levels, we can derive actionable insights. These insights will assist in personalizing player experiences, improving game design, and optimizing marketing strategies.

## Dataset Overview
The dataset used in this project includes the following columns:
- **Player ID**: Unique identifier for each player.
- **Age**: Age of the player.
- **Gender**: Gender of the player (Male/Female).
- **Location**: Country or region of the player.
- **Game Genre**: Genre of the game played (e.g., Action, Strategy).
- **Play Time in Hrs/Wk**: Average weekly playtime in hours.
- **In-Game Purchases**: Whether the player makes in-game purchases.
- **Game Difficulty**: The difficulty level of the game.
- **Sessions per Week**: Number of gaming sessions per week.
- **Avg Session Minutes**: Average duration of a gaming session.
- **Player Level**: Current level of the player in the game.
- **Achievements Unlocked**: Number of achievements unlocked by the player.
- **Engagement Level**: Qualitative measure of player engagement (e.g., High, Medium, Low).

## Data Cleaning and Preparation
Before conducting the analysis, several data cleaning steps were taken to ensure accuracy:
1. **Checking for Null Values**: The dataset was checked for missing values, and no null values were found.
2. **Checking for Duplicates**: No duplicate records were found, ensuring that the dataset is clean and reliable.
3. **Renaming Columns**: Column names were standardized for readability and consistency.
4. **Data Type Conversion**: The `Play Time in Hrs/Wk` column was rounded to two decimal points to simplify the analysis.

## Exploratory Data Analysis (EDA)
The EDA was performed to answer key questions about the dataset and to uncover patterns and insights. Below are the key sections of our analysis:

### Distribution of Player Ages
- **Questions Answered**: What is the age distribution of players?
- **Graph Added**: A histogram showing the distribution of player ages.
- **Observations**: The majority of players fall within the 18-25 age range.
- **Conclusion**: The player base is predominantly young adults, particularly those aged 18-25.
- **Business Insights**: Focus on content and marketing strategies that resonate with the 18-25 age group.

### Gender Distribution
- **Questions Answered**: What is the gender distribution of players? Is there a significant gender gap?
- **Graph Added**: A bar chart showing the gender distribution.
- **Observations**: The dataset reveals a male-dominated player base.
- **Conclusion**: A significant gender gap exists, with male players outnumbering female players.
- **Business Insights**: Implement diversity initiatives and create content that appeals to female players.

### Play Time by Gender
- **Questions Answered**: How do male and female players differ in terms of total playtime?
- **Graph Added**: A distribution graph showing playtime by gender.
- **Observations**: Male players tend to engage in longer play sessions.
- **Conclusion**: Male players are generally more engaged in longer play sessions.
- **Business Insights**: Tailor game content and marketing strategies to match gender-specific playtime patterns.

### Play Time by Game Genre
- **Questions Answered**: How do different game genres compare in terms of total playtime?
- **Graph Added**: A bar chart showing playtime by game genre.
- **Observations**: Strategy and RPG games see higher total playtime.
- **Conclusion**: Strategy and RPG games lead in total playtime, indicating higher engagement.
- **Business Insights**: Focus on deepening content and offering long-term incentives in these genres.

### Heatmap of Gender and Game Genre Correlation
- **Questions Answered**: Which game genres are most popular among male and female players?
- **Graph Added**: A heatmap showing the correlation between gender and game genre.
- **Observations**: Male players dominate genres like Action and RPG, while female players are more evenly distributed.
- **Conclusion**: Male players have a strong preference for Action and RPG genres.
- **Business Insights**: Focus on expanding and improving content in Action and RPG genres.

### Average Session Duration vs. Engagement Level
- **Questions Answered**: How does session duration correlate with engagement level?
- **Graph Added**: A scatter plot showing session duration vs. engagement level.
- **Observations**: Engagement tends to decrease as session duration increases.
- **Conclusion**: Engagement decreases as session duration increases.
- **Business Insights**: Create content that maintains player engagement during longer sessions.

### Player Level Distribution by Gender
- **Questions Answered**: How is the distribution of player levels across genders?
- **Graph Added**: A distribution graph showing player levels by gender.
- **Observations**: Male players are more prevalent at higher player levels.
- **Conclusion**: Male players are more likely to progress to higher levels.
- **Business Insights**: Target high-level male players with advanced gaming features or exclusive content.

### Sessions Per Week by Difficulty Level
- **Questions Answered**: How does the number of sessions per week vary across different difficulty levels?
- **Graph Added**: A box plot showing sessions per week by difficulty level.
- **Observations**: Players engaging with the Hard difficulty level tend to have more gaming sessions per week.
- **Conclusion**: More challenging content increases player engagement.
- **Business Insights**: Introduce more content at higher difficulty levels to keep players engaged.

### Gender Distribution Within Each Game Genre
- **Questions Answered**: How is gender distributed within each game genre?
- **Graph Added**: A bar chart showing gender distribution within each genre.
- **Observations**: Puzzle and Casual genres show a relatively balanced gender distribution.
- **Conclusion**: Simulation games have the most balanced gender distribution.
- **Business Insights**: Focus on genres that attract both male and female players equally.

## Conclusion and Business Insights
**Final Conclusion:**
- The analysis revealed that the player base is predominantly young adults aged 18-25, with a significant male dominance. Strategy and RPG games see the highest engagement, particularly among male players, while engagement generally decreases as session duration increases. Male players are more likely to progress to higher levels, while female players show a preference for shorter, more frequent gaming sessions.

**Overall Business Insights:**
- **Player Retention:** Focus on deepening content and offering long-term incentives in popular genres.
- **Inclusivity:** Enhance gaming experiences for female players by addressing gender disparities.
- **Marketing Strategy:** Tailor marketing efforts to target specific demographics and genre preferences.
- **Content Development:** Maintain engagement by developing content that resonates with the core player base, especially the 18-25 age group.
- **Targeted Features:** Introduce rewards and challenges for extended play sessions to cater to highly engaged players.

---

Thank you for exploring this project! Feel free to contribute or reach out with any suggestions.
