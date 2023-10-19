# tutorial_from_posture_to_dynamics
$\textit{Tutorial for quantitative analysis of tracking data from PCA to transition matrix clustering.}$

Welcome! 

Thank you for being here. 

$\textbf{Goal}$: This tutorial is about quantitative, dynamical systems-inspired analysis of tracking data. Rather than a complete, ready-made recipe for unsupervised behavior quantification, this pipeline aims at the informed exploration of a dataset within a theoretical framework. We hope to be as explicit as possible about theoretical ideas, their practical implementation, and their underlying assumptions about the data. 

$\textbf{Content}$: We will analyze tracking data from Irina Korshok's experiment made at the Okinawa Institute of Science and Technology on a freely crawling Drosophila Melanogaster larva. The tutorial is split into three parts. 
- Part 1- PCA: Dimensionality reduction of the dataset with principal component analysis.
- Part 2-State space reconstruction: Build a maximally predictive posture sequence matrix using delay-embedding.
- Part 3- Transition Matrix Clustering: Build the transition matrix and analyze one of its eigenvectors.

 The three parts are best done in order for a smooth experience, but they technically can be run independently. You could substitute any dataset you have in the tutorial, pending some small modifications to the code.

$\textbf{Credits}$ Part 1 is an adaptation of a tutorial from BingKan Xue, PHZ4710 - Introduction to Biological Physics, University of Florida.  
The theoretical framework and code from Parts 2 and 3 are from Antonio C. Costa (École Normale Supérieure de Paris). All the functions for embedding and transition matrices are his as well. This work has been done under the supervision of Greg J. Stephens (Okinawa Institute of Science and Technology and Vrije Universiteit Amsterdam). 

$\textbf{Contact Information}$: 
For any questions, you can email me at anouk.beraud@gmail.com. 


$\textbf{Files}$: Here is a complete record of all the files in this repository. 

Colab notebooks: 
- Part 1- PCA.ipynb
- Part 2-State space reconstruction.ipynb
- Part 3- Transition Matrix Clustering.ipynb

Extra functions: 
- clustering_methods.py
- delay_embedding_1D.py
- operator_calculations.py
- stats.py

Pictures and videos from the text: 
- img_angles_calculation.png
- img_larva_svd0_vs_ant_angle_vs_phi1.png
- img_measurement_matrix.png
- img_trajectory_matrix.png
- img_transition_matrix_schematics.png
- img_umap_celegans_costa.png
- vid_intro_state_space_Sugihara.mp4
- vid_larva_experiment_Irina_Korshok.mp4
- vid_phase_space_pendulum_Ghrist_Math.mp4
- vid_Reconstructed_data.mp4
- vid_Takens_thm_Sugihara.mp4
- vid_tracked_larva_segments.mp4

  Data files:
- file_angles_larva.csv
- file_principal_components_time_series_larva.csv



