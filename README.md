# Statistical Analysis Project: Hypothesis Testing and Confidence Intervals

This project demonstrates the application of **inferential statistics** using Python. It includes calculations for **Z-scores**, **probabilities**, **confidence intervals**, and **hypothesis testing**. The project uses the **scipy.stats** library to perform these statistical analyses.

---

## Features

### 1. **Z-Score & Probability Calculation**
- Given a population mean, sample mean, and standard deviation, the code calculates the **Z-score** and **probability** of obtaining a sample mean below a certain value.
- **Example**:
  - Calculate the probability that the sample mean is less than 58 months, given a population mean of 60 months and a standard deviation of 6 months.

### 2. **Confidence Interval Calculation**
- The code calculates a **95% confidence interval** for the population mean based on sample data.
- **Example**:
  - Calculate the 95% confidence interval for a sample mean of 310, standard deviation of 89, and sample size of 40.

### 3. **Hypothesis Testing**
- Perform **two-tailed hypothesis tests** to determine if the population mean has changed, based on sample data.
  - **Example**:
    - Test if the mean waiting time has changed from 4.5 minutes using a two-tailed test.
  
- Perform a **one-tailed hypothesis test** to check if the mean income is greater than a certain value.
  - **Example**:
    - Test if the mean income is greater than $29,000 based on a sample mean of $30,000 and population standard deviation of $8,000.

---

## Installation

To run the project, you need **Python 3** and the following dependencies:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/HunarAgrawal/Estimation_Theory.git
   cd Estimation_Theory
2. **Install required libraries**:
   ```bash
   pip install scipy math

---

## Usage

After setting up the project and installing dependencies, you can run the script to perform the statistical analysis:

1. Run the script:
   ``bash
   python analysis.py
   
2. The script will print:
- The probability of a sample mean being less than a specified value.
- The 95% confidence interval for the population mean.
- The p-value from a two-tailed hypothesis test.
- The decision of a one-tailed hypothesis test.

---

## File Descriptions

- analysis.py: Main Python script that performs the statistical calculations and prints the results.
  - The script performs:
    - Z-score calculation and probability determination.
    - Confidence interval calculation.
    - Two-tailed and one-tailed hypothesis tests.

---

## Dependencies

- Python 3.7 or higher
- scipy: For statistical functions and distributions.
- math: For mathematical calculations like square root.

Install them with :

- ```bash
  pip install scipy math

---

## Contributing

Contributions are welcome! If you have suggestions for improvements or additional features, feel free to fork the repository, make your changes, and submit a pull request.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Author

Hunar Agrawal

---

## Acknowledgments

Thanks to the documentation and resources provided by the following libraries:

- SciPy: For statistical functions and probability distributions.
- Python Math: For basic mathematical operations.
