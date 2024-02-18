# SPARK - Scientific Python Analysis and Research Kit

SPARK - Scientific Python Analysis and Research Kit is a collection of classes and static methods designed to assist in scientific computations and visualizations. It offers functionalities across various domains including visualization, mathematics, and physics, providing users with tools to perform common tasks efficiently.

# Features

1) Visualization: Generate pie charts, bar graphs, column charts, and line charts effortlessly.
2) Mathematics: Perform logarithmic calculations, basic arithmetic operations, polynomial evaluations, and generate arithmetic or geometric progressions.
3) Physics: Compute wave functions, kinematics equations, vector magnitudes, trigonometric functions, and gravitational forces.

# Contribution

Contributions to the SPARK library are welcome! If you have ideas for improvements, new features, or find any issues, feel free to contribute by submitting pull requests or reporting issues on GitHub.

# Usage

First import the Python math library and then import the SPARK library.

import math
from spark import Visualization, Mathematics, Physics

Visualization.create_pie_chart(data, labels)
Visualization.create_bar_graph(x, y)
Visualization.create_column_chart(x, y)
Visualization.create_line_chart(x, y)

Mathematics.logarithm(x, base)
Mathematics.arithmetic_operations(a, b)
Mathematics.evaluate_polynomial(coefficients, x)
Mathematics.arithmetic_progression(start, step, n)
Mathematics.geometric_progression(start, ratio, n)

Physics.wave_function(amplitude, frequency, phase, time)
Physics.kinematics(initial_velocity, acceleration, time)
Physics.vector_magnitude(vector)
Physics.trigonometry_functions(angle)
Physics.gravitational_force(mass1, mass2, distance)

# License

According to the CC BY 4.0, a user is allowed to remix and even commercially use this project but they will have to include a credit to the creator for their contribution to this project.
