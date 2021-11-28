# rofi配置
rofi可以通过apt直接进行安装，想要进行配置就需要使用以下命令在.config文件下生成配置文件
'''shell
mkdir -p ~/.config/rofi
rofi -dump-config > ~/.config/rofi/config.rasi
'''
rasi文件的写法类似于css形式。
之后可以通过以下命令使得配置生效:
'''
rofi -show drun -theme config(配置名)_
'''
## rofi语法
\/\/ 和\/\* \*\/ 表示的是注释，需要将注释取消才能够使得指定代码生效

