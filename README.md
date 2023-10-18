# RSA Factoring Challenge Repository

This repository contains Python scripts for factoring natural numbers into a product of two smaller numbers (factors) and for factoring RSA numbers into their prime factors. The repository also includes a folder named `tests` with test files for both functions.

## `factors` Script

The `factors` script is designed to factor natural numbers into a product of two smaller numbers, which may or may not be prime. It reads numbers from an input file and factors them.

### Usage

```./factors <file>```
  
+ <file>: The name of the input file containing natural numbers, with one number per line.

Example:
```./factors tests/test00```

## rsa Script
The rsa script is specifically for the RSA Factoring Challenge. It factors RSA numbers into their prime factors, and it only works if there are exactly two prime factors for the given number.

### Usage
```./rsa <file>```
  
+ <file>: The name of the input file containing RSA numbers, with one number per line.

Example:
```./rsa tests/rsa-1```

## Tests
The tests folder includes test files for both the factors and rsa functions. You can use these test files to check the functionality of the scripts.

### Test Files  
tests/test00: Test file for the factors function.  
tests/rsa-1: Test file for the rsa function with a small RSA number.  
tests/rsa-2: Test file for the rsa function with a different RSA number.  
tests/rsa-15: Test file for the rsa function with a larger RSA number.  
tests/rsa-16: Test file for the rsa function with another RSA number.

## Dependencies
Both scripts depend on the sympy library for prime number checks and efficient factorization. Ensure you have sympy installed on your system before running the scripts.

## How to Run

###Clone this repository to your local machine:
```git clone https://github.com/nobleenia/RSA-Factoring-Challenge.git```
```cd RSA-Factoring-Challenge```

### Make the Python scripts executable:
```chmod +x factors```
```chmod +x rsa```

Feel free to modify and extend this repository for your needs, and good luck with the RSA Factoring Challenge!