---
name: Jonathan Rodriguez
course: Cis106
semester: Fall2023
---

# Week Report 7

## Cat Command
+ What is the command used for
  + Displaying the content of a file
+ What is the formula of the command
  + cat + option + file(s)
+ Examples
  + cat dracula.txt
  + cat -n bible.txt
## Tac Command
+ What is the command used for 
  + displaying contents of file in reverse order
+ What is the formula
  + tac + option + file(s)
+ Examples
  + tac bible.txt
  + tac todo.md
## head command
+ What is the command used for?
  + Displays top N number of lines of a given file
+ What is the formula for the command
  + head + option + file(s)
+ Examples
  + head -5 dracula.txt
  + head-10 bible.txt
## tail command
+ what is the command used for 
  + last N number of lines in a file
+ what is the formula for the command
  + tail + option + file
+ Example
  + tail -5 dracula.txt
  + tail -10 bible.txt
## cut command
+ what is the command used for 
  + extract a specific section of each line of a file
+ what is the formula
  + cut + option + file(s)
+ Examples
  + cut -d ':' -f1 /etc/passwd
  + cut -d ':' -f1,7 /etc/passwd
## paste command
+ What is the command used for
  + paste command is used for joining files horizontally
+ What is the formula for the command
  + paste + option + file(s)
+ Example
  + pase users.lst ip_address.lst
  + pase -d ":" users1.lst ip_addresses.lst
## sort command
+ what is the command used for
  + sorting files 
+ what is the formula
  + sort + option + file(s)
+ example
  + sort users.lst
  + sort -o sorted.lst users.lst
## wc command
+ what is the command used for
  + used for printing the number of lines characters, and bytes in a file
+ what is the formula
  + wc + option + file(s)
+ example
  + wc -m users.txt
  + wc -l users.txt
## tr command
+ wHat is the command used for
  + translating or deleting characters from standard output
+ what is the formula   
  + standard output | tr + option + set + set
+ example
  + cat file.txt | tr '.' ','
  + cat program.py | tr "{:space:}" '\t'
## diff command
+ wHat is the command used for
  + difference of files and displays the difference between them
+ what is the formula
  + diff + option + file1 + file 2
+ example
  + diff cars.csv cars-backup.csv
  + diff -y cars.csv cars-backup.csv
## Grep command
+ wHat is the command used for
  + search text in a given file
+ what is the formula
  + grep + option + search criteria + file(s)
+ example
  + grep 'dracula' dracula.txt
  + grep 'jesus' bible.txt
## awk command
+ wHat is the command used for
  + scripting language used for processing and displaying text
+ what is the formula
  + awk + options + {awk command} + file
+ example
  + awk -F: '{print $1}' cars.csv
  + awk -F: '{print $3,4}' cars.csv
  + awk -F: '{print $7}' cars.csv
  + awk -F: '{print $NF}' cars.csv
  + awk -F: '{print $1, " = ",$4}' cars.csv
## Sed Command
+ What is the command used for
  + stream editor that performs operations n files and standard output
+ What is the formula
  + sed options + sed script + file
+ Example
  + sed 's/pizza/rice/' shopping-list.lst
  + sed '5d' shopping-list.lst
  + sed'$d' shopping-list.lst
  + sed G shopping-list.lst
  + sed 'G;G' shopping-list.lst

