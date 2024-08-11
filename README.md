# Adobe_GenSolve_Hackathon
# Curvetopia: A Journey into the World of Curves

Welcome to Curvetopia! This project is dedicated to the identification, regularization, and beautification of curves in 2D Euclidean space. The main goal is to transform hand-drawn shapes into perfect curves and shapes.

## Table of Contents
1. [Objectives](#objectives)
2. [Key Tasks](#key-tasks)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Examples](#examples)
6. [Expected Outputs](#expected-outputs)
7. [Evaluation Criteria](#evaluation-criteria)
8. [Use Cases](#use-cases)
9. [Contributing](#contributing)
10. [License](#license)

## Objectives

- **Identify Regular Shapes**: Detect regular geometric shapes within a set of curves, including straight lines, circles, ellipses, rectangles, rounded rectangles, regular polygons, and star shapes.
- **Explore Symmetry**: Analyze curves for symmetry, starting with reflection symmetries.
- **Complete Incomplete Curves**: Identify and naturally complete curves that have been fragmented or occluded.

## Key Tasks

1. **Regularize Curves**: 
    - Detect and regularize straight lines, circles, ellipses, rectangles, rounded rectangles, regular polygons, and star shapes within the given curves.
    - Handle hand-drawn shapes and doodles, ensuring the algorithm can distinguish between regularizable and non-regularizable shapes.

2. **Symmetry Detection**: 
    - Focus on closed shapes and identify lines of symmetry where applicable.
    - Consider different representations of the same shape and ensure the symmetry detection is accurate.

3. **Curve Completion**: 
    - Address scenarios where curves have been "planarized," leaving gaps or partial holes.
    - Develop algorithms to complete these curves based on principles of smoothness, regularity, and symmetry.

## Installation

To get started with Curvetopia, you'll need to clone the repository and install the necessary dependencies. Here's how:

```bash
git clone https://github.com/yourusername/curvetopia.git
cd curvetopia
pip install -r requirements.txt

## Usage
