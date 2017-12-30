## Prerequisites

> Following python libraries are needed for this project
    1. gTTS (1.2.2 or greater)
    2. PyPDF2 (1.26.0 or greater)

##  Install Pip

> sudo apt-get install python-pip python-dev build-essential 
  sudo pip install --upgrade pip 
  sudo pip install --upgrade virtualenv
    
  or optionally a script form github can be used to

  wget https://github.com/manjeetbhatia/useful_files/blob/master/get_me_latest_pip.sh
  chmod a+x get_me_latest_pip.sh
  ./get_me_latest_pip.sh

## Install Libraries

> sudo pip install gTTs
  sudo pip install PyPDF2

## Get pypdf2mp3

> git clone https://github.com/manjeetbhatia/pypdf2mp3
  cd pypdf2mp3/pdf2mp3
  python pdfto_mp3.py -f "filepath" -o "outpufilename"
 
Note: It may take several minutes to output mp3 file.