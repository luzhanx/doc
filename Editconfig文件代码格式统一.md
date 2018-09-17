# Editconfig文件代码格式统一
[EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

```
# 创建.editconfig 文件 editconfig写法

[*]
charset = utf-8                         # 设置编码                    
indent_style = space                    # 设置缩进风格(tab是硬缩进，space为软缩进)
indent_size = 2                         # 用一个整数定义的列数来设置缩进的宽度，如果indent_style为tab，则此属性默认为tab_width
end_of_line = lf                        # 设置换行符, 值为lf cr 和 crlf
insert_final_newline = true             # 设为true表示使文件以空白行结尾
trim_trailing_whitespace = true         # 是否将行尾空格自动删除
```
> CR：Carriage Return，对应ASCII中转义字符\r，表示回车
> LF：Linefeed，对应ASCII中转义字符\n，表示换行
> CRLF：Carriage Return & Linefeed，\r\n，表示回车并换行

