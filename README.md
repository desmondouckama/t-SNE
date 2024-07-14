# t-SNE
unbiased dimension reduction

In this code, I create a figure of subplot to demonstrate the steps in the algorithm for t-SNE. 
Under guidance of Dr. Vargas in the Systems Medicine Infectious Disease (SMID) Lab, this figure is to be used as reference in Latex notes for "Foundations of Machine Learning" course taught at University of Idaho and Shanghai University. 

Each sublpot is defined in a function. There are global variables for the input data, and subsequent manipulations, while each function has it's own local variable to handle the iterations. 

You can change the C1, C2, C3 cluster variables to any random data points and this algorithm will reduce the dimesions according to the t-SNE alogrithm for any given data. 

This code is valuable because it does not simply reduce without explanation. Being able to articulate a communicate a process is valuable in data science. This code demonstrates this skill. 

Possible future changes to this could would include cleaning it up a bit, and using less "for loops" so that it can run faster with bigger data. 
