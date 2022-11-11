##### twlviewer

The twlviewer package can be used to open and view the results from TWL processing. 

## 1. Installation

### 1.1 Download or clone the **twlviewer** repository

**download option** - navigate to the latest release `(v1.0)` on the RHS of the root project page and download and unzip the source code.

**clone option** - from your local machine clone the repository from its GitHub address https://github.com/NOC-EO/twlviewer


### 1.2 Create an environment with Anaconda

To run the code in the project you need to install the required Python packages in an environment. To do this we will use **Anaconda**, which can be downloaded [here](https://www.anaconda.com/download/).

Open the Anaconda prompt (in Mac and Linux, open a terminal window) and use the `cd` command (change directory) to the directory where you have installed the **SAR-TWL** repository.

Create a new environment named `sartwl` with all the required packages and activate this environment by entering the following commands:

```
>>> conda env create --file env/environment.yml
>>> conda activate twlviewer
```

If you have successfully activated `twlviewer`, your terminal command line prompt will now start with `(twlviewer)`.


## 2. Running the code

In the terminal window opened in the **twlviwer** directory enter the following command:

```
>>> jupyter notebook
```

This will open a iPython session in your brower where you can run the cells and view your data
