# Handwritten math equation solver

To solve this complex problem, I have divided it into following steps:
1. Unzip .rar file to extract images for each classes
2. To keep the solution simple, I have taken only these classes images: 0-9, +, -, times, div, =
3. Limit the number of images upto 4K to train the classifier
4. Convert each image into 784 vector form
5. Create a Neural network model to train and classify each image vector to its class
6. Save the model as a file
7. Get the image from the user to test
8. Fetch each symbol from the given image and convert to 784 vector form
9. Predict class for each symbol vector using trained model
10. Evaluate the expression and return the result of the expression.

## Tech stack

1. `Python`, `Numpy`, `Pandas`, `Matplotlib`
2. `OpenCV` to extract symbol from the image
3. `Pytorch` to train and classify the image to math symbol

## Future improvements

1. Train for more classes for math symbols
2. Improve the model's accuracy (Current: 88%)
3. Write a web app to take input image from user and then evaluate the expression to display result.

## References:

[Handwritten equation solver](https://github.com/vipul79321/Handwritten-Equation-Solver)
[Pytorch tutorials](https://pytorch.org/tutorials/)
[To draw expressions and then snapshot the expression](https://www.mathsisfun.com/geometry/drawing.html)