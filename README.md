# Cricket Score Analyzer

## Overview
The Cricket Score Analyzer is a Python-based project that records, manages, and visualizes cricket scores using Excel files. The project leverages Python libraries such as OpenPyxl, Pandas, NumPy, and Matplotlib to handle data and generate insightful visualizations of cricket match performances.

## Features
- **Record Match Scores**: Users can input over-wise scores for two teams.
- **Data Storage**: Saves match data in an Excel file.
- **Data Extraction**: Reads and processes data from an Excel file.
- **Visualization**: Plots team scores along with wickets using Matplotlib.

## Technologies Used
- Python
- OpenPyxl (for Excel file handling)
- Pandas (for data manipulation)
- NumPy (for numerical operations)
- Matplotlib (for data visualization)

## Installation & Setup
### Prerequisites
Ensure you have the following dependencies installed:
```bash
pip install openpyxl pandas numpy matplotlib
```

### Running the Project
1. Run the script.
2. Enter scores for each over.
3. Data is stored in `excelproject.xlsx`.
4. The script reads the file and generates a visualization.

## How It Works
1. **User Input**: The script prompts users to input scores for each over.
2. **Data Storage**: Scores are saved in an Excel sheet (`excelproject.xlsx`).
3. **Data Processing**: The script reads the Excel file and organizes data into Pandas DataFrame.
4. **Visualization**:
   - Line plot showing the runs scored by each team per over.
   - Wickets are highlighted using scatter points.

## Output
- Console displays structured data in tabular format.
- A graph with:
  - Team1 and Team2 scores plotted against overs.
  - Wickets indicated with red (Team1) and yellow (Team2) markers.

## Future Enhancements
- Add graphical user interface (GUI) for better user experience.
- Implement real-time data updates.
- Support for multiple matches.

---
This project provides an easy and efficient way to analyze cricket match scores.

