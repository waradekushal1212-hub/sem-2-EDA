

---

# README – Functions Used in Experiment 11

## **Overview**

This document explains the key Python and pandas functions used for performing categorical data analysis in the notebook.

---

## **pd.DataFrame()**

**Purpose:**
Creates a DataFrame from structured data such as a dictionary or list.

**Usage:**
Converts raw data into a tabular format for analysis.

---

## **value_counts()**

**Purpose:**
Counts the frequency of unique values in a column.

**Usage:**
Used to determine how many times each category or value appears.

**Example Use Case:**
Counting number of orders per category or payment method.

---

## **unique()**

**Purpose:**
Returns all unique values from a column.

**Usage:**
Helps identify distinct categories present in the dataset.

---

## **nunique()**

**Purpose:**
Returns the number of unique values in a column.

**Usage:**
Used to measure diversity or variation in categorical data.

---

## **pd.crosstab()**

**Purpose:**
Generates a cross-tabulation table between two columns.

**Usage:**
Used to analyze relationships between categorical variables.

**Example Use Case:**
Comparing Category vs Payment Method or Delivery Type vs Customer Type.

---

## **Column Selection (df['column_name'])**

**Purpose:**
Accesses a specific column from the DataFrame.

**Usage:**
Used as a base operation for applying functions like value_counts() or unique().

---

## **Data Filtering (Boolean Indexing)**

**Syntax:**
df[df['column'] == value]

**Purpose:**
Filters rows based on a condition.

**Usage:**
Extracts specific subsets of data, such as all orders from a particular category.

---

## **Arithmetic Operations**

**Purpose:**
Used to compute percentages or ratios.

**Example:**
Dividing frequency counts by total values to get percentage distribution.

---

## **len()**

**Purpose:**
Returns the total number of elements (rows in DataFrame).

**Usage:**
Used in calculating proportions and percentages.

---

## **Conclusion**

The notebook primarily uses pandas functions for:

* Data creation
* Frequency analysis
* Identifying unique values
* Cross-tabulation
* Filtering and basic computations

These functions form the foundation of categorical data analysis in Python.

---


