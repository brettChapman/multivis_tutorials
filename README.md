# README.md - `Chapman_et_al_2019`

<p align="justify">
This repository contains the tutorials for the Metabolomics review paper "Multivariate visualisation strategies in metabolomics: A review". There are five different tutorials explaining visualisations from PCA, Hierarchical Clustered Heatmaps (HCH), Polar Dendrograms, Spring-embedded network plots, and Hierarchical Edge Bundle plots, all demonstrated using a dataset from (<a href="https://physoc.onlinelibrary.wiley.com/doi/full/10.1113/EP087159">Lawler et al. (2018)</a>) published in <i>Experimental Physiolgy</i>. The tutorials stress the important of multivariate analysis and provides multiple options for it's visualisation. Each tutorial can be downloaded and run locally through Jupyter Notebook or run on the cloud through Binder.
</p>

<br />
    
## Quick Start

#### *To launch the tutorial in the cloud:* [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brettChapman/multivis_tutorials/master)

#### Tutorial 1:
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brettChapman/multivis_tutorials/master?filepath=Tutorial1.ipynb)

#### Tutorial 2:
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brettChapman/multivis_tutorials/master?filepath=Tutorial2.ipynb)

#### Tutorial 3:
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brettChapman/multivis_tutorials/master?filepath=Tutorial3.ipynb)

#### Tutorial 4:
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brettChapman/multivis_tutorials/master?filepath=Tutorial4.ipynb)

#### Tutorial 5:
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brettChapman/multivis_tutorials/master?filepath=Tutorial5.ipynb)

<br />

## Download the notebook from Binder

To download the notebook (as changes to the notebook are lost when the Binder session end):
    1. Return to Jupyter landing page, by choosing "File" then "Open.."   
    2. Click the checkbox next to each file you wish to download   
    3. Click the 'Download' button from the top menu   

## Create a Local Copy:

#### Step 1. Install Jupyter and Python using Anaconda

1. Go to the [Official Anaconda Website](https://www.anaconda.com/distribution/) and click the 'Download' button. 
2. Press the 'Download' button under the 'Python 3.7 version' in Bold to download the graphical installer for your OS. 
3. After the download has finished, open (double-click) the installer to begin installing the Anaconda Distribution
4. Follow the prompts on the graphical installer to completely install the Anaconda Distribution (The final page is 'Thanks for installing Anaconda3')
5. Open the app called 'Anaconda Navigator' and press the 'launch' button in the 'Jupyter Notebook' box (to open Jupyter Notebook / confirm it was successfuly installed)
<br /><br />

#### Step 2. Create a local copy using the Anaconda Navigator app

1. Go to https://github.com/brettChapman/multivis_tutorials
2. Press the green 'Clone or Download', and then click 'Download zip'
3. Move this downloaded folder to a suitable directory (by default it is is the 'Download' folder)
4. Open the Anaconda Navigator Application
5. Move from the 'Home' tab to the 'Environment' tab (on the left side)
6. Click import (at the bottom), which opens a box called 'Import New Enviroment'
7. In 'Import New Enviroment', press the 'folder' icon and navigate to the 'environment.yml' file in the folder downloaded in step 2/3.
8. Click Import and wait for the environment to install (note: may take 5-10 minutes)
9. Return to the 'Home' tab
10. Change 'Application on... base(root)' to 'Application on... multivis_tutorials' (at the top)
11. Press the 'Launch' button under the 'Jupyter Notebook' box
12. Using the Notebook Dashboard, locate the downloaded folder in step 2/3 and open (double-click) on the 'Tutorial.ipynb'.
<br /><br />

#### Step 2. Create a local copy using Terminal / Command Prompt **(Alternative)**
1. Open Terminal on Linux/MacOS or Command Prompt on Windows
2. Enter the following into the console (one line at a time)

```console
git clone https://github.com/brettChapman/multivis_tutorials
cd multivis_tutorials
conda env create -f environment.yml
source activate multivis_tutorials
jupyter notebook
```

Note: if you recieve the following error, "fatal: destination path 'multivis_tutorials' already exists and is not an empty directory". You need to delete the 'multivis_tutorials' folder in that current directory or move to a new directory. This folder can be deleted using Terminal / Command Prompt  with:
```console
rm -rf multivis_tutorials
```

## Tutorials

1.	[Principal Component Analysis (PCA) with biplot](#one)
2.	[Hierarchical Clustered Heatmap](#two)
3.	[Polar Dendrogram](#three)
4.	[Hierarchical Edge Bundle](#four)
5.	[Spring-embedded network](#five)

<br />

<a id="one"></a>
## Tutorial 1: Principal Component Analysis (PCA) with biplot
<p align="justify">
<i>In this tutorial we will step through a workflow to produce a PCA with bitplot.</i>
</p>

Launch tutorial 1 by clicking the "Launch Binder" icon: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brettChapman/multivis_tutorials/master?filepath=Tutorial1.ipynb)

<br />

<a id="two"></a>
## Tutorial 2: Hierarchical Clustered Heatmap
<p align="justify"><i>
<i>In this tutorial we will step through a workflow to produce a Hierarchical Clustered Heatmap.</i></p>

Launch tutorial 2 by clicking the "Launch Binder" icon: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brettChapman/multivis_tutorials/master?filepath=Tutorial2.ipynb)

<br />

<a id="three"></a>
## Tutorial 3: Polar Dendrogram
<p align="justify"><i>
<i>In this tutorial we will step through a workflow to produce a Polar Dendrogram.</i></p>

Launch tutorial 3 by clicking the "Launch Binder" icon: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brettChapman/multivis_tutorials/master?filepath=Tutorial3.ipynb)

<br />

<a id="four"></a>
## Tutorial 4: Spring-embedded network
<p align="justify"><i>
<i>In this tutorial we will step through a workflow to produce a Spring-embedded network.</i></p>

Launch tutorial 4 by clicking the "Launch Binder" icon: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brettChapman/multivis_tutorials/master?filepath=Tutorial4.ipynb)

<br />

<a id="five"></a>
## Tutorial 5: Spring-embedded network
<p align="justify"><i>
<i>In this tutorial we will step through a workflow to produce a Hierarchical Edge Bundle.</i></p>

Launch tutorial 5 by clicking the "Launch Binder" icon: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brettChapman/multivis_tutorials/master?filepath=Tutorial5.ipynb)
