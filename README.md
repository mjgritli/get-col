# get-col
This script helps you print a column with awk by passing column number and field seperator.

#Announcement
this repo has been migrated to a newer version, please follow the link below:
https://github.com/mjgritli/bash-filters


Copy the file to your path and make executable

### Options
- -c specifies column number, 1 is default
- -s specifies the field separator, default is space/tab
- -h print this help guide

### Usage
Piping
```
cat file | get-col # first column, space/tab seperated
cat file | get-col -c 2 # second column, space/tab seperated
cat file | get-col -c 2 -s ':' # second column, seperated with :
```
Or via stdin
```
get-col file1 file2 filen
get-col -c 2 file1 file2 filen
get-col -c 2 -s ':' file1 file2 filen
