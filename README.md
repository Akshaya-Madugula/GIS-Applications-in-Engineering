## Texas Bridge Condition Analysis

This project analyzes bridge data from Texas for the years 2022 and 2023 using Geographic Information Systems (GIS) techniques and Python programming to predict bridge conditions.

### Data Preprocessing:
- Loaded 2022 and 2023 bridge datasets.
- Converted Latitude/Longitude from DMS to Decimal Degrees.
- Identified bridges surveyed in 2023 but not in 2022.

### Feature Engineering:
- Calculated bridge age.
- Converted bridge condition ratings (deck, superstructure, channel) into binary values (Satisfactory = 1, Unsatisfactory = 0).

### Logistic Regression:
- Selected key features: Average Daily Traffic (ADT), Deck Area, Max Span Length, and Age.
- Trained a Logistic Regression model to predict bridge deck conditions (Good or Critical).
- Applied the model to predict conditions for newly surveyed bridges in 2023.

### Visualization:
- Visualized the results on a map of Texas with distinct color codes for critical (red) and good (green) bridge conditions.

### Files:
- **Mini Project_AkshayaM.ipynb**: The Jupyter Notebook containing all data processing, model training, prediction, and visualization steps.
- **Work_Flow.png**: Visual representation of the workflow.
