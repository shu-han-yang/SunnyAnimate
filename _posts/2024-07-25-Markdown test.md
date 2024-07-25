---
layout: default
title: Markdown test post
thumbnail: images/2024-06-29-01.JPG
---

# Markdown test
 
This is a test for markdown.  

=============  
Summary  

1. 圖片位址有“/”開頭，在Github Preview無法顯示。(但在published的網頁中可以)  
2. 圖片網址使用liquid標示relative_url，Github Preview無法顯示，會直接顯示整行原始碼(但在published的網頁可正常顯示圖片)  
3. 要連結圖片，直接“image/...”，開頭不要加/      

=============  
  

● path uses /images and liquid url filter

  
one   
![]({{'/images/2024-06-29-01.JPG' | relative_url }})  


-------  
  
● path uses images

one  
![](images/2024-06-29-01.JPG)  
two  
![](images/2024-06-29-01.JPG)


  





