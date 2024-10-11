
# MATLAB Utility Functions Overview

This is not a project but a collection of MATLAB functions that are generally useful and applicable in various scenarios. These functions simplify common tasks, especially in cases where automation or specific functionality is required for Simulink models.

## MATLAB Functions

- **ggcb**: This function retrieves the complete path of a block in Simulink, even when working with reference models, which is an enhancement over the standard `gcb` function. It is particularly useful when navigating complex model hierarchies. The MATLAB Central exchange link for `ggcb` is: [ggcb on MATLAB Central](https://in.mathworks.com/matlabcentral/fileexchange/74722-ggcb).

- **Automated CSV Test Case Execution and Result Extraction:**: This function streamlines the process of executing test cases from a .csv file on a Simulink model and extracting the results back into a .csv file. It is particularly beneficial for Software-in-the-Loop (SIL) testing, where validating that the generated code accurately reflects the model's logic is crucial. The function automates the capture of both input and output variables across time steps, allowing for seamless analysis of model behavior under different conditions. This approach ensures efficient validation and simplifies the comparison between expected and actual outcomes.
