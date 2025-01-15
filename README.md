# Physics-Informed-Neural-Networks
A collection of python notebooks used to solve Physics Informed Neural Networks (PINNs) for phase change material problems. PINN essentially solves differential equations. Most of the mechanical based problem are governed by differential equations, hence a robust differential equation solver is required. Hence, PINN has grown into prominence for its ability to provide accurate answers for a differential equation. 

## Final Update
Implemented Res-Net based architecture to implement diffuse interface based formulation

## Previously Attempted
- Transfer Learning, RNN and GRU based time stepping methodologies. 
- Gradient enhanced PINN
- Coupling of gradient and evolutionary optimiser(genetic algorithm)

## Architecture
- General Architecture of PINN.
  
<img width="600" alt="image" src="https://github.com/sanjeet178/Physics-Informed-Neural-Networks/assets/69724036/c0a34eda-7edb-4cf5-b91d-d0cfcf174acf">

-Res-Net based architecture for improving the performance of PINN

<img width="600" alt="image" src="https://github.com/sanjeet178/Physics-Informed-Neural-Networks/assets/69724036/c48d90f2-6397-4642-a191-de3b732f59b3">


## Results
- Phase Change Material (ice) heated from two sides and the other two sides are insulated 

  <img width="900" alt="image" src="https://github.com/sanjeet178/Physics-Informed-Neural-Networks/assets/69724036/990de879-3cd0-4f9c-a062-f53fcc1fa072">

## Future Scope
- Create activation functions that is robust in training Higher order derivatives

## References
- Maziar Raissi, Paris Perdikaris, George Em Karniadakis, "Physics Informed Deep Learning (Part I): Data-driven Solutions of Nonlinear Partial Differential Equations," [URL: http://arxiv.org/abs/1711.10561], November 2017.
- Chang Miao, Yibo Yang, Paris Perdikaris, Daniel E. Hurtado, Ellen Kuhl, "Physics-Informed Neural Networks for Cardiac Activation Mapping," Frontiers in Physics, vol. 8, February 2020. [DOI: 10.3389/fphy.2020.00042]
