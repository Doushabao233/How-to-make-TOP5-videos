# How-to-make-TOP5-videos

ello guys. Today we have a tutorial of how to make TOP5 videos. 爱咯盖子。今天我们学习如何制作TOP5视频。

欢迎你在学成归来后为本仓库做贡献。你可以分享你的视频草稿，把它保存到`video_draft`文件夹下，并命名为视频的id或av号。你只需要在GitHub上fork（创建分支）本仓库，并将自己的视频草稿上传后向我提出pull request（合并代码请求）。只要符合的我都会通过。关于视频草稿的样子，请看`video_draft`文件夹或下面的教程。

# 前言

Top 5 视频是最近兴起的网络meme。它以西班牙口音的英文配音、青色的视频背景和每次5个视频的特点在视频平台上有很多人制作，并且也有很多人观看。这种风格最初是由YouTube用户[squewe](https://www.youtube.com/@squewe)定义的。由于这种视频制作简单，具有一定幽默性，[squewe](https://www.youtube.com/@squewe)已经在YouTube上发布了224个视频，并拥有106万订阅者。[截止2023/7/22]。除了squewe，相关的创作者在B站也有出现，如[squwe@bilibili](https://space.bilibili.com/1211770205)、[坦然奥特@bilibili](https://space.bilibili.com/2014827662)

# 步骤

1. 选题：选题很重要。你的题目就是视频的标题，如：Top 5 汉堡、Top 5 跳脸、Top 5 猫。任何无聊或有趣的内容都可以用作选题。  
2. 素材：你的素材可以来自任何视频。通常去meme集锦中可以找到，或自行搜索。  
3. 列表：将你搜到的视频整理出一个列表，你可能找到了多于五个的视频，那么你可以筛选一下哪些应当放入视频中。  
4. 视频草稿：
   1. 总结视频排名顺序，列一个列表，最好加上每个排名的视频链接；
   2. 为你选取的内容撰写文字稿。它们将会粘贴到文字转语音软件中处理成音频（也就是开头那句熟悉的ello guys）。注意，为了音频效果到位，部分需要手动添加错别词纠正读音，如  
        - guys -> gays
        - number [n] -> numero [n]
        - ABC -> A.B.C   （添加点，让朗读停顿一下）
   
   我选择性列了个文档。你可以不用列这个。
   ```
   # Top 5 xxxxxxxx

    ## 找到的视频

    视频 A
    视频 D
    视频 C
    视频 E
    视频 B
    视频 F
    视频 G

    ## 最终决定要做的顺序

    5. 视频 D
    4. 视频 B
    3. 视频 A
    2. 视频 C
    荣誉提名：视频 F
    1. 视频 E

    # tts文字稿

    hello gays.
    today we have a list of top 5 xxxxxx.
    number 5. [.....]. 
    number 4. [.....].
    number 3. [.....].
    number 2. [.....].
    honorable mention.
    number 1. [.....].

    （注意：有的文字读不对，需要手动添加错别词纠正，如guys）
   ```

5. 文字转语音：将你准备好的文字稿导入到[https://lazypy.ro/tts](https://lazypy.ro/tts/?voice=6-2-2&service=Oddcast&text=&lang=Spanish&g=A)里由Oddcast训练的Jorge (Spanish, Castilian)文字转语音模型。这个模型产生的语音是TOP5视频的灵魂所在。输入文字后，点击`Say It`，将会生成一个音频。点击三个点，可以保存它。  
6. 剪辑：
   1. 打开如**Adobe Premiere Pro**、**剪映专业版**、**必剪**的视频剪辑软件；  
   2. 导入TOP5的视频文件；  
   3. 导入文字转语音的音频文件；  
   4. 创建一个颜色为`rgb(0, 255, 255)` 或 `#00ffff`的背景；  
   5. 按照生成的文字稿添加颜色为`rgb(255, 255, 255)` 或 `#ffffff`的文字，字体可选择Windows系统自带的`MS Reference Sans Serif`；  
   6. 添加文字和视频，重复以上操作。  
   7. 在结尾，可以添加自己的署名，也可以不添加任何信息。  
   
   需要注意的是，制作过程中

   1. 每一个视频的长度不要过长；  
   2. 可以适当压制视频码率和分辨率，使其看起来有电子包浆；  
   3. 荣誉提名不应该与主题有太大关系。  
7. 发布：在你要发的网站上传视频即可。

# 是用ChatGPT做的吗？

不是，但这个文章的风格也太像了……（x