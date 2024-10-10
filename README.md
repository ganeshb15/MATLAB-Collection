
# MATLAB Utility Functions Overview

This is not a project but a collection of MATLAB functions that are generally useful and applicable in various scenarios. These functions simplify common tasks, especially in cases where automation or specific functionality is required for Simulink models.

## MATLAB Functions

- **ggcb**: This function retrieves the complete path of a block in Simulink, even when working with reference models, which is an enhancement over the standard `gcb` function. It is particularly useful when navigating complex model hierarchies. The MATLAB Central exchange link for `ggcb` is: [ggcb on MATLAB Central](https://in.mathworks.com/matlabcentral/fileexchange/74722-ggcb).

- **CSV Testcase Passing and Result Extraction**: This function automates the process of passing test cases from a `.csv` file to a Simulink model and then extracting the results back into a `.csv` file. It is especially useful for Software-in-the-Loop (SIL) testing, where you need to ensure that the code's functionality matches the model's logic. The function captures both the input and output variables across time steps, providing an easy way to analyze the behavior and logic of the model under differe...
