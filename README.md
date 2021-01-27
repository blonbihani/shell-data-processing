# INTRODUCTION TO SHELL DATA PROCESSING

## Important commands to use in Powershell
- mkdir : create a new directory
- rmdir : remove the directory
- cd : change the directory
- cd .. :change to root directory
- ni : create a new item
- ls : list items
- rm : remove item

## Important commands to use in Bash
- touch : creates a file
- pwd : print working directory
- mv : move or rename directory
- grep : search
- cat : read, create and concatenate a file
- | : pipe
- head : read the start of a file
- tail : read the end of the file
- git add. : adds files
- git commit : change record into local repo
- git push : send changes to the remote location

## Curl command to get the data from a URL

``` curl "https://blog.reedsy.com/creative-writing-prompts/contests/65/submissions/40259/" -O "testing.txt" ```

## Command to find the most common words, sorted

``` tr ' ' '\12' < testing.txt | sort | uniq -c | sort -nr > result.txt ```

## Files
- Data file: [https://github.com/blonbihani/shell-data-processing/blob/master/testing.txt] 
- Results file: [https://github.com/blonbihani/shell-data-processing/blob/master/result.txt]
