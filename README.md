#   OREAS-Catalogue-Parser
#   This project is intended for internal RSC use, when adding details of new CRMs to the CRM Details sheet in the RSC pXRF Roster Workbook.
  - To update the catalogue: goto https://www.oreas.com/downloads/ and select 'OREAS CRMs Spreadsheet.csv'. May have to change the file extension to a .txt. Download to the same directory as the Parser .py file, and change the catalogueName variable on to match the new file name.
  - To add an element: Add it to the element list creation section at Ln ~8, as well as a corresponding section in the scraper section at line ~109, and in the output writer at line ~1838
  - No external modules required, as csv is part of the default library.
