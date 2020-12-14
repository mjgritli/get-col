# get-col
This script helps you print a column with awk by passing column number and field seperator.

Author: Mohammed Griti <mjgritli>

### Options
- -c specifies column number, 1 is default
- -s specifies the field separator, default is space/tab
- -h print this help guide

### Usage
```
cat file | get-col # first column, space/tab seperated
cat file | get-col -c 2 # second column, space/tab seperated
cat file | get-col -c 2 -s ':' # second column, seperated with :
```
