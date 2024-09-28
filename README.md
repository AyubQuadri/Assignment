# Assignment Quantization Task on MNIST Dataset

Documentation is carried out on https://monogr.ph/66f15ebbaf3b9995fec7b814

# Task: A4W2-bit Quantization challenge for a simple Neural Network on MNSIT data. 

# Things to be taken into consideration.

* use seed method to reproduce the results
-Item Set a side 128 images for quantization work
-Item Weights: AdaRound Algorithms weights uniformly to 2 bits
-Item Activation: 4 bit using Method of your choice (Min, Max or MSE) ensure uniform affine manner 
-Item Implantation: Use Fake Quantization {Quantization, Dequantization using FP number}
-Item For AdaRound regularization Beta param is to linearly decay it from 20 to 2. 
-Item AdaRound for 5000 iterations shows good results 

#Deliverables 

-Item Code 
-Item Report {Arch, Quant method and Algo applied, Results, challenges faced and how addressed}

# Evaluation

-Item Correctness: AdaRound algorithm applied for weight Quantization and chosen method for activation Quantization
-Item Performance: retain 99% accuracy 
-Item Code quality: clean code, best practices and well documented
-Item Report Quality: clear, concise, overview of implementation and results

# Additional Guidelines

-Item Ensure reproducability
-Item any assumptions or consideration during implementation 
-Item Task to be in colab notebook
-Item Only Torch, Numpy and Scipy are allowed for the implementation 
-Item Potential improvements or extensions to the current quantization approach in the report. 
