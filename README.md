# IPL_STATS_ANALYSIS

Importing necessary libraries: Streamlit, NumPy, Pandas, Plotly Express, and Plotly Graph Objects.

Loading the dataset for the top 100 batsmen.

Setting up the Streamlit app title and section title for batsman KPIs.

Filtering the batsmen dataset to include only those with more than 3000 runs.

Selecting the top five batsmen based on runs.

Creating a bar chart using Plotly Express to visualize the average and strike rate of all batsmen.

Displaying the bar chart using st.plotly_chart().

Adding a title for the top 5 batsmen based on runs section.

Creating a line chart using Plotly Graph Objects to visualize the runs scored by the top five batsmen.

Displaying the line chart using st.plotly_chart().

Loading the dataset for matches.

Extracting the teams that chose to bat after winning the toss.

Counting the occurrences of each team choosing to bat.

Adding a title for the teams choosing batting when they won the toss section.

Creating a bar chart using Plotly Express to visualize the frequency of teams choosing to bat.

Displaying the bar chart using st.plotly_chart().

Extracting the teams that chose to bowl after winning the toss.

Counting the occurrences of each team choosing to bowl.

Adding a title for the teams choosing bowling when they won the toss section.

Creating a bar chart using Plotly Express to visualize the frequency of teams choosing to bowl.

Displaying the bar chart using st.plotly_chart().

Adding a title for the overall toss mapping section.

Combining the counts of teams choosing to bat and bowl to get overall toss win counts.

Creating a pie chart using Plotly Express to visualize the overall toss mapping.

Displaying the pie chart using st.plotly_chart().

Adding a title for the most successful teams based on win count section.

Counting the occurrences of each team winning matches.

Creating a pie chart using Plotly Express to visualize the win counts of different teams.

Displaying the pie chart using st.plotly_chart().

Adding a title for the Player of the Match award section.

Counting the occurrences of each player receiving the Player of the Match award.

Creating a scatter plot using Plotly Graph Objects to visualize the top 5 players with the most awards.

Displaying the scatter plot using st.plotly_chart().

Loading the dataset for the top 100 bowlers.

Filtering the bowlers dataset to include only those with more than 1 wicket.

Selecting the top five bowlers based on wickets.

Creating a line chart using Plotly Graph Objects to visualize the wickets taken by the top five bowlers.

Displaying the line chart using st.plotly_chart().

Adding a title for the bowlers KPI section.

Creating a bar chart using Plotly Express to visualize the economy and wickets of all bowlers.

Displaying the bar chart using st.plotly_chart().

Adding a title for the bowlers who are leaking more runs section.

Filtering the bowlers dataset to include
