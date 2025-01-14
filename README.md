# Automate the Noip-Dynamic-Update-Client Installation and Noip Startup Process in Ubuntu LTS

[Watch the video guide](https://youtu.be/YmCwn6cYFAE)

<!--<iframe width="560" height="315" src="https://www.youtube.com/embed/YmCwn6cYFAE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>-->

## A simple script that will automate the download, install and configuration (with user input for login and domain setup) of the Noip Dynamic Update Client for Ubuntu Linux as well as create a systemd startup process for the client running on Ubuntu LTS.


### For Ubuntu cli:

#### Prerequisite 
##### Install Zip:

``` sudo apt install zip -y ```

``` mkdir noip && cd noip ```

----------------------------------------------------------------------------------

#### Download the script and extract:

``` sudo wget https://github.com/clickonrefresh/Automate-Noip-DUC/archive/main.zip  ```

``` sudo unzip main.zip ```

##### OR (mirror):

``` sudo wget https://www.procrastinator.me/cloud/mirrors/Automate-Noip-DUC-main.zip  ```

``` sudo unzip Automate-Noip-DUC-main.zip ```

----------------------------------------------------------------------------------

#### To run the script, navigate into the extracted folder:

``` cd Automate-Noip-DUC-main ```


#### Run:

``` sudo bash noip-duc.sh ```

----------------------------------------------------------------------------------
----------------------------------------------------------------------------------

##### Tested on:
- Ubuntu 20.04 LTS
- Ubuntu 18.04 LTS
- Ubuntu 16.04 LTS

[Make remote access, managed DNS and SSL encrytpion easy with a Noip.com account, free and paid options](https://www.noip.com?fpr=clickonrefresh)
