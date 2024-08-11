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
8. [Acknowledgments](#acknowledgments)
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
```

## Usage

Once you have the project set up, you can start experimenting with the various functionalities:

### Regularize Curves

```python
from curvetopia import regularize

input_path = "path/to/your/input.csv"
output_path = "path/to/your/output.csv"
regularize(input_path, output_path)
```

### Symmetry Detection

```python
import cv2
from symmetry_detection import detect_symmetries

image_path = 'path_to_your_image.png'
symmetry_count = detect_symmetries(image_path)
print(f"Number of symmetries detected: {symmetry_count}")
```

### Completing Curves

```python
from curve_completion import complete_curve

incomplete_curve_path = 'path_to_incomplete_curve.csv'
complete_curve(incomplete_curve_path)
```

## Examples
Check out the problems_ex directory for sample input and output files:

-**isolated.csv:** Simple, isolated curves for regularization.

-**frag0.csv & frag1.csv:** Fragmented shapes requiring regularization and symmetry detection.

-**occlusion1.csv:** Curves that need completion due to partial occlusion.

You can run the example scripts to see how the algorithms work on these samples.

## Expected Outputs
-**Regularized Shapes:** Curves that are adjusted to match regular geometric shapes.

-**Symmetry Analysis:** Identification of symmetrical aspects of curves, including lines of reflection symmetry.

-**Completed Curves:** Curves that have been accurately completed, filling in gaps caused by occlusions or fragmentation.

## Evaluation Criteria

The regularization and symmetry detection tasks will be evaluated based on the number of regular geometric shapes and symmetry lines accurately identified in the input. For curve completion, the evaluation will focus on how well the algorithms complete curves with varying levels of occlusion.

## Acknowledgments
 - **OpenCV:** For robust image processing capabilities.
 - **NumPy:** For efficient numerical operations.
 - **Matplotlib:** For versatile data visualization tools.

## Contributing

Contributions are welcome! If you'd like to contribute to Curvetopia, please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature/your-feature-name).
3. Commit your changes (git commit -m 'Add some feature').
4. Push to the branch (git push origin feature/your-feature-name).
5. pen a Pull Request.
6. Please make sure your code adheres to the project's coding standards and passes all tests.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
You can now copy and paste this entire block into your README.md file and make any additional edits as needed.
   
