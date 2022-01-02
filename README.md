# PDARandomData
Programming for Data Analysis - Semester 2 -  2021


<br/>

## Investigating and Simulating Real World Data

<br/>

***

## Overview

***

 - Repository 
   - README.md
   - requirements.txt


- Data Analysis Notebook
  - Review of Datasets
  - Investigation of Dataset Choosen
  - Plotting 
  - Numerical Review
  - Simulation of Data

<br/>

***
## Repository Contents

![atl text](Images/Filing_Cabinat.PNG)

[1]

This repository includes:

- Data Analysis Notebook - jupyter notebook

- Initial Searchs (Links) - jupyter notebook

- requirements.txt 

- Brief Folder

- Data Folder

- Image Folder

- Potential Dataset

- README.md

- gitignore


<br/>

***

## Purpose of this Repository

The purpose of this respository is to investigate a real world dataset, plot the data and simulate a random dataset matching the properties.

I wanted to review a dataset of Human intereactions or Human events, I reviewed initial datasets but choose a dataset based on the Birth Rate in Ireland from 2008 - 2020.

This dataset was broken down by years and also number of other previous born children per Monther. There is also data points for the number of Children born outside of Marriage and Civil Partnership.


<br/>

### Python Installation

To complete this Repository I used Python, specifically Anaconda. Installing this allows you to use Python directly, with a code editor or with Jupyter Notebook.

This project was completed with a mix of both, Visual Studio Code, a code editor and also Jupyter Notebooks, which were launched using command line, with the Notebook opening in an internet browser (this will open in your default browser).


<br/>

