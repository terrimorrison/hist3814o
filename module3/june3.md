    1  grep '~' texas.txt > index.txt
    2  nano texas.txt
    3  sed -r -i.bak 's/(,)( [0-9]{4})(.+)/\2/g'index.txt 
    4  sed -r -i.bak /(,)( [0-9]{4})(.+)/\2/g'index.txt 
    5  sed -r -i/bak 's/(,)( [0-9]{4})(.+)/\2/g' index.txt
    6  sed -r -i.bak 's/(,)( [0-9]{4})(.+)/\2/g' index.txt
    7  history>june3.md
    8  history > june3.md
