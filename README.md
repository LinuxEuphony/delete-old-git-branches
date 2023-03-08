# delete-old-git-branches

<br>

![GitHub issues](https://img.shields.io/github/issues/LinuxEuphony/delete-old-git-branches?&labelColor=black&color=eb3b5a&label=Issues&logo=issues&logoColor=black&style=for-the-badge)
![GitHub Contributions](https://img.shields.io/github/contributors/LinuxEuphony/delete-old-git-branches?&labelColor=black&color=8854d0&style=for-the-badge)
![repo size](https://img.shields.io/github/repo-size/LinuxEuphony/delete-old-git-branches?label=Repo%20Size&style=for-the-badge&labelColor=black&color=20bf6b)
![GitHub forks](https://img.shields.io/github/forks/LinuxEuphony/delete-old-git-branches?&labelColor=black&color=0fb9b1&style=for-the-badge)
![GitHub stars](https://img.shields.io/github/stars/LinuxEuphony/delete-old-git-branches?&labelColor=black&color=f7b731&style=for-the-badge)
![GitHub LastCommit](https://img.shields.io/github/last-commit/LinuxEuphony/delete-old-git-branches?logo=github&labelColor=black&color=d1d8e0&style=for-the-badge)

<br>

This is an automated bash script to delete git branches older than some specific time period. The default set time is 4 months, but you can pass the period in months as a first parameter while running the shell script

----

<br>

# How to download the script


## GIT Clone Option
  1. Navigate to your preferred directory
  2. Run terminal
  3. Type **git clone https://github.com/LinuxEuphony/delete-old-git-branches** to clone repository
  4. Navigate to the folder named **delete-old-git-branches**


## Github Download Option
To download and use this script:
  1. Click on *`code`* on this page.
  2. Click on *`Download Zip`*.
  3. A files named *`delete-old-git-branches-main.zip`* will be downloaded. Extract the zip file in your computer. You will see a folder labelled *`delete-old-git-branches-main`*. 
  4. Navigate to that folder.
  
  
  ----
  
  <br>
  
  # How to run the file

  1. Navigate to and edit the file named **`delete-old-git-branches.sh`**. Replace the value **`YOUR_REMOTE_OR_LOCAL_GIT_URL`** on line **`13`** with your remote/local git url.
  2. Open the terminal inside the, or navigate through terminal into the folder named **`delete-old-git-branches-main`**
  3. Type **`chmod +x delete-old-git-branches.sh`** and click on `enter key` to make the script executable.
  4. Type **`./delete-old-git-branches.sh`** to run the script.

<br>
 
 ## Run options
  
  1. Below will run with the default 4 months period.
  
    ./delete-old-git-branches.sh
  
  2. Below will run with preferred timeline set.
  
    ./delete-old-git-branches.sh 3
  
  3. Below will run with default 4 months period and force delete unmarged branches enabled.
  
    ./delete-old-git-branches.sh -f
    
  4. Below will run with the preferred time set and force delete unmarged branches enabled.
  
    ./delete-old-git-branches.sh -f 3
  
</br></br>


