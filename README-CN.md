# vtt-to-srt-mod.py

## 来源

[jansenicus](https://github.com/jansenicus)/[vtt-to-srt.py](https://github.com/jansenicus/vtt-to-srt.py)

## 使用

### 从命令行调用:

```
python vtt_to_srt.py 路径名 [-r]
路径名 - 需要转换的文件绝对路径，或包含需要转换的文件的文件夹的绝对路径
-r    - 递归查找路径 
```

### 以可执行文件使用:

将vtt文件拖放到可执行文件上~~（目前仅支持单文件）~~ 现在你想拖多少个文件就拖多少个文件

## 功能

- 魔改前本来就有的功能:
  - 独立转换文件
  - 检查一个目录及其全部子目录
  - 将所有vtt文件转换为srt字幕格式
- 魔改追加:
  - 提供非英文字符（简体/繁体中文、韩语、日语）支持。转换此类文件不再显示 ` 'gbk' codec can't decode byte ... `
  - 提供同时转换多个vtt文件支持

