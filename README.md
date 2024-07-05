# Infosys_internship
Welcome to the repository documenting fashion-related research papers from the past decade! This repository is organized to provide a comprehensive overview of the datasets used and the machine learning models applied in these studies. 

Repository Structure
1. Introduction:
   
Overview: A brief explanation of the importance and growth of fashion-related research over the past decade.

  Datasets: An introduction to the various datasets commonly used in fashion research.

  Machine Learning Models: A summary of popular machine learning models employed in these studies.

  2. Sections by Data Types:
     
i) Clothing Segmentation

Detailed descriptions of papers focused on segmenting clothing items from images.
Information includes the dataset used, dataset size, a brief description of the dataset, the ML model used, performance metrics, and links to the papers.

ii) Clothing Classification

Detailed descriptions of papers focused on classifying different types of clothing items.
Information includes the dataset used, dataset size, a brief description of the dataset, the ML model used, performance metrics, and links to the papers.

3. Detailed Examples of Machine Learning Models:
   
a) ResNet (Residual Networks)

Overview of ResNet, its significance, and an example use case in fashion research.
Detailed information on how ResNet was used in a specific paper, including dataset details and performance metrics.

b) VGG16 (Visual Geometry Group 16-layer)

Overview of VGG16, its significance, and an example use case in fashion research.
Detailed information on how VGG16  was used in a specific paper, including dataset details and performance metrics.


## How to Use This Repository:

-> Browse the Papers:

Navigate through the sections to find detailed information on various fashion-related research papers.
Use the provided links to access the full papers for deeper insights.

-> Explore Datasets:

Understand the datasets used in these studies, including their size and description.
Find links to the datasets where available.

-> Learn About ML Models:

Gain insights into the machine learning models used in fashion research.
See examples of how these models were applied and their performance metrics.


import numpy as np # linear algebra
import pandas as pd # data processing, CSV file I/O (e.g. pd.read_csv)

# Input data files are available in the read-only "../input/" directory
# For example, running this (by clicking run or pressing Shift+Enter) will list all files under the input directory

import os
for dirname, _, filenames in os.walk('/kaggle/input'):
    for filename in filenames:
        print(os.path.join(dirname, filename))
