# -arrRecords-_GetRecords
$arrRecords = _GetRecords("TestTable",$arrSelectFields) _ArrayDisplay($arrRecords)  ;Retrieve Records from Table with Where Clause Dim $arrWhereFields[1]=["Firstname = 'Dave'"] $arrRecords = _GetRecords("TestTable",$arrSelectFields,$arrWhereFields)
