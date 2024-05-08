# Unsupervised-Learning-for-Risk-Stratification-in-IgA-Nephropathy-Using-Network-Biomarkers.

# User Guide: Generating Cluster Labels

# Introduction
This code is used for predicting cluster labels, suitable for data analysis in biomedical research.

# Requirements
Python version: 3.6+
Install the following Python libraries:
Pandas: version 2.0.3
NumPy: version 1.25.2
NetworkX: version 3.3
SciPy: version 1.11.4
Joblib: version 1.4.2
Scikit-learn: version 1.2.2
UMAP: version 0.5.6
Matplotlib: version 3.7.1

# Usage Steps
Install Python and the required libraries.
Prepare your data file in Excel format, ensuring it matches the format of the reference sample data file stored in the repository.
Call the generate_graph2vec_embeddings_and_predict_clusters function, providing the paths to your data file and the reference sample data file stored in the repository, and specify the output file path.
```
generate_graph2vec_embeddings_and_predict_clusters(input_file_path, reference_file_path, output_file_path)
```

# Function Description
generate_graph2vec_embeddings_and_predict_clusters(input_file_path, reference_file_path, output_file_path):
Input Parameters:
input_file_path: Path to your data file in Excel format.
reference_file_path: Path to the reference sample data file stored in the repository.
output_file_path: Path to the output file where the results will be saved.
Functionality:
Reads your data and the reference sample data from the provided files.
Generates graph embeddings and predicts cluster labels.
Saves the results to the output file.

# Notes
Ensure that your data file format matches the format of the reference sample data file stored in the repository.
Adjust the parameters and thresholds in the code according to your requirements.
Make sure to install the required Python libraries and ensure the versions match the specified versions before usage.

# Example Code
```
input_file_path = "/path/to/your_data_file.xlsx"
reference_file_path = "https://raw.githubusercontent.com/exampleuser/reference_samples/main/reference_samples.xlsx"
output_file_path = "/path/to/output_file.xlsx"
generate_graph2vec_embeddings_and_predict_clusters(input_file_path, reference_file_path, output_file_path)
```

# Feedback and Support
If you encounter any issues or have any suggestions while using the code, feel free to reach out to us. Happy coding!
