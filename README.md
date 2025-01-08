
# Mixture Model Analysis Project

This project demonstrates how to identify latent subgroups in data using mixture models. It includes a dataset with variables like performance, stress, age, and gender, as well as an R Markdown file to perform the analysis.

---

## Overview

The goal of this project is to fit a Gaussian Mixture Model (GMM) to the dataset to classify participants into latent groups based on their performance and stress levels. This approach is commonly used in psychology, human factors, and behavioral research to uncover hidden patterns in data.

---

## Files in This Project

1. **`mixture_data.csv`**  
   - A simulated dataset with 200 participants.  
   - Includes:
     - Performance scores.
     - Stress levels.
     - Demographic variables (age and gender).  

2. **`mixture_model_analysis.Rmd`**  
   - An R Markdown file for analyzing the dataset using mixture models.  
   - Steps covered:
     - Data exploration and visualization.
     - Fitting a Gaussian Mixture Model (GMM) using the `mclust` package.
     - Visualizing clusters and interpreting the results.

---

## Getting Started

1. **Download the Files**:  
   Clone this repository or download the files manually.

2. **Install Required R Packages**:  
   Ensure the following packages are installed:  
   ```R
   install.packages(c("tidyverse", "mclust"))
   ```

3. **Run the Analysis**:  
   Open `mixture_model_analysis.Rmd` in RStudio and knit it to an HTML file. Follow the steps in the R Markdown file to visualize the data, fit the model, and interpret the clusters.

---

## Dataset Details

- **Performance**: Task performance scores (higher is better).
- **Stress**: Self-reported stress levels (1–10 scale).  
- **Age**: Participant age (18–65).  
- **Gender**: Participant gender (Male, Female, Non-Binary).  

The data includes two latent subgroups:
1. **High Performance, Low Stress**: Represents participants with strong task performance and low stress levels.  
2. **Low Performance, High Stress**: Represents participants with weaker performance and higher stress levels.  

---

## Why Mixture Models?

Mixture models are useful for identifying hidden subgroups in data. This project uses a Gaussian Mixture Model (GMM) to classify participants based on performance and stress levels. The results can help researchers understand the characteristics of each group and guide further analysis or interventions.

---

## Contribution

If you have suggestions, improvements, or questions, feel free to open an issue or submit a pull request.

---

## License

This project is available under the [MIT License](LICENSE). Feel free to use it, adapt it, and share it with proper attribution.
