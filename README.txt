MTO EXTRACTOR
=============
Reads a datasheet PDF (Euroclima CATCALC prints, equipment schedules)
straight from its text layer — no highlights or mark-up needed. Every
labelled field becomes its own spreadsheet column, so you can rename the
columns later without touching the data.

Fields read: Position, Unit, Fan, EC-Motor, Cells pcs x size [mm],
Filter type, Coil, Dimensions [mm], Damper, Actuator type.
Pages that belong to the same position are merged into one row.


HOW TO RUN
----------
1. Double-click "MTO Extractor.exe".
2. Drag a PDF anywhere onto the window (or click "Choose PDF").
3. Review the extracted columns and rows.
4. Click "Export .xlsx" and save the workbook.

The workbook has two sheets:
  MTO     one row per unit, one column per field (headers A, B, C, ...)
  Fields  which column came from which label on the datasheet

No installation is needed. Everything runs on this computer; nothing is uploaded.


IF WINDOWS SHOWS A BLUE "WINDOWS PROTECTED YOUR PC" PROMPT
----------------------------------------------------------
This build is not code-signed. Click "More info" -> "Run anyway".


FILES
-----
MTO Extractor.exe    the application
resources\app\       the application code and its libraries (do not move)
locales, *.dll, *.pak, resources.pak, snapshot_blob.bin
                     Electron runtime files (do not move)


SYSTEM REQUIREMENTS
-------------------
Windows 10 or later, 64-bit.
