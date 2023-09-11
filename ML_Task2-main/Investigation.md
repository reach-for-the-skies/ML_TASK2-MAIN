# Testing Ehe Effect of Different Activation Functions on Machine Learning Models
![sigmoid](assets/sigmoid.png)

## Introduction
This experiment will test the effect of different activation functions on a machine learnig model. The functions will be tested on a machine learning model that is learning how to drive around a track with 5 inputs. The functions that will be tested are the sigmoid, Rectified Linear Unit (ReLU), Hyperbolic Tangent (Tanh), clamped. The average fitness of generations 3, 5, 10, 20 30, 40, 50 will be recorded. This will asses the best function for this application.

## Method
1. Download this repository and open the `newcar.py` file. The default function is the sigmoid function.
2. Install the required libraries including `neat-python` and `pygame`
3. Run the python file and wait until the generation counter reaches 52 then quit the application
4. In the terminal locate the 3rd, 5th, 10th, 20th, 30th, 40th and 50th generations and record the average fitness for each of these generations
5. Repeat steps 3 and 4 but open the `config.txt` file and change the values of `activation_default` and `activation_options` to be `relu` on the first repeat `tanh` on the second and `clamped` on the third
6. Repeat steps 3, 4 and 5 three times to get an accurate result.

## Results

