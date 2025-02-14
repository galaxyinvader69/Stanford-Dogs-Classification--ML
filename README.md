# Final Project - Machine Learning Methods: Stanford Dogs Dataset

## Overview
The **Stanford Dogs Dataset** contains images of 120 breeds of dogs from around the world. This dataset has been built using images and annotations from ImageNet for the task of fine-grained image categorization. It was originally collected for fine-grain image categorization, a challenging problem as certain dog breeds have near identical features or differ in color and age.

The goal of this project is to implement, tweak, and optimize a deep learning pipeline for classifying images in the Stanford Dogs Dataset using TensorFlow.
![image](https://github.com/user-attachments/assets/e42ca08f-4096-49f2-8d00-130477779957)


## Objective
The objective of this project is to:
1. Preprocess the dataset and prepare it for training.
2. Build, compile, and train a deep neural network (DNN) model using TensorFlow.
3. Optimize the model for better accuracy and performance.
4. Ensure that the pipeline is bug-free and achieves a test accuracy above the baseline of 0.70.

## Results
- **Final Accuracy**: 0.7372
- **Final Loss**: 1.4730

The model correctly classified approximately 73.7% of the images in the test set, which is above the baseline accuracy of 0.70 set for this project.

## Files
- **final.ipynb**: Jupyter Notebook containing the complete implementation, from data preprocessing to model evaluation.
- **requirements.txt**: List of dependencies required to run the notebook, including TensorFlow.

## Instructions
1. Clone the repository to your local machine.
2. Install the necessary dependencies by running the following command:
    ```
    pip install -r requirements.txt
    ```
3. Open the `final.ipynb` notebook and run the cells to execute the pipeline.

## Future Improvements
- Hyperparameter tuning to optimize model performance.
- Experiment with different architectures, such as deeper CNNs or transfer learning with pre-trained models.
- Implement data augmentation techniques to improve model generalization.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
