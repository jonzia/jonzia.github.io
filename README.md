## About Me

I'm an aspiring physician-scientist based in Atlanta, GA, USA. My coding hobbies involve creating A.I.-powered bots for multiplayer games and occasionally publishing various machine learning templates I create in the course of my research. You can check out all my projects on my (admittedly sparsely-updated) **[GitHub Profile](https://github.com/jonzia)** -- or simply scroll down for project descriptions, documentation, and videos. Feel free to **[contact me directly](https://www.jonzia.me)** for comments and questions!

I hope you find one or more of these repositories helpful!

---
---
## Machine Learning Templates
Various template scripts for performing machine learning tasks.

#### Neural Net Studio (Matlab)
This (*really old!*) program trains and analyzes recurrent neural networks (RNNs) as well as non-recurrent feedforward networks. It works for both recurrent and non-recurrent networks, and any number of different neural network architectures can be tested at once. The program is automatically formatted for parallel processing across computer cores. This code was used to create the attached research paper, an early example of using machine learning to predict freezing of gait in Parkinson's patients.

// **[Documentation](https://jonzia.github.io/NeuralNetStudio/)** // **[Demo](https://www.youtube.com/watch?v=WBxCHDFzexQ)** // **[Paper](https://www.researchgate.net/publication/309339519_Utilizing_Neural_Networks_to_Predict_Freezing_of_Gait_in_Parkinson's_Patients)** //

---
#### LSTM Network (Tensorflow)
This (*really old!*) program is an LSTM network written in Python for Tensorflow.

// **[Documentation](https://jonzia.github.io/LSTM_Network/)** // **[Demo](https://youtu.be/DSzegLte0Iw)** //

---
#### Recurrent Autoencoder (Tensorflow)
This program implements a recurrent autoencoder for time-series analysis. Useful as a buidling block for higher-level nonlinear dynamical systems modeling. An example implementation based on a more complex version of this program is shown in the attached research paper, which models the cardiovascular system as a nonlinear dynamical system to interpret cardiomechanical signals.

// **[Documentation](https://jonzia.github.io/Recurrent_Autoencoder/)** // **[Paper](https://www.researchgate.net/publication/339979069_Modeling_Consistent_Dynamics_of_Cardiogenic_Vibrations_in_Low-Dimensional_Subspace)** //

---
#### Graphical Modeling (Matlab)
Framework for designing, solving, and implementing probabilistic graphical models for statistical modeling. Includes features such as message passing, variable elimination, recursive solving of factor graphs, and solving hidden Markov models (HMMs) via the Viterbi algorithm.

// **[Documentation](https://jonzia.github.io/GraphicalModeling/)** //

---
#### Genetic Algorithms (Matlab)
This program implements a genetic algorithm with the use-case of sorting a shuffled dataset. Useful as a building-block for higher-level genetic algorithms, with some advanced features such as multithreading with genetic migration between separate populations built in.

// **[Documentation](https://github.com/jonzia/GeneticSort/)** //

---
#### Unsupervised Clustering (Matlab)
This program implements unsupervised clustering via Gaussian mixture modeling (GMM). This code was used to create the attached research paper, which uses a statistical approach to identify consistent time-domain features in dynamic, stochastic signals.

// **[Documentation](https://jonzia.github.io/GeneticSort/)** // **[Paper](https://www.researchgate.net/publication/335795238_Automated_Identification_of_Persistent_Time-Domain_Features_in_Seismocardiogram_Signals)** //

---
#### Manifold Mapping (Matlab)
This program implements the ISOMAP algorithm for mapping a low-dimensional manifold of datapoints. This code was used to create the attached research paper, which analyzes the underlying low-dimensional dynamics of cardiomechanical signals.

// **[Documentation](https://jonzia.github.io/Manifold/)** // **[Paper](https://www.researchgate.net/publication/343446322_Harnessing_the_Manifold_Structure_of_Cardiomechanical_Signals_for_Physiological_Monitoring_during_Hemorrhage)** //

---
---
## Games!
Sometimes I design programs for games that I have a hard time winning.

#### Catan RL (Matlab)
This program learns to play Settlers of Catan via reinforcement learning. The quality function is learned by training a neural network to map board states generated from Monte Carlo simulations to the ultimate number of victory points achieved by the player. The program follows an epsilon-greedy function based on the most current quality function approxmation.

// **[Documentation](https://jonzia.github.io/Catan/)** //

---
#### Chess RL (Tensorflow)
This program learns to play chess via reinforcement learning. The action-value functions are learned by training a neural network on the total return of randomly-initialized board states, determined by Monte Carlo simulations. The program follows an epsilon-greedy policy based on the most current action-value function approximations.

// **[Documentation](https://jonzia.github.io/Chess_RL/)** // **[Demo](https://youtu.be/PgVgvZ9_X8c)** //

---
#### Codenames AI (Matlab)
This program generates clues based on either 8 or 9 words entered by the user. The words must be taken from the 400-word set of the Codenames board game. The clues are generated based on an analysis of the Priceton Wordnet database, which seeds a dependency graph that may later be tuned via reinforcement learning (not yet implemented). You can check out a demo of the program on [YouTube](https://youtu.be/yX2YkhvAtM4)!

// **[Documentation](https://jonzia.github.io/Codenames/)** // **[Demo](https://youtu.be/yX2YkhvAtM4)** //

---
---
## Other Projects
Random other projects related to my work and hobbies.

#### Swarm Robotics + RL (Matlab)
A simple project which uses reinforcement learning to teach networked agents to perform herding tasks. This software was designed for simulation in Matlab and implementation in the Robotarium laboratory at Georgia Tech.

// **[Documentation + Demos](https://jonzia.github.io/Robotarium/)** //

---
#### Drone Flight Controller (Arduino)
Check back soon! This project will utilize reinforcement learning as the basis for a flight controller.

---
#### Wordnet Data Capture (Java)
The purpose of this program is to scan the Princeton Wordnet database and store the hyponym and meronym data as well as full hypernym trees such that this data may be analyzed by another program. This program uses the JWI API from MIT to read and translate the Wordnet 3.0 database into workable .txt files for use in applications such as MATLAB. This program was used to build the dataset for the [Codenames AI](https://github.com/jonzia/Codenames) also available on GitHub.

// **[Documentation](https://jonzia.github.io/WordnetDataCapture/)** //

---
