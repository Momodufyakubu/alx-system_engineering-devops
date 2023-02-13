ls -lt | head	Displays the 10 newest files in the current directory.
du | sort -nr	Displays a list of directories and how much space they consume, sorted from the largest to the smallest.
find . -type f -print | wc -l	Displays the total number of files in the current working directory and all of its subdirectories.
