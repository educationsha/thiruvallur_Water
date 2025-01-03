# Groundwater in Coastal Blocks of Tiruvallur District

## Aim
This study analyzes the behavior of cations and anions in water samples obtained from the coastline regions of Tiruvallur area, Tamil Nadu, India. Thirteen physiochemical characteristics are examined in identically gathered freshwater specimens. 

Key findings include:
- Fifty percent of freshwater tests exceeded the guidelines for water quality for drinking and agriculture.
- Statistical descriptive analysis is employed to understand hydrological features better.
- Hydrochemical patterns are assessed using graphical plots such as Piper, Wilcox, and Gibbs:
  - **Piper Plot**: Indicates that high sodium concentrations stimulate cation exchange between Ca<sup>2+</sup> and Mg<sup>2+</sup> from the soil.
  - **Gibbs Plot**: Indicates anthropogenic activities dominate evaporation.
  - **Wilcox Plot**: Shows groundwater is suitable for agriculture.
- The cation concentration is notably higher in the eastern section of the chosen area.

The study highlights the need for appropriate treatment of groundwater for drinking and agricultural applications, addressing saline water invasion, rock-water interaction, and irrigation flows.

---

## Key Features
- **Purpose**: Assessing water potability and usability.
- **Dataset Size**: 400,000 rows x 10 columns.
- **Parameters Studied**: pH, Total Dissolved Solids (TDS), Electrical Conductivity (EC), Calcium (Ca), Magnesium (Mg), Sodium (Na), Potassium (K), Fluoride (F).

---

## Dataset
### Pre-Monsoon Dataset
(https://github.com/educationsha/thiruvallur_Water/blob/main/PreMonsoon_thiruvallur)

### Post-Monsoon Dataset
(https://github.com/educationsha/thiruvallur_Water/blob/main/postMonsoon_thiruvallur)

---

## AI Model Implementation
The AI model employs a feedforward deep neural network developed using the Keras API in the TensorFlow framework. 

### Architecture
- **Input Layer**: Accepts standardized feature sets.
- **Hidden Layers**:
  - First layer: 64 neurons with ReLU activation.
  - Second layer: 32 neurons with ReLU activation.
- **Output Layer**: 4 neurons with Softmax activation for water quality grade classification.

### Training Details
- **Loss Function**: Sparse categorical crossentropy.
- **Optimizer**: Adam.
- **Batch Size**: 32.
- **Epochs**: Maximum 50.
- **Validation Split**: 20%.
- **Early Stopping**: Patience of 5 epochs.

### Related Links
![Model Architecture](https://github.com/educationsha/thiruvallur_Water/blob/main/Archi.png)
![Preprocessing Workflow](https://github.com/educationsha/thiruvallur_Water/blob/main/preprocessing_Flow.png)

---

## Visualization
![AI Model Accuracy and Loss](https://github.com/educationsha/thiruvallur_Water/blob/main/Acc_Loss.png)
![Confusion Matrix](https://github.com/educationsha/thiruvallur_Water/blob/main/confus.png)
![Pre-Simulation Details](https://github.com/educationsha/thiruvallur_Water/blob/main/pre_thiru.png)
![Heat Map](https://github.com/educationsha/thiruvallur_Water/blob/main/corr_heat.png)
![Parameter Boxplots](https://github.com/educationsha/thiruvallur_Water/blob/main/box_parameters.png)
![Post-Simulation Details](https://github.com/educationsha/thiruvallur_Water/blob/main/post_thiru.png)

---

## Results
- Summarize the key findings or metrics, such as throughput, latency, or accuracy.

---

## Conclusion
Summarize the project’s outcomes and its implications.

---

## Future Directions
- Potential improvements or future research areas.

---

## How to Use
1. Clone the repository.
2. Access the datasets for preprocessing and model training.
3. Follow the provided architecture and preprocessing steps to replicate or enhance the study.

---

## Links
- [GitHub Repository](https://github.com/educationsha/thiruvallur_Water)
