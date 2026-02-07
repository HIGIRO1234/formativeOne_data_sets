# formativeTwo_data_sets

# Principal Component Analysis (PCA) From Scratch  
## Advanced Linear Algebra – Formative Assignment

---

## Project Overview
This project implements **Principal Component Analysis (PCA) from scratch** using advanced linear algebra concepts, including **covariance matrices, eigenvalues, and eigenvectors**.  
The objective is to reduce the dimensionality of an **Africanized real-world dataset** while preserving as much variance (information) as possible.

The implementation strictly avoids high-level PCA libraries (such as `sklearn`) and instead relies on **NumPy-based linear algebra operations**, in accordance with the assignment requirements.

---

## Dataset Description
- **Dataset Name:** African Economic Outlook Dataset  
- **Context:** African socio-economic and development indicators  
- **Key Characteristics:**
  - Contains **more than 10 columns**
  - Includes **missing (NaN) values**
  - Contains **non-numeric (categorical) columns**
- **Source:** Public African economic data hosted on GitHub

Before applying PCA, non-numeric columns were excluded and missing values were handled using appropriate preprocessing techniques.

---

## Project Objectives
The main objectives of this project are to:
1. Implement PCA **from scratch** using linear algebra principles  
2. Compute the **covariance matrix** of the dataset  
3. Perform **eigendecomposition** to obtain eigenvalues and eigenvectors  
4. Project the data onto principal components  
5. Dynamically select the number of components based on **explained variance**  
6. Optimize the PCA implementation for performance and scalability  

---

## Methodology
The PCA process followed these steps:

1. Load and explore the dataset  
2. Separate numeric and non-numeric features  
3. Handle missing values using **mean imputation**  
4. Center the data by subtracting the mean  
5. Compute the **covariance matrix**  
6. Compute **eigenvalues and eigenvectors**  
7. Sort components based on explained variance  
8. Project data onto selected principal components  
9. Dynamically select components using a **95% cumulative variance threshold**

---

## Technologies Used
- Python 3.x  
- NumPy  
- Pandas  
- Matplotlib  
- Google Colab  

---

## How to Run the Project (Google Colab)

This project is designed to be executed using **Google Colab**.

1. Open the notebook using the link below:  
   https://colab.research.google.com/drive/1i19CLWYw8diPsmF9Ve-yr6D0Rb5ZUpXf#scrollTo=2aBBHCgqVDPH

2. Ensure you are signed in to your Google account.

3. Click **Runtime → Run all** to execute all cells sequentially.

4. All outputs, including tables, calculations, and visualizations, will be displayed directly in the notebook.

 No local installation is required.

---

## Repository Structure
