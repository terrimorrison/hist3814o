    url http://archive.org/stream/diplomaticcorre33statgoog/diplomaticcorre33statgoog_djvu.txt > texas.txt
    nano texas.txt
    terrimorrison@d12b0858c9d9:~$ nano texas.txt
    grep '\bto\b' texas.txt
    grep 'to' texas.txt
    ~
    sed -r -i.bak 's/(.+\bto\b.+)/~\1/g' texas.txt
    ls
    nano texas.txt
    history > june2.md
