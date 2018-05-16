# Train-computer-to-imitate-world-famous-paintings
通过python的深度学习算法包去训练计算机模仿世界名画的风格，然后应用到另一幅画中
步骤一：
# 命令行安装keras、h5py、tensorflow
pip3 install keras
pip3 install h5py
pip3 install numpy
pip3 install scipy
pip3 install tensorflow
# 如果pip3失败请用pip就好

步骤二：
在C:/Users/Administrator 下新建.keras文件夹。注意，这里不能直接右键新建.开头的文件夹，但是用DOS命令就OK了。
WIN键+R键打开运行对话框，输入cmd，打开DOS命令行，使用mkdir .keras，在当前目录建立了一个名为“.keras”的文件夹，这个keras其实是。


步骤三：
新建一个空文件夹，把上一步骤的文件neural_style_transfer.py放入这个空文件夹中。然后把相应的模板图片，待转化图片放入该文件当中。
python neural_style_transfer.py   你的待转化图片路径    模板图片路径   保存的生产图片路径加名称（注意不需要有.jpg等后缀）
 python neural_style_transfer.py './me.jpg' './starry_night.jpg' './me_t'
