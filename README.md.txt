# Netflix Data Analysis 

This project explores and analyzes a dataset of Netflix movies and TV shows to uncover insights related to content type, release year, country distribution, and more.

## Dataset

The dataset contains information about Netflix titles, including:
- Title
- Type
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Description
- Listed in

##Data discrepancies 
- Checked for duplicates-not found 
- missing value
  director        2634
  cast             825
  country          831
  date_added        10
  rating             4
  duration           3
- inconsistent date-format etc.
  


## Data Cleaning Steps

- Handled missing values by replacing director, cast, country, duration with 'Unknown'
  and date_added with 'Not Available',and filled rating with most frequent rating using   
  mode.
- Standardized inconsistent text formats (e.g., country names, ratings).
- Converted date columns to a consistent format and datetime dtype.
- Renamed all column headers to be lowercase and remove spaces.
- Checked and handled inconsistent formats.

## 🧰 Tools & Technologies

- Python
- Pandas
- Jupyter Notebook

## 📌 How to Run

1. Clone the repository or download the notebook.
2. Open the `.ipynb` file in Jupyter Notebook.
3. Make sure to install required libraries (Pandas, etc.).
4. Run the cells to view analysis and insights.

## Author

   Sapana Pal


