
Instructions for GNU/Linux RedHat/Fedora/Oracle/CentOS
Step 1: Installing instagram-scraper
1. Route 1 (Reccomended).Open Up the Terminal and Type in.
yum install -y epel-release
yum install -y python34
# Install pip3
yum install -y python34-setuptools  # install easy_install-3.4
easy_install-3.4 pip
pip3 install instagram Scraper

You will most likley already have Python3 Installed but in case you dont I included the Command to install. Route 1 is only needed for if you want Instagram Scraper to be in the default directory and to be able to use the command instagram-scraper without specifing a full location for the executable. 



1. Route 2 (For Advanced Users). 
yum install git
git clone https://github.com/rarcega/instagram-scraper.git
cd /home/osusername/instagram-scraper/
python3 setup.py install

This will create a folder in your Home Directory where you can manually run the programme from. You will need to specify the full location of the instagram-scraper executable. 

Step 2: Install Java
su -c "yum install java-1.8.0-openjdk"

Step 3: Download the GUI
git clone https://github.com/Asbestosstar/instagram-scraper_gui.git

Step 4: Make sure it is executable
cd /home/osusername/instagram-scraper_gui/
chmod +x Instagram-Scraper_GUI-ver.jar     (replace ver with the version number)

Step 5: Make sure you have a Desktop Eviroment
In order to run Most GUI Software you must have a Desktop Enviroment such as GNOME, XCFE, or MATE 


Step 6: Run the GUI
Instagram-Scraper_GUI-ver.jar     (replace ver with the version number)
