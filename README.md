# Excel for Analyzing Inefficiency and Preference Manipulation in Two-Sided Matching

This tool is an educational Excel Macro (VBA) program designed to execute and analyze Many-to-One Matching algorithms. It allows users to study matching outcomes, evaluate their inefficiency, and explore strategic aspects such as preference manipulation.

## Overview

The program targets assignment problems where workers are assigned to groups, each with its own capacity. It serves as a revised version of "Excel for Two-Sided Matching Ver. 3.2," adding specialized functions for searching better choices under various algorithms.

## Features

The program consists of seven Excel sheets and a VBA core:
* **Matching Algorithms**:
    * **DA (Deferred Acceptance)**: Supports both worker-proposing and division-proposing algorithms.
    * **Boston Algorithm**: Executes the worker-proposing Boston algorithm.
* **Welfare Evaluation**:
    * Analyzes whether a matching is **Pareto inefficient** by examining all possible exchanges of divisions between pairs of workers.
* **Preference Manipulation Analysis**:
    * **Search Better Choices (Boston)**: Finds alternative preference representations that result in a more favorable outcome for a worker under the Boston algorithm.
    * **Search Identical Choices (DA)**: Verifies if preference manipulation can generate identical or better outcomes under the DA mechanism.
* **Random Generation**:
    * Includes a "randomize" function to generate worker preferences and division priority orders for educational exercises.

## Usage

1.  Set the numbers of workers and divisions in the VBA window.
2.  Input numerical data on workers' preferences, divisions' evaluation, and quotas in the `man` sheet, the `group` sheet, and the `conf` sheet, respectively.
3.  Open the `result` sheet.
4.  Choose one button out of three in the result sheet to run the desired algorithm.
5.  View computation results in the `result` sheet.

## Manual

For detailed usage instructions, please refer to the following manual.

*   [manualEnSh.pdf](https://github.com/shuya-abe/excel-for-two-sided-matching/blob/main/manualEnSh.pdf)

## Author and Developers

*   [Shuya Abe](https://abe-network.com/)
*   [Naoki Watanabe](https://naoki-watanabe50.github.io/index.html)