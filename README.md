# NCAA Division 1 Men's Big West Conference Performance Analysis

This project analyzes performance metrics from the NCAA Division 1 Men's Big West Conference to identify key features influencing team success. The analysis combines data from Random Forest feature importances and Win Counts to determine which features most consistently correlate with winning outcomes. The ultimate goal is to provide insights into which metrics are most indicative of a team's performance and success in the league.

## Objectives
1. Identify Top Features: Determine the most influential features based on Random Forest and Win Counts.

2. Compare Features: Evaluate how top features differ between winning and losing teams.

3. Feature Analysis: Investigate features where a majority of teams consistently perform well.

4. Visualization: Create visualizations to highlight the relationship between key features and team performance.

## Data and Features
### Data
The dataset includes various performance metrics for teams in the NCAA Division 1 Men's Big West Conference. Some key features include:

- Goals
- Total attacks ending with shots ratio
- Shots on target inside penalty area ratio
- Clearances
- Match tempo

### Top Features
The analysis focuses on the top features derived from:

1. Random Forest Model
2. Win Counts Analysis

## Methodology
1. Feature Selection:

- Extracted top 20 features from Random Forest and Win Counts.
- Combined and removed duplicates.
- Focused on features of interest.

2. Feature Comparison:

- Compared features between winning and losing teams to identify metrics where winners consistently outperform losers.
- Calculated win rates for each feature and filtered features with a 60% win rate or higher.

3. Performance Metrics:

- Weighted performance metrics for top and bottom teams based on specific criteria.
- Normalized and calculated weighted averages to determine overall team performance.

4. Visualization:

- Generated scatter plots to explore relationships between selected features.
- Created bar charts to visualize weighted performance metrics.


## Results
### Key Findings
- Offensive Metrics: Features such as 'Shots on target inside penalty area ratio' and 'Match tempo' are crucial for scoring goals and maintaining a high tempo to disrupt opponents.
- Defensive Metrics: Metrics like 'Interceptions', 'Low loss ratio', and 'Clearances' are essential for maintaining defensive stability and managing transitions.
- Balanced Approach: Success in the conference requires a balance between attacking efficiency and defensive resilience.

### Visualizations
- Bar Charts: Showed weighted performance metrics for teams, emphasizing the influence of selected features.
- Scatter Plots: Displayed relationships between key features to highlight their importance and correlation.
<img width="838" alt="Screenshot 2024-09-13 at 4 40 57 PM" src="https://github.com/user-attachments/assets/161269fc-5c87-4980-b413-de87da99453c">
<img width="856" alt="Screenshot 2024-09-13 at 4 42 02 PM" src="https://github.com/user-attachments/assets/38c6be00-1220-49d1-942a-df50a0ddf2d6">

## Conclusion
The analysis demonstrates that a comprehensive approach, integrating multiple facets of play, is crucial for success in the Big West Conference. Teams excelling in both offensive and defensive metrics, while managing transitions effectively, have a competitive advantage. The insights and visualizations provided offer a roadmap for teams to optimize their strategies and enhance performance.

## Future Works
- Further analysis on additional metrics and their impact.
- Exploration of other models to validate findings.
- Continuous updates with new data to refine the insights.



## Contact
For any questions or further information, please contact:

- Sean McDonnell 
- mcdonnellcsean@gmail.com
- linkedin/mcdonnellcsean
