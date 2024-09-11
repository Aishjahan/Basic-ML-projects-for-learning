
# Student Placement Prediction

This project uses a logistic regression model to predict whether a student will get placed based on their IQ and CGPA. The goal is to help students and educational institutions better understand the factors influencing placements.

## Table of Contents
- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview
In this project, we predict student placement outcomes based on two key factors:
- **IQ (Intelligence Quotient)**
- **CGPA (Cumulative Grade Point Average)**

Logistic regression is used as the classification algorithm due to its effectiveness in binary classification tasks like this.

## Technologies Used
- **Python**
- **Libraries**:
  - Scikit-learn (for logistic regression and evaluation metrics)
  - NumPy (for numerical operations)
  - Pandas (for data handling and analysis)

## Dataset
The dataset contains the following columns:
- `IQ`: Student's IQ level
- `CGPA`: Student's CGPA
- `Placement`: Binary outcome (1 if placed, 0 if not placed)


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/placement-prediction.git
   cd placement-prediction
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

### Required Libraries
- Scikit-learn
- NumPy
- Pandas

You can install these using the `requirements.txt` file provided.

The script will:
- Load and preprocess the dataset
- Split the dataset into training and testing sets
- Train the logistic regression model
- Predict the placement status for the test set
- Display the accuracy and evaluation metrics of the model

## Results
The logistic regression model will output whether a student is predicted to be placed or not based on their IQ and CGPA. You can review the performance using metrics like accuracy, precision, and recall, which will be printed in the console.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss your ideas.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

