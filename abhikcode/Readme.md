# Automated Code to Build and search a Chemistry database using Mongo DB.

Scripts taken from Matt Swain https://github.com/abhik1368/mongodb-chemistry
The scripts generates databasen adds fingerprints and perform search.

 To build a database
 * db_build.py  
 * addfps.py
 * query.py


A small dataset is given in data directory to test 

## Usage

python db_build.py -h

python db_build.py --i benzodiazepine.smi --tag chembl_id --fpname mfp1 morgan

python addfps.py
python addfps.py --db moltest --fpSize 1024 --fpname mfp2 morgan

python query.py
python query.py --db chemtest --smi 'CC1=NN=C2N1C3=C(C=C(C=C3)Cl)C(=NC2)C4=CC=CC=C4' --fpSize 512


Check the Readme.pdf for usage or email abhik1368@gmail.com 

