--------------------------
Precruise setup
--------------------------
using SBEdata processing application, edit datcnv and bottlesum to confirm the necessary fields are being output to the .cnv files
--------------------------
Notes
--------------------------
base.xmlcon should stay in the raw directory.  datcnv, derive, and bottlesum require an input xmlcon file to open, but will use the instrument generated cast file during processing.

ctd_archive defines the file paths for proc, procontrol, raw, and archive directories.  These should remain static for cruise operation. To run this on a different machine, edit these paths to match the local pathways.

Additional processing modules may be added or removed by editing ENPRO.txt

Bottle summary can be used with or without bottles being fired.  An error will be triggered at the end of processing.  Accept the error, and upon the next cast processed a window will pop up.  Choose to start the processing from line 1. 