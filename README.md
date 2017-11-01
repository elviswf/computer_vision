# computer_vision

python CV feature extractor:
Sift、Gist、LBP、HOG、颜色直方图、BOVW、VLAD和Fisher Vector。

From blog:
[VLAD](http://www.cnblogs.com/jeromeblog/p/4181862.html)

其中，SIFT和GIST特征提取需要调用可执行文件。

GIST特征提取的[源码](http://lear.inrialpes.fr/software/)，该源码依赖FFTW库，windows环境下的相关库我已经准备好了；  
linux下载FFTW的[源码](http://www.fftw.org/download.html)，解压后依次执行
```
./configure --enable-single;make;sudo make install
```
即可编译源码了。

Sift特征提取的可执行文件来源于VLFeat。

BoVW、Vlad和Fisher Vector依赖Numpy、scikit-learn、Pillow。
