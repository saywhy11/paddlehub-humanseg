# paddlehub-humanseg
在使用之前，我们先来安装飞桨，可以进入官网，按指引快速安装：
https://www.paddlepaddle.org.cn/install/quick
为了方便，这里直接在jupyternote 的环境下使用pip安装CPU版本的。我们在虚拟terminal中执行下列语句：
pip install paddlepaddle -i https://mirror.baidu.com/pypi/simple
安装完成后，可以在环境中测试一下是否成功。
import paddle.fluid 
paddle.fluid.install_check.run_check()
如果控制台显示Your Paddle is installed successfully! Let's start deep Learning with Paddle now，就代表我们已经安装成功了。
另外我们还需要安装PaddleHub：
pip install -i https://mirror.baidu.com/pypi/simple paddlehub
其后参照ipynb文档即可
