# Experiment - 18 - Data Visualization using Advanced Graphs

Complex visualization in Python involves using libraries like Plotly, Bokeh, or Seaborn to create multi-dimensional, interactive, or hierarchical charts that go beyond standard bar and line graphs. 

These techniques, such as treemaps or 3D plots, are used to uncover hidden patterns and relationships within large, high-dimensional datasets that simple visuals cannot capture. By providing interactivity and depth, they allow stakeholders to intuitively explore data and make more informed, data-driven decisions.

### Aim:
To visualize Data using Advanced Graph. 

### Tools used:
Google Colab or Jupyter Notebook

### Theory:

To visualize data using Advanced Graphs, certain libraries are needed other than Seaborn and matplotlib. These are:

* plotly.express: A high-level interface for Plotly that allows for rapid creation of complex, interactive figures with minimal code. In this notebook, it is specifically used to generate a Treemap to visualize department budgets.

* scipy.cluster.hierarchy: A module used for hierarchical and agglomerative clustering. The notebook utilizes its linkage and dendrogram functions to compute the relationships between data points and visualize them as a Dendrogram.

* matplotlib_venn: A library designed for plotting area-weighted Venn diagrams. While mentioned in your list, this specific notebook primarily focuses on advanced graphs like Treemaps and Dendrograms for visualization.

* plotly.graph_objects: A lower-level interface to Plotly that provides more granular control over figure customization and structure. It is the foundation upon which Plotly Express is built, offering more flexibility for intricate chart designs.

### Advanced Graph:**
Traditional Charts like bar chart, Line graphs are useful for visualizing basic trends, advanced graphs are essential for uncovering hierarchial structures, multi - dimensional relationship and complex data flows

#### Treemap:

* A Treemap is a visualization that represents hierarchical data using nested rectangles.

**Key Features:**

* Each rectangle represents a category 
* Size of rectangle = value of data 
* Smaller rectangles are inside larger ones

<img width="986" height="986" alt="image" src="https://github.com/user-attachments/assets/4b176ec4-483d-4534-911b-1382ed826ee0" />


#### Dendrogram:

* A Dendrogram is a tree-like diagram used to show hierarchical clustering.

**Key Features:**

* Shows how data points are grouped 
* Branches represent clusters 
* Height shows similarity/distance


<img width="1061" height="796" alt="image" src="https://github.com/user-attachments/assets/67aa2b53-5bef-49c3-8fd9-c6ac4ac15768" />


#### Ven Diagram:

* A Venn Diagram shows relationships between sets using overlapping circles.

**Key Features:**

* Each circle = a set 
* Overlapping area = common elements 
* Non-overlapping = unique elements

<img width="879" height="912" alt="image" src="https://github.com/user-attachments/assets/7684bc4a-9d60-4999-b50c-7109d2e00a85" />


#### Heatmap

A heatmap is a graphical representation of data where values are shown using colors.

**Key Features:**

* Show correlationship between variables 
* Identify patterns quickly 
* Highlight strong/weak correlations

<img width="1238" height="1079" alt="image" src="https://github.com/user-attachments/assets/c9e3fb29-4a33-465f-a2f5-94d09dac6186" />


#### 3D Scatter Plot

* A 3D scatter plot is used to display the relationship between three numerical variables.
* X-axis → first variable 
* Y-axis → second variable 
* Z-axis → third variable 

**Key Features:**

* Analyze 3 variables at once 
* Identify patterns in multi-dimensional data 
* Used in scientific and business analysis

<img width="1092" height="1132" alt="image" src="https://github.com/user-attachments/assets/5117fd07-d6f8-4c07-a96c-fa8fcfc2bf39" />


#### Sankey Diagram

* A flow diagram in which the width of the arrows is proportional to the flow rate.
* It visualizes the transformation and movement of data between multiple states or nodes.

**Key Features:**

* Proportional Link Width
* Flow Conservation
* Visualizing Many-to-Many Mappings

<img width="1000" height="750" alt="image" src="https://github.com/user-attachments/assets/aebb4ad2-acde-47ae-81dd-a6e8f203b392" />


#### Radar Chart

* A 2D chart that displays multivariate data on three or more quantitative variables represented on axes starting from the same central point.

**Key Feature:**

* Common Central Origin
* Comparison of multiple entities in the same graph
* Pattern & Outlier Detection

<img width="4032" height="2689" alt="image" src="https://github.com/user-attachments/assets/46598f85-302d-4be0-a80a-a95fd70f93e1" />


### Learning Outcomes:
* Implementation of Hierarchical Visualizations
* Mastery of Clustering Visuals
* Proficiency in Python Visualization Libraries

### Applications:
* Corporate Finance
* Data Science & Machine Learning: Using Dendrograms to determine the optimal number of clusters for algorithms like K-Means or Agglomerative Clustering.
* Biological & Genetic Research: Identifying similarities between different species or gene expressions based on multi-dimensional feature sets.

### Advantages:
* Space Efficiency: Treemaps allow for the display of hundreds of categories in a compact space while maintaining the ability to see part-to-whole relationships.

* Clarity in Relationships: Dendrograms provide a clear visual map of how individual data points or groups are related based on their mathematical similarity (distance).

* Interactivity: Using tools like Plotly provides dynamic features (hovering for data labels) that static charts cannot offer, making data exploration more intuitive.

### Conclusion:
 This experiment demonstrates the effective use of advanced Python libraries like Plotly and SciPy to visualize complex hierarchical and clustered data through Treemaps and Dendrograms and the output is verified.


