# Stockholm
A small ransomware program that affects a directory called "infection" in your /home.
The program will act only on files with the extensions that were affected by Wannacry 
and will encrypt and rename all the files in the mentioned folder adding the ".ft" extension.

Algorithm used: AES

## Requierements:
sudo apt-get install python3-tk python-crypto

## Usage:

[] Normal mode:
python3 stockholm.py

[-h] help flag:
show help message and exits

[-v] version flag:
displays program version

[-r] reverse flag:
decreypts the encrypted files

[-s] silent mode
