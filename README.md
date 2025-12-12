# Modeling HIV Transmission Across Vocational Groups in a High-Risk Social Network <br>
## Group 6 Final Project <br>
This project analyzes the effects of targeted and random node removal on transmission in the Colorado 90 dataset, as well as analyzes the effects different groups have on the dataset and analyzing various network characteristics, such as assortativity, largest connected component, and identifying communities. <br> 
Project by: Baanee Raheja, John Teurman, Grace Bradecamp

File Breakdown <br> 
The data folder includes "edges.tsv" and "nodes.tsv." "nodes.tsv" identifies the nodes by number includes data about the nodes, including race, gender, and vocation, while "edges.tsv"
The code folder includes "project code GB.ipynb," which is the code used to clean and filter the data, "SI_Final_Project_code.ipynb" which is the code used for the SI models of random and targeted node removal (si_random_removal.png and si_targeted_removal.png), "finalproject.ipynb" which is the code used for the Newman coefficient and  Louvain community detection algorythm"codewithedits.ipynb," which is the code used for the bar graph and largest connected component graphics (bargraphfixed.png and LCC.png).
The figures folder includes the above mentioned figures si_random_removal.png, si_targeted_removal.png, bargraphfixed.png, and LCC.png, as well as the explainer image used in our paper, explainerimage.jpg.
<br> 

Packages Used <br> 
import numpy as np <br>
import matplotlib.pyplot as plt <br>
import networkx as nx <br>
import polars as pl <br>
import pandas as pd <br>
import seaborn as sns <br>
