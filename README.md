# Rename files
This small but powerful routine was created to automate a simple but tedious task I had to perform on a monthly basis at work: renaming powerpoint files by incorporating the title of a slide into the new file's name and adding a year-month timestamp and version number.

# How to use
1. Change the `folder` variable value to the path where files are stored
2. Change the `title_pattern` variable to the pattern you would like to apply to the file name
3. Change the 2nd parameter of rename function `r'.txt'` to the file extension of your choice
   - `rename(folder, r'*.txt', title_pattern)`
