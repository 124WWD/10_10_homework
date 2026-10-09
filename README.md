# 图像矩阵编程作业

## 1. 进入下载作业的目录

打开终端，使用 `cd` 进入你想存放作业的目录。例如，将作业下载到“下载”目录：

```bash
cd ~/Downloads
```

也可以将 `~/Downloads` 替换为你自己的目录路径。路径包含空格时，请用英文双引号包住路径。

## 2. 使用 Git 下载作业

在终端运行：

```bash
git clone https://github.com/inspirepassion/10_10_homework.git
```

Git 会在当前目录下创建 `10_10_homework` 文件夹，并将作业文件下载到其中。此命令需要电脑已安装 Git。

## 3. 完成 starter.py 中的四个函数

打开下载后的 `starter.py`，完成以下函数：

- `build_grayscale`：将一维像素序列转换为二维灰度图像。
- `edit_pixel`：在图像副本中修改指定像素。
- `grayscale_to_rgb`：将二维灰度图像转换为三维 RGB 数组。
- `adjust_brightness`：调整像素亮度，并将数值限制在 0–255 范围内。

每个函数中都有一行 `raise NotImplementedError(...)`。**删除这一行，在原位置编写你的代码，并使用 `return` 返回结果。**

请阅读 `starter.py` 中各函数的说明、示例输入和预期输出，了解具体要求。其他已提供的检查代码和绘图流程无需修改。

## 4. 在终端运行并检查结果

回到终端，进入下载后的作业文件夹。如果你按照上面的例子下载到了“下载”目录，请运行：

```bash
cd ~/Downloads/10_10_homework
```

如果你选择了其他下载位置，请相应修改路径。

检查当前所在目录和其中的文件：

```bash
pwd
ls
```

`pwd` 显示当前目录的完整路径，确认它是你的作业文件夹；`ls` 列出该目录中的文件，确认其中有 `starter.py`。

使用 Python 3 运行代码：

```bash
python3 starter.py
```

如果终端提示缺少 `numpy` 或 `matplotlib`，请先安装，再重新运行：

```bash
python3 -m pip install numpy matplotlib
python3 starter.py
```

程序会分别显示四个函数的检查结果：`通过`、`未通过`、`未完成`或`运行出错`。根据提示修改代码，保存文件后再次运行。四个函数全部通过时，会显示图像对比窗口。

关闭图像窗口即可结束程序；也可以在终端按 `Ctrl + C` 停止运行。