> To install and use Python you can download it directly [here](https://www.anaconda.com/products/individual)

You can install this on your Windows, Mac or Linux OS

[2]

<br/>

### Additional Requirements

(Please note that these specifications are for Windows and may differ for the other OS)

It is also recommended that you should also install the following along side Anaconda:

> [Visual Studio Code](https://code.visualstudio.com/) - This is a code editor and will allow you to create and view the code. 


> [CMDR](https://cmder.net/) - which will allow you to access the terminal on your computer - you can use this as an alternative command line. Through this you can push commands to run the code on your device.


> [Git](https://git-scm.com/) - Which will allow you to connect with Guthub and Fork this respository


> [Github.com](https://github.com/) - this is where the repository is stored and from here you can acccess the repository. You can fork a copy of the respository to your Github account.

[3][4][5][6]

<br/>

### Accessing Git Hub


When you have installed Anaconda and the additional required programs you can then fork or clone github - this allows you to take a copy of this repository and save it to your computer where you can interact with the code - running it, changing it, and testing different parts of it. 

None of these actions you make to this copy effects the repository.

Forking:

![alt text](Images/FrkGitHub.PNG)

You will find this fork symbol on the top right of the repository. From here you can make a copy of the repository - this saves to your own GitHub account. Now you have a copy of the repository to review on Github.

You can also star the repository allowing you to save the repository to come back to.

Cloning:

![alt text](Images/Clone_https.PNG)

Using the clone method you can save a copy of the repository to your own device. 

Open CMDR :

Using commands `cd ` navigate to the folder you want to save the file.

Once in the file location use the following commands:

`git clone` plus the HTTPS address

You will now have a copy of the repository on your computer.

[7][8][9]

<br/>

### Libraries Used

For this project I have used the following librares within Python:

-  `NumPy`, which is numerical python

-  `Pandas`, which allows us to create dataframes and is a step up from the numerical capablities of `NumPy`

- `Matplotlib`, which I review and use for plotting

- `Seaborn`, which is built on `Matplotlib` and expands on its capabilities

- `Scipy`, which allows for use to analyise data

- `Fitter`, which identifies distributions

<br/>

***

If you do not either have the space on your device for this full Python download Install or are perhaps reviewing this Repository as a starting point for Python and Jupyter Notebookes, I have also included below the details to access the notebooks without downloading Anaconda.


***

<br/>

## Jupyter Notebooks

This project was completed using [Jupyter Notebooks](https://jupyter.org/).

Jupyter can be launched via CMDR and works through your browser. This is an open source notebook that allows you to run your code, testing it, changing it and viewing the outputs in one place.

It is visually clean, and allows for the users to view the code and outputs clearly and in one linear space.

Navigate in your CMDR to the file you would like to open your notebook and type either Jupyter Notebook or Jupyter Lab.

These will launch a notebook via your browser - you can then create a new file - choosing the Python 3 option. This is an interactive Python page which allows you to run and save code.

This is now an interactive Jupyter Notebook.

When you are finished within the notebook you can use `CTRL S` - saving the file, and close the browser.

Then in CDMR use `CTRL C` to close the notebook browser which will continue to run in the background.


Jupyter Notebooks are comprised of cells, in each cell there will be either code or markdown text (text outling the project /code). To click down through each cell, which also action each cell click `Shift` & `Enter`.

You will also find a range of options along the top of the notebook which provide additional funactionality (note there is slight differences between Jupyter notebook and lab).

By choosing Kernal - Restart & Run All, will clear all outputs and rerun the entire notebook.

When you view the notebook using this method you will be able to make changes to the code, change outputs and save this new version.


For additional information on Jupyter Notebooks please review [here.](https://www.dataquest.io/blog/jupyter-notebook-tutorial/)

[9][10]

### Viewing & Running Notebooks
<br/>

As outlined above if you do not want to install Anaconda you can run the notebook in both an online viewer and also in Binder which will allow you to interact with the code without changing the notebook.

<br/>

NBViewer offers a static overview of the notebook - here you can view the code but there is no ability to interact with the code or run the code.


[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/VCurry20/PDARandomData/tree/main/)


[11]

<br/>

Binder offers users the choice to interact with the code without needing any installation of the above listed programs to your device. 

You can change the code - run the code - amend the code. None of this will be saved and allows you the opportunity to test with no reprocussions.

Also when accessing the notebooks using binder you can use the same commmands to work through the cells as those used directly in a Jupyter Notebook.

This is a link to the overall project:

[![Binder](https://mybinder.org/badge_logo.svg)](https://hub.gke2.mybinder.org/user/vcurry20-pdarandomdata-2djh8nqo/lab)

[12]

<br/>

### Action Binder Notebook

When the notebook opens you will that the files within the repository are listed along the left handside:


The .ipynb are the Jupyter notebooks - click on these files to open the notebook:

- action the cells by clicking 'SHIFT' and 'ENTER'


- click into the cells to change the code


All outputs of code will appear underneath the cells the code is written into.

Also you can download the code from page to your device.

None of the tests you run on this binder link will save to or amend the original repository.

<br/>


<br/>

***
References:

***

[1] Filing Cabinat Image, https://media.istockphoto.com/photos/vintage-wooden-cabinet-with-multicolor-labels-picture-id1162597226?k=20&m=1162597226&s=612x612&w=0&h=8MeTr597u3y7nvSOpP1QqYE--U54LdglyxqoZ-WtaKg= 

[2] Anaconda, Individual Edition, (2021) https://www.anaconda.com/products/individual 

[3] Visual Studio Code, main page, (2021) https://code.visualstudio.com/ 

[4] Cmder, main page, (2021) https://cmder.net/ 

[5] Git, main page, (2021) https://git-scm.com/ 

[6] Github, github main page, (2021), https://github.com/ 

[7] Fork Image from git hub repository -screen snip https://github.com/VCurry20/FDAProject2021/blob/main/Images/FrkGitHub.PNG 

[8] Clone Image, screensnip, https://github.com/VCurry20/PDARandomData/blob/main/Images/Clone_https.PNG 

[9] Tools QA, Difference between Git Clone and Git Fork, (7th July 2021)   https://www.toolsqa.com/git/difference-between-git-clone-and-git-fork/ 

[9] Jupyter, Main page, (2021) https://jupyter.org/ 

[10] Data Quest, How to use Jupyter Notebook in 2020: A beginner’s tutorial, (24th Aug, 2020) https://www.dataquest.io/blog/jupyter-notebook-tutorial/ 

[11] nbviewer, main page, (2021) https://nbviewer.org/ 

[12] binder, main page, (2021) https://mybinder.org/ 

