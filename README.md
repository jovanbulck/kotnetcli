kotnetcli
=========

An easy automated way to log in on Kotnet.

Installation
-----

You can either install the dependencies and run the python file, or skip
that and just download the binary. Currently, we only support 64-bit
Linux. If you decide to download the binary, skip steps 1 and 2.

1. Install the dependencies: `python-mechanize`:
  - Ubuntu: `sudo apt-get install python-mechanize`
  - Arch: `sudo pacman -S python2-mechanize`
  - Pip: `sudo pip install mechanize`
2. Clone this repository
3. Create the file `credentials.py` in the `kotnetcli` directory, and
put this data in it:

        gebruikersnaam = "s0123456"
        wachtwoord = "w4chtw00rd"

4. Mark kotnetcli.py as executable: `chmod +x kotnetcli.py`
5. Run kotnetcli.py: `./kotnetcli.py` (or `python kotnetcli.py`)

You can add this command to your autostart programs to log in to Kotnet
at boot-time.
