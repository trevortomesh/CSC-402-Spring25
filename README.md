# **<u>CSC 402</u>**

## **Storytelling and Analytics: Transforming Data into Insightful Narratives**

# Week 1

---

## **Part 1: The Foundations of Data Storytelling**

**1.1 Course Overview and Objectives**

- **1.1.1 Syllabus Overview**
  
    This course, *Storytelling and Analytics*, is designed to equip students with the tools and methodologies to transform raw data into meaningful stories. These stories drive better decisions, inspire action, and present data-driven insights in an engaging way.
    
    **Key Details:**
    
    ​	•	**Schedule:** Tuesdays, 5:30–7:59 PM EST (Instructor in CST).
    
    ​	•	**Block Dates:** January 13 – March 2.
    
    ​	•	**Instructor Contact:**
    
    ​	•	**Email:** trevor.m.tomesh@willmw.edu (primary communication channel).
    
    ​	•	**Canvas Messaging:** Secondary method but not preferred.
    
    **Office Hours:**
    
    ​	•	Tuesdays, 3:30–5:30 PM EST. Appointments outside these hours are available upon request.
    
    **Course Textbook:**
    
    Kirk, A. (2016). *Data Visualization: Exploring and Explaining with Data* (Cengage). The textbook is essential for mastering data visualization techniques and understanding the role of narrative in data interpretation.
    

**1.2 Storytelling: The Universal Language**

- **1.2.1 Why Stories Resonate**
  
    Storytelling is intrinsic to human experience, crossing cultural, temporal, and technological boundaries. People naturally relate to stories because they provide structure, emotional engagement, and a sense of purpose. From ancient myths to modern cinema, stories drive our understanding of the world.
    
    In analytics, storytelling:
    
    •	**Motivates:** Captures attention by creating relatable scenarios.
    
    •	**Illuminates:** Highlights insights while addressing gaps or missing data.
    
    •	**Inspires Action:** Encourages stakeholders to make informed decisions.
    
    **The Importance of Structure in Stories:**
    
    Think about your favorite activities—reading books, watching movies, or even playing video games. All of these mediums use stories to guide your experience and emotions. Similarly, in analytics, data-driven stories can evoke powerful responses by making complex data accessible and actionable.

**1.3 Data Storytelling in Action: Case Studies**

- **1.3.1 Case Study 1: Abraham Wald and Aircraft Survivability (WWII)**
  
    During World War II, the Allied forces faced the challenge of deciding where to reinforce armor on their aircraft. They collected data on bullet holes in planes that returned from missions, identifying common areas of damage, such as the wings and fuselage.
    
    ![plane.png](images/plane.png)
    
    **Initial Assumption:**
    
    Reinforce the areas with the most bullet holes to protect aircraft from damage.
    
    **Abraham Wald’s Insight:**
    
    Wald recognized survivorship bias in the data. The planes returning were hit in areas that allowed them to survive. The absent data—planes that did not return—revealed that hits in other areas (engines, cockpits) were critical to the planes’ survival.
    
    **Action Taken:**
    
    Armor was applied to areas with no bullet holes, significantly improving aircraft survivability.
    
    **Lesson:** Stories, when supported by data, can challenge assumptions and lead to better outcomes (citation needed).
    
    
    
- **1.3.2 Case Study 2: Falling Cats and Survivorship Bias**
  
    A veterinary study analyzed data on cats falling from various heights. The study found that cats falling from heights of six stories or less were frequently injured, while fewer injuries were reported for falls from greater heights.
    
    **Misinterpretation:**
    
    It was initially believed that higher falls gave cats more time to right themselves and land safely.
    
    ![Berlin_Badensche_Straße_Katze_auf_Balkon_03.10.2011_14-48-09.jpg](images/Berlin_Badensche_Strae_Katze_auf_Balkon_03.10.2011_14-48-09.jpg)
    
    **Reality:**
    
    Dead cats were not brought to veterinarians, skewing the data. Higher falls were often fatal, but this data was excluded.
    
    **Lesson:** Data collection must consider what is missing, as excluding critical information leads to flawed conclusions (citation needed).
    
    
    
