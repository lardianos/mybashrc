############################

lardianos   

# bashrc custom file 

############################

first install the fonts


# sudo apt-get install fonts-powerline

after if you havent, install git

# sudo apt-get install git

then go in user directory

# cd ~ 
or
# cd /home/"username"/

make buckup of the old bash rc file

# cp .bashrc .bashrc.old

download the new bashrc file from git

# git clone https://github.com/lardianos/mybashrc

at last, overwrite the bashrc file with the new bashrc file

# cp mybashrc/bashrc .bashrc

after install remove usless files

# sudo rm -r mybashrc

close and open again the terminal.
you are ready!

