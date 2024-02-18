# SPARK - Scientific Python Analysis and Research Kit

SPARK is a Python Library which helps developers to do scientfic calculations and data related tasks. It has advanced features such as logarithms, trigonometry, gravitation, progressions and etc.


1) Visualization Class: This class provides static methods for creating various types of visualizations, including pie charts, bar graphs, column charts, and line charts. These methods serve as utilities for generating graphical representations of data, enhancing the understanding and interpretation of datasets.

2) Mathematics Class: This class encompasses static methods for performing mathematical operations and computations. It includes functionalities such as logarithmic calculations, arithmetic operations (addition, subtraction, multiplication, division), polynomial evaluation, generation of arithmetic and geometric progressions, etc. These methods facilitate common mathematical tasks and calculations in Python programming.

3) Physics Class: This class offers static methods for conducting physics-related computations and simulations. It includes functionalities such as computing wave functions, solving kinematic equations, calculating vector magnitudes, evaluating trigonometric functions, and determining gravitational forces between masses. These methods cater to a variety of physics-related scenarios, aiding in simulations, modeling, and analysis of physical phenomena.

# Usage 

First import the python math library and then import any desired class such as 'Mathematics', 'Physics' or 'Virtualization.
Example:

import math
from spark import Visualization, Mathematics, Physics

data = [20, 30, 50]
labels = ['A', 'B', 'C']
Visualization.create_pie_chart(data, labels)
Visualization.create_bar_graph([1, 2, 3], [10, 20, 30])
Visualization.create_column_chart([1, 2, 3], [10, 20, 30])
Visualization.create_line_chart([1, 2, 3], [10, 20, 30])

print(Mathematics.logarithm(100, 10))
print(Mathematics.arithmetic_operations(5, 2))
print(Mathematics.evaluate_polynomial([1, 2, 3], 2))
print(Mathematics.arithmetic_progression(1, 2, 5))
print(Mathematics.geometric_progression(2, 3, 4))

print(Physics.wave_function(1, 2, 0, 1))
print(Physics.kinematics(10, 2, 3))
print(Physics.vector_magnitude([3, 4, 5]))
print(Physics.trigonometry_functions(math.pi / 4))
print(Physics.gravitational_force(5, 10, 2))
