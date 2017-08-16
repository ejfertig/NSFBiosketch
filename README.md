# NSFBiosketch

R markdown file extracts a list of collaborators and affiliations from pubmed for NSF biosketch. 

The main script is the `CollaboratorList.Rmd`, designed for my usage but can be adapted to your name following the instructions in the script. `CollaboratorsNew.xlsx` is a spreadsheet designed to contain new collaborators and add them to the list. The Rmd outputs `CollaboratorList.docx` which contains the collaborators formatted per NSF requrements and `ConflictOfInterest.csv` for the table formatted per NSF requirements.

Please note this includes only the list of collaborators for conflicts of interest sections in the Biosketch. The results may be copied and pasted into the appropriate section of your biosketch. Formatting of affiliations is from the `address` field in pubmed and may require manual editing.

Please use freely, but note that I am not responsible for errors or ommissions that may result.

This is just a first pass with awkward formatting. Any additions and/or edits are welcome! Please comment under issues or email ejfertig@jhmi.edu.
