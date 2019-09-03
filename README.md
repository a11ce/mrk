# mrk 

> A line-based note-taking tool inspired by ed.

## Installation

- Download with `git clone https://github.com/a11ce/mrk.git`
- Install with `python3 setup.py install`
- Run (anywhere) with `mrk`

## Usage

- Run without arguments, mrk will list your note files reverse chronologically by creation date.
- Run as `mrk <integer>`, mrk will enter edit mode with the file with the specified number. Keep in mind that file numbers will not change unless a note is deleted.
- Run as `mrk <string>`, mrk will enter edit mode with the specified file, starting with a blank file if it does not already exist.

### Edit mode
- Upon entering edit mode, the note is printed with line numbers. Then, commands may be entered.
    - `p` prints the note with line numbers.
    - `a` appends the next entered line to the end of the note.
    - `i<integer>` inserts the next entered line after the specified line number.
    - `d<integer>` deletes the specified line.
    - `w` writes all changes to the note file.
    - `q` quits mrk. If you have unsaved changes, a `?` will be printed instead of quitting. Enter `q` again to quit without saving.

--- 

All contributions are welcome by pull request or issue.
`mrk` is licensed under GNU General Public License v3.0. See [LICENSE](../blob/master/LICENSE) for full text.