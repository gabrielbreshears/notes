# Command Line

## Getting out of trouble

- Remember to `ctrl` + `C`
- Use **man** + **name of command here**, man will provide a description as to what the command does. Sometimes it won't make much sense but hey, the more you know


## Terminal Shortcuts

- `control` + `A` Jump to beginning
- `control` + `E` Jump to end
- `control` + `U` Deletes everything


## Commands

- `echo`  write arguments to the standard output
- `man` Stands for manual, provides description of a command and much more! Do `man` + `man` to find out
- `clear` or `control` + `L`: clears the terminal
- `exit` or `control` + `D`: exits the terminal
- `cat` short for "concatenate”, dumps the the contents of a file on screen
- `diff` comparison of files that are similar but not identical. When there is no diff between two files, output is nothing
- `ls` list directory contents
- `mv` renames file
example: `mv test.txt text2.txt`
- `rm` deleting a file
- `cp` copy example: same as mv
- `touch` create a file (its real use it to change both modification and access times)
- `head` displays first 10 lines of files
- `tail` you know what this does
- `wc` word count displays how many lines, words, and bytes (in that order!) of a text


## Useful Optional Forms Examples

`*.txt` The `*` stands for wildcard. In this case the commands list any files that ends in `.txt`
Who can use it? `ls`, `rm`, etc

`-i` conformation about `rm`,`cp`,etc

### `ls`

`-l`: long format

`-rtl` list by reversed time of modification (long format)

Example:  `ls -l *.txt` => list long format of any file in the directory that ends in .txt

`-a` show hidden files
`-h` human readable

### `head` + `tail`

`-n 20` defaults shows first 10 lines `-n` allows you to specify



## Creating files on the command line

```
echo "It's the questions we can't answer that teach us the most. They teach us how to think. If you give a man an answer, all he gains is a little fact. But give him a question and he'll look for his own answers" > theWiseManFear_1.txt
```
`>` the redirect operator
- the `>` takes the string output from `echo` and redirects the content to a file called `theWiseManFear_1.txt`

`>>` append operator


## Curl!
Curl can do a LOT will need to investigate more

-`curl` allows us to interact with a URL in the command line and so much more!


### Curl Flags

`-I` Fetch the headers only! HTTP-servers feature the
              command  HEAD which this uses to get nothing but the header of a
              document. When used on an FTP or FILE file,  curl  displays  the
              file size and last modification time only.
## Random


- The first directory => /Users/"nameOfUser"

- Type in **yes** in the terminal,
