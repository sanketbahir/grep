# grep
grep:=> global regular expression print

grep name fliename {using this commend we can get whole line of name}
grep -i( here i satnds for ignore ) name filename {using this cmd we  can get output without  having issue of upper or lower case }
grep -iv name filename (iv stands for this things we dont want and it will returen other things)
grep -c name filename {it will return us the count of name how meny time it is used like 7 or 8 times}
grep -w name filename {we use -w for find exat word  }
grep -n  name filename {it will return the line  number of the name}
grep name file1 file2 file3  {it will find the name in multipal files}
grep -h name filename {it will just the content without file  name}
gerp -e name -e name filename { it will check multipal name  in single commend}
gerp -e name -e name filename1 filename2 { it will check multipal name in a single commend in multipal files}
grep -l name  file1 file2  {it only prints the file names which matches given key word}
grep -l -e name -e name  filename1 filename2 filename3 {we use this commend to check multipal names in multipal files}
grep -f txtfilename filename1 filename2 filename3{in this  code we create a file.txt and we put all name in it and we put grep -f and file.tx and the file name we want to search}
grep "^103" filename {it will return the hole content of id}
grep "Doctor$" file name {it will return the  line which ends with the matching keyword}
grep -R -f txtfilename nameOfFolder/ {here -R -f file name with folder name and its search name in the whole folder}
egrp "name1|name2|name3" filename {it will search all three name in one file}
grep -q name file name {to get without  print echo $ = 0 means we have the name and echo $= 1  we did not get}
grep -qs name file name {to supress error message }
ls | grep nameoffile {it will  search  related file in folder}
