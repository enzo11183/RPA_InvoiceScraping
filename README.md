# RPA_InvoiceScraping
Required input files can be downloaded from: https://drive.google.com/drive/folders/1s7lTORmHgAKI5T0U1NpcbnOUgxRYRH1-?usp=share_link

This bot takes each pdf file in Input folder as an input and extracts some information from it; like invoiceNumber, invoiceDate etc.
These info will be saved to the xlsx file which provided within the project folder.

If successful, the pdf file will be moved to "Output/Successful" directory. (Must be created before run)
Else, will be moved to "Output/Failed".
