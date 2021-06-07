# Evaluating_Mathematical_Equations_Using_AI

This project is used to detect and solve handwritten mathmatical equations.

## Problem statement

Handwriting Detection is a technique or ability of a Computer to receive and interpret intelligible handwritten input from source such as paper documents, touch screen, photo graphs etc. Adoption of the Handwritten Text Recognition software is a practical idea and, it is easier to store and access data that was traditionally stored. Furthermore, it provides more security to the data. Therefore, computer is needed to be able to read document or data for ease of document processing.

## Dataset

The dataset used for this project is a subset of the chrome dataset.

### Dataset's description

- Dataset consists of jpg files **(28 x 28)**.
- For simplicity, **we are using 0–9 digits, +, — and, times images** in our equation solver.
- On observing our dataset, we can see that it is biased for some of the digits/symbols, as it contains 12000 images for some symbol and 3000 images for others. **To remove this bias, we reduced the number of images in each folder to approx. 4000.**

## Model summary

![image](https://user-images.githubusercontent.com/62230055/120970828-9047be80-c789-11eb-9172-93de51f09dc5.png)

## Results

![image](https://user-images.githubusercontent.com/62230055/120970892-a5245200-c789-11eb-8ef4-7f63a1cd09b8.png)

![image](https://user-images.githubusercontent.com/62230055/120970908-a8b7d900-c789-11eb-909e-940247fb64c5.png)

After training we found our model’s accuracy to be around **98.4%**.

## References

### Dataset
https://www.kaggle.com/xainano/handwrittenmathsymbols

### Literature survey
- Guyon, I., D. Henderson, P. Allbrecht, Y. Le Curt and J. Denker (1991). Writer independent and writer adaptive neural network for on-line character recognition. Proc. 2nd lnternat. Workshop on Frontiers in Handwriting Recognition, Bonas, France, 1991, 313-326. 
- Wang, P.S.P., M.V. Nagendraprasad and A. Gupta (1991). A 'hybrid' approach to handwritten numerical recognition. Proc. 2nd Internal. Workshop on Frontiers in handwriting Recognition, Bonas, France, 199l, 101-110. 
- Kimura, F. and M. Shridhar (1991). Handwritten numerical recognition based on multiple algorithms. Pattern Recognition 24 (10), 969-983. 





























