# Bioplex-BAMA-Primary-QC-Script
Primary QC script for Bioplex BAMA assays

# Version Notes
**2.1**
  - Script was converted into loops and functions so that it can run automatically on all files within a folder
**2.1.1**
  - TO DO: Implement filtering function within the interpolation function before printing the filtered frames
  - FilterQCValues() Overview:
      - Handle the QC (low bead count, high CV, high blank bead MFI) and set failing values to "NA"
      - Inputs: frame that is about to be filtered, low bead count cutoff, high cv cutoff, high blank bead mfi cutoff
