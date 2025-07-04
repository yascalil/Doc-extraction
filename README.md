for finalmdcgra
1. you put your files in the input directory
2. run dgra6v2.py
3. run metafix.py
4. run cgra3.py
5. run jsonfix3.py
6. grab the files from the folders
    a. metadata fix
    b. definitions
    c. clause fix
7. look at the input directory
8. see how the document was sorted there
9. mkdir the same as how it was
10. drop those files in that directory

python3 -m venv venv
source venv/bin/activate
pip install PyMuPDF tools tqdm anthropic dotenv frontend
python3 dgra6v2.py
python3 metafix.py
move folder defi+meta/folder into finalouput folder and delete the metadata.json and put the metadata.json from metadata folder into there
python3 cgra3.py
rename the json to clauses.json
python3 jsonfix2.py
move clauses.json from the folder clause to the finaloutput folder
keep the finaloutput
delete all the old info eg old metadata.json, old definitions.json, old clauses.json etc etc
(sorry i need to clean this part up!)

if anything in here breaks and it needs to be fixxed text / call me at +1 (424)4641078 / email gheatmc@gmail.com
or gheat@gheat.net, remeber im on california time witch is -8 hours from yours (uk) goodluck with it im happy to
help especially with the confusing finalmdcgra (its a weird thing)!
