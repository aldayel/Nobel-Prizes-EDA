# Nobel Prizes 1901-2016 Analysis

This project explores and analyzes the Nobel Prize data from 1901 to 2016. The main goal is to provide insights into trends, distributions, and patterns among Nobel laureates over more than a century of awards. 

## Overview

This project analyzes the historical data of Nobel Prizes awarded between 1901 and 2016. It covers various aspects of the awards, including:
- Distribution of prizes over time
- Categories of awards (Physics, Chemistry, Peace, etc.)
- Geographical trends and nationalities of laureates
- Gender distribution among the winners


## Data Description

The dataset used in this project contains records of Nobel Prize winners from 1901 to 2016. Each record typically includes:
- **Year**: The year the prize was awarded.
- **Category**: The field of the Nobel Prize (e.g., Physics, Chemistry, Medicine, Literature, Peace, and Economic Sciences).
- **Laureate Information**: Names, nationalities, and other pertinent details about the laureates.

## Project Structure

```
Nobel_Prizes_1901-2016/
├── Nobel_Prizes_1901-2016.ipynb   # Main Jupyter Notebook for data analysis
├── data/
│   
├── README.md                      # This file
└── requirements.txt               # List of required Python packages
```

- **Nobel_Prizes_1901-2016.ipynb**: The primary notebook that contains the complete analysis workflow.
- **requirements.txt**: A file specifying the Python dependencies required to run the notebook.


## Installation and Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/Nobel_Prizes_1901-2016.git
   cd Nobel_Prizes_1901-2016
   ```

2. **Create a Virtual Environment (Optional but Recommended)**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

   *Dependencies may include:*
   - Python 3.x
   - pandas
   - numpy
   - matplotlib
   - jupyter

4. **Launch the Jupyter Notebook**

   ```bash
   jupyter notebook Nobel_Prizes_1901-2016.ipynb
   ```
   
## License
MIT License.
