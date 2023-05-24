# Handwritten_equation_solver
Given an image with handwritten mathematical equation, the model solves the equation and gives final value of the expression.

Input -
<br>
<img width="500" height="150" alt="image" src="https://github.com/shreya-malraju/Handwritten_equation_solver/assets/132793649/8738f3c2-0b20-43e3-9175-31ecc044a0d6">

Output -
<br>
<img width="300" height="100" alt="image" src="https://github.com/shreya-malraju/Handwritten_equation_solver/assets/132793649/b1e07c90-4e2e-4331-9909-48065d4879eb">


Extended MNIST dataset is used which has 14 classes( 10 digits, +, - ,* ,/ ).

• The digits(0-9) are classified by CNN. The input image is segmented and according to the borders and are classified into different classes.

• Accuracy obtained = 98.6%
