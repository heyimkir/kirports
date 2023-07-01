Hello. if you are reading this, this means you probably reached the repository link for the kirports Debian/Ubuntu repo. The repo is currently adding more packages, but we will be up soon and a handy dandy repo adder script will be released soon!
how to install:
''' 
$ curl -s --compressed "https://heyimkir.github.io/kirports/KEY.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/kirports.gpg >/dev/null
$ sudo curl -s --compressed -o /etc/apt/sources.list.d/my_list_file.list "https://heyimkir.github.io/kirports/my_list_file.list"
$ sudo apt update
'''

list of packages:
code (1.79.2-1686734195_amd64)
discord (0.0.27)
minecraft (1.1.26)
