# Numerical Methods for PDEs

## Single PDEs

### [Linear Equations](./Single Linear PDEs)

1. [Laplace’s equation](./Single Linear PDEs/laplace_equation.ipynb)

Consider Laplace's equation in 2D dimension:
$$\frac{\partial^2 u}{\partial x^2} + \frac{\partial^2 u}{\partial y^2} = 0, \quad (x, y) \in [0, 1]^2$$

2. Helmholtz’s (or eigenvalue) equation

Consider Helmholtz equation in 2D dimension which is defined as:
$$\nabla^2 u + k^2 u = f(x, y), \quad (x, y) \in \Omega = [0, 1]^2$$

We consider two typical problems:

i) Given a known $k$ and a manufactured source $f$, find $u$ satisfying:
$$\frac{\partial^2 u}{\partial x^2} + \frac{\partial^2 u}{\partial y^2} + k^2\, u = f(x, y)$$
with homogeneous Dirichlet boundary conditions $u = 0$ on $\partial\Omega$.

ii) Find pairs $(\lambda_i, \phi_i)$ (eigenvalues and eigenfunctions) satisfying:
$$-\nabla^2 \phi = \lambda\, \phi, \quad \phi = 0 \text{ on } \partial\Omega$$