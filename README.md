# SQL highlighting in Python multiline strings for VS Code

Adds automatic syntax highlight support SQL strings embedded in Python strings. Improvements made with extensive use of Microsoft(R) Copilot(TM).

**This is still under development,** if you experience issues please try to help us fix them. :)  Auto detecting SQL, and highlighting it properly insight Python is _hard_!

View source code [Github](https://github.com/RadoslawDeska/better-python-string-sql-refined/blob/HEAD/github.com/RadoslawDeska/better-python-string-sql-refined/).

![Image showing syntax highlighting working for SQL embedded inside a Python string](https://github.com/RadoslawDeska/better-python-string-sql-refined/blob/main/docs/demo.png)
![Image showing syntax highlighting exclusion for print statements in Python](https://github.com/user-attachments/assets/235bcad7-4332-4944-bc6a-d05956d75786)


## Community
- 2024-10-30 forked from [better-python-string-sql](https://github.com/Submersible/better-python-string-sql)

## Release Notes

### [0.0.1] - 2024-10-30
- Made it so that it doesn't highlight in print() statements and is impervious to single quotation marks inside multiline string starting with double-quotation marks
- Forked from better-python-string-sql
