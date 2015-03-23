#In order to remove the \n newline token at the end of the subject you can run the following command
printf %s "$(< invite_user_subject.txt)" >invite_user_subject.txt
