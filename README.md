# Advanced-programming-report

![download](https://github.com/Harsha-Vardhan-Tangudu/Advanced-programming-report/assets/121998082/5b4431eb-d606-40c4-b7d5-7504d6fcba8f)

Certainly! Here's an example README page for the project documentation on GitHub:

# Evaluation Application for Coding Contest

This is the documentation for the Evaluation Application, which is used for scoring and verifying solutions in coding contests held at universities.

## Introduction

The Evaluation Application is designed to evaluate the performance of participants in coding contests. It verifies the candidates' solutions against a reference solution and assigns scores based on various criteria. This document compares the usage of C++ 17 and Python 3 in the Evaluation Application, highlighting their similarities, differences, and code efficacy.

## Comparison of C++ 17 and Python 3

### Similarities

- Both C++ 17 and Python 3 are popular programming languages used in coding contests.
- They offer a wide range of features and libraries for implementing complex algorithms and data structures.
- C++ 17 and Python 3 support input/output operations, conditional statements, loops, and other fundamental programming constructs.

### Differences

1. **Syntax**: C++ 17 has a syntax that is more complex and requires explicit memory management, while Python 3 has a simpler syntax and utilizes automatic memory management.
2. **Performance**: C++ 17 is generally faster and has lower memory overhead compared to Python 3. This is particularly important in coding contests where execution time and memory usage can impact the scores.
3. **Multithreading**: C++ 17 provides better support for multithreading, allowing for concurrent execution of multiple threads. Python 3, on the other hand, has the Global Interpreter Lock (GIL), which restricts the execution of multiple threads and can impact performance in certain scenarios.

### Code Efficacy

The Evaluation Application uses C++ 17 for its evaluation process due to the following reasons:

1. **Multithreading**: C++ 17's superior multithreading support allows for concurrent evaluation of multiple candidates, resulting in faster execution and improved efficiency.
2. **Memory Management**: C++ 17 provides more control over memory management, ensuring efficient memory utilization during code evaluation.
3. **Performance**: The faster execution speed and lower memory overhead of C++ 17 make it well-suited for evaluating large volumes of code submissions within the time constraints of coding contests.

## Evaluation Process

The Evaluation Application follows a four-step process for scoring the candidates' solutions:

1. **Matching Sample Inputs and Outputs**: The candidate's solution is compared against the reference solution using sample inputs and outputs. A percentage match is calculated, and if it is 100%, the candidate is awarded 40% of the marks.
2. **Output Validity with Hidden Inputs**: Hidden inputs are used to validate the candidate's solution further. If the candidate's output matches the reference solution for hidden inputs, an additional 20% of the marks are awarded.
3. **Execution Memory**: The execution memory of the candidate's solution is compared to the reference solution. If the candidate's memory usage is less than or equal to the reference solution, another 20% of the marks are awarded.
4. **Execution Time**: The execution time of the candidate's solution is compared to the reference solution. If the candidate's execution time is less than or equal to the reference solution, the remaining 20% of the marks are awarded.

## Usage

To use the Evaluation Application, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies and ensure the appropriate compilers/interpreters are installed.
3. Run the application and provide the necessary inputs for evaluating the candidates' solutions.
4. The application will generate score reports and provide feedback messages based on the evaluation criteria.

For detailed instructions on running the Evaluation Application, refer to the [User Manual](./user-manual.md).



## License

This project is licensed under the [MIT License](./LICENSE).

---

This README provides an overview of the Evaluation Application, highlights the comparison between C++ 17 and Python 3, and guides users on how to use the application. It also includes information about the contributors and the project's license.

Please note that this README is a fictional example and you may need to adapt it to your specific project and requirements.
