# algorithms
# This project helps to understand and demonstrate algorithms.
# The pseudocode for execution is as follows

    1. Check each character in the sentence that is not point (Used point to exit the loop)
    2. For each of those character also count an index to identify the character
    3. Select each character to determine if it is a space " "
        Generally, for every space there must be space + 1 words (For 2 spaces there is 3 words)
        Therefore words = space + 1
    4. Check if character is a vowel by comparing with a or e or i or o or u
    5. Sum the point back to the sentence

    SUM OF DISTINCT FILE in sum_distinct.algo
    Step 1: Function to create an array from user input return the array.
    Step 2: Function to check distinct of each of the array1 and array2.
    Step 3: Sum the array distinct elements of array1 and array2.


    VECTOR DOT PRODUCT in vector_dot_product.algo
    Dot product is sum of all products of two corresponding array elements
    1. Declare variables
    2. Check if the two vectors are equal.
    3. Multiply elements at the same position in both vector arrays
    4. Sum the products of each position


    ORTHOGONAL VECTORS in vector_dot_product.algo
    Orthogonal vectors are perpendicular vectors ie. dot product = 0
    1. Loop through each elements of each array.
    2. Find the dot product
    3. If dot product = 0 then the vectors (array) are orthogonal