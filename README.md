Task 1
For this task I downloaded a csv file about Onboarding With Username(https://support.staffbase.com/hc/en-us/article_attachments/360009197031/username.csv) I uploaded the file to one of my GitHub repositories

I downloaded it in my linux terminal from there via the following command: wget https://support.staffbase.com/hc/en-us/article_attachments/360009197031/username.csv
I showed the first 10 lines of the csv via the following command: head -n 10 username.csv
I showed how many items there are in the csv via the following command: wc -l username.csv
I showed the first and third column of the csv via this command: awk -F ";" '{print $1" "$3}' username.csv 
I add the output and the command to a text filevis this command: command > output.txt 

Task 2
For this task I created a script file "myscript.sh", put the commands I used in the previous task into it, and executed it.

I used the following command to create the mycript.sh file: touch myscript.sh
I used the following comand to print the string: echo
I used the following command to prepare the file for execution: chmod +x myscript.sh
I used the following command to execute the file: ./myscript.sh
