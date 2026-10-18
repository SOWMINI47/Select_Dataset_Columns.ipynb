# Select Dataset Columns Using Pandas

## Project Overview
This project demonstrates how to select specific rows and columns from a Pandas DataFrame using `loc` and `iloc`. It includes label-based and integer-position-based selection examples.

## Objectives
- Understand the difference between `loc` and `iloc`.
- Select individual rows and columns.
- Select multiple rows and columns together.
- Retrieve a specific value from a DataFrame.
- Filter records using a condition.

## Technologies Used
- Python
- Pandas
- Google Colab / Jupyter Notebook

## Concepts Covered

### 1. Label-Based Selection with `loc`
`loc` selects rows and columns by their labels.

```python
df.loc[0]
df.loc[:, ["Name", "Marks"]]
df.loc[0:2, ["Name", "Marks"]]
```

### 2. Position-Based Selection with `iloc`
`iloc` selects rows and columns using integer positions.

```python
df.iloc[0]
df.iloc[:, [0, 2]]
df.iloc[0:3, 0:2]
```

### 3. Conditional Selection
The project filters students whose marks are 85 or above.

```python
df.loc[df["Marks"] >= 85, ["Name", "Marks"]]
```

## Dataset
A sample student dataset is created in the notebook with these columns:
- `Name`
- `Age`
- `Course`
- `Marks`

## Tasks Performed
- Created a DataFrame using sample student data.
- Displayed the complete dataset.
- Selected a row using `loc` and `iloc`.
- Selected specific columns.
- Selected rows and columns together.
- Retrieved an individual cell value.
- Filtered records based on marks.

## How to Run
1. Open the notebook in Google Colab or Jupyter Notebook.
2. Run the code cell.
3. Review the printed results for each selection operation.

## Key Learning Outcomes
- Use `loc` for label-based selection.
- Use `iloc` for integer-position-based selection.
- Access particular rows, columns, and cell values.
- Apply a condition to filter DataFrame records.

## Project Structure

```text
Select-Dataset-Columns/
├── Select_Dataset_Columns.ipynb
└── README.md
```

## Conclusion
This project provides hands-on practice with Pandas `loc` and `iloc`, two essential methods for selecting and exploring data in a DataFrame.
