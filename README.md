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

## Finansowanie / Funding

Pl:
Badania zostały sfinansowane przez Narodowe Centrum Nauki (NCN) w ramach projektu badawczego nr **2023/51/D/ST1/00118** pt. *"Nieoczekiwane powierzchnie typu (d+k,d) w przestrzeni rzutowej P^N"*. 

Wszelkie dane, metadane oraz kod źródłowy zawarte w tym repozytorium są udostępniane na licencji **[MIT](LICENSE)**.

Eng:
This research was funded by the National Science Centre, Poland (NCN) under the research project no. **2023/51/D/ST1/00118** entitled *"Nieoczekiwane powierzchnie typu (d+k,d) w przestrzeni rzutowej P^N"*.

All data, metadata, and source code in this repository are distributed under the **[MIT](LICENSE)** license.
