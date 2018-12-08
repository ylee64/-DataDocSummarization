## Getting the data using git lfs 
You need to install git lfs to use the data in the directory. 

1. Create a directory in your home directory and name it anything you'd like    . It will hold the files to install git lfs. 
 
2. Inside the directory, download the installation package. 
    ```
    wget https://github.com/git-lfs/git-lfs/releases/download/v2.6.1/git-lfs-linux-amd64-v2.6.1.tar.gz
    ```  
3. Untar the file 
    ```
    tar -xvzf git-lfs-linux-amd64-v2.6.1.tar.gz
    ```
4. Then run the install.sh file
    ```
    sudo bash install.sh
    ``` 
5. Once git lfs is installed, you will want to clone the data repo
    ```
    git clone https://github.com/ylee64/DataDocSummarization.git
    ```
