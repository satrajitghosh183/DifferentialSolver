# DifferentialSolver
A differential equation solver 
# Differential Equation Solver Project

## Overview

Welcome to the README for the **Differential Equation Solver** project. This project aims to provide a comprehensive solution for solving differential equations using artificial intelligence and computational techniques.

## Motivation

The motivation behind this project originated from the challenges faced by students and researchers in solving differential equations, particularly in scientific and engineering domains. Traditional methods and available tools often fell short, prompting the development of an advanced solver.

## Project Components

### 1. Equation Recognition

- Utilizes a Convolutional Neural Network (CNN) to recognize and extract mathematical equations from images.
- Trained on a diverse dataset of handwritten and printed equations.
- Accurately identifies various mathematical symbols and expressions.

### 2. Equation Preprocessing

- Cleans and structures recognized equations for further analysis.
- Binarizes images, removes noise, and segments individual characters for improved accuracy.
- Enhances the equation for optimal processing by subsequent modules.

### 3. Equation Solving

- Employs the SciML Python package, integrating with the DifferentialEquations.jl library in Julia.
- Offers a comprehensive suite of numerical methods for solving ordinary, partial, and stochastic differential equations.

## Dataset Creation

A unique challenge in this project was the lack of a comprehensive dataset. The team is actively working on building a dataset sourced from various websites and books containing a diverse collection of differential equations.

## Frontend

- Developed using React JS.
- Provides users the flexibility to upload images or use a sketchpad to input equations.
- Transmits encoded images to the REST-API through POST requests for further processing.

## Backend - CNN Model

- Trained on a dataset of handwritten mathematical equations.
- Employs layers like Convolution 2D and MaxPool2D for feature extraction.
- Utilizes the Sympy library for symbolic computation.

## Image Processing

- Binarization: Converts images to black and white for easier feature extraction.
- Line Segmentation: Identifies different parts of the differential equation.
- Character Segmentation: Isolates individual characters in the equation.
- Generates a string representation of the differential equation.

## Equation Prediction and Solving

- Initial character replacement using Sympy for simple math strings.
- Integration of SciML for solving complex mathematical equations.
- Plans for a Python-based calculator application for simple math string solutions.

## Future Integration

- Plan to integrate SciML Python package, leveraging Julia for solving a wide range of differential equations.
- Evaluation of alternative libraries like Pytorchdiffeq for versatility.

## Project Demo

- Displays examples and a small demo showcasing an initial stage of the project.
- Acknowledges a current CNN model accuracy of 55%, with ongoing efforts to improve.

## Potential Applications

- **Education:** A valuable tool for students to visualize and understand solutions.
- **Scientific Research:** Enables efficient analysis and solution of complex mathematical models.
- **Engineering Applications:** Useful for designing and optimizing systems governed by differential equations.

## Conclusion

In its current stage, the Differential Equation Solver project is undergoing refinement and improvement. Despite challenges, it promises to be a powerful and versatile tool, addressing the complexities of solving differential equations.

## Acknowledgments

Thank you for your attention and interest in our project. Feel free to reach out for collaboration or further information.
