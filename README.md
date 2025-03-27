################## TASK1 ###########
wildtype and mutant type alpha synuclein fibrils discrimination using Deep Learning based Autoencoder
                for that first wildtype dataset reconstruction using wildtype trained autoencoder and mutant-dataset reconsturct using wild-trained model or vice-versa 
Dataset for this method = residue-pair distance (Feature) over trajectory
Result = DIO (originial input - reconstucted output)
##########TASK2#######
identy residue-pair for discrimination (Feature importance)
#######TASK3###
Extract the important residues from Feature importance (Residue important)








###########script for TASK1#####
######Load the Libraies 
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import random
from sklearn.neural_network import MLPRegressor
from sklearn.model_selection import train_test_split

