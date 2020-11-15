# Running the Bernstein Algorithm and then post-processing results to mitigate errors
- Picked a random number in this case 5, and implemented the Bernstein-Vazirani algorithm to guess the number in one try by leveraging phase kickback. 
- Then ran the circuit on a quantum computer and received noisy results
- Used qiskit.ignis to calibrate a fitter to these results and used the inverse matrix to filter out errors
- Compared raw results vs. mitigated results 

![](https://user-images.githubusercontent.com/70229100/99189404-04a80b00-272f-11eb-94ff-1afd31b47e71.png)
![](https://user-images.githubusercontent.com/70229100/99189396-f954df80-272e-11eb-9444-09ed066eb868.png)
