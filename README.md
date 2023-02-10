# learn_bash_script_by_building_five_program

Instruction on how to write the script:

Create the bingo, fortune, questionnaire and the countdown file one by one.

Key in touch file_name.sh in the terminal to create a bash script file.

Add shebang at the top most line of each file.

Key in chmod +x file_name.sh in the terminal to get executable permission.

Key in the code as instructed. See each file for the codes.

Run the script after finishing writing the code in the file editor. Type ./file_name.sh in the terminal to run the script. 

Type help / man function_name to search in the terminal to find out how to write the code in the file editor. 


Questionnaire Script

To use the shell interpreter, enter sh questionnaire.sh in the terminal. 

To use the bash interpreter, enter bash questionnaire.sh in the terminal. The bash stands for bourne-again shell.

To search for the location of the bash, enter which bash in the terminal.

The return is usr/bin/bash which is the absolute path to the bash interpreter. 

When the script is run by executing ./file_name.sh in the terminal, the default will be bash instead of sh.

To list the files inside the project folder, enter ls -l in the terminal; long list

Create VARIABLE_NAME=VALUE in the file editor.

Enclose the value with double quotation marks.

Enter read command VARIABLE_NAME.

To activate the variable, key in echo $VARIABLE_NAME in the terminal

To enter a title in the file editor, key in the code below which will set a space in between the title; above and below

 echo -e \n~~ script_title ~~\n

To enter a sentence with and empty line at the beginning, leave out \n at the end of the sentence or text. 

  echo -e "\n<text>"




