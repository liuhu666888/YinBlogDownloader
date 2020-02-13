# YinBlogDownloader
下载王垠博客上的所有文章并转为PDF

# 依赖
pdfkit、os、requests、BeautifulSoup、time

# pdfkit 安装教程
1. 安装 python-pdfkit:
> pip install pdfkit
2. 安装 wkhtmltopdf:
* Debian/Ubuntu:
> sudo apt-get install wkhtmltopdf
* Fedora/RHEL/CentOS
> yum install wkhtmltopdf
* Windows
从以下[wkhtmltopdf downloads list](https://wkhtmltopdf.org/downloads.html)页面下载安装包，然后将包含
wkhtmltopdf二进制文件到路径添加到PATH下。
* Mac
从以下[wkhtmltopdf downloads list](https://wkhtmltopdf.org/downloads.html)页面下载安装镜像然后将文件拷贝到PDFkit能够找到的路径下。 Homebrew也是支持的，运行以下命令即可。
> brew install Caskroom/cask/wkhtmltopdf

# 执行方法
* 安装python3
* 执行命令: > python3 crawler.py


