# README: Confidence Interval Analysis

## Project Overview
This project involves the application of statistical methods to estimate confidence intervals for the mean durability of print-heads in terms of the number of characters printed before failure. The work focuses on quality control processes, where destructive sampling necessitates small sample sizes.

### Background
In the given scenario, a manufacturer of print-heads for personal computers aims to estimate the mean durability of their product. The destructive testing process, which assesses whether the print-heads meet quality standards, destroys the items being tested, making large sample sizes impractical.

### Data Description
A random sample of 15 print-heads was tested until failure. The recorded durability (in millions of characters) for each print-head is as follows:

```
1.13, 1.55, 1.43, 0.92, 1.25, 1.36, 1.32, 0.85, 1.07, 1.48, 1.20, 1.33, 1.18, 1.22, 1.29
```

### Tasks
1. **99% Confidence Interval Using Sample Standard Deviation**
   - Construct a 99% confidence interval for the mean durability using the sample standard deviation.
   - Justify the use of the t-distribution due to the small sample size.

2. **99% Confidence Interval Using Known Population Standard Deviation**
   - Construct a 99% confidence interval assuming the population standard deviation is known to be 0.2 million characters.

### Methodology
#### Confidence Interval Using Sample Standard Deviation
- **Step 1:** Calculate the sample mean and sample standard deviation.
- **Step 2:** Use the t-distribution to account for the small sample size (degrees of freedom = n – 1).
- **Step 3:** Calculate the margin of error using the t-critical value and the sample standard deviation.
- **Step 4:** Construct the confidence interval as:
  
  “Sample Mean ± Margin of Error”

#### Confidence Interval Using Known Population Standard Deviation
- **Step 1:** Use the sample mean from the data.
- **Step 2:** Use the z-distribution, as the population standard deviation is known.
- **Step 3:** Calculate the margin of error using the z-critical value and the population standard deviation.
- **Step 4:** Construct the confidence interval similarly as:

  “Sample Mean ± Margin of Error”

### Results
This section includes the computed confidence intervals for both cases, ensuring accurate interpretation of statistical estimates. Replace this placeholder with your detailed results and conclusions.

## Prerequisites
- Python or any statistical software for computation (optional for manual calculations).
- Basic knowledge of statistics, particularly t-distributions and z-distributions.

## Files
- **Confidence Interval.docx:** The project brief and sample data.
- **README.md:** This documentation file.

