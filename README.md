# Dat_490_Capstone
Repository Structure and Overview:
- Data_Tables:
Holds base tables used throughout the entire project as well as cleaned and reformatted tables for the various models
- EDA:
Contains the notebooks used for EDA on batter performance by age and level, as well as, pitcher performance by age and level
- Base_Model_Performance:
Original models developed during the methodology portion of the project for batters and pitchers project performance in the Major Leagues
- Base_Model_Prediction:
Original models developed during the methodology portion of the project for batters and pitchers predicting promotion from MiLB to MLB
- Optimized_Model_Performance
Fine tuned models for batters and pitchers projecting performance in the Major Leagues
- Optimized_Model_Prediction
Fine tuned models for batters and pitchers predicting promotion to the Major Leagues

For Group Members To Add Files & Data Tables:
1. Download and install Git on your local machine: https://git-scm.com/downloads

2. Once git is installed configure your identity:
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
** Use the same name / email this repository was shared to, most likely your ASU email

3. Clone the repository, I recommend your Desktop:
cd $HOME\Desktop
git clone https://github.com/YourOrg/DAT_490_Capstone.git
cd DAT_490_Capstone

4. Copy your Juypter Notebooks and relevant data tables to the appropriate directory. Within the Data_Tables, EDA, Base_Model_X, and Optimized_Models_X is a subdirectory for Batters and Pitchers. You can copy the Notebooks directly into the new DAT_490_Capstone as well as any intermidiary data tables created for your models however you would like. For example on windows just open two file explorers and drag and drop your files from one directory to another

5. Once you have added all of your files run the following commands:
git status
git add .
git status (should have different output from previous command)
git commit -m "your_name added my relevant files and data tables"

This will update the local repository with all of your changes

6. Synch your local changes with the remote repository:
git push origin main


