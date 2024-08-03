

# Data Analysis Project

## Overview

This project demonstrates data analysis and visualization using Python libraries such as pandas, numpy, matplotlib, and seaborn. It includes scripts for data cleaning, manipulation, and generating insightful visualizations to support data-driven decision-making.


#Exploratory Data Analysis

In the exploratory data analysis, I will be looking at the distribution of the data, the correlation between the features, and the relationship between the features and the target variable. I will start by looking at the distribution of the data, followed by relationship between the target variable and independent variables.

![image](https://github.com/user-attachments/assets/9e8ffb08-f629-42f3-b5cc-19fac7af2b83)

Age Distribution and Diabetes

![image](https://github.com/user-attachments/assets/55b6cdbb-bceb-49ae-ac88-f6e508d31009)

From the graph, it is quite clear that majority of the patients are adult within the age group of 20-30 years. Patients in the age range 40-55 years are more prone to diabetes, as compared to other age groups. Since the number adults in the age group 20-30 years is more, the number of patients with diabetes is also more as compared of other age groups.

Pregnancies and Diabetes

![image](https://github.com/user-attachments/assets/9ce62b2e-4a11-49ab-8cec-d44d5c9d04cb)
Both boxplot and violinplot shows strange relation between the number of preganacies and diabetes. According to the graphs the increased number of pregnancies highlights increased risk of diabetes.

Glucose and Diabetes¶
![image](https://github.com/user-attachments/assets/f0aa42cf-37c8-41d3-a092-b121e97d1cdb)
Glucose level plays a major role in determine whether the patient is diabetic or not. The patients with median gluocse level less than 120 are more likely to be non-diabetic. The patients with median gluocse level greather than 140 are more likely to be diabetic. Therefore, high gluocose levels is a good indicator of diabetes.

Blood Pressuse and Diabetes¶

![image](https://github.com/user-attachments/assets/7895b81f-4263-4294-b670-7c8b3f71cb46)
Both the boxplot and voilinplot provides clear understanding of the realtion between the blood pressure and diabetes. The boxplot shows that the median of the blood pressure for the diabetic patients is slightly higher than the non-diabetic patients. The voilinplot shows that the distribution of the blood pressure for the diabetic patients is slightly higher than the non-diabetic patients. But there has been not enough evidence to conclude that the blood pressure is a good predictor of diabetes.

Skin Thickness and Diabetes

![image](https://github.com/user-attachments/assets/a679e808-3f64-4308-9ed5-fb9d6269d27f)

Here both the boxplot and violinplot reveals the effect of diabetes on skin thickness. As obserevd in the boxplot, the median of skin thickness is higher for the diabetic patients than the non-diabetic patients, where non diabetic patients have median skin thickness near 20 in comparison to skin thickness nearly 30 in diabetic patients. The voilinpplot shows the distribution of patients' skin thickness amoung the patients, where the non diabetic ones have greater distribution near 20 and diabetic much less distribution near 20 and increased distribution near 30. Therefore, skin thickness can be a indicator of diabetes.

Insulin and Diabetes

![image](https://github.com/user-attachments/assets/36148af6-07f3-46bb-ac47-8b009484186b)

Insulin is a major body hormone that regulates glucose metabolism. Insulin is required for the body to efficiently use sugars, fats and proteins. Any change in insulin amount in the body would result in change glucose levels as well. Here the boxplot and violinplot shows the distribution of insulin level in patients. In non diabetic patients the insulin level is near to 100, whereas in diabetic patients the insulin level is near to 200. In the voilinplot we can see that the distribution of insulin level in non diabetic patients is more spread out near 100, whereas in diabetic patients the distribution is contracted and shows a little bit spread in higher insulin levels. This shows that the insulin level is a good indicator of diabetes.

BMI and Diabetes

![image](https://github.com/user-attachments/assets/65c369c3-9661-4983-a7e6-a02ba11ed757)

Both graphs highlights the role of BMI in diabetes prediction. Non diabetic patients have a normal BMI within the range of 25-35 whereas the diabetic patients have a BMI greater than 35. The violinplot reveals the BMI distribution, where the non dibetic patients have a increased spread from 25 to 35 with narrows after 35. However in diabetic patients there is increased spread at 35 and increased spread 45-50 as compared to non diabetic patients.Therefore BMI is a good predictor of diabetes and obese people are more likely to be diabetic.

Diabetes Pedigree Function and Diabetes Outcome

![image](https://github.com/user-attachments/assets/f7641957-cf27-4f54-9f17-43f0cbd66dd4)

Diabetes Pedigree Function (DPF) calculates diabetes likelihood depending on the subject's age and his/her diabetic family history. From the boxplot, the patients with lower DPF, are much less likely to have diabetes. The patients with higher DPF, are much more likely to have diabetes. In the violinplot, majority of the non diabetic patients have a DPF of 0.25-0.35, whereas the diabetic patients have a increased DPF, which is shown by the their distribution in the violinplot where there is a increased spread in the DPF from 0.5 -1.5. Therefore the DPF is a good indicator of diabetes.

Coorelation Matrix Heatmap

![image](https://github.com/user-attachments/assets/d8b52712-cf96-4db1-9564-858cd8f487d3)









Model Evaluation

Evaluating Logistic Regression Model¶
![image](https://github.com/user-attachments/assets/065c50ee-e037-4c7f-937e-3f71fb1b3e34)

![image](https://github.com/user-attachments/assets/d5c59536-53e0-4286-bbb9-17496ea61179)


Evaluating Random Forest Classifier
![image](https://github.com/user-attachments/assets/0f129cd8-0182-4777-9f8c-44d74d02a44e)

![image](https://github.com/user-attachments/assets/0519b264-46a9-4ebc-bb40-e7870b59d5bc)


Evaluating SVM Model

![image](https://github.com/user-attachments/assets/c996d673-2a53-4c27-b9e1-25a221ea9b24)

![image](https://github.com/user-attachments/assets/7cc52b04-7bfe-4604-bdf3-db52470e2638)



Comparing the models

![image](https://github.com/user-attachments/assets/42add876-0b1c-49de-8cb9-6d53180ebe17)

Conclusion
From the exploratory data analysis, I have concluded that the risk of diabetes depends upon the following factors:

Glucose level
Number of pregnancies
Skin Thickness
Insulin level
BMI
With in increase in Glucose level, insulin level, BMI and number of pregnancies, the risk of diabetes increases. However, the number of pregnancies have strange effect of risk of diabetes which couldn't be explained by the data. The risk of diabetes also increases with increase in skin thickness.

Coming to the classification models, Logistic Regression outperformed Random Forest and SVM with 78% accuracy. The accuracy of the model can be improved by increasing the size of the dataset. The dataset used for this project was very small and had only 768 rows.




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
