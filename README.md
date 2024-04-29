\`\`\`markdown

\# Semi-Supervised Learning with MNIST

\## Project Overview

This repository contains the implementation of several semi-supervised learning techniques applied to the MNIST dataset of handwritten digits. The project was developed as part of the CSC 4850/6850 courses, focusing on enhancing model performance using limited labeled data alongside a larger pool of unlabeled data.

\## Techniques Implemented

\- \*\*Baseline Model\*\*: A simple supervised model using only labeled data.

\- \*\*Entropy Minimization\*\*: Reduces the entropy of model predictions to leverage unlabeled data.

\- \*\*Pseudo Labeling\*\*: Uses the model's predictions as labels for unlabeled data to extend the training set.

\- \*\*Virtual Adversarial Training\*\*: Improves model robustness by training against input perturbations that maximize output distribution changes.

\- \*\*K-means Pseudo Labeling\*\*: Combines K-means clustering and pseudo labeling for utilizing structural patterns in unlabeled data.

\## Repository Structure

\`\`\`

/

├── Data\_Creation.ipynb # Notebook for data setup and preprocessing.

├── E0\_BaseLine\_Model.ipynb # Baseline model using only labeled data.

├── E1\_Entropy\_Minimization.ipynb # Implements entropy minimization technique.

├── E2\_Pseudo\_Labelling.ipynb # Implements pseudo labeling technique.

├── E3\_Virtual\_Adversarial\_Training.ipynb # Implements VAT.

├── E4\_Kmeans\_Pseudo\_Labels.ipynb # Combines K-means clustering with pseudo labeling.

├── F2023finalProjects.pdf # Project proposal and guidelines.

├── Saved\_Data/ # Folder containing preprocessed data files.

├── Report Sample Images/ # Images and graphs used in the report.

└── README.md # General project information.

\`\`\`

\## Dependencies

\- Python 3.8+

\- PyTorch

\- NumPy

\- Matplotlib

\- scikit-learn

\## Setup and Execution

1\. Clone this repository.

2\. Ensure you have the required dependencies installed:

\`\`\`

pip install torch numpy matplotlib scikit-learn

\`\`\`

3\. Run the Jupyter Notebooks in order, starting with \`Data\_Creation.ipynb\` to set up the datasets.

\## Contributing

Feel free to fork this project and submit pull requests. You can also open an issue if you find any bugs or have suggestions for additional features.

\## License

This project is licensed under the MIT License - see the \[LICENSE.md\](LICENSE.md) file for details.

\`\`\`

I've made the necessary adjustments for GitHub compatibility, changing the file extension of the README from \`.txt\` to \`.md\` and adjusted the links accordingly. Let me know if you need anything else!