- **1.3.3 Case Study 2: Recycling**
  
    ![Screenshot 2025-01-14 at 4.29.19 PM.png](images/Screenshot_2025-01-14_at_4.29.19_PM.png)
    
    **Summary of Recycling Example**
    
    The recycling example highlighted the inefficiencies of plastic recycling systems, using a clear visualization to demonstrate the disparity between public perception and reality.
    
    **Key Data Points:**
    
    •	**83 billion tons** of plastic have been produced globally.
    
    •	**70%** of plastics are single-use and discarded after one use.
    
    •	Of all plastics produced, **only 6%** are recycled.
    
    •	Even among recycled plastics, **1% or less** are reused effectively.
    
    •	**55%** of plastics are discarded outright (e.g., in landfills or oceans).
    
    **Key Insight:**
    
    The graph starkly illustrated that despite efforts to promote recycling, the vast majority of plastic waste ends up in landfills or is incinerated. This disconnect between the idealized vision of recycling and its real-world outcomes emphasizes systemic inefficiencies.
    
    **Purpose of the Example:**
    
    The recycling example demonstrated how data visualization can:
    
    1.	Clarify complex systems for audiences.
    
    2.	Challenge common assumptions (e.g., “recycling solves plastic waste”).
    
    3.	Highlight actionable areas for improvement, such as reducing single-use plastics or improving recycling technologies.
    
    **Takeaway:**
    
    This example emphasized how effective visualizations not only reveal problems but also help frame them in ways that can inspire informed actions and policy changes.
    
    
    
- **1.3.4 Case Study 3: Global Warming**
  
    **Summary of NASA’s Data Zooming Example**
    
    In the lecture, the example of NASA’s global temperature anomaly graph was used to illustrate how the presentation of data can be shaped to tell a specific story.
    
    NASA’s graph displayed global temperature changes from 1880 to 2020, showing a sharp rise in temperatures. This visualization was effective in drawing attention to recent warming trends, aided by design choices like a blinking red light to emphasize the increase.
    
    ![Screenshot 2025-01-14 at 4.28.33 PM.png](images/Screenshot_2025-01-14_at_4.28.33_PM.png)
    
    ![Screenshot 2025-01-14 at 4.26.35 PM.png](images/Screenshot_2025-01-14_at_4.26.35_PM.png)
    
    ![Screenshot 2025-01-14 at 4.26.55 PM.png](images/Screenshot_2025-01-14_at_4.26.55_PM.png)
    
    **Key Insight:**
    
    NASA focused on a relatively narrow timeline, starting in 1880, despite having access to much longer climate records going back hundreds of thousands of years. If the broader timeline were presented (e.g., a chart spanning 800,000 years), viewers would observe natural temperature fluctuations and longer-term trends. This might lead to questions about the immediacy or uniqueness of the current warming trend.
    
    **Purpose of the Zooming:**
    
    NASA’s decision to “zoom in” on the recent data:
    
    •	**Supports the Narrative:** Highlights human-driven (anthropogenic) changes since the Industrial Revolution.
    
    •	**Simplifies the Story:** Makes the message clearer and more urgent for general audiences.
    
    **Implication:**
    
    While narrowing the focus can make data more compelling, it may also omit context that could provide a fuller picture. This approach underscores the dual power and responsibility of data visualization in shaping narratives.

**1.4 The Three Pillars of Analytics**

Analytics is the backbone of modern decision-making. It uses descriptive, predictive, and prescriptive methods to extract actionable insights from data.

- **1.4.1 Descriptive Analytics: Understanding the Past**

​	**Definition:** Summarizes historical data to provide insights into past events.

​	**Applications:**

​		•	Tracking sales performance.

​		•	Summarizing election polling results.

​	**Tools:** Dashboards, reports, and statistical summaries.

- **1.4.2 Predictive Analytics: Forecasting the Future**

​	**Definition:** Uses historical data to identify trends and forecast future outcomes.

​	**Applications:**

​	•	Predicting market trends.

​	•	Anticipating customer behavior.

​	**Tools:** Regression analysis, time-series modeling, machine learning.

​	**Example:**

​		NASA’s global temperature records from 1880 to 2020 reveal a steady increase in temperature anomalies. Using predictive 	analytics, scientists forecast continued warming trends, driving awareness and action on climate change.

![Screenshot 2025-01-14 at 4.28.33 PM.png](images/Screenshot_2025-01-14_at_4.28.33_PM%201.png)

- **1.4.3 Prescriptive Analytics: Guiding Decisions**

​	**Definition:** Recommends actions based on insights derived from descriptive and predictive analytics.

