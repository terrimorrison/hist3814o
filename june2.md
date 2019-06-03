    1  curl http://archive.org/stream/diplomaticcorre33statgoog/diplomaticcorre33statgoog_djvu.txt > texas.txt
    2  curl http://archive.org/stream/diplomaticcorre33statgoog/diplomaticcorre33statgoog_djvu.txt > texas2.txt
    3  nano texas.txt
    4  terrimorrison@d12b0858c9d9:~$ nano texas.txt
    5  grep '\bto\b' texas.txt
    6  grep 'to' texas.txt
    7  ~
    8  sed -r -i.bak 's/(.+\bto\b.+)/~\1/g' texas.txt
    9  ls
   10  nano texas.txt
   11  history > june2.md
