---
layout: default
title: Post image test ~
thumbnail: images/2024-06-29-01.JPG
---

# Post imgae test
 
This is a test for inserting image path in posts running by jekyll on GitHun Pages.  

=============  
### Summary  

for #Projects Pages...
1. 圖片url“/”開頭的話，在Github Preview無法顯示。(但published網頁中可以)  
2. 圖片url使用liquid加上relative_url，在Github Preview無法顯示　→會直接顯示整行原始碼(但在published的網頁可正常顯示)  

3. 【結論】post要加圖片時，url直接用“image/...”，開頭不要加/      

=============  
  

● path uses /images and liquid url filter

  
one   
![]({{'/images/2024-06-29-01.JPG' | relative_url }})  
two   
![]({{'/images/2024-06-29-01.JPG' | relative_url }})  


-------  
  
● path uses images

one  
![](images/2024-06-29-01.JPG)  
two  
![](images/2024-06-29-01.JPG)


  
  
↑以上為個人遇到圖片在Github Preview跑不出來但在網頁跑得出來的實驗跟筆記..
  



