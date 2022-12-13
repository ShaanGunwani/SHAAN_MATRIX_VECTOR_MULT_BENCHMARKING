# SHAAN_MATRIX_VECTOR_MULT_BENCHMARKING



I will identify and examine the space complexity as well as the time complexity of the vector multiplication and matrix multiplication.

To run it, we can enter the following code in the terminal :- 

make; ./main_test.out


The output will be as follows:- 

Test #1:
Actual V[0] = 32; Expected V[0] = 32
Actual V[1] = 31; Expected V[1] = 31
Actual V[2] = 39; Expected V[2] = 39

Test #2:
Actual V[0] = 109; Expected V[0] = 109
Actual V[1] = 49; Expected V[1] = 49
Actual V[2] = 69; Expected V[2] = 69

Test #3:
Actual V[0] = 56; Expected V[0] = 56
Actual V[1] = 89; Expected V[1] = 89
Actual V[2] = 101; Expected V[2] = 101


The function I made is called multiply_vector_matrix. In this function, it takes four inputs. They are :- mat, vec, N, and vector_expected. I used three test cases so that's why I used N = 3. The function runs as anticipated if the actual and the anticipated output are the same. 


THE TIME COMPLEXITY


To run the time complexity, we can enter the following code in the terminal :- 

make time 

The output will be as the following diagram:- 

![image](https://user-images.githubusercontent.com/114371881/207378149-9f39b576-487a-45e3-bc99-04ccda47de56.png)


Below in the graph we can see that if the matrix size increase, it will take more time. 

<img width="656" alt="207312916-95a388d0-3baa-4c77-b31f-6cb273564105" src="https://user-images.githubusercontent.com/114371881/207378659-6d8d0aa4-6144-41bf-bb64-677b95864eae.png">


THE SPACE COMPLEXITY

To run the space complexity, we can type the following code in the terminal :- 

make space


The output will be as follows:- 

![image](https://user-images.githubusercontent.com/114371881/207379835-094061f1-b423-43a9-9a10-cf4ab96cbd0a.png)




<img width="681" alt="207312941-b6b5c53d-25a8-4cf9-bc05-32f094e628a0" src="https://user-images.githubusercontent.com/114371881/207380188-7076a3e2-f305-406e-8e97-98217a5e2c5f.png">

From the graph given above, we can see and conclude that it will need more memory if the matrix size will increase. 


