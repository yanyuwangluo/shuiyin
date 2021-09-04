# marker.py

为图片添加文字水印
可设置文字**大小、颜色、旋转、间隔、透明度**

# usage

需要 PIL 库 `pip install Pillow`

```
usage: marker.py [-h] [-f FILE] [-m MARK] [-o OUT] [-c COLOR] [-s SPACE]
                 [-a ANGEL] [--size SIZE] [--opacity OPACITY]

optional arguments:
  -h, --help            show this help message and exit
  -f FILE, --file FILE  image file path or directory
  -m MARK, --mark MARK  watermark content
  -o OUT, --out OUT     image output directory, default is ./output
  -c COLOR, --color COLOR
                        text color like '#000000', default is #8B8B1B
  -s SPACE, --space SPACE
                        space between watermarks, default is 75
  -a ANGEL, --angel ANGEL
                        rotate angel of watermarks, default is 30
  --size SIZE           font size of text, default is 50
  --opacity OPACITY     opacity of watermarks, default is 0.15
  --quality QUALITY     quality of output images, default is 90
```

# 效果

`python marker.py -f ./input/test.png -m 添加水印`

`-f参数，输入图片的位置（可以是具体的一张照片，也可以是整个文件夹）`

`-m参数，你要添加的内容`

`另外，上边提到的其他功能参数：`

`-o 参数，指定输出水印文件的位置，默认为output文件夹。`

`-c 参数，指定水印的颜色，默认值为黄色，#8B8B1B`

`-s 参数，指定水印之间的空隙，默认值为75。`

`-a 参数，指定水印的旋转角度，默认值30度。`

`--size参数，指定水印文本字体大小，默认值为50。`

`--opacity参数，指定透明度，默认为0.15，数值越小越透明。`

![](wwww)
