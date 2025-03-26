# Erdős Matrix Generator

This repository contains a **Mathematica Notebook (`.nb`)** for generating **Erdős matrices**, which are bistochastic matrices that saturate the following inequality, due to Marcus and Ree, 
```math
\sum_{i, j=1}^n A(i, j)^2 \leq \max_{\sigma\in S_n}\sum_{i=1}^{n}A(i, \sigma(i))\;,
```
satisfied by all $n \times n$ bistochastic matrices. The code can efficiently construct and classify these matrices for low dimensions.

## How to Use
1. **Download the latest release** from the [Releases Section](https://github.com/amankoir/Erdos-matrices/releases).
2. Open the **`ErdosMatrixGenerator.nb`** file in **Mathematica**.
3. Evaluate the notebook by supplying the values of $n$ and $k$ to produce all non-equivalent $n \times n$ Erdős matrices that are convex combination of exactly $k$ linearly independent permutation matrices.


## Requirements
- **Mathematica 12.0+** (or Wolfram Engine)
- No external dependencies

## License
This project is licensed under the **MIT License** – see the [`LICENSE`](LICENSE) file for details.

## Future Work
- Extending the algorithm to **higher-dimensional cases**.
- Exploring **connections with random matrix theory**.
- Optimizing performance for **large-scale computations**.

## Acknowledgments
This work is inspired by and builds upon the research of **Raghavendra Tripathi** and his paper [Some observations on Erdős matrices](https://www.sciencedirect.com/science/article/pii/S0024379524004749).

---
### **Contact**
For questions or collaboration, reach out via **GitHub Issues** or email **aman_7778@maths.du.ac.in**.

---
