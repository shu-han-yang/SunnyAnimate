---
layout: default
title: Markdown test post
thumbnail: images/2024-06-29-01.JPG
---

# Markdown test
 
This is a test for markdown.  

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


  





