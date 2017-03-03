# Fun-With-Encryption

Alright, so I was trying to free up some space on my hard drive because it's getting a little full (has been for a while) and I found this mysterious old crypto script. Original file creation date was Sept. 19, 2014 so I must have been a junior in college when I wrote this. It was in C:\Python27 folder. C:\Python27\README.txt revealed to me that I must have coded it in Python 2.7.6

Anyway, it looked cool so I started messing around with it and that's where you get funWithEncryption.py
I'll admit, I don't actually know which algorithm this is, though I highly doubt it's an original construction

The brunt of the script is actually command line argument parsing and output stuff. The crypto stuff really only exists in
the encryptString and decrypt functions. genKey and expKey count as well, I suppose.

Anyway, you can use it in the following ways:

python funWithEncryption.py Any number of command line arguments here it doesn't matter

The above will take your command line arguments as plain text and encrypt them

python funWithEncryption.py -o outputFileName.extension Any number of command line arguments here it doesn't matter
python funWithEncryption.py --output outputFileName.extension Any number of command line arguments here it doesn't matter

The above will take your command line arguments as plain text and encrypt them and put the encrypted hex in the specified file

python funWithEncryption.py -f inputFileName.extension
python funWithEncryption.py --file inputFileName.extension

The above will take the contents of a specified file and encrypt them

python funWithEncryption.py -f inputFileName.extension -o outputFileName.extension
python funWithEncryption.py -f inputFileName.extension --output outputFileName.extension
python funWithEncryption.py --file inputFileName.extension -o outputFileName.extension
python funWithEncryption.py --file inputFileName.extension --output outputFileName.extension

The above will take the contents of a specified file and encrypt them and put the encrypted hex in the specified file

The script funWithEncryption.py is written for Python 3.4.0 and was developed on Windows 10 with the following specs:

