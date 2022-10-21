# EXCEL-TASK-EDUBRIDGE

Sneha is an MIS executive her boss provided her a list of customers in Excel as shown below

Customer name 	Duplicate name
Akshay Rathod	
Amit Kumar	
Amit Kumar	
Animesh verma	
Arti Ahuja	
Arti Ahuja	
Ashutosh Mahajan	
Eshank sharma	
Eshank sharma	
Harmeet kaur	
Kapil Khatri	
Kapil Khatri	
Mohit Jain	
Raj Sharma	
Sunil Yadav	
Swati singh	
Want to populate the Duplicate name field for names that occurs more than once. The required table is shown below

Customer name 	Duplicate name
Akshay Rathod	Amit Kumar
Amit Kumar	Arti Ahuja
Amit Kumar	Eshank sharma
Animesh verma	Kapil Khatri
Arti Ahuja	
Arti Ahuja	
Ashutosh Mahajan	
Eshank sharma	
Eshank sharma	
Harmeet kaur	
Kapil Khatri	
Kapil Khatri	
Mohit Jain	
Raj Sharma	
Sunil Yadav	
Swati singh	
Step 1: Enter the values to the excel as table formate and save it.

Step 2: In the Cell below the Duplicate Name column just do the Logic to populate the duplicate name field for names that occurs more than once

=IFERROR(INDEX([[Customer name ]],MATCH(0,COUNTIF(B1:$B$1,[[Customer name ]])+IF(COUNTIF([[Customer name ]],[[Customer name ]])>1,0,1),0)), "")
In this Logic the [[[Customer name]] is the selected value cell from the excel. Actually that is (A2:A17)

If your Excel also updated then it will display us like the column header name
