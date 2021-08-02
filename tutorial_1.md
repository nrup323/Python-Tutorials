# Difference Between *, .mul, .matmul, .prod, .dot

This was the most confusing part for me while learning various python libraries.
When to use above operations had always been puzzling for me.
In this tutorial I have tried to exaplain 
what they do and when to use them.

### 1) * and .mul

If two tensors have same size then operation(+ , - , *, /) by default are applied element wise. The use of  * and lib.mul gives us the element wise multiplication of two tensors.
Now basically whenever we use arrays from Numpy or tensors for Tensorflow/Pytorch use of  * is same as using lib.mul
![image](https://user-images.githubusercontent.com/47531228/127900228-37661fc6-8c84-408f-a002-c3130e2da37d.png)

### 2) .dot

dot operatos take the dot product of two 1d tensors. Answer to this is a scalar number which is sum of element wise multiplication of two
vectors/1d tensors.

![image](https://user-images.githubusercontent.com/47531228/127900668-c21e70dc-774a-42a3-a2d1-c431c3206ba2.png)

### 3) .matmul

This is basically used for matrix multiplication of two matrices, output of this operation is also a matrices and size of the output matrice depends on 
the size of input matrices.
![image](https://user-images.githubusercontent.com/47531228/127901902-79f7b1c9-390c-48d0-9416-1870f1775125.png)

### 4) .prod

This is just the multiplication of the elements of the given tensor/vector. Output is a scalar value.
![image](https://user-images.githubusercontent.com/47531228/127901971-d281c97b-012c-4176-8315-96ef3e1564ab.png)





