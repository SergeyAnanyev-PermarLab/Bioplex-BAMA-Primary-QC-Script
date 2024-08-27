# Bioplex-BAMA-Primary-QC-Script
Primary QC script for Bioplex BAMA assays

# Version Notes
**2.1**
  - Script was converted into loops and functions so that it can run automatically on all files within a folder
**2.1.1**
  - Edited the interpolation function to handle QC filtering differently
  - Filtered MFI values in "Blank()" column that are over 1000 are set to NA
  - Filtered MFI values that are under 100 are set to NA
