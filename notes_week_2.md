# Notes from CLI/Git transition. CLI = command line
Notes from CLI/Git transition

Nice part about GUI (graphical user interfaces):
- you can see what you're about to click or what your options are
- What you see is what you get in GUI
- What you see in a GUI is all you get.

CLI fundamentals
- knowing where you are currently? 
- how to make things like folders/files
- how to move things
- start processes
- check status of processes
- terminate processes

At least 2 questions on CLI before moving forward:

Scenario 1:
- 2 teammembers edit the same line 23 on the same file
- git doesn't know which to keep if we did the work @ the same time
- git creates a "merge conflict" instead of accidentally overwriting any one author's work
- "merge conflict" is prompt the humans on what stays vs. what goes vs. does everything stay from both?

Scenario 2:
- 2 teammembers need to do edits.
    - Adam edits line 25
    - Ryan edits line 72
- no conflict
- git merges everythign together appropriately
- only place where this is a problem is a jupyter notebook
- if we're .txt or .sql or .py, we're gold


- Question: if you make a clone, is that clone automatically updated? short answer: no. we're not talking autosave or autobackups.

Question: is GitHub a good example from where you would pull your CSVs from? No. Filesize is limited to 50 or 100mb

Comment: git is tracking line changes in files by line and is not a database.