# HanCat_Alist
Alist美化  
# 自定义头部  
```html
<link href="alist.css" rel="stylesheet" type="text/css">  
<script>
function getRandomNum(Min, Max) {
            var Range = Max - Min;
            var Rand = Math.random();
            var res = (Min + Math.round(Rand * Range));
            if(res == 2) return 1;
            return res;
        }
 		localStorage.setItem('modelId', getRandomNum(1,4));  
 		localStorage.setItem('modelTexturesId',  getRandomNum(1,4));
 </script>  

<script>
const live2d_path="http://api.itggg.cn/live2dnew/left/";function loadExternalResource(url,type){return new Promise((resolve,reject)=>{let tag;if(type==="css"){tag=document.createElement("link");tag.rel="stylesheet";tag.href=url}else if(type==="js"){tag=document.createElement("script");tag.src=url}if(tag){tag.onload=()=>resolve(url);tag.onerror=()=>reject(url);document.head.appendChild(tag)}})}if(screen.width>=768){Promise.all([loadExternalResource(live2d_path+"waifu.min.css","css"),loadExternalResource(live2d_path+"live2d.min.js","js"),loadExternalResource(live2d_path+"waifu-tips.min.js","js")]).then(()=>{initWidget({waifuPath:live2d_path+"waifu-tips.json",apiPath:"http://api.itggg.cn/live2d_api/",})})}</script>  
```

# 自定义内容  
```html
<script src="http://39.103.236.238:19090/public/jq.js"></script>

<div id="jsi-flying-fish-container" class="fish-container"></div>

<script src='http://39.103.236.238:19090/public/fish.js'></script>  
```

# 效果图  
![image](https://user-images.githubusercontent.com/109069769/229329197-b5c9a104-e5dd-4513-9e63-784bfcba90e8.png)  

![image](https://user-images.githubusercontent.com/109069769/229329259-4a839d8b-3e31-47d5-a034-cee25c1bf3e8.png)

