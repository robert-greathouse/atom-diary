## 1.2.1 - Fixing a bug
* Replaced last, overlooked use of cal.getCreateDirectories with calling the
  proper routine, fixing [Issue #6](https://github.com/sluedecke/atom-diary/issues/6)

## 1.2.0 - Improved Usability
* Added context menu to calendar view for easy creation of entries for now and the selected day
* All keyboard shortcuts now start with Alt-Shift-d which is hopefully unique
* User can open the diary folder as an atom project in a separate window
* Some code cleanup to let Atom do work automatically
* Fixed spelling and grammar errors

## 1.1.0 - Relicensed
* atom-diary is now under the MIT license (switched from Apache Public License 2.0)
* Bugfix: weekday name was formated same as TODAY although it shouldn't
* Bugfix: fixed [Issue #1](https://github.com/sluedecke/atom-diary/issues/1): could not create initial diary directory

## 1.0.1 - First one-for-all printable diary
* only update calendar when it is visible (toggling visibility updates anyways)
* Generate summary files per year for AsciiDoc
* Added "New (now)" and "Print all" as action items to both the menu and the calendar screen

## 1.0.0 - The Release
* calendar view updates when a diary file is changed (saved).  Diary file has to be opened via atom-diary mechanisms!
* learned the meaning of fat arrow and made use of it
* learned how to use closures and made use of it

## 0.9.1 - The Release is near
* calendar view colors now follow the atom theme

## 0.9.0 - Preparing 1.0
* Added calendar view
  * shows three months
  * highlights days with entries and toggles day background on mouse hover on days with entries
  * days with entries can be clicked, will open respective month file and jumps to first entry for this day
  * has close button
  * has navigation buttons (previous month, next month, previous year, next year, today)
  * makes use of atom theme colors
* Added opening the diary basedir as a project (nothing else yet)
* Reorganized TODOs in README.md
* some refactoring of code to make it more modular

## 0.3.0 - Make it accessible
* Added support for Markdown
* Remove configuration option for file extensions
* Improved README.md

## 0.2.0 - Get some Work done
* Language for diary files can now be set
* Added some more descriptive text to README

## 0.1.0 - First Release
* Basic version which can produce AsciiDoc
