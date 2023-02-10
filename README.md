# learn_bash_script_by_building_five_program

Create the bingo, fortune, questionnaire and the countdown file one by one.
Key in touch file_name.sh in the terminal to create a bash script file.
Add shebang at the top most line of each file.
Key in chmod +x file_name.sh in the terminal to get executable permission.
Key in the code as instructed. See each file for the codes.
Run the script after finishing writing the code in the file editor. Type ./file_name.sh in the terminal to run the script. 
Type help / man in the terminal to check out how to write the code in the file editor. 

questionnaire Script

To use the shell interpreter, enter sh questionnaire.sh in the terminal. 

To use the bash interpreter, enter bash questionnaire.sh in the terminal. The bash stands for bourne-again shell.

To search for the location of the bash, enter which bash in the terminal
The return is usr/bin/bash whcih is the absolute path to the bash interpreter. 

When the script is run by executing ./file_name.sh in the terminal, the default is bash instead of sh.

To list the files inside the project folder, enter ls -l in the terminal 

Create VARIABLE_NAME=VALUE in the file editor
The value is enclosed with a double quotation mark. 
Enter read command. For example read VARIABLE_NAME
To use the function, key in echo $VARIABLE_NAME

To enter a title in the file editor
Key in the code below which will set a space in between the title; above and below

 echo -e \n~~ script_title ~~\n

To enter a sentence with and empty line at the beginning

  echo -e "\n<text>"




