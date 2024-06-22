# Constrained Carbon Equilibrium (CCE) Calculator

## Introduction
The CCE model was first developed by J.G. Speer et al. [1] [2] and termed "constrained paraequilibrium" (CPE), but it is currently known as CCE. With this model, it is possible to predict the amount of carbon partitioned from supersaturated martensite to metastable austenite when the chemical potential of carbon between ferrite (or carbon-depleted martensite) and austenite is equal at a particular temperature. The final proportion of retained austenite and ferrite can also be predicted. It is used as a guide for the development of Advance High Strength Steel of the Third Generation (AHSS 3rd gen)

## Constraints 
- One of the constraints imposed by the CCE model is that the number of iron (and substitutional) atoms is conserved in each phase during the partitioning process, which means a stationary α/γ interface (ferrite/austenite). With this consideration, a matter balance for iron is presented by the authors.

- It is also assumed that virtually all the carbon in the martensite partitions to the austenite.

- The suppression of carbide precipitation is an important consideration that must be addressed for the correct development of the model. Any carbide precipitation will reduce the amount of carbon available to be part of the partitioning process, which in turn will affect the predictions made by the model. Silicon and aluminum are generally used to avoid carbide precipitation (cementite but not the transition carbide).

## How to use the code

- Enter the chemical composition of your alloy, which will be processed by Q&P (Quenching and Partitioning).
<p align="center"> 
  <img src="https://github.com/moralesluis26/Constrained-Carbon-Equilibrium-CCE-Calculator/assets/46792756/6e5de9eb-ce86-4207-9f77-eeac09076229"  width="250" />
</p>

- Martensite start (Ms) can be predicted as a function of austenite composition using empirical relations. **The ecuation used in this code is by default, but you can insert the most suitable equation into your project for better prediction results**.
<p align="center"> 
  <img src="https://github.com/moralesluis26/Constrained-Carbon-Equilibrium-CCE-Calculator/assets/46792756/ce303747-e090-4440-970b-3054e5256e89" width="440" />
</p>

- As an input parameter, you can select the partitioning temperature in °C.
<p align="center"> 
  <img src="https://github.com/moralesluis26/Constrained-Carbon-Equilibrium-CCE-Calculator/assets/46792756/3061cd6b-cd91-4d5f-b400-438690957c84" alt="Ms equation used by default in this code">
</p>

## Outcomes
 With this calculator you can obtain the following outcomes:
- Carbon content in austenite after partitioning at temperature *TC*, taking into account for the assumptions made by the original model.
- Maximum retained austenite fraction.
- Optimal quenching temperature to obtain the highest proportion of retained austenite fraction. 
- Graph of curves depicting the different phases as a function of the quenching temperature *Tq​*.

<p align="center"> 
  <img src="https://github.com/moralesluis26/Constrained-Carbon-Equilibrium-CCE-Calculator/assets/46792756/070d3560-0857-44ac-9fa8-6e0bc49f4dd9" width="500" />
</p>


## References

[1]	J. G. Speer, A. M. Streicher, D. K. Matlock, F. Rizzo, and G. Krauss, “Quenching and partitioning: A fundamentally new process to create high strength trip sheet microstructures,” Mater. Sci. Technol. 2003 Meet., pp. 505–522, 2003.

[2] J. Speer, D. K. Matlock, B. C. De Cooman, and J. G. Schroth, “Carbon partitioning into austenite after martensite transformation,” Acta Mater., vol. 51, no. 9, pp. 2611–2622, 2003, doi: 10.1016/S1359-6454(03)00059-4.
