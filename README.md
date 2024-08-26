# Zomato_Data_Analysis
**Step-by-Step Analysis of Zomato Data Project
**Libraries Used:****

Pandas for data manipulation and analysis.
NumPy for numerical operations.
Matplotlib.pyplot and Seaborn for data visualization.
**Data Preparation:**

Loaded the dataset using pandas with pd.read_csv("Zomato data.csv").
Inspected the dataset with dataframe.head() and dataframe.info().
**Data Cleaning:**

Converted the 'rate' column to a numerical format using a custom function, handleRate(value), to split and extract the rating score.
**Data Visualization and Analysis**:

Restaurant Types: A count plot (sns.countplot) showed the distribution of restaurant types. Most restaurants were categorized under "Dining".
Votes by Restaurant Type: Grouped data by 'listed_in(type)' and plotted total votes for each category. Dining restaurants received the maximum votes, indicating their popularity.
Rating Distribution: A histogram (plt.hist) showed the distribution of ratings, helping to visualize how restaurants are rated overall.
Cost Analysis: Analyzed the 'approx_cost(for two people)' to see the preferred cost range for couples, finding that most prefer restaurants costing around 300 rupees.
Order Type vs. Rating: A box plot (sns.boxplot) compared ratings between online and offline orders, revealing that online orders generally received higher ratings.
Ordering Preferences Heatmap: A pivot table and heatmap (sns.heatmap) showed the correlation between restaurant types and order modes. It was found that dining restaurants predominantly receive offline orders, while cafes often receive online orders.
**Conclusions:**

Restaurant Category: The majority of restaurants fall under the "Dining" category.
Popularity: Dining restaurants not only dominate in numbers but also receive the most votes.
Cost Preference: Couples generally prefer dining options with an approximate cost of 300 rupees for two people.
Rating Insights: Restaurants offering online ordering tend to receive better ratings than those that do not.
Ordering Patterns: There is a clear trend where dining restaurants prefer offline orders, while cafes cater more to online orders, reflecting differing customer behaviors based on the restaurant type.
