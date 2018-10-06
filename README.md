# dump2csv
A command line to convert mysqldump file to csv and sql file
## Usage
```command
dump2csv -s <dump filename>
```
or
```command
dump2csv --source <dump filename>
```
## Todo
Fix this issue: if table data contains text fields that contain the sequence of characters `),(` ,`awk` will split that field across multiple record lines.