​	**Applications:**

​		•	Optimizing inventory management.

​		•	Formulating marketing strategies.

​	**Integrated Example:**

​	A retailer examines historical sales (descriptive), forecasts demand during peak seasons (predictive), and adjusts inventory 	accordingly (prescriptive).

---

##  **Part 2: Big Data in the Modern Era**

- **2.1 The Four Vs of Big Data**
  
    Big Data is defined by four primary characteristics:
    
    1.	**Volume:** Sheer quantity of data generated daily.
    
    2.	**Velocity:** Speed at which data is created and processed.
    
    3.	**Variety:** Diversity in data formats (e.g., text, images, audio).
    
    4.	**Veracity:** Reliability and quality of the data.
    
    **Example:** A fitness tracker collects data on heart rate, movement, and sleep patterns. This diverse, high-velocity data is aggregated into actionable insights for users (citation needed).
    
- **2.2 Data Visualization: The Key to Storytelling**
  
    **The Funnel Chart:**
    
    A funnel chart visualizes the customer conversion process, showing where users drop off. For example, a software company may find that while 74% of visitors download a trial version, only 28% subscribe, revealing a need to improve the user experience during trials.
    
    ![funnel.png](images/funnel.png)
    
    **Time-Series Graphs:**
    
    Time-series graphs track changes over time, such as rising global temperatures. These graphs not only describe past trends but also help predict future outcomes.
    
- **2.3 Applying the Hero’s Journey in Analytics**
  
    Joseph Campbell’s Hero’s Journey (1949) offers a storytelling framework that parallels data storytelling:
    
    1.	**Call to Adventure:** Present the problem (e.g., declining customer retention).
    
    2.	**Crossing the Threshold:** Dive into data insights and suggest actions.
    
    3.	**Trials and Tribulations:** Implement strategies to test and refine solutions.
    
    4.	**Return with the Elixir:** Present results and actionable recommendations.
    
    **Example:**
    
    A software company uses data visualization to identify drop-offs between trial users and subscribers. By refining support interactions, the company increases conversion rates and creates a loyal customer base.
    
- **2.4 Conclusion and Future Exploration**
  
    Storytelling is the bridge between raw data and meaningful insights. By combining descriptive, predictive, and prescriptive analytics with compelling visualizations, analysts can drive better decisions and inspire action. In the next chapter, we’ll explore advanced visualization techniques using Excel and other tools.
    

---

- **References**
  
    •	Campbell, J. (1949). *The Hero with a Thousand Faces*. Princeton University Press.
    
    •	NASA Climate Change. (2020). Global temperature anomalies. Retrieved from nasa.gov.

---

# Week 2

**Introduction to Data Analytics and Visualization: Lecture Overview**

File(s) for this lecture:
[zoo spreadsheet](/xls/zoo.xlsx)

**Introduction**

In this lecture, we explored foundational concepts in data analytics, spreadsheet tools, and the importance of data visualization. Emphasis was placed on practical applications, decision-making insights, and understanding the relationships between data points.

**1. Understanding Analytics**

**Definition**

Analytics is defined as the scientific process of transforming data into insights for better decision-making.

**Three Types of Analytics**

​	1.	**Descriptive Analytics**:

​		•	Describes what happened in the data.

​		•	Example: Identifying trends in zoo attendance across months.

​	2.	**Predictive Analytics**:

​		•	Uses historical data to predict future trends.

​		•	Example: Forecasting next year’s zoo attendance based on current patterns.

​	3.	**Prescriptive Analytics**:

​		•	Recommends actions based on descriptive and predictive insights.

​		•	Example: Adjusting ticket prices during peak zoo months to maximize revenue.



Prescriptive analytics is particularly nuanced as it requires clear goal definition and may involve subjective decisions based on different perspectives or values.

**2. Types of Data**

**Quantitative Data**

​	•	Represents measurable values (e.g., weight, temperature).

​	•	Mathematical operations like addition and multiplication are applicable.



**Categorical Data**

​	•	Represents categories or groups (e.g., types of expenses like “food” or “bills”).

​	•	Arithmetic operations do not apply directly.

**Key Differentiator: Ask, “Can I perform mathematical operations on this data?”**

**3. Cross-Sectional vs. Time Series Data**

**Cross-Sectional Data**

​	•	Collected from several entities at the same point in time.

