# MCrestool
帮助您一键检索我的世界的音效文件，避免繁复的查看索引来对照音效文件的位置，并且自带OGG转换到其他格式
------------------------------------------------------
本程序使用易语言制作
------------------------------------------------------
我的世界音效文件存放在".minecraft\assets"目录下
通过indexex中的json作为索引来定位objects中的音效或资源文件。
通过手动对照json中的哈希值以获得音效文件无疑是繁琐的
所以您可以提供assets文件夹的路径
直接在列表中选择直观的文件命名来下载或者播放mc的音效文件。
并且在保存时可以保存为任意格式(通过ffmpeg转换)

具有搜索功能，并且支持给定多个关键词（用",")分割以搜索
仅支持中文。

PS:做的时候是为了方便自己的视频放音效，所以做的比较潦草，很容易触发BUG，代码也几乎没有可读性
