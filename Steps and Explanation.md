# EXCEL-TASK-EDUBRIDGE


=IFERROR(INDEX([[Customer name ]],MATCH(0,COUNTIF(B1:$B$1,[[Customer name ]])+IF(COUNTIF([[Customer name ]],[[Customer name ]])>1,0,1),0)), "")


