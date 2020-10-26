# Download-OS-maker
Run the commands
$ sudo add-apt-repository ppa:cubic-wizard/release
$ sudo apt update
$ sudo apt install cubic
$ mkdir d editor
$ cd d editor
$ wget https://releases.ubuntu.com/20.04.1/ubuntu-20.04.1-live-server-amd64.iso?_ga=2.116755268.378875231.1603710019-174531754.1600589707
$ sudo passwd root

Then enter a new root password
Then open cubic
Enter the password
When prompted, select the iso
Customize to your liking*!


*I have put some files in the repository.
To activate them, run in the cubic chroot environment:
$ git clone https://github.com/cccoder123/Download-OS-maker/
$ nano /ect/apt/sources.list
At the end of each line, put universe multiverse
Run the commands (In order):
$ cd Download-OS-maker
$ sudo sh osc-1.sh
$ sudo sh osc-2.sh
$ sudo sh osc-3.sh
$ sudo sh osc-4.sh
$ sudo sh osc-5.sh

Then customise!
