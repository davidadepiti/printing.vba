# printing.vba
This prints a job directly on your default printerr
Sub PRINTNOW()
'
' PRINTNOW Macro
' this send job to the default printer
'

'
    ActiveWindow.SelectedSheets.PrintOut From:=1, To:=1, Copies:=1, Collate _
        :=True, IgnorePrintAreas:=False
End Sub
