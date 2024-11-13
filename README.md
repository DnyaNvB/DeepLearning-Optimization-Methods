This notebook explores various optimization methods used in deep learning, specifically applied to challenging test functions like the Ackley and Beale functions. The goal is to visualize and compare the performance of different optimization algorithms in finding the global minimum of these functions, which often contain many local minima and complex surfaces.

# Optimization Algorithms Covered

Gradient Descent: A basic first-order method that uses the gradient to iteratively move towards a minimum.

Momentum: An enhancement over gradient descent that accumulates past gradients to help escape local minima.

RMSProp: An adaptive learning rate method that adjusts based on recent gradients, suitable for functions with varying scales.

Adam (Adaptive Moment Estimation): Combines momentum and adaptive learning rates, making it versatile for complex surfaces.

Newton's Method: A second-order method using the Hessian matrix to improve convergence by considering curvature.

ADOPT (Adaptive Gradient Descent with Optimal Learning Rate): A variant that adapts learning rates based on gradient history, providing stable updates without momentum.