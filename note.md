- To download a file:
```
wget "http://domain.com/directory/4?action=AttachFile&do=view&target=file.tgz"
```

- `srun`: run parallel jobs

- `wc`: count the number of lines in the file. For example:
```
wc -l *.pdb*
```

- save out to a file: `>`
```
wc -l *.pdb > lengths.txt
```

- `cat`: read the content inside a file
```
cat lengths.txt
```
