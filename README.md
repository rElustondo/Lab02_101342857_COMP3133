# Node.js Calculator Test Suite

This project includes a set of unit tests for basic arithmetic operations (addition, subtraction, multiplication, and division) using Node.js' built-in `assert` module. The tests are designed to validate the correctness of a hypothetical calculator's operations by checking expected outcomes against actual results.

## 📂 Overview

The tests are implemented in the following file:

### `calculator.test.js`

The file uses the `Mocha` framework to define test cases within four primary mathematical operations: **Add**, **Subtract**, **Multiply**, and **Divide**.

## 🧪 Test Cases

### 1. **Add**
- **Test 1**: `add(5, 2)` expected result **7** - ✅ **PASS**
- **Test 2**: `add(5, 2)` expected result **8** - ❌ **FAIL**

### 2. **Subtract**
- **Test 1**: `sub(5, 2)` expected result **3** - ✅ **PASS**
- **Test 2**: `sub(5, 2)` expected result **5** - ❌ **FAIL**

### 3. **Multiply**
- **Test 1**: `mul(5, 2)` expected result **10** - ✅ **PASS**
- **Test 2**: `mul(5, 2)` expected result **12** - ❌ **FAIL**

### 4. **Divide**
- **Test 1**: `div(10, 2)` expected result **5** - ✅ **PASS**
- **Test 2**: `div(10, 2)` expected result **2** - ❌ **FAIL**

## 🚀 How to Run the Tests

1. **Install Mocha (if not already installed)**:
   ```bash
   npm install -g mocha

Run the Tests
mocha calculator.test.js

📄 Example Output
  Calculator
    Add
      ✓ add(5, 2) expected result 7 PASS
      1) add(5, 2) expected result 8 FAIL
    Subtract
      ✓ sub(5, 2) expected result 3 PASS
      2) sub(5, 2) expected result 5 FAIL
    Multiply
      ✓ mul(5, 2) expected result 10 PASS
      3) mul(5, 2) expected result 12 FAIL
    Divide
      ✓ div(10, 2) expected result 5 PASS
      4) div(10, 2) expected result 2 FAIL

  4 passing
  4 failing
🛠️ Technologies Used
Node.js for server-side scripting.
Mocha for running the test suite.
assert module for validating test conditions.
⚠️ Notes
Ensure you have Mocha installed globally or locally in your project to run the tests.
Tests are expected to pass for valid calculations and fail when the expected result is incorrect.
