# Comparative Analysis of ConvLSTM And LRCN For Human Activity Recognition

## Overview
This dissertation investigates the efficacy of Convolutional Long Short-Term Memory (ConvLSTM) and Long Short-Term Memory with Recurrent Convolutional Neural Network (LRCN) architectures for human activity recognition in video data. Utilizing the UCF50 dataset, encompassing diverse human actions across 50 categories, as a benchmark for evaluation, the study meticulously evaluates the performance of both models primarily based on accuracy.

## Results
- **LRCN Model Accuracy**: 93.44%
- **ConvLSTM Model Accuracy**: 84.43%

Results indicate that the LRCN model achieves superior accuracy compared to the ConvLSTM model, showcasing its effectiveness in classifying human activities from video sequences. However, challenges such as computational complexity and model architecture nuances are evident, particularly in the case of the ConvLSTM model. Additionally, the LRCN model's testing on real-world videos from YouTube provides further insights into its practical applicability.

## Contributions
This research contributes insights into the application of deep learning architectures for human activity recognition, emphasizing the significance of model selection and optimization in real-world scenarios. The findings have broad implications for domains such as surveillance, healthcare, and human-computer interaction.

## Dataset
- **Dataset Used**: UCF50
- **Description**: The UCF50 dataset contains video clips of diverse human actions across 50 categories, providing a comprehensive benchmark for evaluating human activity recognition models.

## Model Architectures
### ConvLSTM
ConvLSTM combines convolutional layers with LSTM units to capture both spatial and temporal dependencies in video data.

### LRCN
LRCN integrates convolutional layers for spatial feature extraction with recurrent layers (LSTM/GRU) for temporal sequence modeling.

## Evaluation Metrics
- **Accuracy**: The primary metric for model evaluation in this study.

## Challenges
- Computational complexity, particularly in ConvLSTM models.
- Model architecture nuances and their impact on performance.

## Future Work
- Further optimization of ConvLSTM models to address computational challenges.
- Exploration of additional datasets to validate the generalizability of findings.
- Application of these models in real-world scenarios, such as surveillance and healthcare.

## How to Run the Project
1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    ```
2. Navigate to the project directory:
    ```bash
    cd your-repo-name
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Download and preprocess the UCF50 dataset.
5. Train the models:
    ```bash
    python train_conv_lstm.py
    python train_lrcn.py
    ```
6. Evaluate the models:
    ```bash
    python evaluate.py
    ```

## Repository Structure
- `data/`: Contains the dataset.
- `models/`: Contains the model architectures and training scripts.
- `notebooks/`: Jupyter notebooks for data exploration and analysis.
- `results/`: Contains the results of the experiments.
- `README.md`: Project overview and instructions.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgements
Special thanks to the creators of the UCF50 dataset and the contributors to the deep learning libraries used in this project.

## Contact
For any questions or inquiries, please contact [Your Name] at [your-email@example.com].

