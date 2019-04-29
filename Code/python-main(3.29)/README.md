# Ethereum-Score-Hella

## 环境准备

### 当前系统及库版本

anaconda: Anaconda navigator 1.9.2

opencv: Opencv3 3.1.0

AipOcr: Newest

re: Common

python：Python 3.7.0

### 环境安装
1.下载anaconda：https://www.anaconda.com
1.1anaconda安装spyder等基本开发环境

2.anaconda命令行创建虚拟环境（python建议3.7）：
conda create -n your_env_name python=X.X 

3.激活虚拟环境
source activate your_env_name

4.安装opencv（opencv-python的版本号可能不同，不同版本号可能与一些系统不兼容）
pip install opencv-python==3.4.2.16 -i https://pypi.mirrors.ustc.edu.cn/simple/
或者
anaconda里面用包管理器安装

5.

### 项目版本更新：
main3.29－00.00 :接通了百度api文本识别接口，实现了基本的自然语言处理（对基本题号和题目情感倾向的处理）

main3.31-18.46 :优化了自然语言处理过程（增加了对题目选项的语意识别），增加了新的工具函数

main4.2－00.00 :优化了自然语言处理效果（增加了对注意事项等无关内容的排除），实现了基本的切题功能

main4.14-00:00 :解决了自然语言处理的bug，实现了基本题型的高成功率识别，解决了图片切割范围判定逻辑的问题

main4.14-23:00 :实现了题号识别不出‘.’时，依然可以根据题号顺序规律将其划分出来。
