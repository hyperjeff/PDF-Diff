PDF Diff extracts plain text from pdfs and then compares their differences using FileMerge
(requires dev tools to be installed). This is a rudimentary 5-minute implementation.
Making it nicer to use, win prizes.

An executable app and the Automator script are both provided here.

## Usage
Open PDF Diff.app in Finder. An open file dialog will ask the user to select the first PDF file,
then after that the 2nd PDF, and then it will open FileMerge showing the diff between them.
If there are no differences, nothing happens.

The script saves the output of each PDF's text contents as pdfContents1 and pdfContents2 on your Desktop. Afterwards you can delete or use them as you see fit.

## Modifying
To update source, open PDF Diff.workflow in Automator and edit there.
Do not try to edit the script in a text editor.

License type: BSD. Use, share.
