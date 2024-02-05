# MLP-Handwritten-Number
Handwritten Number Recognition With Multi-Layer Perceptron ( MLP)

# Handwritten Digit Recognition using Multi-Layer Perceptron (MLP)

With advancements in hardware system design, the execution of more advanced and complex algorithms has become feasible. As a result, numerous events have occurred, one of which is the transformation in digital image processing.

Digital image processing involves the analysis and pattern recognition within digital images. The applications of image processing can be seen in face recognition systems in smartphones. These systems, by receiving an image as input, determine whether the person is authorized to access the smartphone or not. However, the functionality of these systems goes beyond simple recognition, as someone might attempt unauthorized access by taking a picture of you in front of the smartphone's camera!

Moving beyond face recognition, one of the simplest examples in image processing is handwritten digit recognition. This entails the computer's ability to recognize which digit is being inputted based on an image of a handwritten number.

## Dataset Explanation

The training dataset consists of 60,000 rows and 785 columns. Each row represents the information of an image. The first column indicates the label of the sample (the digit within the image), and the following 784 columns represent the features of an image.

An image can be considered as a matrix where each element represents a pixel. The number in each element ranges from 0 to 255, where values closer to 255 indicate higher brightness levels. A pixel with a value of 255 is completely white, while a pixel with a value of 0 is completely black. For example, in the image above, pixels with the value 4 have a higher value compared to the black background around the image.

This dataset consists of 60,000 matrices of size 28x28. For your convenience, we have flattened each of the 28x28 matrices, meaning we have arranged the rows of the matrix alongside each other, creating an array of 784 elements for each matrix.

Thus, each row of the dataframe (each image) contains 784 columns or features, along with one label.

The column naming convention in the dataframe is in the form of 𝑖*𝑗, indicating that the number you see in this column was located in the 𝑖th row and 𝑗th column of the original matrix (before flattening). Another column named 'label' is only present in the training dataframe, representing the digit within the image.

## Usage

 **Clone Repository:**
   ```
   git clone <repository_URL>
   ```
   Clone the repository to your local machine.


Make sure to have Python 3.x installed along with the required libraries: NumPy, Pandas, Matplotlib, and Scikit-learn.

## Requirements
- Python 3.x
- Libraries: NumPy, Pandas, Matplotlib, Scikit-learn

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- The dataset used in this project is sourced from [MNIST Database](http://yann.lecun.com/exdb/mnist/).
