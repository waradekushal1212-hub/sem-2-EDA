

---

# README – Functions Used in Experiment 12

## **Overview**

This document explains the key Python and pandas functions used in the notebook for data manipulation, analysis, and basic operations.

---

## **pd.read_csv()**

**Purpose:**
Loads data from a CSV file into a DataFrame.

**Usage:**
Used to import datasets for further processing and analysis.

---

## **pd.DataFrame()**

**Purpose:**
Creates a DataFrame from structured data like dictionaries or lists.

**Usage:**
Used to organize and structure data for analysis.

---

## **head()**

**Purpose:**
Displays the first few rows of the dataset.

**Usage:**
Helps in quickly understanding the structure of the data.

---

## **tail()**

**Purpose:**
Displays the last few rows of the dataset.

**Usage:**
Used to inspect the ending portion of the dataset.

---

## **info()**

**Purpose:**
Provides a concise summary of the DataFrame.

**Usage:**
Shows column names, data types, and non-null values.

---

## **describe()**

**Purpose:**
Generates summary statistics for numerical columns.

**Usage:**
Used to understand distribution, mean, standard deviation, etc.

---

## **shape**

**Purpose:**
Returns the number of rows and columns.

**Usage:**
Used to check dataset size.

---

## **columns**

**Purpose:**
Displays column names.

**Usage:**
Helps identify variables in the dataset.

---

## **isnull()**

**Purpose:**
Detects missing values.

**Usage:**
Returns a boolean structure indicating null entries.

---

## **sum()**

**Purpose:**
Calculates total values.

**Usage:**
Commonly used with isnull() to count missing values.

---

## **dropna()**

**Purpose:**
Removes missing values.

**Usage:**
Used to clean the dataset by dropping null rows or columns.

---

## **fillna()**

**Purpose:**
Fills missing values.

**Usage:**
Replaces null values with mean, median, or a specified value.

---

## **sort_values()**

**Purpose:**
Sorts the DataFrame by specified column(s).

**Usage:**
Used to arrange data in ascending or descending order.

---

## **iloc[]**

**Purpose:**
Selects data using integer-based indexing.

**Usage:**
Used to access specific rows and columns by position.

---

## **loc[]**

**Purpose:**
Selects data using labels.

**Usage:**
Used to filter data based on row/column names.

---

## **Conclusion**

The notebook uses essential pandas functions for:

* Data loading
* Data inspection
* Handling missing values
* Data selection and sorting

These functions are fundamental for efficient data preprocessing and analysis.

---

