# Test Cases for Simple Calculator Application

## TC_ADD_01: Addition of two positive integers
**Precondition:** Calculator application is open  
**Steps:**
1. Enter 5  
2. Press +  
3. Enter 3  
4. Press =  
**Expected Result:** Result displayed is 8  

## TC_ADD_02: Addition with a negative number
**Precondition:** Calculator is open  
**Steps:**
1. Enter -5  
2. Press +  
3. Enter 10  
4. Press =  
**Expected Result:** Result displayed is 5  

## TC_ADD_03: Addition of decimal numbers
**Precondition:** Calculator is open  
**Steps:**
1. Enter 2.5  
2. Press +  
3. Enter 1.2  
4. Press =  
**Expected Result:** Result displayed is 3.7  

## TC_SUB_01: Subtraction of two numbers
**Precondition:** Calculator is open  
**Steps:**
1. Enter 10  
2. Press -  
3. Enter 4  
4. Press =  
**Expected Result:** Result displayed is 6  


## TC_SUB_02: Subtracting a negative number
**Precondition:** Calculator is open  
**Steps:**
1. Enter 5  
2. Press -  
3. Enter -3  
4. Press =  
**Expected Result:** Result displayed is 8  


## TC_MUL_01: Multiplication of two numbers
**Precondition:** Calculator is open  
**Steps:**
1. Enter 6  
2. Press *  
3. Enter 4  
4. Press =  
**Expected Result:** Result displayed is 24  

## TC_MUL_02: Multiplication with zero
**Precondition:** Calculator is open  
**Steps:**
1. Enter 9  
2. Press *  
3. Enter 0  
4. Press =  
**Expected Result:** Result displayed is 0  


## TC_MUL_03: Multiplication of decimals
**Precondition:** Calculator is open  
**Steps:**
1. Enter 2.5  
2. Press *  
3. Enter 2  
4. Press =  
**Expected Result:** Result displayed is 5  

## TC_DIV_01: Division of two numbers
**Precondition:** Calculator is open  
**Steps:**
1. Enter 20  
2. Press /  
3. Enter 4  
4. Press =  
**Expected Result:** Result displayed is 5  


## TC_DIV_02: Division resulting in decimal
**Precondition:** Calculator is open  
**Steps:**
1. Enter 5  
2. Press /  
3. Enter 2  
4. Press =  
**Expected Result:** Result displayed is 2.5  


## TC_DIV_03: Division by zero
**Precondition:** Calculator is open  
**Steps:**
1. Enter 10  
2. Press /  
3. Enter 0  
4. Press =  
**Expected Result:** Error message "Cannot divide by zero" is displayed  


## TC_BOD_01: Operator precedence (BODMAS)
**Precondition:** Calculator is open  
**Steps:**
1. Enter 2 + 3 * 4  
2. Press =  
**Expected Result:** Result displayed is 14  

## TC_BOD_02: Bracket precedence
**Precondition:** Calculator is open  
**Steps:**
1. Enter (2 + 3) * 4  
2. Press =  
**Expected Result:** Result displayed is 20  


## TC_INV_01: Alphabet input
**Precondition:** Calculator is open  
**Steps:**
1. Enter a  
2. Press =  
**Expected Result:** Error message "Invalid input" is displayed  


## TC_INV_02: Special character input
**Precondition:** Calculator is open  
**Steps:**
1. Enter @  
2. Press =  
**Expected Result:** Error message "Invalid input" is displayed  


## TC_INV_03: Empty input
**Precondition:** Calculator is open  
**Steps:**
1. Press = without entering anything  
**Expected Result:** Error message "No input provided" is displayed  


## TC_NEG_01: Operation with two negative numbers
**Precondition:** Calculator is open  
**Steps:**
1. Enter -4  
2. Press +  
3. Enter -6  
4. Press =  
**Expected Result:** Result displayed is -10  


## TC_DEC_01: Complex decimal calculation
**Precondition:** Calculator is open  
**Steps:**
1. Enter 1.5 + 2.5 * 2  
2. Press =  
**Expected Result:** Result displayed is 6.5  
