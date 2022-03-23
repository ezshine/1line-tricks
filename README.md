# 1line-tricks
一行代码系列


#### 去掉稿定水印
```
javascript:var gdstyle=document.createElement("style");gdstyle.innerText=`.editor-watermark{position:static!important;z-index:-999!important}`;document.body.insertBefore(gdstyle,document.body.firstChild);document.querySelector("div.remove-watermark").style.display="none";document.querySelectorAll(".editor-watermark").forEach((item)=>{item.style.zIndex=-999});
```


#### 去掉创客贴水印
```
javascript:document.querySelector('.water-mark').style.opacity=0;document.querySelector('.remove-cktTemplate-watermark').style.opacity=0;
```
