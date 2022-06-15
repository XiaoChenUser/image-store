#工程介绍
该 repository 使用 github作为图床，保存各个开源项目的图片。用于在各个项目的 README.md 文件中引用。  

#使用步骤
1.各个项目在当前 repository(image-store)下创建与项目名相同的文件夹，并将各项目的图片放置在其同名文件夹下。  

2.上传到 github 后，点开各个图片，获取其地址，例如：  
https://github.com/XiaoChenUser/image-store/blob/main/LogbackTest/appender-impl.PNG  
将 URL 中的 blob 修改为 raw：
https://github.com/XiaoChenUser/image-store/raw/main/LogbackTest/appender-impl.PNG   

3.在项目 README.md 中使用  
使用方式：![图片说明](图片 URL)  
比如：  
![logback appender](https://github.com/XiaoChenUser/image-store/raw/main/LogbackTest/appender-impl.PNG)
