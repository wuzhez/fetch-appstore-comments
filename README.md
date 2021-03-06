# fetch-appstore-comments
支持：

	- 抓取 App Store 应用的最新500条评论生成 Excel
	- 抓取 Google Play 应用的任意条评论生成 Excel
	- 写入 Excel 前调用谷歌翻译 API 翻译评论内容为中文
 
# Run
## for App Store
```
python3 ./splider.py
```
输入 appid，应用名自定义

## for Google Play
```
node index.js
```

# Effect
![效果图](https://raw.githubusercontent.com/wangwanjie/fetch-appstore-comments/master/snapshots/example.jpg)

![效果图](https://raw.githubusercontent.com/wangwanjie/fetch-appstore-comments/master/snapshots/google_play.jpg)


# LICENCE
MIT License

Copyright (c) 2019 VanJay

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
