# pic_to_ascii
简单的将图像转换为字符画
RGB-->灰度值-->自定义的字符

两个要点：
1.使用Python的argparse库
    argparse是python的一个命令行解析包，非常编写可读性非常好的程序
2.了解灰度值公式
    灰度值公式 ： 0.2126*r+0.7152*g+0.0722*b 

思考：当图像的RGB值比较集中时，可以改进的算法
