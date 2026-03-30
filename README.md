# Cafe Sales Cleanup

## Objective

The Cafe Sales Cleanup project aimed to create a useable data for practical use. The primary focus was to fill in missing values as accurately as possible. This experience was designed to widen my knowledge in different ways to accomplish the same task.

### Skills Learned

- Ability to identify different types of missing data.
- Implement different techniques to impute data.
- Utilize data cleaning tools in excel.

## Steps

I cleaned this data using Excel. The dataset is from
<a href="https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training"> Kaggle. </a>

<img width="500" height="500" alt="Screenshot 2026-03-28 125304" src="https://github.com/user-attachments/assets/1f1c79ca-b8d8-4825-a66e-fca35ea135ba" />

*Ref 1: Preview of data before cleaning*

### Step 1: Remove Duplicate Values

I started with removing duplicates using Excel's built-in "Remove Duplicates" feature.

<img width="368" height="296" alt="Screenshot 2026-03-30 165016" src="https://github.com/user-attachments/assets/0ca6ec21-f852-4e15-bd50-13e82c80b6ab" />

*Ref 2: "Remove Duplicates" button in Data tab in excel*

### Step 2: Normalize Data

The next step involved normalizing the data, which included ensuring consistency in formatting within each column (ex: dates formatted as MM/DD/YYYY). Additionally, I reviewed text-based columns to standardize categorical values and eliminate inconsistencies (ex: ensuring “cake” and “Cake” are treated as the same category).

### Step 3: Handle Null and Blank Values

The thrid step was the most tedious, as it involved handling the null and blank values. I applied different impuation techniques depending on the field. I used:

- Mean imputation for quantity and location
- Forward fill for missing date values
- Pivot tables to determine a correlation between price and item
- Simple calculations for total, price, and quantity

I deleted a total of 6 rows (where at least 3 fields were missing from item, price, qty, and total). The amount of information present was not enough to discern the values for the missing fields.

### Step 4: Remove Unnecessary Columns

The final step in the data cleaning process involved evaluating and removing unnecessary columns. Given the dataset’s limited scope, all columns were determined to provide meaningful value for analyzing basic sales trends. No columns were removed.


<img width="500" height="500" alt="Screenshot 2026-03-28 125402" src="https://github.com/user-attachments/assets/f1654384-da72-4b9e-9d22-54cdeeefc147" />

*Ref 3: Preview of data after cleaning*
