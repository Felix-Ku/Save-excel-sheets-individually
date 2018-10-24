# Save-excel-sheets-individually
### Version: 3.0

### First try of programming in VB.net

## Main function:
- Save every worksheets inside .xls or .xlsx file to new individual workbooks

## To-Do (Program):
  - Ini files storing sheet name and company name
  
## To-Do (Documentation):
  - Add reference of program script used from internet
  
## To-Do (Past and done):

  - Reduce size of new individual workbooks
    - Fixed: Use copy function and build new workbook
  - .xls file cannot save as .xlsx
    - Fixed: Specify second parameter (File Format) instead of directly changing file extension
           Use copy function to copy sheet content to newly created workbook
  - Simplifying the script
  - Adjust the variables (private? public?)
    - Fixed
  - Check exist files and overwrite or not
    - Fixed
  - Signals
    - XXX number of file(s) processed
    - Fixed

## Remainder & Knowledge：
- Workbook should be closed before assiging it to "Nothing" (workbook.close() workbook=Nothing)
- Garbage collect is related to the declaration of variables and COMs
- gc.collect() should be used carefully
- Buttons need to be manully disabled while running
- ToolStripProgressBar = percentage

## Reference:
[To be added]
https://stackoverflow.com/questions/20469524/save-a-file-in-xlsx-format-in-vb
https://docs.microsoft.com/zh-hk/dotnet/api/microsoft.office.interop.excel?view=excel-pia