​	•	Example: Share prices of companies on a specific date.

**Time Series Data**

​	•	Collected from one or multiple entities over time.

​	•	Example: Monthly sales trends for a product over a year.

A series of cross-sectional data points over time can also be visualized as time series data.

**4. Big Data**

**Characteristics of Big Data (4Vs)**

​	1.	**Volume**: Amount of data.

​	2.	**Velocity**: Speed of data generation.

​	3.	**Variety**: Types of data collected.

​	4.	**Veracity**: Reliability and accuracy of the data.

Big data often requires advanced computational tools and techniques for processing and analysis.

**5. Data Visualization**

**Purpose**

Data visualization helps explore, explain, and guide decision-making by representing data in visual formats.

**Types of Visualization Goals**

​	1.	**Composition**:

​		•	Displays the parts that make up a whole.

​		•	Example: Monthly zoo attendance as part of total annual attendance.

​	2.	**Ranking**:

​		•	Shows the relative importance or order of items.

​		•	Example: Ranking factors that job seekers consider important (e.g., salary, company culture).

​	3.	**Correlation**:

​		•	Demonstrates relationships between two variables.

​		•	Example: Scatter plots showing the relationship between temperature and snowfall.

**6. Spreadsheet Basics**

**Key Concepts**

​	•	**Cells**: Individual units in a spreadsheet identified by their column and row (e.g., A1).

​	•	**Formulas**: Operations programmed into cells to automate calculations and updates.



**Applications**

​	•	Spreadsheets can:

​	•	Automate repetitive tasks.

​	•	Visualize time series data.

​	•	Serve as tools for financial forecasting, game design, or engineering analysis.

**7. Selecting the Right Chart**

**Chart Selection Criteria**

​	•	**Goal of Visualization**:

​	•	Are you explaining, exploring, or persuading?

​	•	**Type of Data**:

​	•	Quantitative or categorical.

​	•	Cross-sectional or time series.

**Examples**

​	1.	**Time Series Data**: Line or scatter plots.

​	2.	**Composition**: Stacked bar charts or pie charts.

​	3.	**Ranking**: Sorted bar charts.

​	4.	**Correlation**: Scatter plots with trend lines.

**8. Applications Across Fields**

​	1.	**Business**:

​		•	Procter & Gamble’s “Business Sphere” rooms use advanced visualizations for decision-making.

​	2.	**Finance**:

​		•	Stock price charts to analyze trends and volatility.

​	3.	**Engineering**:

​		•	Control charts for quality assurance in production.

​	4.	**Sports**:

​		•	Shot charts in basketball to evaluate player performance.

**Conclusion**

Data analytics and visualization are critical tools across disciplines, enabling better decision-making and storytelling. Spreadsheets, with their flexibility and computational power, remain a vital tool for analyzing and visualizing data. Selecting the appropriate chart or method depends on the nature of the data and the goal of the analysis.

---

# Week 3

**Introduction**

Data visualization is more than just making charts and graphs—it’s about **designing visual representations of data that effectively communicate insights**. A good visualization is not only accurate but also intuitive, leveraging **human perception** to highlight key patterns and trends.

This chapter explores fundamental design principles, including **pre-attentive attributes, Gestalt principles, and cognitive load**. We will also discuss **common visualization mistakes** and how to avoid them.

**3.1 The Importance of Perception in Visualization**

When designing a visualization, **understanding human perception is crucial**. The way people interpret visual information affects how they understand the data.



**3.1.1 The Role of Memory in Visualization**

Visual processing relies on three types of memory:

​	•	**Iconic Memory:** The most **immediate form of memory**, lasting less than a second. It allows for quick pattern recognition.

​	•	**Short-term Memory:** Stores information for about **a minute**. Most people can only hold about **4 chunks of visual information** at a time.

​	•	**Long-term Memory:** Stores information over extended periods, typically through **repetition, association, or storytelling**.

Effective visualizations rely primarily on **iconic and short-term memory**, ensuring that the audience can process the information **instantly and without cognitive overload**.

**3.2 Pre-Attentive Attributes**

Pre-attentive attributes are **visual features** that our brains process **automatically, without conscious effort**. They allow viewers to grasp patterns in a visualization **at a glance**.

**3.2.1 Key Pre-Attentive Attributes**

