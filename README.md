# UploadAndDownload
简单的用socket和tcp/ip实现了文本文件的上传和下载
其中服务器的端口号默认为8888,输入的时候按格式输入即可。由于容错的处理考虑不够细致，可能对错误的处理的不足之处，希望日后可以改进。
运行程序的时候，只需要在eclipse下建立新的工程项目，然后分别建立两个包，一个server,一个是client。其中Server类和ServerThread类放在server包下，这部分程序放在服务端。Client类放在client下，这部分程序放在客户端。在本机上测试的时候，输入的ip地址可以输入“localhost”
