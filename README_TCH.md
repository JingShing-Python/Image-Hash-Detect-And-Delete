# Image-Hash-Detect-And-Delete
[English](README.md) | 繁體中文

一個可以幫你清除相同圖片的腳本。

有數種函數可以選擇：

* check_image_by_path(folder_path, detect_file_path):
  * 給一個資料夾的路徑和圖片的路徑，會幫你刪除在給定資料夾中和給定的檔案相同哈希的檔案。
* check_image(folder_path, detect_file_path):
  * 給一個資料夾的路徑和給定資料夾之中檔案的名稱，會幫你刪除在給定資料夾中和給定的檔案相同哈希的檔案。
* check_all_image(folder_path):
  * 給一個資料夾的路徑，會幫你刪除比對所有圖片，每種哈希值只留下一張圖片。