| **Attribute**           | **Description**                                              | **Example Use in Visualization**                             |
| ----------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| **Color**               | Differences in hue, saturation, and luminance help distinguish elements. | Highlighting key data points (e.g., red dot in a trend graph). |
| **Size**                | Larger elements attract attention more quickly.              | Bigger bars in a bar chart indicate higher values.           |
| **Shape**               | Different shapes can be used to categorize data.             | Squares for Category A, circles for Category B.              |
| **Length**              | Longer bars or lines naturally indicate greater magnitude.   | Bar charts rely on length for comparison.                    |
| **Width**               | Less commonly used; varies across visualizations.            | Width in a Sankey diagram represents flow volume.            |
| **Orientation**         | Angle or rotation can convey meaning.                        | Sloped lines in a trend graph indicate change over time.     |
| **Spatial Positioning** | The relative location of elements on a chart affects interpretation. | Scatter plots show relationships between variables.          |
| **Motion**              | Movement captures attention but is only useful in digital media. | Animated visualizations showing real-time data.              |

**3.2.2 The Power of Pre-Attentive Processing**

Consider the following example:

​	•	If asked to find all instances of the number **7** in a list of random digits, it takes time to **scan row by row**.

​	•	If the **7s are highlighted in red**, the task becomes almost **instantaneous**.

​	•	Similarly, if the **7s are larger in size**, they immediately stand out.

This demonstrates how **color and size** help **reduce cognitive load** and make data easier to process.

**3.3 The Gestalt Principles**

The **Gestalt principles** describe how humans naturally **group and interpret visual elements**. These principles **guide how we structure and design data visualizations**.

**3.3.1 Key Gestalt Principles in Data Visualization**

​	1.	**Similarity**

​		•	Objects with **similar colors, shapes, or sizes** are perceived as part of the same group.

​		•	Example: In a scatter plot, using different colors for different categories makes grouping more intuitive.

​	2.	**Proximity**

​		•	Objects that are **physically close together** are perceived as related.

​		•	Example: Clustering in a scatter plot suggests **subgroups** within the data.

​	3.	**Enclosure**

​		•	Elements enclosed within a boundary are seen as **belonging together**.

​		•	Example: Drawing a **dashed box** around related points in a scatter plot reinforces groupings.

​	4.	**Connection**

​		•	Elements that are **physically connected** (e.g., lines between points) are seen as related.

​		•	Example: Line graphs create connections between **data points over time**, making trends visible.

**3.3.2 Using Gestalt Principles Effectively**

​	•	**Combine multiple principles** (e.g., shape + color + proximity) for **clearer visual groupings**.

​	•	**Avoid excessive complexity**, which can **increase cognitive load**.

​	•	**Use connections wisely**—adding too many can make the visualization **cluttered** rather than helpful.

**3.4 The Data-Ink Ratio**

Proposed by Edward Tufte, the **data-ink ratio** principle states:

​	“A good visualization should maximize the proportion of ink used to represent actual data, minimizing non-essential elements.”

**3.4.1 High vs. Low Data-Ink Ratio**

| **Type**                | **Characteristics**                           | **Example**                                       |
| ----------------------- | --------------------------------------------- | ------------------------------------------------- |
| **Low Data-Ink Ratio**  | Excessive gridlines, decorations, and colors. | Cluttered pie charts, overly colorful bar graphs. |
| **High Data-Ink Ratio** | Simple, clean design that focuses on data.    | Minimalist bar charts, well-labeled line graphs.  |

**3.4.2 Striking a Balance**

​	•	**Avoid unnecessary visual elements (e.g., background colors, thick borders).**

​	•	**Use white space effectively to improve readability.**

​	•	**Limit the number of colors to avoid distractions.**

For example, a **bar chart with subtle gridlines and a clean background** has a better data-ink ratio than a **pie chart filled with excessive labels and colors**.



**3.5 Common Mistakes in Data Visualization**

Even well-intentioned visualizations can **fail to communicate effectively**. Here are common mistakes to avoid:

​	1.	**Excessive Use of Colors**

​		•	Too many colors create **cognitive overload**.

​		•	Use **only 3-5 distinct colors** in a single visualization.

​	2.	**Overloaded Pie Charts**

​		•	Humans **struggle to compare angles accurately**.

​		•	**Bar charts** are usually a better choice.

​	3.	**Misleading Scale Manipulations**

​		•	**Truncated Y-axes** can **exaggerate small differences**.

