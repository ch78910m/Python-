# 文件下载器-Python编写
可实时显示每个文件的下载进度，
克隆或下载（文件下载脚本_v1.0.zip）文件后需解压，将解压后的文件放在同一个文件夹内，然后按以下步骤操作。

第1步打开"文件链接.txt"文件，填写需要下载的文件名和文件的下载链接，每行写一条信息。

格式：文件名+";"+链接

例如：文件名;https://x.w3sfxersfoo.com/mp4/bsdsdwece8.mp4

注意：中间的分号是英文的；如果程序出错请检查并修改"文件链接.txt"的内容格式是否正确,然后重新运行程序;

第2步打开"配置文件.txt"文件，在第一行填写下载的文件将要存储的目录完整路径（路径最后一部分为即将创建的文件夹名称）。

如不修改配置文件则程序将下载的文件存储在默认路径下。默认路径为:"F"盘下的"文件下载器测试"文件夹

例如：F:\文件下载器测试

备注：程序运行后会自动按照配置文件中的路径创建文件存储目录，无需手动创建文件夹（目录）。

第3步运行程序：

打开cmd，切换到当前目录下输入命令：python.exe "FileDownloader.py"

注意：如果windows系统的电脑没装python.exe则无法使用本程序，建议先在电脑上检查并安装python3.7（64位）版本。

重点备注：

程序默认下载完之后，自动倒计时10秒后关机。取消自动关机的方法如下：

在下载完成后的10秒内，打开cmd命令行输入命令：shutdown /a 按回车键即可取消。




