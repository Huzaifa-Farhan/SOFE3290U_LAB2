# Lab 2: Maven & Web Application - SOFE 3290U

## Overview
This report covers the implementation and testing of a binary operations controller in a Spring Boot application. The application performs binary addition, multiplication, bitwise AND, and bitwise OR operations. Each of these operations is tested using unit tests to ensure correct functionality.

## Video link 
[CLICK HERE]([https://huzaifafarhan.com/](https://drive.google.com/file/d/1U9sp1rcy7KbL5PF7aHeYFoVUxUoFdbSS/view?usp=sharing)) to watch the full functionality!  

## Test Cases

### BinaryControllerTest
- **getDefault**: Verifies that the default view is displayed when no parameter is supplied.
- **getParameter**: Confirms that the passed query parameter is processed and displayed correctly.
- **postParameter**: Verifies that the binary addition operation works correctly when submitted via a POST request.

### testMultiplication
- **testMultiplication**: Confirms that the multiplication of two binary numbers works as expected.
- **testMultiplicationWithZero**: Validates the multiplication result when one operand is zero.
- **testMultiplicationWithOne**: Ensures that multiplying by one returns the other operand unchanged.
- **testMultiplicationWithDifferentLengths**: Verifies that multiplication handles binary numbers with different lengths.
- **testMultiplicationWithLargeNumbers**: Confirms multiplication works for large binary numbers.

### testBitwiseAND
- **testBitwiseAND**: Verifies that the bitwise AND operation works correctly for two binary numbers.
- **testBitwiseANDWithZeros**: Ensures that the AND operation returns zero when one operand is all zeros.
- **testBitwiseANDWithOne**: Verifies the AND operation when one operand is 1.
- **testBitwiseANDWithDifferentLengths**: Tests the AND operation with operands of different lengths.
- **testBitwiseANDWithLargeNumbers**: Confirms the AND operation works with large binary numbers.

### testBitwiseOR
- **testBitwiseOR**: Verifies the OR operation between two binary numbers.
- **testBitwiseORWithZeros**: Ensures that the OR operation works when one operand is all zeros.
- **testBitwiseORWithOne**: Verifies the OR operation when one operand is 1.
- **testBitwiseORWithDifferentLengths**: Validates that the OR operation works with operands of varying lengths.
- **testBitwiseORWithLargeNumbers**: Confirms that the OR operation works with large binary numbers.

### BinaryAPIControllerTest
- **add**: Verifies that binary addition works as expected for two operands.
- **add2**: Ensures that the addition API returns the correct JSON response.
- **addJson**: Verifies that the binary addition API returns accurate JSON data.
- **testMultiplicationAPI**: Confirms that multiplication via the API works correctly.
- **testMultiplicationWithZeroAPI**: Ensures multiplication by zero returns zero.
- **testMultiplicationWithOneAPI**: Validates that multiplying by one returns the other operand unchanged.
- **testMultiplicationWithDifferentLengthsAPI**: Verifies that multiplication handles operands with different lengths.
- **testMultiplicationWithLargeNumbersAPI**: Confirms that multiplication works for large binary numbers.
- **testBitwiseANDAPI**: Verifies that the AND operation works as expected via the API.
- **testBitwiseANDWithZerosAPI**: Confirms that the AND operation returns zero when one operand is all zeros.
- **testBitwiseANDWithOneAPI**: Verifies that the AND operation returns the correct result when one operand is 1.
- **testBitwiseANDWithDifferentLengthsAPI**: Validates that the AND operation works with operands of different lengths.
- **testBitwiseANDWithLargeNumbersAPI**: Confirms that the AND operation works with large binary numbers.
- **testBitwiseORAPI**: Verifies that the OR operation works as expected via the API.
- **testBitwiseORWithZerosAPI**: Ensures that the OR operation returns the correct result when one operand is all zeros.
- **testBitwiseORWithOneAPI**: Verifies that the OR operation works correctly when one operand is 1.
- **testBitwiseORWithDifferentLengthsAPI**: Confirms that the OR operation works for operands of different lengths.
- **testBitwiseORWithLargeNumbersAPI**: Ensures the OR operation works correctly with large binary numbers.
