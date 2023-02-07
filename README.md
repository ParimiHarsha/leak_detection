# Description
This file contains the information to set up and run the ML models on Benchmarking Hanoi Dataset(https://github.com/KIOS-Research/LeakDB/tree/master/CCWI-WDSA2018/Benchmarks)

# Python Setup Instructions
- Install the latest version of python 3.10 using your favourite installer

# Setup the Virtual Environment
1. Install conda
2. Create new virtual environment using `conda create --name venv python=3.10`
3. Activate the conda environment using `conda activate venv`
4. Install all the required packages `pip install -r requirements.txt` | 
    - Alternatively you can also run `pip-sync -r requirements.txt` which would delete unncessary packages
5. Install any other packages that you  might require and add them to the requirements.txt file

# Running the Google colab notebooks
1. To run the colab notebooks you need to add the Hanoi Dataset zip version from 
    https://drive.google.com/drive/folders/1DBUnMX31HC0V4ozoQH37Q2gYUeNqOZ8c to your Google Drive
2. Request for access for the notebooks: https://drive.google.com/drive/folders/1MO8Ww1SCXKAeARppEFBXboEbIqxJH_Y8
3. Run the cells in the given order

# Running the Local Github Notebooks
1. To run the notebooks you need to install the Hanoi Dataset from https://github.com/KIOS-Research/LeakDB/tree/master/CCWI-WDSA2018/Benchmarks
2. Unzip the file and store it in your local disk or external hard disk(This is large dataset with size ~25GB)
3. Assign the path of the data folder to the the raw_path variable in the cell no. 2 of the notebook
4. Run the cells in the given order

Note: Local Notebooks are not upto date. They were primarily used in the initial testing phase of the project. They also take a 
      lot of CPU memory and storage to run. Hence it is suggested to use the colab notebooks for replicating this work.
      
# Contributions to the repo 
- Any contributions to the repo are hightly encouraged
- Raise a PR for the intented change and wait till it gets reviewed
- In case of any issue reach out to me @ParimiHarsha(Github) or parimi97@gmail.com

# Leak-Detection-Using-Machine-Learning
## Done By: 
- P V Sri Harsha
## Worked under: 
Prof. A. Vasan, Ph.D.
Professor, Department of Civil Engineering
Birla Institute of Technology & Science, Pilani
Hyderabad Campus

