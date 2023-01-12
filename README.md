# Move_File_Python
A python script to move files

In this script, you will need to replace /path/to/source/directory and /path/to/destination/directory with the actual paths of the source and destination directories respectively.

The script uses the os.walk() function to recursively traverse the source directory and find all files that match the specified file types. It then moves each file to the destination directory, creating subdirectories based on the file's creation date. A log file is also created to keep track of the number of files and total size moved, as well as the date added or created and destination of each file.

This script move the files and delete them from the source directory, if you want to keep the files in the source directory and just copy them to the destination directory, you can replace shutil.move() with shutil.copy()
