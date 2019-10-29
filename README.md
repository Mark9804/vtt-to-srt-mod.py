# vtt-to-srt-mod.py

 [简体中文/Simplified Chinese/中国語](https://github.com/Mark9804/vtt-to-srt-mod.py/blob/master/README-CN.md)

## Source

[jansenicus](https://github.com/jansenicus)/[vtt-to-srt.py](https://github.com/jansenicus/vtt-to-srt.py)

## Usages

### From terminal:

```
python vtt_to_srt.py pathname [-r]
pathname - a file or directory with files to be converted 
-r       - walk path recursively
```

### As executable:

Drag & Drop .vtt file on the executable. (Only single file is supported right now.)

## Features

- Original features:
  - Convert file individually
  - Check a directory and all its subdirectories
  - Convert all vtt files to srt subtitle format
- Added:
  - Enable support on non-English (Japanese, Korean, Chinese) vtt files instead of showing ` 'gbk' codec can't decode byte ... `

