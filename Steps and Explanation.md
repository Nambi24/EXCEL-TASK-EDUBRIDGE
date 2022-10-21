# EXCEL-TASK-EDUBRIDGE

For excel we have to get the input and we have to first sort the columns.

We have to find the duplicate values by applying this formula like=IFERROR(INDEX([[Customer name ]],MATCH(0,COUNTIF(B1:$B$1,[[Customer name ]])+IF(COUNTIF([[Customer name ]],[[Customer name ]])>1,0,1),0)), "")

Then we have the result of duplicate values in it.

