# Install

    $ sudo mkdir /usr/share/fonts/truetype/sourcesanspro
    $ sudo cp -r target/TTF/* /usr/share/fonts/truetype/sourcesanspro/

# Check it works

    $ fc-list | grep -i "Source Sans Pro"

# Uninstall

    $ sudo rm -r /usr/share/fonts/truetype/sourcesanspro
