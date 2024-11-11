## Quantumania

Quantumania is a project developed for the Qiskit Fall Fest 2024. It does numerous things. (1) It demonstrates the procrustean distillation technique using Qiskit, (2) it demonstrates a method to convert successfully distilled entangled qubits into singlets for use in the Ekert91 protocol, (3) it proves that for a given number of required perfect singlet states, the Procrustean distillation protocol can generate these with high-fidelity states that closely approximate ideal singlets, and (4) it proves the potential to preserve entanglement in practical implementations of Ekert91 (QKD). 

## Installation

Clone the repository to your local machine:
git clone https://github.com/your-username/Quantumania.git
cd Quantumania

Use pip install to install required libraries.

## Usage

To take states from partially to maximally entangled in preparation for E91 protocol. 
The degree of entanglement can be changed by adjusting the value of theta.
To experiment with Quantumania, users can adjust the degree of entanglement by modifying the angle 
𝜃. This parameter, which is set as:
theta = np.radians(45)
appears throughout the code. By changing the value of 𝜃, users can explore how different levels of entanglement impact the distillation process and the fidelity of the resulting states.

## Contributing 

Pull requests are welcomed. For major changes or error corrections please utilize our contact information in the section below. 

## Contact Information
Valeria Diaz Moreno (diazmoreno@wisc.edu)
Carlos Alvarez (alvarezballa@wisc.edu)

## License 

This project was created by Valeria Diaz Moreno and Carlos Alvarez. You are free to use, modify, and share the code for non-commercial purposes. For commercial use or further inquiries, please contact us.
