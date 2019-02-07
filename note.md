- To download a file:
```
wget "http://domain.com/directory/4?action=AttachFile&do=view&target=file.tgz"
```

- `srun`: run parallel jobs

- `wc`: count the number of lines in the file. For example:
```
wc -l *.pdb*
```

- save out to a file: `>` (redirect)
```
wc -l *.pdb > lengths.txt
```

- `cat`: read the content inside a file
```
cat lengths.txt
```

- `sort`: sort the output (alphabetically sort)
```
sort lengths.txt
```
Add `-n` for numeric sort:
```
sort -n lengths.txt
```

- `bash`: run an `.sh` script
```
bash learn.sh
```
