# RPA-Salary-Calculation

![maxresdefault](https://github.com/AWESOME04/RPA-Salary-Calculation/assets/102630199/e87de533-56ec-4917-a153-907e57f27fb7)

This repository contains a solution for automating the calculation of employee salaries using Robotic Process Automation (RPA).

The solution utilizes UiPath, an RPA tool, to read employee data from the Main Sheet, calculate salaries based on hours worked, and update the Update Sheet with the calculated salaries. The code and relevant files are provided in this repository, serving as a reference for automating salary calculations in an Excel-based environment.

The solution reads employee data from the Main Sheet, calculates salaries based on hours worked, and updates the Update Sheet with the calculated salaries. The provided code and files serve as a reference for automating salary calculations in an Excel-based environment.

## Table of Contents

    Prerequisites
    Installation
    Usage
    File Structure
    License

## Prerequisites

Before using this solution, ensure that you have the following prerequisites:

    UiPath Studio installed on your machine.
    Microsoft Excel installed with the required Excel files: MainSheet.xlsx and UpdateSheet.xlsx.

## Installation

    Clone or download this repository to your local machine.

    Open UiPath Studio and navigate to the project folder.

    Open the UiPath project by selecting the Main.xaml file.

## Usage

    Launch UiPath Studio and open the project.

    Update the file paths in the workflow to match the location of your Excel files:
        In the "Excel Application Scope" activities, update the file paths for MainSheet.xlsx and UpdateSheet.xlsx.

    Customize the workflow as per your specific requirements:
        Adjust the range of cells in the "Read Range" activity to match the employee data in the Main Sheet.
        Modify the calculations or salary rules in the "Assign" activity to suit your needs.
        Update the cell reference in the "Write Cell" activity to match the appropriate column and row in the Update Sheet.

    Save and run the UiPath project.

    Check the Update Sheet to verify that the salaries have been calculated and updated correctly.

## File Structure

The repository contains the following files:

    Main.xaml: The main UiPath workflow file that automates the salary calculation and update process.

    MainSheet.xlsx: An Excel file that contains the list of employees and their hours worked.

    UpdateSheet.xlsx: An Excel file where the calculated salaries will be updated.
