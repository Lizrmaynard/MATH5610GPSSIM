# MATH5610GPSSIM

The codes could be ran as followed (using b12.dat for example):

cat b12.dat | java vehicle | python3 satellite.py | python3 receiver.py

or

cat b12.dat | java vehicle | python3 satellite.py | java receiver

or

cat b12.dat | java vehicle | java satellite | python3 receiver.py

All of which should result in the desired outputs.

vehicle is a java script and is designed by Peter W Alfeld for the purposes of the given class assignment, and the associated data files are also created by him.

java satellite and java receiver are also designed by Peter W Alfeld to give a basis of what the desired output should look like to ensure the student written code works properly.

receiver.py and satellite.py are codes written by Elizabeth Maynard and Morgan Kelley for the purposes of aforementioned assignment. DAT files are meant to be fed into the vehicle, then the satellite, then the receiver as shown above. 