​		•	**Irregular intervals** distort trends.

​	4.	**Too Much Non-Data Ink**

​		•	Heavy gridlines, 3D effects, and unnecessary labels distract from the **actual data**.

​	5.	**Poor Use of Legends**

​		•	**Inline labeling** is better than requiring users to **match colors to a separate legend**.

**3.5.1 Case Study: McDonald’s vs. Afghanistan’s GDP**

A misleading chart compared **McDonald’s revenue** to **Afghanistan’s GDP**, using:

​	•	**Logos instead of bars**, which made comparisons difficult.

​	•	**Excessive colors and unnecessary details**.

​	•	**Lack of clear scale**, making interpretation ambiguous.

A simpler **bar chart** provided the same information in a **clear, effective way**.

**3.6 Conclusion**

A well-designed visualization follows **the principles of perception and cognition**. By leveraging **pre-attentive attributes**, **Gestalt principles**, and an **optimal data-ink ratio**, we can create **engaging and intuitive visual representations** of data.

**Key Takeaways**

✔ **Use color, size, and position to guide attention.**

✔ **Apply Gestalt principles for clear groupings.**

✔ **Minimize distractions by maximizing the data-ink ratio.**

✔ **Avoid misleading visuals that distort or confuse the message.**

By following these guidelines, we ensure that our visualizations are **not just beautiful—but also meaningful.**

---

## Week 4

**The Role of Color in Data Visualization**

### Introduction
Color is a crucial element in data visualization, influencing how we perceive and interpret information. It can draw attention to key insights, evoke emotions, and enhance clarity. However, the effective use of color requires an understanding of its properties and its psychological and cultural significance. This section explores the attributes of color, color psychology and symbolism, and best practices for using color in data visualization.

### Attributes of Color
Color has three primary attributes:
1. **Hue**: The base of a color, typically represented by the RGB (red, green, blue) or CMY (cyan, magenta, yellow) color models. Hues combine to form secondary and tertiary colors.
2. **Saturation**: The intensity or purity of a color. Fully saturated colors contain no gray, while desaturated colors appear washed out.
3. **Luminance**: The relative brightness of a color. High luminance colors are lighter, while low luminance colors are darker.

Understanding these attributes helps in designing effective visualizations by ensuring appropriate contrast, clarity, and emphasis.

### Color Psychology and Symbolism
Colors evoke different emotions and meanings based on psychological and cultural contexts:
- **Cool colors** (blue, green, purple) are associated with calmness, trust, and stability.
- **Warm colors** (red, orange, yellow) evoke energy, urgency, and caution.
- **Red** often signifies danger, passion, or importance.
- **Blue** represents trust, professionalism, and calmness.
- **Green** is associated with growth, nature, and prosperity.
- **Yellow** conveys happiness and alertness but can also indicate caution.
- **Black and white** together symbolize elegance and contrast.

Cultural variations in color perception must also be considered. For example, in Western cultures, red can signal danger, while in some Eastern cultures, it symbolizes prosperity.

### Effective Use of Color in Data Visualization
To maximize the effectiveness of color in data visualization, consider the following best practices:
- **Avoid excessive color usage**: Too many colors create visual clutter and increase cognitive load.
- **Use color contrast strategically**: High contrast improves readability, while low contrast can make distinctions difficult.
- **Leverage color schemes appropriately**:
  - **Categorical schemes**: Use distinct colors for unordered categories.
  - **Sequential schemes**: Use gradient-based colors for ordered data.
  - **Diverging schemes**: Use two contrasting hues to represent values above and below a reference point.
- **Ensure accessibility**: Consider colorblind-friendly palettes and avoid relying solely on color to convey meaning.
- **Maintain consistency**: Use the same colors across related charts to create a cohesive visual narrative.

### Case Study: NASA's Climate Change Graph
An example of effective color use is NASA’s global temperature graph, where a flashing red dot highlights the urgency of rising temperatures. The red color evokes caution and draws immediate attention, reinforcing the narrative of climate change’s impact.

### Conclusion
Color is a powerful tool in data visualization, capable of enhancing clarity and storytelling. By understanding its attributes, psychological effects, and best practices, designers can create more effective and engaging visual representations of data.

---

**Chapter 5: Visualizing Variability**

---

