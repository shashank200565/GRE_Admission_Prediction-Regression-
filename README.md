# GRE_Admission_Prediction-Regression-
This project implements a Deep Learning-based regression model to predict a student’s likelihood of admission to graduate programs based on their GRE Score, CGPA, TOEFL Score, University Rating, Statement of Purpose (SOP) strength, Letter of Recommendation (LOR) strength, and Research Experience.

The model helps students:

- Estimate their admission chances before applying to universities.
- Identify key areas for improvement (e.g., GRE score, research experience.
- Optimize their applications by understanding how different factors influence admission decisions.    

Key Features & Data Attributes
Input Features:    

1.)GRE Score (260–340)

2.)TOEFL Score (0–120)

3.)CGPA (0–10 scale)

4.)University Rating (1–5, based on prestige)

5.)Statement of Purpose (SOP) Strength (1–5)

6.)Letter of Recommendation (LOR) Strength (1–5)

7.)Research Experience (0 or 1)

Output Prediction:

8.)Admission Probability (0 to 1, where 1 = high chance of admission)

The neural network is structured as follows:

-Input Layer: Takes numerical features (GRE Score, CGPA, etc.).

Hidden Layer:

-1 Dense Layer with ReLU activation for non-linearity.

Output Layer:

-1 Neuron with Linear activation (since it’s a regression task).

Training Details

-Loss Function: Mean Squared Error (MSE)

– Penalizes large prediction errors.

-Optimizer: Adam (adaptive learning rate for efficient training).

-Validation Split: 20% of data used for validation.

-Early Stopping: Implemented to prevent overfitting.

Performance & Evaluation

-R² Score: Indicates how well the model explains variance in data (closer to 1 is better).
