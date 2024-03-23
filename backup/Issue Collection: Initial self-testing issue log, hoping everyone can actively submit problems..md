- [x] Text Editor Issues
    - [x] Unable to invoke find dialog in editor
    - [X] Texts with certain extensions unable to be edited and previewed should prompt
    - [X] Images and PDFs should be previewed in the browser
    - [x] Attempted to add a blank section without line numbers at the bottom of the text editing box for better aesthetics, tried several methods unsuccessfully (downgrade)
    - [X] Web text editor fails to preserve line breaks when retrieving text
    - [X] In Safari browser, Chinese input in web text editor causes misalignment of line numbers due to the occurrence of div>br + span, not observed in Google Chrome
    - [X] Lack of modifying status when clipping large texts, requires special handling upon saving
    - [X] Certain text editors prone to crashing (CHANGELOG.md) - seems to be resolved (under observation)
    - [X] Misalignment of label files in certain text editors, issue with file level hierarchy
    - [X] No prompt to save when closing large text editing in text editor
- Tab Switching
    - [X] Web document reloads when switching tabs
    - [X] Occasionally unable to locate corresponding business tab when switching tabs
    - [X] Entire business menu re-renders upon switching (can it be cached?)
- [X] Menu Bar Styling Issues
    - [X] Gray underline on each item in menu bar
    - [X] Not all selectable areas in menu bar occupy the entire row, should fill the entire row
    - [X] Ineffective toggle of folder expansion and collapse in menu bar
- [X] Independently selected folders lack permissions (after reinstallation)
- [X] Excessive delay in loading when directory contains too many files, lazy loading strategy needed
- [X] Inability to open large texts leads to program deadlock
    - [x] Currently, only large texts trigger logical jumps, recommended to use other editors for opening, but still unable to smoothly edit large files (downgrade)
- [X] Dropdown multi-select box freezes
- [X] Add search functionality to dropdown boxes
- [X] Logout not fully effective, automatic login upon clicking login again
- [X] Lag when clicking or losing focus on text box (Apple's own issue, triggers touch bar input method suggestion)
    - [X] Attempt to encapsulate text box of web browser for interactive processing
- [X] Git commands such as Clon and Push not working, network needs checking

Due to inconsistent development, some issues were overlooked, which is regrettable, as they are valuable experiences.

Once again, I earnestly request everyone to actively submit issues. I will promptly respond and, as appropriate, add them to my repair or feature list.
