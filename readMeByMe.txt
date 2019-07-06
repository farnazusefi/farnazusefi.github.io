go to the directory that contains index.html file on your system

cd Desktop/APPLY\ STUFF/Farnaz\'s\ Homepage/

copy the index.html file to the server 

scp index.html faryousefi@ce.sharif.edu:~/public_html/

password: feriusid

to copy a directory 

scp -r ~/Farnaz\'s\ Homepage/ faryousefi@ce.sharif.edu:~/public_html/