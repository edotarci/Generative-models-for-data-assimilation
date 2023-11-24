# Generative-models-for-data-assimilation

- Attempt: togheter with other few students in the project I built a generative model for data assimilation trough Optimal Transport.
- Supervisors: prof. Giulio Trigila (CUNY) and prof. Ricardo Baptista (CalTech).
- Info: This project was part of Polymath Jr. summer program (https://geometrynyc.wixsite.com/polymathreu)

In many real-world problems, the data doesn’t arrive all at once and, in practice, the unknown state is evolving over time.
Our goal is to update our belief for the state as we sequentially collect observations. 
This process, known as data assimilation is divided into two parts: forecast and analysis.

We focused on the analysis part; sequentially estimating and correctly simulating (conditional) densities from samples is a very hard task for high dimensional problems but a map from a prior ρ(xt|y1:t−1) to a posterior ρ(xt|y1:t) is a useful tool to estimate and simulate the posterior distribution. To find such a map we used the framework of optimal transport.

We worked on the code written togheter with the professors (see MoonExampleRC.ipynb).

The notions and references we had to delve into to proceed in the project are:
- Background material on: Kalman FIltering and Ensemble Kalman filtering
- Background material on Optimal Transport
- Papers: https://drive.google.com/drive/folders/1eqy6dxU_MOPbKC6CsTG942loJfdBcMnl?usp=share_link






