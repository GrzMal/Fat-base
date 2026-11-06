# Fat base schemes – Singular computations

This repository contains **Singular** code for constructing examples of plane curves and surfaces subject to prescribed multiplicity conditions, and for computing their **absolute factorization**.

## Contents

The file [`code.txt`](code.txt) contains two examples:

- **In $\mathbb{P}^2$:** Constructs the ideal of a configuration of 13 points (three double points and ten simple points), together with an additional point of multiplicity four. It then computes a polynomial in the resulting ideal and its absolute factorization.
- **In $\mathbb{P}^3$:** Constructs an ideal involving a Fermat-type point configuration, coordinate points (including a triple point), and a double line. It then computes an example polynomial and its absolute factorization.

## Requirements and usage

The computations require **Singular** and the library `absfact.lib`. Run the script in Singular with:

`<"code.txt";`

The script prints the polynomials, their degrees, and their absolute factors.

## License

The code is distributed under the [MIT License](LICENSE).
