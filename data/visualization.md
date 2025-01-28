# Visualization


# Timetable

- Class 9:00 - 10:30 (17.00 - 18.30 JST)
- Break 10:30 - 10:40 (18.30 - 18.40 JST)
- Class 10:40 - 11:50 (18.40 - 20.10 JST)
- Break 11:50 - 12:00 (20.10 - 20.20 JST)
- Class 12:00 - 13:05 (20.20 - 21.05 JST)
- `Lunch break`
- Class 14:05 - 15:35 (self paced learning)
- Break 15:35 - 15:45
- Class 15:45 - 17:15 (self paced learning)
- Break 17:15 - 17:25
- Class 17:25 - 18:10 (self paced learning) (00.25 - 01.10 JST)


# Today's agenda

- Telling a story <!-- .element: class="fragment" data-fragment-index="2" -->
- Libraries <!-- .element: class="fragment" data-fragment-index="3" -->
- Advanced libraries <!-- .element: class="fragment" data-fragment-index="4" -->
- Chossing the right plot <!-- .element: class="fragment" data-fragment-index="5" -->
- Exercise <!-- .element: class="fragment" data-fragment-index="6" -->


# Examples

- Katapult magazine


# Telling a story

- Find the story that the data tries to tell <!-- .element: class="fragment" data-fragment-index="2" -->
- Raw data compared to dashboards <!-- .element: class="fragment" data-fragment-index="3" -->
- Infographics <!-- .element: class="fragment" data-fragment-index="4" -->
- Pitch decks <!-- .element: class="fragment" data-fragment-index="5" -->
- Lets build a quick flow diagram <!-- .element: class="fragment" data-fragment-index="6" -->
- Trends/patterns, colors or logos <!-- .element: class="fragment" data-fragment-index="7" -->


# For you as a consultant

1. Understanding the Target Audience: Identify the needs, preferences, and expertise of the cloud provider's customers. <!-- .element: class="fragment" data-fragment-index="2" -->
2. Scalability and Performance: Ensure that chosen visualization tools can handle large datasets and perform well. <!-- .element: class="fragment" data-fragment-index="3" -->
3. Security and Compliance: Select data visualization solutions that meet security requirements and comply with relevant industry standards (e.g., HIPAA, SOC 2). <!-- .element: class="fragment" data-fragment-index="4" -->
4. Integration with Cloud Services: Look for tools that integrate seamlessly with the cloud provider's services, such as AWS QuickSight or Google Data Studio. <!-- .element: class="fragment" data-fragment-index="5" -->
5. Interoperability and Customizability: Ensure that chosen visualization solutions can be easily embedded in the cloud provider's platforms and customized to meet specific customer needs. <!-- .element: class="fragment" data-fragment-index="6" -->
6. Real-time and Dynamic Visualizations: Offer tools for creating real-time, interactive, and exploratory visualizations for customers to gain insights from their data more effectively. <!-- .element: class="fragment" data-fragment-index="7" -->
7. Accessibility and Usability: Ensure that chosen visualization solutions are accessible to diverse audiences and easy to use for a wide range of users. <!-- .element: class="fragment" data-fragment-index="8" -->
8. Collaboration and Sharing: Provide options for real-time collaboration and sharing of visualizations between team members and stakeholders. <!-- .element: class="fragment" data-fragment-index="9" -->
9. Support and Maintenance: Offer robust support, maintenance, and upgrade options to ensure that customers have access to the latest features and functionality. <!-- .element: class="fragment" data-fragment-index="10" -->


# Introduction to Data Visualization

- `Importance of Visualizing Data in SAP https://www.sap.com/documents/2022/01/5e49ac93-127e-0010-bca6-c68f7e60039b.html` <!-- .element: class="fragment" data-fragment-index="2" -->
- Know your data <!-- .element: class="fragment" data-fragment-index="3" -->
- Know you audience <!-- .element: class="fragment" data-fragment-index="4" -->
- Libraries Overview: Plottly, Matplotlib and Seaborn <!-- .element: class="fragment" data-fragment-index="5" -->


# Plotly

- Start with javascript and plottly <!-- .element: class="fragment" data-fragment-index="2" -->
- Advanced D3.js <!-- .element: class="fragment" data-fragment-index="3" -->


# Matplotlib


### Basic Plotting

- Creating a Simple Line Plot <!-- .element: class="fragment" data-fragment-index="2" -->
- Overview of Different Types of Plots: Line Plot, Bar Chart, Histogram <!-- .element: class="fragment" data-fragment-index="3" -->


# Practical Exercise: Creating Basic Plots

- Line Plot Example: `plt.plot([1, 2, 3, 4, 5], [1, 4, 9, 16, 25])` <!-- .element: class="fragment" data-fragment-index="2" -->
- Bar Chart Example: `plt.bar(['Apples', 'Bananas', 'Cherries'], [12, 15, 7])` <!-- .element: class="fragment" data-fragment-index="3" -->
- Histogram Example: `plt.hist(data, bins=10)` <!-- .element: class="fragment" data-fragment-index="4" -->
- https://colab.research.google.com/drive/13LIyQnnhta0mQ0RLNxqnDo2Npwh1PdEV <!-- .element: class="fragment" data-fragment-index="5" -->


# Introduction to Pandas

- What is Pandas?
- Why use Pandas in data analysis?

Speaker Notes:

- Explain Pandas as a high-level data manipulation tool developed on top of the Python programming language.
- Highlight its role in data analysis for its simplicity and powerful data handling capabilities.


# Datascience terms

