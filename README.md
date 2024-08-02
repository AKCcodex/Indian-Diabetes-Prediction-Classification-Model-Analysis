

# Data Analysis Project

## Overview

This project demonstrates data analysis and visualization using Python libraries such as pandas, numpy, matplotlib, and seaborn. It includes scripts for data cleaning, manipulation, and generating insightful visualizations to support data-driven decision-making.

## Libraries Used

- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations and array manipulation.
- **matplotlib**: For creating static, animated, and interactive visualizations.
- **seaborn**: For statistical data visualization based on matplotlib.

## Installation

To run the scripts and replicate the analyses, you need to install the required libraries. You can do this using pip. It's recommended to create a virtual environment for your project. Here are the steps to set it up:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. **Navigate into the project directory:**

   ```bash
   cd your-repository
   ```

3. **Create a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   ```

4. **Activate the virtual environment:**

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS/Linux:

     ```bash
     source venv/bin/activate
     ```

5. **Install the required libraries:**

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

## Usage

1. **Prepare Your Data:**

   Place your data files in the `data/` directory. Ensure the files are in the format expected by the scripts.

2. **Run the Analysis Scripts:**

   The main script for analysis is `analysis.py`. You can execute it as follows:

   ```bash
   python analysis.py
   ```

3. **View the Results:**

   The generated visualizations will be saved in the `results/` directory. You can also view them directly if your script includes display commands.

   From the exploratory data analysis, I have concluded that the risk of diabetes depends upon the following factors:
1. Glucose level
2. Number of pregnancies
3. Skin Thickness
4. Insulin level
5. BMI

With in increase in Glucose level, insulin level, BMI and number of pregnancies, the risk of diabetes increases. However, the number of pregnancies have strange effect of risk of diabetes which couldn't be explained by the data. The risk of diabetes also increases with increase in skin thickness.

Coming to the classification models, Logistic Regression outperformed Random Forest and SVM with 78% accuracy. The accuracy of the model can be improved by increasing the size of the dataset. The dataset used for this project was very small and had only 768 rows.

## Project Structure

- `data/`: Contains raw data files.
- `scripts/`: Contains Python scripts for data analysis and visualization.
- `results/`: Contains output visualizations and results.
- `analysis.py`: Main script for data analysis.
- `requirements.txt`: Lists the required Python packages.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request with your proposed changes. Make sure to include tests and documentation for any new features.


## Contact

For questions or feedback, please contact [ashishchoudharythefuture@gmail.com](mailto:ashishchoudharythefuture@gmail.com).

---

Feel free to customize this template to better fit the specifics of your project!
