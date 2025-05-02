# Data-preprocessing:
Internal Marks Sheet of students:

* Open the excel(marks) Sheet.  
* Apply filter to the entire sheet and select "Stream" column for filtration.
* Now select required stream("ARTS", "Science"," Commerce", "Vocational") using the filter.
* After selecting the stream hide the unwanted columns.
* Required columns are Roll No, Registration-No, Sub Name, Subject internal (if we are preparing internal sheet else consider practical marks for practical sheet) marks.
* Consider individual subjects and their marks with respective to the students roll no.'s..., and paste them in new sheet.
* Repeat the process for remaining subjects("MIL", "E1", "E2", "E3", "E4") and paste then in new sheets.
* As we have two papers for internal marks (P1 & P2) for E3 & E4 columns. 
* We have to check both the columns and select the column which contain marks in it. And use the column as internal marks.
* Paste all the individual subject columns in individual sheets.
* Arrange/Concatenate the data from all the sheets into single sheet one below the other.
* After arranging the data apply filter on all columns and sort the internal marks column in ascending order.
* Now convert the internal marks column into numbers.(select and copy the marks column and special paste then select "add" & "values" and press ok in the new column)
* Now convert the numbers into 3 digit value by using custom define cell.(select the column then right click ---> format cell---> "custom"--->"0"--->In type cell enter "000" press ok)
* Now insert a new column beside the Roll NO column and name it as "Paper code" And the paper code value of all subjects is "I1" (as it is internal sheet and if it is practical sheet then the values in that column will be P1). 
* Because the sheet contain only internal marks student. So the paper code will be "I1" for all the students. 
* Insert one more column after internal marks column name it as "AWM", These column contains marks of Absent, Withheld & Malpractice students.
* Now delete the blanks in marks column, And cut the A's, W's and M's and paste it in the new column which we named with AWM.
* Paste the AWM values("A","AA","a") in the adjucent cell of marks column named "AWM", paste them in such a waay that they are pasted immediatly after the marks cell ends.
* Now arrange the columns in order, And the order of the columns is (Roll no, Subject name, Paper code, Internal marks, AWM, Registration no). 
* Repeat the same process with the remaining streams.
