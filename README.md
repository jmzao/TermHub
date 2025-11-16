###to instal TermPak do this commands in order
'''bash
pkg update -y && pkg upgrade -y && pkg install -y wget git curl

'''bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/jmzao/TermHub/main/ ./" > $PREFIX/etc/apt/sources.list.d/termhub.list

###to update
'''bash
pkg update

####Some errors occur when running `pkg update` after downloading the repository It's normal and doesn't cause any problems.