### **Summary**
In this chapter, we explore how to visualize variability in data, focusing on two main areas: categorical and numerical data. Key visualization tools include pivot tables, pivot charts, frequency distributions, histograms, and frequency polygons. We emphasize the importance of clear visual communication, avoiding cognitive overload through thoughtful design choices like appropriate color use and chart selection. Examples include analyzing the age range of U.S. Olympic gymnasts and grocery data through pivot tables and charts.

---

### **1. Types of Data**
Data is typically categorized into two types:
- **Numerical Data:** Data with numerical values (e.g., ages, prices).
- **Categorical Data:** Data with labels or names (e.g., fruit types, soda brands).

---

### **2. Visualizing Categorical Data**

#### **2.1 Pivot Tables and Charts**
Pivot tables are useful for quickly summarizing large datasets. Pivot charts provide visual representations of these summaries.

##### **Example: Grocery Data**
A small dataset with fruit categories was visualized using a pivot table and chart. Fruits included apples, bananas, and cherries. The process involved:
1. Creating a pivot table to count the frequency of each fruit.
2. Inserting a pivot chart to visualize these frequencies.
3. Applying colors thoughtfully (e.g., green for apples, yellow for bananas, red for cherries) to avoid cognitive overload.

#### **2.2 Frequency Distributions and Percent Frequencies**
Frequency distributions show how often each category appears, while percent frequencies show relative proportions.

##### **Example: Soda Purchases**
A dataset containing hundreds of soft drink purchases was analyzed. Brands included Coca-Cola, Diet Coke, Pepsi, Dr. Pepper, and Sprite. Frequencies and percent frequencies were calculated using Excel's COUNTIF function and displayed via pivot charts.

---

### **3. Visualizing Numerical Data**

#### **3.1 Histograms**
Histograms visualize the distribution of numerical data by grouping data into bins.

##### **Example: Age of Death**
A dataset with 700 ages of death was analyzed. Key points:
- Most common age range: 77 to 84 years.
- Histogram bins were set at a width of 7 years, balancing detail with clarity.
- Skewness was observed, with data skewed right (more people dying at older ages).

#### **3.2 Frequency Polygons**
Frequency polygons provide an alternative to histograms, connecting midpoints of bins with lines to show distributions more clearly.

##### **Example: U.S. Olympic Gymnasts' Ages**
- Overlapping range bar charts were initially confusing due to poor color choices and layout.
- Frequency polygons displayed male and female gymnast ages more effectively, reducing cognitive load.

---

### **4. Design Considerations in Data Visualization**
- **Color Use:** Limit the number of colors to avoid confusion.
- **Bin Selection:** Choose an appropriate number of bins (recommended: 5 to 20) to avoid oversimplification or overcomplication.
- **Chart Type:** Match the chart type to the data type (e.g., use histograms for continuous data and bar charts for categorical data).
- **Cognitive Load:** Design charts to be easily interpretable without excessive mental effort.

---

### **5. Real-World Application: Benford's Law**
Benford's Law states that in many datasets, the first digit of numbers follows a predictable distribution. This principle is used in forensic accounting to detect anomalies in financial data.

##### **Example:**
Analyzing transaction data using frequency distributions can reveal whether the data conforms to Benford's Law, potentially indicating fraudulent activity.

---

### **Optional Exercises**
1. Create a pivot table and chart from a dataset of your choosing (e.g., types of pets owned by classmates).
2. Using Excel, calculate frequency and percent frequency for a dataset of daily temperatures over a month.
3. Create a histogram with varying bin widths for the dataset above. How does changing the bin width affect the interpretation?
4. Analyze a dataset using Benford's Law. Does the data follow the expected distribution?
5. Compare a frequency polygon and histogram for the same dataset. Which is easier to interpret and why?

---

### **Key Takeaways:**
- Pivot tables and charts are powerful tools for summarizing categorical data.
- Frequency distributions and histograms are essential for visualizing numerical data variability.
- Careful design choices enhance interpretability and reduce cognitive load.
- Benford's Law is a practical application of frequency analysis in real-world scenarios.

---

End of Chapter 5.

---

# CSC402 - Final Lecture: Data Analysis and Storytelling

## Overview
Welcome back! Today marks the final lecture in our **Data Analysis and Storytelling** series. We will explore high-level concepts from **Chapter 6** and **Chapter 7**, focusing on wrapping up the course with discussions on **Exploratory Data Analysis (EDA)**, **Data Visualization**, and **Storytelling with Data**. Today's lecture is less technical and more conceptual, emphasizing how to effectively communicate data-driven insights.

