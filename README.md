# Class 1  
Compiler UE4 editor and pack an Android apk  
通过源码编译UE4，并且打包生成安卓apk  
* 主要遇到的问题  
    * 在安卓手机上运行游戏时报错*No Google Store Key*  
    ![No Google Store Key](https://github.com/pineisme/myUnrealCareer/blob/main/image/noobb.jpg?raw=true)  
    在应用发布到应用商店时需要对应用进行签名，我们手机中缺少obb文件，可以将手机设置为USB调试模式，允许USB安装应用，最后使用pakage包中的install脚本进行安装  
    ![obb](https://github.com/pineisme/myUnrealCareer/blob/main/image/installobb.PNG?raw=true)  
    最后成功在安卓手机上运行。  
    ![run](https://github.com/pineisme/myUnrealCareer/blob/main/image/runGif.gif?raw=true)  
    在安卓手机上的[运行视频](https://github.com/pineisme/myUnrealCareer/blob/main/image/runScene.mp4)在myUnrealCareer/image/runScene.mp4
