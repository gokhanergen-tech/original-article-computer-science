# Optimization Algorithms — Key Original Papers

This file contains **foundational and influential optimization algorithms** inspired by nature and swarm intelligence.  
Each entry includes the year, authors, and a short description of the algorithm.

---

## 📌 1. Particle Swarm Optimization (PSO)

- **Year:** 1995
- **Authors:** Kennedy & Eberhart
- **Original Paper:** Kennedy, J., & Eberhart, R. (1995). _Particle Swarm Optimization_. Proceedings of IEEE International Conference on Neural Networks.

**Summary:**  
Particle Swarm Optimization (PSO) is a population-based stochastic optimization technique inspired by **social behavior of birds flocking or fish schooling**.

- Particles represent candidate solutions moving through the search space.
- Each particle adjusts its position based on its own experience and the best-known positions of the swarm.
- PSO is widely used for continuous, nonlinear, and multi-dimensional optimization problems.

[More info](https://ieeexplore.ieee.org/document/488968)

---

## 📌 2. Differential Evolution (DE)

- **Year:** 1997
- **Authors:** Storn & Price
- **Original Paper:** Storn, R., & Price, K. (1997). _Differential Evolution – A Simple and Efficient Heuristic for Global Optimization over Continuous Spaces_.

**Summary:**  
Differential Evolution is a **population-based optimization method** for continuous spaces:

- Uses differences between randomly sampled population members to generate new candidate solutions.
- Includes **mutation, crossover, and selection** steps similar to genetic algorithms.
- Efficient for high-dimensional and nonlinear optimization problems.

[More info](https://ieeexplore.ieee.org/document/400568)

---

## 📌 3. Ant Colony Optimization for Continuous Domains (ACOR)

- **Year:** 2008
- **Authors:** Socha & Dorigo
- **Original Paper:** Socha, K., & Dorigo, M. (2008). _Ant Colony Optimization for Continuous Domains_. European Journal of Operational Research.

**Summary:**  
ACOR extends traditional **Ant Colony Optimization (ACO)** from discrete problems to continuous domains:

- Uses artificial ants to sample solution space probabilistically.
- Maintains a **solution archive** to guide exploration.
- Effective for continuous optimization problems where classical ACO cannot be directly applied.

[More info](https://www.sciencedirect.com/science/article/pii/S0377221707007712)

---

## 📌 4. Artificial Bee Colony (ABC)

- **Year:** 2005
- **Authors:** Karaboğa, Derviş
- **Original Paper:** Karaboğa, D. (2005). _An Idea Based on Honey Bee Swarm for Numerical Optimization_.

**Summary:**  
Artificial Bee Colony (ABC) algorithm is inspired by **foraging behavior of honey bees**:

- Employs **employed bees, onlooker bees, and scout bees** to explore the search space.
- Each bee explores candidate solutions and communicates quality information.
- Well-suited for complex numerical optimization problems.

[More info](https://www.sciencedirect.com/science/article/pii/S0957417405001063)

---

## 📌 How to Use

- Download the original papers using the links.
- Summarize the algorithm principles in your own words.
- Compare the algorithms in terms of **population size, convergence, and problem suitability**.
- Add notes, implementation tips, or improvements for reference.

---

## 📌 Citation Example (BibTeX)

```bibtex
@inproceedings{kennedy1995pso,
  title={Particle Swarm Optimization},
  author={Kennedy, J. and Eberhart, R.},
  booktitle={IEEE International Conference on Neural Networks},
  year={1995}
}

@article{storn1997de,
  title={Differential Evolution – A Simple and Efficient Heuristic for Global Optimization over Continuous Spaces},
  author={Storn, R. and Price, K.},
  year={1997}
}

@article{socha2008acor,
  title={Ant Colony Optimization for Continuous Domains},
  author={Socha, K. and Dorigo, M.},
  journal={European Journal of Operational Research},
  year={2008}
}

@article{karaboga2005abc,
  title={An Idea Based on Honey Bee Swarm for Numerical Optimization},
  author={Karaboğa, D.},
  journal={Studies in Fuzziness and Soft Computing},
  year={2005}
}
```
