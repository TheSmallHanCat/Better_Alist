# Better_Alist  

* 半透明化目录背景  

* 随机甘城背景图  

* 添加回到顶部猫猫  

## 使用方法  
   * 在Alist后台页面依次选择```设置```-->```全局```
   * 将以下内容添加到对应框框内
     * 自定义头部  
        ```html
        <link href="https://cdn.jsdelivr.net/gh/TheSmallHanCat/Better_Alist@main/alist.css" rel="stylesheet" type="text/css">  
        ```  

     * 自定义内容  

        ```html
        <script src="https://cdn.jsdelivr.net/gh/TheSmallHanCat/Better_Alist@main/jq.js"></script>
        <div class="st-Container">
            <a style='display:none' class="st-Menu closed" id="st-Menu" href="javascript:void(0);"></a>
        </div>
        <div class="sw-Hennnyano" id="sw-Hennnyano">
            <div class="layer body w100" data-depth="0.1"></div>
            <div class="layer eyes w100" data-depth="0.2"></div>
        </div>
        <script src="https://cdn.jsdelivr.net/gh/TheSmallHanCat/Better_Alist@main/js/lib.js"></script>
        <script src="https://cdn.jsdelivr.net/gh/TheSmallHanCat/Better_Alist@main/js/parallax.min.js"></script>
        <script src="https://cdn.jsdelivr.net/gh/TheSmallHanCat/Better_Alist@main/js/app.bundle.js"></script>
        <div id="jsi-flying-fish-container" class="fish-container"></div>
        <script src='https://cdn.jsdelivr.net/gh/TheSmallHanCat/Better_Alist@main/fish.js'></script>
        ```

## 效果图  
* 亮色主题
![light-20240425181503](https://github.com/TheSmallHanCat/Better_Alist/assets/109069769/6c5a7317-df58-4bc8-b469-92c8e664754b)

* 暗色主题
![dark-20240425181503](https://github.com/TheSmallHanCat/Better_Alist/assets/109069769/24f1a8ad-76b5-4f19-8a26-c541e97b36b9)

* 点击猫猫即可返回顶部
![20240425181635](https://github.com/TheSmallHanCat/Better_Alist/assets/109069769/7b006d58-612c-47e4-83d9-7f6c8b6ebf41)

