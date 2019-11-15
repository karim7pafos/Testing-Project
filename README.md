# Testing-Project
Testing web services, apps, and programs
adding VBscript to reverse a string:

Dim myStr
myStr = "QAInsights"
  For i = 1 to Len(myStr)
    getChr = mid(myStr,i,1)
    output = getChr + output 
  Next
MsgBox output
