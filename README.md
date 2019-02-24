#!/bin/bash/

# install git on your devices by running the follwoing command on terminal 
apt-get install git -y

# make a directory labelled as lab2 (you know these commands)
mkdir lab2 
cd lab2

# open the github link you are given and register as a student
# now there is a green button labelled as (clone)... copy the link from there
# make clone of the link of repo by running the following commands (replace url with the copied link)
git clone url

# congratualtions the online reposotory will be downloaded
# now cd to downloaded directory
# forexample 
cd lab2-your_name

# boom you'll get the structure of folders now 
# all you need to do is fill that structure with the details given in lab.txt
# when you are done with all the tasks just run this command to submit it

git add . && git commit -m "first attempt"
git push origin master