- [Standard deviation](https://en.wikipedia.org/wiki/Standard_deviation#Interpretation_and_application)
- [Mean](https://en.wikipedia.org/wiki/Expected_value)
- [Median](https://en.wikipedia.org/wiki/Median)


# Standard Tommy
![std_tommy](./data/img/std_tommy.JPG)


# Pandas Data Structures
- Series
- DataFrames

Speaker Notes:

- Describe Series as one-dimensional arrays with any data type.
- Introduce DataFrame as a two-dimensional, size-mutable, potentially heterogeneous tabular data.


# Creating and Loading Data
- Creating DataFrames manually
- Loading data from files (CSV, Excel)

Speaker Notes:

- Show how to create DataFrames from lists and dicts.
- Demonstrate loading data from various file formats into DataFrames.


# Basic Operations with Pandas
- Viewing and selecting data
- Filtering data
- Adding and deleting columns

Speaker Notes:

- Teach how to view portions of data using head() and tail().
- Explain selecting specific columns or rows using indexing and slicing.
- Cover filtering data based on conditions.
- Show how to add new columns or delete existing ones in a DataFrame.


# Data Manipulation Techniques
- Applying functions to data
- Handling missing data
- Merging and joining DataFrames

Speaker Notes:

- Discuss applying custom or built-in functions to DataFrame columns.
- Explain strategies for dealing with missing data (e.g., fillna, dropna).
- Teach merging and joining techniques to combine multiple DataFrames.


# Grouping and Aggregating Data
- Group by operations
- Aggregate functions
- Pivot tables
- [Examples](https://chat.openai.com/share/f002495f-8ce6-4739-96fa-baccffede941)

Speaker Notes:

- Illustrate how to use groupby for grouping data based on some criteria.
- Explain using aggregate functions like sum, mean, and max.
- Show how to create pivot tables for data summarization.


# Practical Exercise: 
## Data Analysis with Pandas
- Analyze a real-world dataset using Pandas
- Perform data cleaning, manipulation, and visualization

Speaker Notes:

- Provide a dataset for students to practice on.
- Guide them through cleaning, manipulating, and visualizing data using Pandas.


# Introduction to Seaborn

- Why Seaborn over Matplotlib? <!-- .element: class="fragment" data-fragment-index="2" -->
- Built-in themes and color palettes. <!-- .element: class="fragment" data-fragment-index="3" -->
- Ability to handle Pandas data structures directly. <!-- .element: class="fragment" data-fragment-index="4" -->
- High-Level Interface for Statistical Plots <!-- .element: class="fragment" data-fragment-index="5" -->


# Practical Exercise: 
## Choose a case and visualize with seaborn or matplotlib

1. Showing growth of newsletter subscribers
2. Estimate segments of demographics soon reachable
3. Distribution of genderdiversity in CEO positions
4. Fluctuation of people with migration background
5. Decline of stockvalue compared to oilprice


# Linear algebra in python

- Plotting functions.ipynb
- Speaking of Arrays tensorflow-shapes.ipynb
- How to use stochastic gradient decent https://colab.research.google.com/drive/1Rcz1967Gj8gU8bnaI0HtTDuJJi5e0NfF#scrollTo=iBmUnY6V0arN


# Seaborn Plot Types


### Scatter Plots, Box Plots, and Heatmaps

- Scatter Plot: `sns.scatterplot(x='height', y='weight', data=df)`
- Box Plot: `sns.boxplot(x='day', y='total_bill', data=tips)`
- Heatmap: `sns.heatmap(data.corr())`

Speaker Notes:

- Explain when to use each type of plot:
	- Scatter plots for relationships between variables.
	- Box plots for distributions with respect to categories.
	- Heatmaps for data intensity and correlation matrices.


# Jupyter notebooks

- llama and message analysis
- health data


# Combining Plots and Customizing Graphics
### Overlaying Plots and Customizing with Matplotlib and Seaborn

- Combine a line plot and bar chart <!-- .element: class="fragment" data-fragment-index="2" -->
- Apply a theme  <!-- .element: class="fragment" data-fragment-index="3" -->
- customize the legend and labels <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:

- Show how to overlay plots using `plt.plot()` and `sns.barplot()`.
- Discuss how to customize plots with:
	- Labels: `plt.xlabel()`, `plt.ylabel()`
	- Legends: `plt.legend()`
	- Themes: `sns.set_style()`


### Practical Exercise: Customizing and Combining Plots

- Combine a line plot and bar chart
- Apply a theme and customize the legend and labels


# Data and ethics

- Can be used for manipulation, opinion change and propaganda <!-- .element: class="fragment" data-fragment-index="2" -->
- Importance of data verification and fact checks <!-- .element: class="fragment" data-fragment-index="3" -->
- Personal tips like reverse stance on a subject <!-- .element: class="fragment" data-fragment-index="4" -->
- Avoid misinterpretation, hidden messages <!-- .element: class="fragment" data-fragment-index="5" -->
- Respect privacy <!-- .element: class="fragment" data-fragment-index="6" -->
- Accessibility <!-- .element: class="fragment" data-fragment-index="7" -->
- Depth of the visualization <!-- .element: class="fragment" data-fragment-index="8" -->


# Future

- Real time <!-- .element: class="fragment" data-fragment-index="2" -->
- VR/AR <!-- .element: class="fragment" data-fragment-index="3" -->


# Q&A and Review of Data Visualization

- Open floor for questions
- Review essential visualization concepts and tools

Speaker Notes:

- Address any questions the students might have.
- Recap key points from the visualization segment, emphasizing the practical applications of Matplotlib and Seaborn in real-world data analysis.# Cyber Security
