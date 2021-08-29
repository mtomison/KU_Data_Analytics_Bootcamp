# KU_Data_Analytics_Bootcamp

flowchart.funflowchart.fun
flowchart.fun

https://ku.bootcampcontent.com/
GitLabGitLab
Sign in
GitLab Community Edition

# Visual Basic
Debug.Print ("hello")
Sub datatypes()
Dim anum
Dim bnum
anum = Range("B1").Value
bnum = Range("B2").Value

If anum < bnum Then
    MsgBox ("it is less")
ElseIf anum = bnum Then
    MsgBox ("they areequal")
Else
    MsgBox ("no it is not")
    If (True = True) Then
        MsgBox ("true is true")
    End If
End If


End Sub

Sub MyMacro()
Dim choice As Integer
choice = Range("B1").Value

If choice = 1 Then
MsgBox ("option a")
ElseIf choice = 2 Then
MsgBox ("you are in a dark cave")
ElseIf choice = 3 Then
MsgBox ("you are in a sunny place")
ElseIf choice = 4 Then
MsgBox ("you are there")
Else
MsgBox ("I don't know how to do that dave")
End If

End Sub

Sub myLoop():

For i = 1 To 10
  
    Debug.Print (Cells(i, 1))
Next i
End Sub


