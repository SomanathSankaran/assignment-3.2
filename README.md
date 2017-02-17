# assignment-3.2
QN 1
I have created the text file max-temp.txt using cat command and entered the temperature and then checked whether that is present using "ls" and checked the details using cat command(IMAGE ASSMT-2-QN-1 AND ASSMT -2-QN-1-LS) 

QN 2 I have moved the file from local file system using "hadoop fs -put max-temp.txt(source file) user/acadgild/hadoop/"(assmt-2-qn-1 ) and checked that using hadoop fs -ls user/acadgild/hadoop/max-temp.txt (assmt-2-qn-2)

QN 3 I have changed the permission by using "hadoop fs -chmod 774 user/acadgild/hadoop/max-temp.txt" and checked that using
hadoop fs -ls user/acadgild/hadoop/max-temp.txt (assmt-2-qn-3)

