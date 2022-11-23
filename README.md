# Image-Hash-Detect-And-Delete
A script for helping you killing all same image.

There are different mode to delete image:

* check_image_by_path(folder_path, detect_file_path):
  * give a folder path and a path for the file you want to check. It will delete all same hash image.
* check_image(folder_path, detect_file_path):
  * give a folder path and a name of file in that folder. you want to check. It will delete all same hash image.
* check_all_image(folder_path):
  * give a folder path. It will check all image delete all same hash image leave every various image.