---

## Chapter 6: Exploratory Data Analysis (EDA)

### What is EDA?
EDA is a critical first step in data science, blending **art and science** to explore datasets and uncover patterns without preconceived assumptions. Think of it as venturing into a cave—you don’t know what you’ll find, but you map out what you discover.

**Key Elements:**
- **Descriptive Statistics:** Measures like mean, median, mode, and standard deviation to describe data characteristics.
- **Visualization:** Tools like histograms, box plots, and scatter plots help reveal data trends and outliers.
- **No Assumptions:** EDA is purely exploratory; you're observing, not concluding.

### The AWESOME Acronym in Data Science:
1. **A** - Obtain data
2. **S** - Scrub (clean) data
3. **E** - Explore data (EDA stage)
4. **M** - Model data
5. **E** - Evaluate model

### Data Cleaning (Scrubbing)
Raw data often contains:
- Missing values
- Inconsistent labels
- Redundant columns

**Example:** Downloading bank statements for spending analysis might require removing headers, transaction IDs, and converting formats. Tools like Excel, Python, and **ChatGPT** are invaluable for cleaning data efficiently.

---

## Chapter 7: Data Visualization and Storytelling

### The Importance of Visualization
Humans struggle to spot patterns in raw data. Visualizations bridge this gap, turning numbers into accessible narratives.

**Common Visualization Types:**
- **Bar Charts:** Great for comparing categories.
- **Pie Charts:** Show parts of a whole (use sparingly).
- **Heatmaps:** Represent data density or value intensity.
- **Box and Whisker Plots:** Reveal data spread and outliers.

### Understanding Your Audience
**Tailor your visualizations:**
- **High-Level Executives:** Prefer simple, clear visuals like bar charts or pie charts.
- **Data Analysts:** Appreciate complex visuals like box plots or violin charts.
- **General Audience:** Use straightforward visuals with minimal technical jargon.

### Empathy Through Data
Numbers represent people. Adding human elements to data visualizations creates emotional connections.

**Example:** Instead of just showing the percentage of shelter dogs adopted, include a photo of "Max," a shelter dog still waiting for adoption.

---

## Storytelling with Data

### Why Storytelling Matters
Data is powerful, but storytelling makes it **persuasive**. Use narrative structures like **Freytag's Pyramid**:
1. **Introduction:** Set the stage.
2. **Rising Action:** Present the problem.
3. **Climax:** Reveal key insights.
4. **Falling Action:** Discuss potential solutions.
5. **Conclusion:** Provide actionable recommendations.

### Real-World Example: Hawaiian Bell Case Study
- **Problem:** Customer service scores related to internet outages were below industry benchmarks.
- **Action:** Data scientists analyzed customer call logs and found long wait times and unaddressed neighborhood outages.
- **Solution:** Presenting a fictional customer’s frustrating experience helped executives empathize and understand the urgency of improving response times.

---

## Practical Demonstrations
During class, we:
- Obtained and cleaned COVID-19 death data by state.
- Calculated **deaths per capita** to fairly compare states.
- Visualized the data using **heatmaps** and **bar charts**.
- Discussed how audience needs affect visualization choices.

### Tools Explored:
- **ChatGPT:** For data cleaning and quick insights.
- **Google Colab:** To execute Python scripts and generate visuals.
- **Pandas (Python Library):** Used to manipulate and analyze datasets.

---

## Final Thoughts & Key Takeaways
- **EDA** is the foundation for understanding data.
- **Clean data** leads to clearer insights.
- **Visualizations** should match audience needs.
- **Storytelling** transforms data into impactful narratives.
- Always remember: Data represents real-world elements and people.

Thank you for your engagement this semester! I hope you walk away with a stronger understanding of how to not just analyze data, but also how to **tell compelling stories with it**.

Good luck with your future endeavors. I hope to see you in future courses, or even over the summer!

---

## Optional Exercises
1. Download a dataset of your choice and perform a basic EDA.
2. Create two visualizations for different audiences: one for executives and one for data scientists.
3. Write a short narrative using your data visualizations to tell a compelling story.
4. Reflect on how different visualizations can lead to different interpretations.

---

*Thank you for an amazing semester!*